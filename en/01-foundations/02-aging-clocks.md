# Aging Clocks

**Core Concept**: Aging clocks are quantitative tools that use molecular biomarkers (DNA methylation, protein abundance, transcript levels, telomere length, etc.) as input, calibrated through algorithms to output "biological age." Unlike chronological age, biological age reflects the rate of aging and organ functional status, serving as a core surrogate endpoint for evaluating aging intervention efficacy and predicting disease and mortality risk. This repository introduces four types of clocks by molecular level: epigenetic clocks, proteomic clocks, transcriptomic clocks, and telomere clocks, and discusses their current status and limitations as clinical endpoints.

```
  Molecular measurement ──▶ Feature selection/dimensionality reduction ──▶ Algorithmic modeling ──▶ Biological age output
   DNA methylation     353/513 CpG       Elastic Net     Horvath Clock
   Plasma proteins     ~373 proteins      Cox/elastic net  PhenoAge/GrimAge
   RNA expression      Panel genes        PLS/RF          Transcriptomic clock
   Telomere length     qPCR/Flow-FISH    Cox regression   Telomere clock
         └── Calibration target: chronological age / mortality risk / phenotypic age ──┘
```

## I. Epigenetic Clocks

### 1.1 Horvath Clock (2013, Multi-tissue Pan-clock)
**Principle**: DNA methylation (5-methylcytosine, 5mC) undergoes systematic drift with age — methylation at some CpG sites increases with age while others decrease. Horvath hypothesized that a set of cross-tissue consistent "age-related methylation sites" exists, whose weighted combination can output a tissue-independent age estimate.

**Construction**: Training data of 8,000 samples across 51 tissue/cell types (blood, brain, skin, muscle, etc.); using Illumina 27K/450K methylation array data; after feature selection, **353 CpG sites** were locked in (elastic net regression, L1+L2 regularization); output is "epigenetic age (DNAmAge)."

**Validation**: Training set median error approximately 3.6 years; independent validation across 51 tissues with average error <4 years; in embryonic/induced pluripotent stem cells (iPSCs), output approaches 0 (reprogramming returns to zero age); in cancer tissues, DNAmAge accelerates (can be 20–40 years ahead).

**Applications**: Measuring overall aging rate (epigenetic age acceleration DNAmAge acceleration = epigenetic age − chronological age predicted value); pre-post comparison in intervention studies (caloric restriction, exercise); forensic age estimation.

**Limitations**: Training predominantly European-ancestry (limited racial generalizability, larger error for African ancestry); some tissues (sperm, certain immune cells) predict poorly; the specific functions of most of the 353 sites are unknown — the clock is a "readout" not a "mechanism"; sensitivity to individual interventions (response speed) is not fully characterized.

### 1.2 Hannum Clock (2013, Blood-specific)
**Principle and Construction**: Modeled using only peripheral blood (482 samples), 71 CpG sites, also using elastic net; outputs blood DNAmAge. Because the training set contains many blood samples, blood prediction accuracy is slightly higher than Horvath's.

### 1.3 PhenoAge (2018, Phenotypic Age)
**Principle and Construction**: The Belsky/Levine team changed the calibration target — **instead of using chronological age as the label, they used "phenotypic age" (a mortality risk score derived from 9 clinical blood biochemical markers + chronological age via Cox regression) as the label**; then fitted on methylation data to obtain the PhenoAge clock with **513 CpG sites**. It outputs "age equivalent to mortality risk."

**Validation and Applications**: PhenoAge acceleration is strongly associated with all-cause mortality, cardiovascular mortality, cancer, and frailty — every 5-year epigenetic age acceleration corresponds to approximately 8–15% increased mortality risk; it is more sensitive to interventions (lifestyle, drugs) than first-generation clocks, making it one of the preferred choices for current intervention research. Note: PhenoAge's "phenotypic age" components (albumin, creatinine, glucose, CRP, lymphocyte ratio, etc.) are themselves direct measurements of health status, so it partially measures "current physiological health" rather than pure epigenetic changes — this is why it is both more sensitive and more "confounded" than the Horvath clock.

