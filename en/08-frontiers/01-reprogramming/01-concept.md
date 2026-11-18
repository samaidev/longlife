# Apparent Reprogramming 01: Concepts and Mechanisms

> Special topic: Epigenetic reprogramming · Article 1 / 4 articles in total
> Positioning: concepts and mechanisms (OSKM/OSK factors, partial vs complete reprogramming, apparent clocks, molecular switches)
> Related articles: For an overview of aging hallmarks, see 01-foundations/01-aging-hallmarks.md; for NO pathways, see 01-foundations/03-no-basics.md

## Core concepts

Epigenetic reprogramming refers to the use of a set of transcription factors (the core is Yamanaka factor OSKM: Oct4, Sox2, Klf4, c-Myc) or equivalent small molecules to "dial back" the gene expression program of adult cells to a younger or even pluripotent state. Its theoretical basis is a hypothesis that is being repeatedly tested by experiments: **Ageing is not just the accumulation of damage, but also the gradual loss and drift of epigenetic information (DNA methylation, histone modifications, chromatin organization)**; the "youth instructions" are still intact in the genome, and the role of reprogramming is to allow cells to read it again. Different from "delay" strategies such as clearing senescent cells (Senolytics) and nutrient-sensing intervention, epigenetic reprogramming is currently the only technical path that can **reverse biological age** (epiclock clock back, transcriptome rejuvenation) at the cellular level. It is regarded as the ultimate frontier of "rejuvenation", and its risks (dedifferentiation, carcinogenesis) and rewards (multi-system rejuvenation) are equally huge.

## 1. Genealogy: from cloned sheep to mountain factors

**1996 Dolly the sheep**: Wilmut's team injected the nuclei of adult mammary epithelial cells into enucleated oocytes to obtain a cloned sheep. Nuclear transfer (SCNT) proves a key fact - the genome of adult cells can return to a totipotent state under the action of the "reprogramming machine" in the oocyte cytoplasm, and cell identity and aging are not irreversible**. Although Dolly has left a shadow due to controversies such as short telomeres and lung disease, she provided the earliest experimental anchor for the concept of "reprogramming".

**2006 Shinya Yamanaka**: At Kyoto University, Takahashi and Yamanaka screened out **Oct4, Sox2, Klf4, and c-Myc four transcription factors** from 24 candidate factors, and obtained "induced pluripotent stem cells" (iPSCs) after transducing mouse embryonic fibroblasts, published in *Cell* 2006;126:663-676, which caused a sensation in the academic world; in 2007, human and mouse iPSCs were successively established (Takahashi et al. *Cell* 2007; Yu et al. *Science* 2007, using OCT4/SOX2/NANOG/LIN28 combination). In 2012, Yamanaka and Gurdon won the Nobel Prize in Physiology or Medicine. Reprogramming thus changes from "the mysterious power of the oocyte" to "four programmable molecular switches" - this is the starting point of the anti-aging intervention that this library focuses on.

## 2. Epigenetic basis of aging: drift, clock and chromatin

### 2.1 Epigenetic Drift

The global epigenetic changes accompanying aging are biphasic: **decreased global DNA methylation** (especially the repetitive element LINE-1/Alu, which can activate transposons and compromise genome stability), but **hypermethylation of specific CpG islands** (the promoters of tumor suppressor genes such as p16^INK4a are silenced). At the histone level: H4K16ac reduction, H3K9me3 heterochromatin relaxation (heterochromatin loss is a hallmark event of aging, Hutchinson-Gilford progeria syndrome is a Lamin A splicing mutation that causes nuclear tissue disintegration), H3K4me3/H3K27me3 ratio drift. These changes are not random noise but directional "drifts" coupled with "dedifferentiation-like" drifts in the transcriptome.

### 2.2 The epigenetic clock: a readout of age

In 2013, Horvath used 353 CpG sites, more than 8,000 samples, and 51 types of tissues to construct a pan-tissue epigenetic clock (*Genome Biol* 2013;14:R115). The median error in predicting age is about 3.6 years, and the correlation coefficient with chronological age is about 0.96. Therefore, DNA methylation has become the most reliable single-molecule readout of "biological age". The clock family has since expanded: Hannum clock (blood), PhenoAge (2018, predicts mortality), GrimAge (2019, predicts lifespan and healthspan), DunedinPACE (2022, measures aging rate). **Key Cognitive Leap**: The epizootic clock is not only a "reader", but may also be a "driver" - Sinclair's team used the ICE system (inducing DNA double-strand breaks to locally rearrange the epigenome without introducing mutations) in 2023 to prove that only disrupting epigenetic information can drive multi-system aging in mice, and the recovery is reversible (Yang et al., *Cell* 2023;186:305-326). This provides causal support for "reprogramming = reversal of apparent age = reversal of aging".

## 3. The whole chain of molecular mechanism (core)

### 3.1 Molecular division of OSKM factors

Four factors work together but perform their own duties, all of which are "pioneer factors" (pioneer factors that bind closed chromatin and recruit remodeling machinery):

| Factors | Primary Targets | Role in Reprogramming |
|---|---|---|
| Oct4 (POU5F1) | Pluripotency enhancer (such as NANOG, Sox2 itself) | Core founder, if missing, reprogramming cannot start |
| Sox2 | Pluripotency gene promoter/enhancer, co-binds with Oct4 | Forms Oct4-Sox2 complex with Oct4 to activate pluripotency network |
| Klf4 | Epithelial gene promoter, tumor suppressor network | Drives MET, inhibits apoptosis; can also promote cancer (double-edged sword) |
| c-Myc | Global active promoter | Chromatin "amplifier", promotes proliferation; has the highest risk of carcinogenesis, so it is usually eliminated in anti-aging programs |

### 3.2 Molecular process of reprogramming: MET → apparent reset → somatic memory erasure

Complete reprogramming (fibroblast → iPSC) is roughly divided into three stages:

1. **Mesenchymal-Epithelial Transition (MET)**: Fibroblasts are of mesenchymal phenotype. OSKM inhibits mesenchymal transcription factors such as Snail/Zeb1, upregulates E-cadherin, and cells acquire epithelial morphology and adhesion - this is one of the earliest molecular events (about 0-3 days), accompanied by the shutdown of TGF-β signaling and the upregulation of FGF/IGF signaling.
2. **Apparent reset**: The promoter of pluripotency loci (NANOG, OCT4 itself, etc.) acquires H3K4me3 (activation mark), loses H3K27me3 (repression mark), DNA methylation is dynamically rewritten by DNMT3A/3B (remethylation) and TET1/2/3 (active demethylation); heterochromatin remodeling, X chromosome reactivation (female), telomeres undergo TERT Elongated by re-expression, mitochondria convert from fragmented to fused networks and restore oxidative phosphorylation.
3. **Somatic memory erasure**: The remaining donor cell methylation marks (such as fibroblast-specific gene loci) on the iPSC genome are gradually erased with passage. The degree of erasure of "somatic memory" determines the differentiation bias of iPSCs, and is also molecular evidence of reprogramming "erasing the past".

```
OSKM (Pioneer Factor)
│ Binds to close chromatin and recruit SWI/SNF, histone modifying enzymes
▼
MET ──► Pluripotency network activation (Oct4-Sox2-NANOG positive feedback)
│ │
▼ ▼
TET1/2/3 active demethylation ◄── DNMT3A/3B demethylation
│ │
▼ ▼
Epigenetic clock site dialback ──► Young transcriptome / young chromatin state
│
▼
(Completely reprogrammed) iPSCs: Identity erasure + uncontrolled proliferation + teratoma risk
(Partial Reprogramming) Identity Preservation + Clock Rollback + Function Restoration ← Anti-Aging Route
```

### 3.3 Partial Reprogramming: Braking Before Identity Loss