### 1.4 GrimAge (2019, DNAm Surrogate Markers)
**Principle and Construction**: Lu et al. first fitted DNA methylation to **7 plasma protein surrogate markers** (e.g., ADM, B2M, Cystatin C, GDF15, Leptin, PACKYEAR (pack-years of smoking), TIMP-1) plus age and sex, then calibrated to all-cause mortality risk via Cox regression; the final model contains 1,030 CpG sites. GrimAge is currently the **epigenetic clock with the strongest mortality risk prediction** (each 1 SD acceleration → all-cause mortality HR≈1.5–1.6).

**Features and Limitations**: Integrates information on "smoking, inflammation, kidney function" with strong predictive power; but interpretation is complex (partially lifestyle surrogates), and the meaning of "biological age" is confounded. **Note**: GrimAge acceleration is largely driven by DNAm smoking surrogate marker (PACKYEAR) and inflammation/kidney function-related proteins (GDF15, Cystatin C) — smoking cessation and inflammation control can improve GrimAge, which is both an advantage (intervenable) and a limitation (may overestimate the impact of lifestyle on "aging itself").

**Key References**: Horvath S. *Genome Biology* 2013;14:R115. / Hannum G. *Mol Cell* 2013;49:359–367. / Levine ME. *Aging* 2018;10:573–591. / Lu AT. *Aging* 2019;11:303–327.

### 1.5 Epigenetic Clock Comparison Summary

| Clock | Number of Sites | Calibration Target | Tissue | Mortality Prediction | Intervention Sensitivity |
|---|---|---|---|---|---|
| Horvath | 353 | Chronological age | Pan-tissue | Moderate | Moderate |
| Hannum | 71 | Chronological age | Blood | Moderate | Moderate |
| PhenoAge | 513 | Phenotypic age | Blood | Strong | High |
| GrimAge | 1,030 | Mortality risk | Blood | Strongest (HR≈1.6) | High |

## II. Proteomic Clocks

### 2.1 Plasma Proteome and Aging (Lehallier 2019)
**Principle**: The plasma proteome reflects organ secretory activity and systemic status, undergoing non-linear changes with age. Lehallier et al. (*Nature Medicine* 2019) measured 2,925 plasma proteins in 4,263 individuals (ages 18–95), finding that changes concentrate at **three "waves" at ages 34, 60, and 78** (non-linear transitions) — around age 34, structural/metabolic-related protein changes; around 60, inflammation/immune-related; around 78, kidney function, etc. This suggests that aging is not uniformly linear but has key turning points.

### 2.2 OrganAge (2023, Organ-specific Protein Clock)
**Principle and Construction**: The Oh/…/Wyss-Coray team (*Nature* 2023) used **11 organs** (heart, brain, lung, liver, kidney, immune system, muscle, pancreas, intestine, adipose tissue, vasculature), each with 100–300 specific plasma proteins to establish organ age (OrganAge). Defined "organ age acceleration (age gap) = organ age − chronological age."

**Key Findings**: Approximately **20% of healthy individuals over 50 have ≥1 organ with significant accelerated aging** (acceleration >2 SD); organ acceleration independently predicts disease risk for the corresponding organ — e.g., heart acceleration → heart failure risk HR≈2.5; kidney acceleration → elevated mortality risk. Neuroimaging confirmed that brain acceleration correlates with actual structure (hippocampal atrophy, etc.). This is currently the most mature tool for organ-level aging assessment.

### 2.3 ProtAge and PAC (Mortality Risk Protein Clocks)
ProtAge (multiple teams around 2021): Fitted with all-cause mortality as the label using plasma protein panels; PAC (Proteomic Aging Clock, Argentieri 2022, *Nature Aging*) was constructed using UK Biobank data with **204 proteins**, predicting mortality and multimorbidity (HR≈1.7–2.0/1SD acceleration).

**Validation and Applications**: Protein clocks predict mortality risk comparably to or stronger than GrimAge; the advantage is traceability to organs/pathways (directly guiding intervention targets); the disadvantage is high protein detection cost, large batch effects, and insufficient racial coverage.

**Limitations**: Plasma proteins are affected by immediate physiological states (acute inflammation, eating, exercise); causality is unclear — protein changes may be consequences rather than drivers of aging; cross-platform (Olink/SomaScan) comparability remains to be resolved; **organ-specific protein selection depends on tissue expression profile databases, which may deviate from actual secretion**; accelerated organs show a "spreading" phenomenon over time (after one organ accelerates, others subsequently accelerate), with unclear mechanisms.