**Complete reprogramming** (continuous expression of OSKM to a pluripotent state) erases cell identity and relieves proliferation inhibition. Abad 2013 (*Nature* 2013;502:340-345) and Ohnishi 2014 (*Cell* 2014;156:663-677) proved that continued expression in vivo can directly induce teratomas and cancers - it cannot be used as an anti-aging strategy. **Partial Reprogramming** Putting the brakes on identity loss: transient, pulsatile, periodic or tissue-localized expression of factors that only rolls back the apparent clock without changing cell type. Three engineering parameters determine the direction: **Factor combination** (OSK is used to eliminate c-Myc, and OS is used to eliminate Klf4 if necessary), **Expression duration** (day level instead of week level), **Period** (Ocampo 2016 classic plan is a 2-day on/5-day off cycle).

The mechanism can be summarized as follows: OSK briefly opens the "anterior hall" of pluripotency (partially opening the chromatin of NANOG and other loci), triggering a round of epigenetic reset centered on TET-mediated active demethylation, and then the factors are removed and the cells return to their original identity, but the completed methylation dialback and transcriptome rejuvenation are retained. Lu 2020 used TET1/TET2 knockdown to directly prove: **Remove TET, and the regeneration effect of OSK disappears** - This is causal chain evidence of "reprogramming = apparent age dialback", not correlational evidence. In addition, partial reprogramming is also accompanied by: downregulation of the expression of NF-κB target genes (IL-6, IL-8, TNF-α and other SASP factors), remodeling of senescence-associated heterochromatin foci (SAHF), and restoration of the enhancer-promoter loop to a youthful conformation. **Note**: Whether apparent dialback and functional recovery are synchronized is still an open question (see Section 8) - Lu 2020 is one of the rare studies that measured "methylation dialback" and "function (visual function, axon regeneration)" at the same time.

### 3.4 Comparison of delivery technology platforms: from genetic modification to chemical reprogramming

Partial reprogramming is moving from the laboratory to the clinic, and delivery technology is the core engineering bottleneck. Each of the four main platforms has trade-offs:

| Platform | Representative | Advantages | Limitations |
|---|---|---|---|
| Transgene induction (tetO system) | Ocampo 2016, Browder 2022 | Precisely controllable time (doxycycline switch), adjustable cycle | Integrated into the genome (risk of insertional mutations), immunogenicity, animals only |
| AAV vector | Lu 2020 (intraocular), Macip 2024 (intravenous) | Non-integrated (mainly free type), tissue-targetable | Irreversible expression (requires timing control elements), immunogenicity, long-term expression carcinogenic risk |
| Transient delivery of mRNA | In vitro verification stage | No genome integration, completely transient | Low delivery efficiency in vivo, need for repeated injections, LNP inflammatory response |
| Small molecule chemical reprogramming | Guan 2022 (*Nature*, human chemical reprogramming) | No genetic manipulation, oral/injectable, adjustable dosage | Low efficiency, complex mechanism, large specificity challenges |

**Key Engineering Judgment**: The delivery requirements for anti-aging applications are "short-lived, controllable, repeatable, and traceless" - the advantages of AAV are tissue-specific and long-lasting expression (with inducible promoter), while mRNA/small molecules are more in line with "pulsatile" requirements but the efficiency needs to be improved. **"Chemical reprogramming" (small molecule cocktails replacing transcription factors) is regarded as the ultimate ideal**: If oral small molecules can be used to simulate the apparent effects of OSK, the delivery problem will be completely solved (Guan 2022 has achieved chemical reprogramming to a pluripotent state in human cells, but "partial chemical reprogramming" for anti-aging is still in its early stages). This is also the engineering premise that [09-immortality/02-breakthrough-candidates](../../09-immortality/02-breakthrough-candidates.md) emphasizes when he lists epigenetic reprogramming as the "strongest candidate."

### 3.5 Systematic engineering control of security risks

The safety risks of partial reprogramming (teratomas, tissue failure, identity loss) are not a question of "whether to prevent it", but an engineering question of "how to systematically control it". Current design security redundancy levels include:

**1. Attenuation at the factor level**: Eliminating c-Myc (oncogenic amplifier) ​​is the first step; further, Klf4 can be eliminated (only OS dual factors are used, which is less effective but safer); or "engineered factors" (mutants retain apparent activity and reduce pro-proliferative activity) can be used - these are all reducing the "molecular basis of oncogenic potential".

**2. Switch of the timing control layer**: The doxycycline induction system (tet-on) is the gold standard - it is expressed only after administration and is closed when the drug is discontinued, making reprogramming a "reversible temporary program"; the 8-week time window switch used by ER-100 is the clinical implementation of this design. Even more cutting-edge are "suicide genes" (which can be used to eliminate reprogrammed cells with drugs after expression) as a last resort.

**3. Isolation of the tissue-limited layer**: Only express factors (tissue-specific promoters) in target tissues, limiting reprogramming to parts that "need regeneration" (eyes, joints, heart) to avoid systemic risks; the liver/intestine exemption plan (2023 *Nat Aging*) further reduces systemic toxicity - "systemic benefits, local risks" is the optimal solution.

**4. Sentinels in the monitoring layer**: Track the "identity loss critical point" with single-cell methylome/transcriptome and automatically terminate before crossing the pluripotency threshold; circulating free DNA methylation serves as a non-invasive sentinel to monitor systemic status (corresponding to the clock tool of [01-foundations/02-aging-clocks](../../01-foundations/02-aging-clocks.md)).

**Core Principle**: The security of reprogramming is not a "single point of protection" but a four-layer defense in depth** of "factor attenuation × time switch × tissue isolation × real-time monitoring" - each layer reduces the risk by an order of magnitude, and the superposition of the four layers constitutes a clinically acceptable safety spectrum. This is also the engineering logic of the ER-100's combined design of "AAV+OSK+doxycycline switch+eye restriction".

## 4. Grading of evidence

| Phenomenon | Level of evidence | Key documents |
|---|---|---|
| OSKM can reprogram adult cells into iPSCs | Real-life (reproducible, Nobel Prize-level) | Takahashi & Yamanaka, Cell 2006 |
| Cyclic in vivo partial reprogramming reverses multiple tissue aging markers in progeria mice and extends lifespan by about 30% | Strong (animal experiments, the mechanism is partially clear) | Ocampo, Cell 2016 |
| OSK restores the youthful methylation profile of optic ganglion cells, axon regeneration, and vision, dependent on TET1/2 | Strong (animal experiments, including mechanism and causal verification) | Lu, Nature 2020 |
| Transient reprogramming of human skin cells reverses apparent age by approximately 30 years and maintains identity | Strong (Ex vivo human cells, multi-omics) | Gill, eLife 2022 |
| Transient OSKM expression of elderly donor human cells restores proliferation and reduces SASP | Strong (isolated human cells) | Sarkar, Nat Commun 2020 |
| Partial reprogramming in vivo extends lifespan and reverses molecular age in physiologically aged (non-progeria) mice | Strong (animal experiment) | Browder, Nat Aging 2022 |
| Apparent clock predicts age/mortality | Real hammer (human observation, multi-cohort validation) | Horvath 2013; Lu GrimAge 2019 |
| Sustained OSKM induces teratoma/cancer in vivo | Real truth (animal experiment, safety warning) | Abad 2013; Ohnishi 2014 |
| Apparent information loss drives aging, recovery is reversible | Qiang (animal experiment, ICE system) | Yang, Cell 2023 |
| Efficacy of systemic reprogramming in humans | None (no human data yet; topical Phase I exploration only) | Turn Bio TRN-001 (details to be verified) |

## 5. Clinical/experimental evidence details

**Ocampo 2016 (*Cell* 167:1719-1733)**: The Belmonte team at Salk Institute performed **cyclic OSKM expression (2 days on/5 days off, from 8 weeks of age to the end)** on progeria mice (Lmna mutant LAKI model, natural life span of about 5 months), and the median life span was extended by about 30%; aging markers (SA-β-gal, p16, p21) in skin, pancreas, spleen, muscle and other tissues were reduced, and grip strength and coordination were improved; 12-month-old wild-type mice were briefly induced for 1 week, and the pancreas and muscle regeneration abilities were restored. **Milestone**: For the first time, it was proven that "partial reprogramming can improve physiological functions in vivo without the occurrence of tumors."