## III. Transcriptomic Clocks

**Principle**: Uses gene expression (mRNA abundance) as input to construct age models (Fleischer 2018 *Genome Research*, etc., using a 127-gene panel). Transcript levels bridge DNA methylation and proteins, theoretically capturing more proximal mechanisms (cell composition, stress response, inflammatory programs).

**Construction and Validation**: Training commonly uses multi-tissue RNA-seq/microarray data (GTEx, GEO public data), random forest/elastic net; prediction error on validation sets is approximately 4–6 years, lower precision than epigenetic clocks.

**Features and Limitations**: **High noise** — transcript levels are highly sensitive to tissue composition, circadian rhythms, and environmental stress (infection, fasting), with large intra-individual variation; severe cross-platform batch effects; lack of consensus on "biological aging" selectivity (which genes should be included); currently mainly used for mechanistic research and cell-type-level analysis (single-cell transcriptomic clocks), not as a clinical first choice.

## IV. Telomere Clocks

**Principle**: Leukocyte telomere length (LTL) shortens with age (see hallmark 2 in document 01), considered a readout of "replication history." Telomere clocks convert LTL (qPCR T/S ratio, Flow-FISH, or Southern blot) to "telomere age."

**Validation and Applications**: LTL is negatively correlated with age (shortening approximately 20–60 bp per year after adulthood); short LTL is associated with all-cause mortality, cardiovascular disease, and cognitive decline; but **individual variation is enormous, correlation with epigenetic age is weak (r≈0.3)**, and telomere shortening slows after age 60 — low resolution as a "clock."

**Limitations**: Large methodological variation (qPCR inter-laboratory CV is high); telomeres are strongly influenced by genetics (primarily paternal inheritance) and lifestyle (smoking, obesity, stress shorten them); cannot reflect organ-specific aging; as a single "age" output, it is less precise than methylation/protein clocks, more suitable as a mechanistic indicator used in combination with epigenetic/protein clocks.

## V. Four-type Clock Comparison Table

| Dimension | Epigenetic Clock | Protein Clock | Transcriptomic Clock | Telomere Clock |
|---|---|---|---|---|
| Input molecule | DNA methylation | Plasma proteins | mRNA | Telomere length |
| Representative model | Horvath/GrimAge | OrganAge/PAC | Fleischer 2018 | LTL |
| Age prediction accuracy | High (2–4 years) | Moderate (4–6 years) | Moderate-low (4–7 years) | Low (±8–10 years) |
| Mortality risk prediction | Strong (GrimAge HR≈1.6) | Strong (HR≈1.7–2.0) | Weak | Weak-moderate |
| Organ/pathway interpretability | Low | High (organ-specific) | Moderate | Low |
| Intervention sensitivity | High (PhenoAge/GrimAge) | Moderate-high | Low | Low |
| Cost/standardization | Moderate/good | High/moderate | Moderate/poor | Low/moderate |
| Main limitation | Racial bias, unclear mechanism | Batch effects, unclear causality | High noise | Low resolution |

**Conclusion**: The current mainstream is a "**methylation + protein**" dual-track approach — epigenetic clocks for overall aging rate, protein clocks for organ localization; transcriptomic and telomere clocks serve as auxiliary mechanistic indicators.

## V·supplementary Evidence for Clock Reversal: Can Aging Truly Be "Turned Back"?

The value of clocks lies not only in "readouts" but also in whether they can be "reversed" through intervention. Current evidence supporting clock reversibility comes from three levels:

**1. Epigenetic Reprogramming — The Strongest "Clock Reset" Evidence**
- In vitro: When somatic cells are reprogrammed to iPSCs, the Horvath clock output resets to zero (reprogramming "erases" epigenetic age) — this proves that epigenetic age information can be actively erased rather than only accumulating unidirectionally.
- In vivo: Lu 2020 (*Nature*) AAV-OSK delivery restored vision in glaucomatous mice, with retinal DNAmAge reversed; Macip 2024 (*Nat Aging*) old mice receiving AAV9-OSK showed multi-tissue clock reversal and 109% remaining lifespan extension — "clock reversal" and "functional reversal" occurred simultaneously.
- Human: ER-100 clinical trial (2026, Life Biosciences) uses epigenetic clocks as an exploratory endpoint; if data support it, this will be the first direct evidence of "human clock reversibility."
- See [Epigenetic Reprogramming Special Topic](../08-frontiers/01-reprogramming/01-concept.md) in this repository.