**Lu 2020 (*Nature* 588:124-129, cover article)**: Sinclair's team used AAV to deliver OSK to mouse retinal ganglion cells (RGC). Axonal regeneration was significantly enhanced in the optic nerve pressure injury model; vision (visual acuity, contrast sensitivity) was restored in glaucoma models (increased intraocular pressure) and elderly mice (over 12 months old); the DNA methylation profile of RGCs overall shifted back to a younger state, and the transcriptome became younger. **Axonal regeneration and vision benefits disappear after knocking down TET1/TET2** - Proving that active demethylation is necessary for the effect directly advances "reprogramming to reverse aging" from correlation to causation.

**Gill 2022 (*eLife* 11:e73578, Babraham Institute)**: "maturation phase transient reprogramming": Dermal fibroblasts were taken from 3 middle-aged donors (average about 50 years old), expressed OSKM and then removed for about 10–17 days, allowing the cells to "mature" and return to fibroblast identity. Results: **The apparent clock was turned back by about 30 years**, the transcriptome and metabolome were younger, collagen synthesis and migration abilities (wound healing-related phenotypes) were restored, and no pluripotent state was entered, and no tumors formed. **Significance**: Human-derived cells, physiological age callback, and identity maintenance are all established at the same time. A subsequent single round of transient reprogramming of the same system also reproduced multi-omics rejuvenation in multiple tissues (pancreas, etc.) of naturally aging mice (Chondronasiou, *Aging Cell* 2022;21:e13578).

**Sarkar 2020 (*Nat Commun* 11:1545)**: Stanford Sebastiano's team used **non-integrating modified mRNA** (no genome integration, no risk of insertional mutation) to transiently express OSKM to treat human skin fibroblasts and chondrocytes from elderly donors: cell proliferation resumed, aging markers (p16, SA-β-gal, SASP factors) decreased, and apparent age dialed back. **Significance**: It proves that the safest grade of "instantaneous, non-integrated" delivery is enough to produce partial rejuvenation, paving the way for clinicalization.

**Browder 2022 (*Nat Aging* 2:243-253)**: The Belmonte team performed cyclic OSK/OSKM induction on **physiologically aged (non-progeria)** mice for about 7 months starting from 15 months of age. The lifespan was significantly extended (the reported median lifespan was extended by about 9–10%, the specific value is subject to the original text), and the apparent age and transcriptome age of tissues such as skin, kidney, and liver were reversed. **Significance**: Partial reprogramming is also effective in the normal aging process, not just in repairing inherited progeria.

**Nervous system extension**: Rodríguez-Matellán 2020 (*Stem Cell Reports* 15:1056-1066, Serrano/Ávila team) Induces partial reprogramming in cells in the dentate gyrus (hippocampal neurogenesis region) and improves memory in aged mice; 2024 Neuron-restricted periodic OSKM overexpression further shows cognitive enhancement (*Commun Biol*, doi:10.1038/s42003-024-06328-w). Wang 2021 (*Nat Commun* 12:3094) Demonstrates that partial reprogramming of muscle fibers promotes muscle regeneration by remodeling the stem cell microenvironment; 2023 Liver/gut-exempt reprogramming protocol reduces toxicity (*Nat Aging* 3:1509-1520).

**Clinical Translational Status**: No human systemic data available as of 2025. Turn Biotechnologies' TRN-001 (mRNA topical preparation encoding OSK) has entered Phase I clinical trials in the United States and completed the first dose (reported in a press release, specific results are to be verified); the details of "Short-term expression of OSK in skin cells of a 96-year-old donor for 3 days reverses apparent age (Cell 2025)" quoted in the original document also need to be verified. In vivo delivery is still dominated by AAV/mRNA, and small molecule cocktails (mimic factor effects) are still in the laboratory stage.

**Significant Advances - ER-100 human trials (starting March 2026)**: Life Biosciences (co-founded by David Sinclair)'s ER-100 becomes **the world's first partial reprogramming therapy to enter humans**: AAV delivers OSK Trifactor (knocks out oncogene c-Myc) + oral doxycycline switch (8 The reprogramming program can be started/stopped within the weekly time window), and the indications are open-angle glaucoma and non-arteritic anterior ischemic optic neuropathy (NAION) - the logic of selecting the eye is "immune privileged area + quantifiable efficacy (visual acuity)". It was approved by the FDA to start in January 2026, and the first dose was completed in March. The clinical trial number is NCT07290244. **Significance**: ① It proves that regulatory agencies accept "partial reprogramming" as a registrable intervention category; ② The "disease-based entry" path (which is safe and effective for a single indication before expanding to the whole body) is officially implemented; ③ If the Phase I safety readout goes smoothly, it will be the first direct data point to verify "reversibility of human apparent age" - this is [09-immortality/02-breakthrough-candidates](../../09-immortality/02-breakthrough-candidates.md) Rating epigenetic reprogramming as the "closest to an immortal drug" as a clinical pillar. It should be noted that ER-100 is administered locally into the eye and is still far from "systemic reverse failure"; the primary endpoint of Phase I is safety, and efficacy and clock-back data need to wait for subsequent readout.

## 6. Contact NO / NAD+ / longevity network

**NAD+/SIRT1 axis is the efficiency switch of reprogramming**: SIRT1 is a NAD+-dependent deacetylase. Mechanistic studies show that SIRT1 deletion significantly reduces iPSC generation efficiency, while NAD+ precursor (NMN/NR) supplementation can improve reprogramming efficiency - NAD+ metabolism affects epigenetic resetting through SIRT1 deacetylation of histones and transcription factors (including pluripotency network components) (see details 01-foundations/03-no-basics.md). **Conversely**, partial reprogramming restores mitochondrial function and a youthful metabolic state, which may increase the NAD+/NADH ratio, forming a positive feedback of "reprogramming→NAD+ recovery→SIRT activity↑→apparent rejuvenation"; whether this is a driver or a companion, there is no conclusion yet.

**Direct intersection between NO and epigenetic modification**: Mechanistic studies show that NO can modify DNMT1/DNMT3B through S-nitrosylation, inhibiting its activity and changing the DNA methylation pattern (the specific site needs to be verified); NO→cGMP→PKG also affects the activity of histone modification enzymes. This means that reduced endothelial function (eNOS downregulation, reduced NO bioavailability) not only damages blood vessels, but may also accelerate epigenetic drift through an imbalance in methylation homeostasis—NO supply may serve as an "upstream throttle" for epigenetic reprogramming.

**Shared downstream anti-inflammatory nodes**: Partial reprogramming inhibits NF-κB driven SASP; NO deacetylation of p65 (K310) via SIRT1 or direct S-nitrosylation of p65 also inhibits NF-κB. The two pathways converge at "Reducing Chronic Inflammation (Hallmark 12)," suggesting synergistic potential for the NO pathway and reprogramming. Corresponding to the 12 major hallmarks of aging, partial reprogramming touches multiple markers such as epigenetic changes, telomere loss, cell senescence, stem cell exhaustion, mitochondrial disorders, and changes in intercellular communication in one go. It is the single intervention with the widest coverage (see 01-foundations/01-aging-hallmarks.md for details).

## 7. Intervention directions and executable suggestions

1. **Three main lines of delivery**: ①AAV/lentiviral vector (tissue-specific promoter + doxycycline/tamoxifen inducible switch); ②Modified mRNA transient expression (no integration, no insertional mutations, the safest profile); ③Small molecule cocktail (low cost, oral, but specificity and efficacy need to be verified). Combination punch: tissue-specific promoter + inducible switch + pulse administration (2 days on/5 days off).
2. **Safety window calibration**: Systematic titration based on the three-dimensional matrix of "dose × duration × cycle interval" - the same tissue is set to have a 2/4/7/14 day gradient of OSK expression, and the single cell methylome + transcriptome tracks the callback trajectory to find the safety window of "maximum callback and zero identity loss"; TET inhibitors are used as negative controls to verify the causality of the mechanism.
3. **Monitoring system**: Develop non-invasive in vivo epigenetic clocks (circulating free DNA methylation, blood cell clock) as clinical endpoints and safety sentinels.
4. **Alternative path that can be implemented in the near future** (honest label: non-reprogramming): NAD+ precursor (NMN/NR) + aerobic exercise maintains eNOS/NO and SIRT activity, indirectly slowing down the apparent drift rate; this is currently the only "apparent protection" intervention that has been verified by humans.
5. **Combination strategy**: Senolytics removes senescent cells + partial reprogramming to restore youthfulness + exercise/CR maintains metabolism, covering the three sections of "clearance-reversal-maintenance" (see subsequent articles of the topic for details).