**2. Lifestyle Interventions — Small but Real Clock Improvements**
- CALERIE trial (2-year 25% caloric restriction): PhenoAge/GrimAge slowed by approximately 2–3 months (*Nature Aging* 2022) — correct direction but small effect size.
- Exercise intervention meta-analysis: Aerobic exercise for 6–12 months can improve epigenetic age acceleration (in some studies), but effects are moderate with heterogeneity.
- TRIIM trial (Fahy 2019, *Aging Cell*): Growth hormone + DHEA + metformin combination for 12 months, 4 clock sets reversed approximately 1.5–2.5 years (synchronized with thymus regeneration) — small sample, no control, but suggests "combination interventions may synergistically reverse clocks."

**3. Drug Candidates — Ongoing**
- Senolytics (D+Q/Fisetin), NAD⁺ precursors (NMN/NR), rapamycin (PEARL trial) all set PhenoAge/GrimAge as exploratory endpoints; results will determine whether clocks can become an "accelerated approval tool" for anti-aging drug development.

**Key Judgment**: Clock reversal has proof-of-principle evidence (reprogramming) and preliminary human data (TRIIM), but the question of "clock reversal ≠ lifespan extension" remains unresolved — direct evidence chains of "clock improvement → hard endpoint improvement" are needed. This is one of the most important validation tasks in the anti-aging field in the next 5–10 years (see the 31/40 score assessment for epigenetic reprogramming in [09-immortality/02-breakthrough-candidates](../09-immortality/02-breakthrough-candidates.md)).

## V·supplementary2 Limitations and Controversies of Clocks: The Difficulty of Measuring "Aging" Itself

**1. "Do clocks measure aging or health risk?"**
PhenoAge and GrimAge are calibrated to "phenotypic age" and "mortality risk" respectively, partially measuring current physiological health (albumin, CRP, kidney function, etc.) rather than pure epigenetic aging — "high sensitivity" and "confounding" are two sides of the same coin. The Horvath clock is "purer" but responds slowly to interventions. **No clock is a direct measurement of "aging itself"** — they are all statistical proxies of "age-related molecular patterns."

**2. Racial and Sex Generalization**
Mainstream clock training data is predominantly European-ancestry, with significantly larger errors for African/East Asian ancestry (Horvath clock error approximately 5–7 years for African ancestry vs. 3.6 years for European ancestry); sex differences are also underestimated (age acceleration distributions differ between males and females for the same clock). Cross-racial equitable clocks (e.g., the ABC 2023 Chinese Aging Biomarker Consortium effort) are a prerequisite for standardization.

**3. Time Scale Issues**
Clock changes are "slow variables": CALERIE's 2-year intervention yielded only a few months of clock difference, meaning **short-term trials (months) may not observe clock response** — this creates methodological difficulties for rapid validation of anti-aging interventions and has driven exploration of "fast clocks" (e.g., immune clocks, cellular senescence clocks).

**4. Unclear Causal Direction**
Are methylation site changes drivers or companions of aging? Current evidence leans toward "partially driving" (epigenetic reprogramming can reverse age phenotypes), but specific sites (which of the 353 Horvath CpGs are causal) are undetermined — "clock improvement" may be a consequence rather than a cause. The ICE experiment (Yang 2023, *Cell*) provided causal evidence for "epigenetic driving of aging" by inducing aging phenotypes through epigenetic enzyme disruption, but a single experiment is insufficient to conclude.

**5. Measurement and Standardization**
DNA methylation arrays (450K/EPIC) have acceptable cross-batch comparability, but plasma protein detection (Olink vs. SomaScan) has poor cross-platform consistency; telomere qPCR inter-laboratory CV can reach 10%+. **There is no unified "standard clock" and reference dataset**, making cross-study comparisons difficult — standardization efforts being promoted by WHO/international consortia (cross-platform benchmarks, racially balanced training sets) are a critical step for clocks to transition from research tools to clinical tools.

## VI. Current Status as Clinical Endpoints (FDA Attitude and CALERIE Lessons)