## 8. Open issues and controversies

- **Dedifferentiation-cancer boundary**: The timing of braking depends on system-level dynamics, and individual differences are large; Klf4/c-Myc itself is a proto-oncogene, and there is no quantitative answer to how much its efficacy will decrease after deletion.
- **Readings vs. Function**: Does apparent clock resetting necessarily accompany restoration of function? Partial decoupling of methylation dialback from phenotypic restoration in Gill 2022; the possibility of "young reading, old function" requires validation of efficacy with functional endpoints rather than clocks.
- **Delivery Bottlenecks**: Organ targeting, immunogenicity and integration risk of AAV; tolerance to repeated dosing of mRNA; systemic vs local (liver/gut exempt regimen shows significant reduction in toxicity, but at much sacrifice in coverage).
- **The nature of apparent age**: Most clock sites are "passenger" sites next to CpG islands, and may not be causal sites of aging; whether reprogramming dials back is the "driving" methylation still awaits single-cell causal experiments.
- **Ethics and Fairness**: If human body weight is programmed into a drug, is it treatment or enhancement? There is no precedent for cost and accessibility, nor for long-term carcinogenicity monitoring cycles (decades).
- **Scientific Controversy**: Some laboratories failed to fully reproduce the lifespan effect of partial reprogramming in vivo; the non-monotonic nature of the dose-response curve (overexpression is harmful) invalidates the "more is better" intuition.

## 9. References

1. Takahashi K, Yamanaka S. Induction of pluripotent stem cells from mouse embryonic and adult fibroblast cultures by defined factors. Cell 2006;126:663-676.
2. Wilmut I, et al. Viable offspring derived from fetal and adult mammalian cells. Nature 1997;385:810-813.
3. Horvath S. DNA methylation age of human tissues and cell types. Genome Biology 2013;14:R115.
4. Ocampo A, Reddy P, Martinez-Redondo P, et al. In vivo amelioration of age-associated hallmarks by partial reprogramming. Cell 2016;167:1719-1733.
5. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. Nature 2020;588:124-129.
6. Gill D, Parry A, Santos F, et al. Multi-omic rejuvenation of human cells by maturation phase transient reprogramming. eLife 2022;11:e73578.
7. Sarkar TJ, Quarta M, Mukherjee S, et al. Transient non-integrative expression of nuclear reprogramming factors promotes multifaceted amelioration of aging in human cells. Nat Commun 2020;11:1545.
8. Browder KC, Reddy P, Yamamoto M, et al. In vivo partial reprogramming alters age-associated molecular changes during physiological aging in mice. Nat Aging 2022;2:243-253.
9. Yang JH, Hayano M, Griffin PT, et al. Loss of epigenetic information as a cause of mammalian aging. Cell 2023;186:305-326.
10. Abad M, Mosteiro L, Pantoja C, et al. Reprogramming in vivo produces teratomas and iPS cells with totipotency features. Nature 2013;502:340-345.
11. Ohnishi K, et al. Premature termination of reprogramming in vivo leads to cancer development through altered epigenetic regulation. Cell 2014;156:663-677.
12. Rodríguez-Matellán A, Alcazar N, Hernández F, Serrano M, Ávila J. In vivo reprogramming ameliorates aging features in dentate gyrus cells and improves memory in mice. Stem Cell Reports 2020;15:1056-1066.
13. Wang C, et al. In vivo partial reprogramming of myofibers promotes muscle regeneration by remodeling the stem cell niche. Nat Commun 2021;12:3094.
14. Chondronasiou D, et al. Multi-omic rejuvenation of naturally aged tissues by a single cycle of transient reprogramming. Aging Cell 2022;21:e13578.
15. Lu AT, et al. DNA methylation GrimAge strongly predicts lifespan and healthspan. Aging 2019;11:303-327.