**Current Status**: The FDA has not approved any aging clock as a drug registration efficacy endpoint; the review framework requires that endpoints have direct or verifiable surrogate evidence of "clinical benefit (health improvement/disease reduction/survival extension)." Aging clocks are currently positioned as **exploratory biomarkers**, usable for Phase II dose/mechanism verification (proof-of-mechanism), but cannot replace hard endpoints.

**CALERIE Lessons (Key Case)**: CALERIE (Comprehensive Assessment of Long-term Effects of Reducing Intake of Energy, 2-year 25% caloric restriction randomized controlled trial, *Nature Aging* 2022 published epigenetic age analysis) — **the intervention group had significantly lower epigenetic age acceleration than the control group** (PhenoAge/GrimAge slowed by approximately 2–3 months), demonstrating that lifestyle interventions can change clock readings in randomized controlled settings. But there are three lessons: (1) Small effect size (2 years of CR yielded only a few months of clock reversal), the clock's "response resolution" to interventions is insufficient; (2) Different clocks do not fully agree (Horvath clock change not significant, PhenoAge/GrimAge significant), **clock choice determines conclusions**; (3) Whether short-term clock changes translate to long-term health/survival benefits **has not been validated** — i.e., "clock improvement" is a surrogate indicator, and its link to hard endpoints lacks direct evidence.

**Other Progress**: Multiple aging clinical projects (e.g., senolytics trials D+Q, NAD+ precursor trials) have set PhenoAge/GrimAge as exploratory endpoints; WHO/international aging biomarker consortia are advancing clock standardization (cross-platform, cross-racial benchmark datasets); **clock consensus (2023 multi-team statement)** recommends: reporting multiple clocks, pre-registration, using mortality risk-calibrated clocks for primary analysis.

## VII. Connection to the NO Pathway

1. **Mechanistic Coupling**: NO regulates epigenetic enzyme activity and mitochondrial metabolism via SIRT1/SIRT3 (see documents 04/06), theoretically capable of altering methylation drift rate; endothelial function (NO bioavailability) is an important determinant of vascular "organ clocks" — OrganAge's vascular/cardiac clocks are directly related to the NO pathway.
2. **Observational Evidence**: Interventions improving endothelial function (exercise, certain antihypertensives like ACEI) are associated with slowed epigenetic aging; chronic inflammation (a concomitant state of NO decline) accelerates PhenoAge/GrimAge — individuals with high IL-6 and CRP show more pronounced epigenetic age acceleration.
3. **Limitations**: Direct causal evidence between NO and clock changes is lacking (no randomized controlled clock data for NO pathway-specific interventions); clocks themselves do not "measure NO" but only indirectly reflect NO-related systemic status.
4. **Direction**: Randomized controlled trials of NMN/NR (NAD+ precursors → SIRT → eNOS upregulation) can be designed with PhenoAge/GrimAge + vascular clocks as endpoints to test "whether NO pathway interventions can reverse clocks" — this is the validation framework for documents 04–07 in this repository.
5. **Practical Tips**: For individuals, the greatest value of clock testing is not "calculating biological age" but **longitudinal tracking** — clock changes in the same person across different intervention stages (e.g., 6–12 months after starting regular exercise, smoking cessation, improved sleep) are more meaningful than a single absolute value. Since clocks are "slow variables," retesting at intervals of at least 6–12 months is recommended; combined with functional indicators such as FMD and PWV (see 02-vascular section) for cross-validation, to avoid being misled by a single reading. Aging clocks are the "ruler" for evaluating anti-aging interventions; using them correctly is more important than frequent testing.

## VII·supplementary Clinical Application Scenarios for Aging Clocks: From Health Checkups to Drug Development

Clocks are transitioning from research tools to clinical applications across multiple scenarios, but each scenario has different maturity levels:

**1. Health Checkups and Personal Health Management (Commercialized)**
Multiple commercial companies (e.g., TruDiagnostic, Elysium, and several domestic methylation testing agencies) offer "epigenetic age testing" services (saliva or blood spot samples, approximately 800–3,000 RMB), outputting DNAmAge and PhenoAge/GrimAge acceleration values. Uses: ① Baseline assessment and annual tracking of personal aging rate; ② Quantitative feedback on lifestyle intervention effects (exercise, diet, sleep, smoking cessation) — "test to know if it works"; ③ Early detection of "accelerated aging" signals (e.g., GrimAge acceleration indicating smoking/inflammation burden). **Limitations**: Commercial testing algorithm transparency varies, lacking clinical validation and regulation (most sold as "research services"), interpretation requires caution — 2–3 years acceleration is statistically common and does not represent "pathology."

**2. Exploratory Endpoints in Drug Clinical Trials (Ongoing)**
Almost all anti-aging intervention trials list clocks as exploratory endpoints: Senolytics (D+Q, Fisetin), NAD⁺ precursors (NMN/NR), rapamycin (PEARL), metformin (TAME substudy), epigenetic reprogramming (ER-100). The logic is "mechanism verification + dose selection": Phase II uses clocks to quickly compare "molecular efficacy" of different doses/regimens, screening for Phase III hard endpoint trials. **Key bottleneck**: Clock response is slow (months to years), effect size is small (CALERIE 2 years only 2–3 months difference), requiring large sample sizes.

**3. Organ-specific Early Screening (Frontier)**
OrganAge (2023, *Nature*) opened a new scenario: testing "which organ is accelerating aging" in people over 50, enabling targeted screening for corresponding diseases (heart acceleration → heart failure screening, kidney acceleration → kidney function monitoring, brain acceleration → cognitive assessment). This is the prototype of "personalized preventive medicine" — **from "overall biological age" to "organ age mapping."** Commercial translation (e.g., organ chips + proteomics detection combinations) is being explored.

**4. Forensic Age Estimation (Applied)**
DNA methylation age estimation is used in forensics for age estimation of unidentified individuals (error ±3–5 years), the most mature non-clinical application of clocks; it has been used as supporting evidence in some judicial proceedings.

**5. Insurance and Actuarial (Controversial)**
Clock-based "biological age" pricing has sparked ethical debates in the European and American insurance industries: on one hand, more precise risk stratification can optimize pricing; on the other, it may cause "genetic discrimination" and privacy risks — legislation in multiple countries (e.g., GINA Act framework) prohibits discrimination based on genetic/epigenetic information, and commercial clock applications must cross this regulatory red line.

**Comprehensive Judgment**: Clock clinical applications are penetrating along the path of "checkups → trial endpoints → early screening → forensics," among which **trial endpoints are the most critical link in the next 5 years** — if ER-100 or any anti-aging trial can use clock data to support regulatory dialogue (e.g., FDA's "biomarker qualification" process), clocks will upgrade from "exploratory" to "registrable" tools, fundamentally changing the pace of anti-aging drug development (see [04-ai-drugs/02-aging-clocks-clinical](../08-frontiers/04-ai-drugs/02-aging-clocks-clinical.md)).

---

## VIII. Open Questions

1. **Causal vs. Companion**: Are the methylation/protein changes measured by clocks **drivers** or **companion readouts** of aging? Current evidence leans toward "partially driving" (epigenetic reprogramming can reverse age phenotypes), but the causal contribution of specific sites is undetermined.
2. **Individualization and Racial Generalization**: Mainstream clock training data is predominantly European-ancestry, with larger errors for cross-racial (African, East Asian) populations — how to build racially equitable pan-clocks?
3. **Intervention Response Speed**: How long does an intervention need to be before clock changes stably reflect it (CALERIE took 2 years to see a few months difference)? Can more sensitive "fast clocks" be expected?
4. **Clock Consistency**: Different clocks (methylation vs. protein vs. organ) often give inconsistent conclusions for the same intervention — how to integrate them into a single reliable "multi-omics biological age"?
5. **Regulatory Translation**: What scale/duration of human trials is needed for the FDA to accept clocks as registration endpoints (the current biggest obstacle is the lack of direct evidence for "clock improvement → hard endpoint benefit")?

**Key References**: Horvath S. *Genome Biol* 2013;14:R115. / Levine ME. *Aging* 2018;10:573. / Lu AT. *Aging* 2019;11:303. / Lehallier B. *Nat Med* 2019;25:1843. / Oh HS et al. *Nature* 2023;624:164. / Argentieri MA. *Nat Aging* 2022;2:418. / Waziry R et al. *Nat Aging* 2023 (CALERIE epigenetic age analysis).
