# Epigenetic Reprogramming 03: Safety Risks – Tumor Risk, Off-Target Effects and Dosage Window

> Special Topic: Epigenetic Reprogramming · Article 3 / Total 4 Articles
> Positioning: Safety risk panorama and avoidance strategies (carcinogenesis, teratoma, epimutation, immunogenicity, uncontrolled dedifferentiation, dose window, supervision and ethics)
> Related documents: For concepts and mechanisms, see `01-concept.md`, for animal evidence links, see `02-animal-evidence.md`, for technology roadmaps, see `04-roadmap.md`; for NO/NAD⁺ main lines, see `01-foundations/03-no-basics.md`

## 1. Core concepts

The safety risk is not a "side effect" of reprogramming therapy, but two sides of its mechanism: the essence of reprogramming is to "regress" somatic cells back to a young and even pluripotent state, and the end point of "regression" - pluripotency - is exactly the starting point of tumor occurrence in the body. **c-Myc in Yamanaka factor (OSKM) is a recognized proto-oncogene**, and Oct4/Sox2 is the master switch of pluripotency; once the expression of the factor crosses the threshold and erases cell identity, it will appear as teratoma or precancerous lesions derived from dedifferentiation in the body. All known risks (carcinogenic, immune, integrative mutations, epimutations, tissue-specific toxicity) share the same set of underlying parameters: **expression intensity × duration × coverage**, the "dose window". The entire task of the safety study is to keep these three parameters within the range where "the apparent age is dialed back in place, but the pluripotency program has not yet been ignited." Understanding the dosage window is the dividing line between "anti-aging therapy" and "carcinogenic procedures."

## 2. The whole chain of risk mechanism

### 2.1 c-Myc oncogenic axis: proto-oncogenic activity of the factor itself

Yamanaka initially used four factors (Oct4, Sox2, Klf4, c-Myc) to induce iPSCs, of which **c-Myc and Klf4 themselves are proto-oncogenes** (Takahashi & Yamanaka, 2006). As a basic helix-loop-helix (bHLH) transcription factor, c-Myc forms a heterodimer with Max, binds to the E-box sequence, and directly or indirectly regulates the transcription of about 15% of human genes - covering cell cycle (Cyclin D/E, CDK), ribosome biogenesis (RNA polymerase I/III transcription), biosynthetic metabolism (glutamine metabolism, nucleotide synthesis) and apoptosis inhibition. The dangers of this axis are:

```
c-Myc continues to be highly expressed
│
├─→ CyclinD/E + CDK4/6 ↑ → G1/S checkpoint loss → uncontrolled proliferation
├─→ p53/p21 pathway is suppressed → DNA damage does not trigger apoptosis → mutation accumulation
├─→ Ribosome/mitochondria biogenesis ↑ → Metabolic reprogramming to "proliferative"
├─→ Telomerase (TERT) reactivation → The replicative senescence barrier is dismantled
└─→ Cooperates with Klf4 → Acquisition of cell "stemness" → Tumor initiation
```

Key chain of evidence: The Yamanaka team discovered the next year that **about 20% of chimeric mice generated with c-Myc-containing iPSCs developed tumors** (Okita et al., 2007, Nature); after c-Myc was deleted, the chimeras no longer formed tumors, only at the expense of reduced efficiency (Nakagawa et al., 2008, Nat Biotechnol). Since then, iPS technology has shifted to "factor subtraction" - **OSK three factors** have become the standard configuration for in vivo reprogramming. But we must be clear: c-Myc is just "removed from the formula", and the MYC network (endogenous promoter containing c-Myc) can still be transactivated by the partial reprogramming program of Oct4/Sox2; partially reprogrammed cells (pre-iPSC) are often accompanied by upregulation of endogenous Myc expression and apparent silencing of the p53 pathway - **"No Myc formula" does not mean "no Myc risk"**.

### 2.2 Uncontrolled dedifferentiation and undifferentiated cells remaining

The pluripotency program is a positive feedback cascade: Oct4/Sox2 activates NANOG and Lin28, and NANOG in turn strengthens Oct4/Sox2 to form a self-sustaining "pluripotency engine." For in vivo applications, the danger is not in the engine itself, but in the braking point: once the factor expression time is long enough and the intensity is high enough, the cell crosses the irreversible threshold (approximately when the NANOG promoter is apparently unlocked), the identity genes of the differentiated cells are silenced on a large scale (such as skin keratin, liver albumin), and the cells return to an "embryonic-like" state.

```
Somatic cells──(OSKM short-term/low-intensity)──→ Partially reprogrammed cells (identity preservation, clock reset)★Treatment goals
│
└──(OSKM continuous/high intensity)──→ pre-iPSC (identity swing, abnormal proliferation, genomic stress)
│
├─→ Completely reprogrammed iPSC → Teratoma (triblast ectopic tissue)
└─→ Stagnant pre-iPSC → Remaining undifferentiated cells → Tumor origin
```

Two lethal outcomes have been directly recorded in animal experiments: **Abad et al. (2013, Nature)** used a systemic inducible OSKM system to directly reprogram mice. Teratoma-like structures appeared in multiple organs (stomach, intestine, kidney, skin), some containing early embryonic tissue, and were accompanied by immune system dysfunction; **Ohnishi et al. (2014, eLife)** found that mice that continued to express OSKM in the body were about 1 Death occurs within weeks, clusters of dedifferentiated cells appear in the liver and gastrointestinal tract, and some transform into true tumors. These two experiments established an iron rule: **In vivo reprogramming must be "cyclical" rather than "continuous"**. In addition, even if the therapeutic reprogramming itself is successful, if the leakage of the delivery vector or promoter causes a small number of cells to stagnate in the pre-iPSC state, the risk will exist in the form of "residual undifferentiated cells" for a long time. It is recognized in the field of iPSC cell therapy that residual undifferentiated cells (the ratio is as low as 10⁻⁵–10⁻⁶) in the transplanted cells can form teratomas. Therefore, in clinical practice, flow cytometry screening for surface markers such as SSEA-1/TRA-1-60 is a mandatory quality control step (for details, see 4.4).

### 2.3 Epimutation and genome instability

The reprogramming process itself is an "overhaul" of the epigenome: large-scale erasure of DNA methylation (TET enzyme-mediated oxidative demethylation), rearrangement of histone modifications, and reorganization of higher-order chromatin structure (TAD/compartments). A side effect of this process is epimutation - the methylation pattern deviates from the normal developmental trajectory during "rewriting", forming stable abnormal methylation sites. Mechanistic studies have shown that DNA replication and apparent rewriting are out of sync during partial reprogramming, and replication stress is prone to occur at immature replication forks, inducing DNA double-strand breaks; at the same time, c-Myc-driven high proliferation in the early stages of reprogramming and "reprogramming stress" (reprogramming stress) activate the p53/INK4a checkpoint, and cells tend to survive in an "escape checkpoint" manner under stress - this is the classic script for tumor initiation. Quantitative evidence: The iPSC literature generally reports that reprogrammed clones have hundreds to thousands of aberrant methylation sites (some from "epigenetic memory" residues, some from newly generated epimutation), a few of which fall in the promoter or enhancer regions of tumor suppressor genes, with unknown long-term consequences. **Partial reprogramming in vivo does not enter the pluripotent state, and its apparent perturbation amplitude is smaller than that of complete reprogramming. However, whether the "callback" itself introduces new epimutation, there is currently a lack of long-term follow-up data at the genome-wide level** - this is one of the weakest links in the safety demonstration.

### 2.4 Immunogenicity: carrier, foreign protein and pre-existing antibodies

Three immune attack paths exist simultaneously:

1. **Viral capsid immunity**: AAV capsid protein can be dually recognized by humoral immunity (neutralizing antibodies) and cellular immunity (CD8⁺ T cells clear transduced cells). The positive rate of pre-stored neutralizing antibodies in the population is about 1/3–1/2, and that of AAV9 is about 1/3** (Mingozzi & High, 2013). Individual differences are large, which directly determines the failure of the standardized dose; the hepatotoxicity of high-dose AAV (the elevation of transaminases caused by the clearance of transduced cells by T cells) has been recorded in gene therapy clinical trials.
2. **Exogenous transcription factor protein immunity**: OSK is a "self-protein" and is theoretically immune tolerant; however, when expressed for a long time and at high intensity, the factor epitopes presented by MHC-I on the surface of transduced cells may break tolerance and trigger autoimmune attacks against "reprogrammed cells" - Mechanism research shows that the stronger and longer the duration of transgene expression, the higher the risk.
3. **Anti-drug antibodies**: If a doxycycline (Dox)-induced switch is used, long-term Dox administration itself has dose-related side effects (intestinal flora, mitochondrial toxicity) and relies on patient compliance - failure of the switch means "continuous expression" and a direct slide to the dedifferentiation zone.

### 2.5 Tissue-specific risks: brain and heart

Different organizations have different risk profiles:

- **Brain/Nerve**: The "reprogramming window" of neurons is extremely narrow - OSK needs to balance the benefits of axonal regeneration against identity drift. Mechanistic studies have shown that excessive or prolonged factor expression can cause abnormal synaptic remodeling and excitability changes in cortical neurons, and even induce neurons to "drift" toward non-neuronal fates (some studies have observed ectopic expression of neural precursor markers). The optic nerve regeneration experiment (Lu 2020) confirmed the feasibility, but also suggested that the window is measured in "weeks" rather than "months".
- **Heart**: Cardiomyocytes are terminally differentiated cells, and the proliferation signals induced by reprogramming may trigger **arrhythmia** (ectopic pacing activity) or cardiac hypertrophy; the cardiac regeneration route of "partially reprogramming" fibroblasts into cardiomyocyte-like cells has a safety issue in that cells with incomplete transdifferentiation form arrhythmogenic foci. Currently, the cardiac direction has the least data and the highest risk level.
- **Liver/metabolic tissue**: The liver has strong regenerative capacity and high transduction efficiency (AAV is naturally hepatotropic). It is the "easiest" target organ, but the risk of hepatocellular carcinoma also requires the most vigilance - in the c-Myc-driven mouse liver cancer model, partial reprogramming of liver cells can accelerate tumor initiation.
- **Retina**: immunoprivileged tissue + topical delivery + non-essential organ, lowest risk, therefore preferred for human trials (logical basis for ER-100 selection of NAION indication).

### 2.6 Dosage Window: The Master Switch for Risk

```
Dose (Intensity × Duration × Coverage)
──|──────────|─────────────────|───────────|──▶▶
No effect Apparent dial-back window Pluripotency activation Complete dedifferentiation
(Waste) (★Treatment Area) (Warning Area) (Danger Area: Teratoma/Cancer)
↑Security window
Window boundaries are defined by 3 measurable markers:
① Methylation age dialback amplitude (Horvath clock)
② Pluripotency gene expression (NANOG, SSEA-1) - must be zero
③ Proliferation/genomic stress markers (γH2AX, p53 target genes) – must be at baseline
```

The key conclusion comes from Ocampo et al. (2016, Cell): **Periodic** (e.g., 2 days on/5 days off) OSKM expression safely improves multi-organ aging phenotypes in premature aging (LAKI) mice without producing teratomas; whereas continued expression in the same system is lethal. Macip et al. (2021) further showed that the **dosing rhythm itself is more important than a single dose in determining safety**—the same factor, periodic expression can extend lifespan, and continuous expression can cause disease. The safety window is therefore a "dynamic rhythm window" rather than a static concentration threshold.

## 3. Grading of evidence

| Risk | Phenomenon | Level of evidence | Key documents |
|---|---|---|---|
| c-Myc causes cancer | About 20% of c-Myc iPSC chimera mice develop tumors; deleting Myc does not form tumors | Real hammer (mouse) | Okita 2007 Nature; Nakagawa 2008 Nat Biotechnol |
| Sustained reprogramming in vivo leads to death | Mice with sustained systemic OSKM expression die in about 1 week with multi-organ teratoma/dedifferentiation | Real hammer (mouse) | Ohnishi 2014 eLife; Abad 2013 Nature |
| Cyclic expression safety | Cyclic OSKM life extension and teratoma-free | Live hammer (mouse) | Ocampo 2016 Cell; Macip 2021 |
| Undifferentiated residual teratomas | Residual undifferentiated cells in transplanted cells can cause teratomas | Real hammer (consensus in the field of iPSC cell therapy) | Review of iPSC transplantation literature |
| Viral vector integration mutations | Retroviral insertion activates LMO2 leukemia (SCID-X1); AAV low frequency integration | Real hammer (human, retrovirus); Animal support (AAV) | Hacein-Bey-Abina 2003 Science |
| AAV immunogenicity | Pre-existing neutralizing antibodies, T cell depletion of transduced cells, dose-related hepatotoxicity | Reality (human, gene therapy trial) | Mingozzi & High 2013 Blood |
| Epigenetic mutations | Abnormal methylation sites present in reprogrammed clones | Animal support/mechanistic speculation (long-term consequences in vivo unknown) | iPSC epigenetic studies |
| Brain/heart specific toxicity | Neuronal identity drift, arrhythmia risk | Mechanism speculation/preliminary animal support | To be verified (preclinical research) |
| Human Safety Window | ER-100 Phase I (2026 launch), no readout data | Ongoing | Life Biosciences Announcements |

## 4. Clinical/experimental evidence details

### 4.1 Two "Death by Reprogramming in the Body" Warnings

- **Abad et al. 2013 (Nature 502:340)**: OSKM was induced systemically in transgenic mice. Teratoma-like lesions (including endoderm, mesoderm, and ectoderm structures) were detected in 8 organ systems, and some clones expressed totipotency markers (Zscan4, etc.); immune system abnormalities (thymic atrophy, T cell reduction) were also observed. Conclusion: Complete reprogramming in vivo = creation of teratomas.
- **Ohnishi et al. 2014 (eLife 3:e01685)**: Mice with sustained OSKM expression in vivo died within about 1 week; clusters of dedifferentiated cells in the liver and gastrointestinal tract appeared before death, and cells with "premature termination" evolved into tumors at a higher frequency - **Halfway reprogramming is more dangerous than complete completion**, because the stalled cells are in an intermediate state where "proliferation has been initiated and differentiation has been lost". This discovery directly defines the clinical logic: either it does not start or it completes the safe rhythm, and it must not be "hanging in mid-air".

### 4.2 Quantitative evidence for life-extending dose windows

- **Ocampo 2016 (Cell 167:1719)**: Cyclic expression of OSKM (2-day induction/5-day rest cycle) improves aging markers in muscles, pancreas, and spleen of LAKI progeria mice, and extends lifespan, with **no teratomas**.
- **Macip et al. 2021**: AAV9 delivery can induce OSK to 124-week-old wild-type old mice, and the remaining median life span is extended from 8.86 weeks to 18.5 weeks (**+109%**); no tumors were found in histopathology, confirming that there is a safety window for "pulsatile, systemic" administration.
- **Lu et al. 2020 (Nature 588:124)**: A single intraocular injection of AAV2-OSK, expressed for about 1 month, dialed back the methylation clock of retinal ganglion cells, axonal regeneration, and vision recovery in optic nerve pinch and glaucoma models; **The effect disappeared after knocking down TET2 in vivo**, proving that the dialing back relies on TET-mediated active demethylation—that is, there is a clear molecular executor of "apparent age reversal". The study also showed that localized administration of tissue can reduce the risk to a single organ.
- **Chondronasiou et al. 2022 (Nat Aging)**: Single-cycle transient reprogramming of naturally aging mice, skin and kidney multiple omics were reset to a younger state, and no teratomas were detected in the whole tissue - the safety margin of "one cycle" was thus established.

### 4.3 Current status of human trials (as of 2026)

- **Life Biosciences / ER-100**: AAV2-OSK + doxycycline-induced switch, indicated for non-arteritic anterior ischemic optic neuropathy (NAION), **The world's first human administration** was completed on 2026-06-09, and it is a Phase I safety trial; preclinical showing vision recovery potential in elderly monkeys. Ophthalmology selection logic: immune privilege + local administration + non-essential organs, risk-benefit is the most favorable.
- **NewLimit** (founded by Brian Armstrong in 2022): uses high-throughput screening + machine learning to find a combination of factors that "reprogram apparent age". Laboratory data claims that age reversal is achieved in **human liver cells**; it will complete a **435 million US dollar Series C** in 2025 (cumulative financing exceeds 630 million), and plans to launch the first human trial for **alcohol-related liver disease**. Its strategy circumvents c-Myc with viral vectors (non-integrated delivery), but there are still no human data.
- **Altos Labs**: High investment "apparent information theory" route (mesenchymal drift hypothesis, 2025), mainly animal model verification, human trials have not been started.
- **Retro Biosciences** (supported by Sam Altman): Multi-target longevity pipeline including reprogramming direction, in preclinical stage.
- Overall judgment: **Human data are only a starting point for "safety ramping" and there are no efficacy readouts; all "age reversal" claims are based on in vitro cell or mouse data**.

### 4.4 The double-edged sword of cancer stemness and reprogramming

Dedifferentiation and tumor initiation share the same molecular language: stem cell markers (OCT4, SOX2, NANOG, KLF4) are highly expressed in the cancer stem cell (CSC) subpopulation of a variety of solid tumors and are positively correlated with chemotherapy resistance and metastasis. This means that there is no molecular firewall between the "lower edge" of the reprogramming dose window (just dialed back, just below pluripotency) and the acquisition of cancer stemness - **signals that promote dedifferentiation are also signals that promote tumor stemness**. On the other hand, this also gave rise to the strategy of "fighting fire with fire": stress induced by partial reprogramming can awaken the p53 checkpoint and senescence program, and in some studies, short-term reprogramming actually eliminates senescent cells; in addition, the embryonic antigens (SSEA-1, TRA-1-60) exposed on the surface of dedifferentiated cells make them immune surveillance targets, and the immune system is the last line of defense against reprogramming carcinogenesis. This is why the inflammation/NO microenvironment can influence the outcome (see Section 5).

## 5. Connection with NO/NAD⁺/Longevity Network

- **NO and reprogramming efficiency**: Mechanistic studies show that NO signaling is involved in the maintenance of pluripotency and the early "metabolic switch" of reprogramming (oxidative phosphorylation → glycolysis). The expression of iNOS/eNOS is up-regulated during the reprogramming process. NO donors can improve the efficiency of iPSC generation in mice (details need to be verified). This means that **vascular/endothelial health (eNOS activity) may influence the success or failure of reprogramming in vivo**—in older individuals with insufficient endothelial NO production, reprogramming factors may not be able to push the apparent reset.
- **NO/The inflammatory microenvironment determines the fate of dedifferentiated cells**: Inflammation (NF-κB, SASP) on the one hand promotes tissue regenerative dedifferentiation, and on the other hand creates an immunosuppressive microenvironment. **NO is a double-edged sword here**: Physiological concentrations of NO maintain immune surveillance (T cells kill tumor cells), while excess iNOS-derived NO reacts with superoxide anions to generate **ONOO⁻**, which not only damages DNA (superimposes with reprogramming stress and amplifies genome instability), but also inhibits T cell function and promotes angiogenesis through nitrosylation - **providing soil for "immune escape + nutrient supply" for remaining undifferentiated cells**. See `01-foundations/03-no-basics.md` for details.
- **NAD⁺/SIRT1 axis**: SIRT1 regulates pluripotency gene promoters through deacetylation. Mechanistic studies show that loss of SIRT1 activity reduces iPSC reprogramming efficiency; nicotinamide (NAM)/NAD⁺ levels affect reprogramming efficiency (specific literature needs to be verified). This creates a strategic paradox: NAD⁺ supplementation may enhance reprogramming "push," but may also amplify pro-proliferative signals downstream of reprogramming stress -- NAD⁺ status should be included as a covariate in individual stratification in dose window designs.
- **NO node of tumor immune surveillance**: If reprogramming therapy is to be implemented safely in the body, "dedifferentiated cells are cleared by immunity" as a back-up mechanism; and this mechanism relies on a complete endothelial-immune NO signal chain. **The combination of reprogramming + NO pathway regulation** (such as combining statin/eNOS activator to maintain immune surveillance) is a risk reduction direction worth exploring. There is currently no clinical evidence and the mechanism is speculative.

## 6. Risk avoidance technology matrix and executable suggestions

| Risk sources | Avoidance methods | Maturity |
|---|---|---|
| c-Myc carcinogenesis | Factor subtraction (OSK); small molecules replace c-Myc function | Standardized |
| Loss of dedifferentiation | Pulse/cycle rhythmic drug delivery (Dox switch); tissue-specific promoter restriction | Animal validated |
| Undifferentiated residue | Suicide switch (iCasp9, HSV-TK); combination of scavenging antibodies | The technology is mature, and the in vivo reprogramming scenario needs to be verified |
| Vector integrated mutagenesis | Non-integrating vectors: mRNA transient expression, Sendai virus, small molecule cocktail | mRNA/Sendai mature; small molecule (C6 cocktail, etc.) preclinical |
| Vector immunity | Stratified enrollment for pre-existing antibody screening; immunosuppressive pretreatment before high-dose ramping; capsid engineering (immune evasion mutants) | The field of gene therapy is mature |
| Epigenetic mutations | Long-term follow-up of whole-genome methylation + histone modifications; single-cell sequencing to monitor heterogeneity | Mature technology, undefined regulation |
| Tissue leakage | Double switch: tissue-specific promoter × drug induction; lipid nanoparticle (LNP) tissue targeting | Preclinical |
| Fully out of control | Tertiary monitoring: liquid biopsy NANOG/SSEA-1 + methylation age + imaging tumor screening | Feasible |

**Executable recommendations (in order of priority)**: ① The first human trial must be immunoprivileged/local tissue (Ophthalmology verified logic); ② Detect AAV neutralizing antibodies and stratify before enrollment; ③ Set up a "stop drug" Dox switch + independent iCasp9 suicide switch double insurance; ④ Set "pluripotency marker clearing" as a hard dose limit standard (DLT definition); ⑤ Establish 5–10 Annual follow-up cohort, endpoints include tumor incidence and apparent mutation load; ⑥ Human studies of systemic administration will not be initiated until long-term (≥24 months) toxicological data in monkeys are completed.

## 7. Risk-benefit assessment framework

```
Indication risk level × certainty of benefit = whether it can enter the human body
───────────────────────────────────────────
Vision Loss (NAION/Glaucoma): High Benefit, Low Risk → First (ER-100 has been initiated)
Skin aging/wound repair: moderate benefit, low risk → short-term feasible (strong in vitro data)
Liver fibrosis/metabolic disease: moderate benefit, moderate risk → long-term monkey toxicity required (NewLimit route)
Cardiac/Nervous System Degenerative Diseases: High Benefit, High Risk → Requires Tissue-Specific Delivery Maturity
"Preventive anti-aging" for healthy people: undefined benefits, unacceptable risks → ethical prohibition
```

Core principles: Prove safety locally first, then talk about the whole body; treat the disease first, then talk about enhancing the body. Any systematic reprogramming with the goal of "reverse aging in healthy people" is beyond the reasonable range of the current risk-benefit balance in the absence of 5–10 years of tumor follow-up data.

## 8. Open issues and controversies

1. **Is apparent dialback "repair" or "rewrite"**: Methylation age dialback ≠ functional repair, the possibility of younger readings but unrestored function (or vice versa) cannot be ruled out; no one knows whether the new epimutation introduced by "callback" will accumulate with age.
2. **Width of the safety window**: The mouse window is measured in "cycles", and the human window width is completely unknown - differences in proliferation kinetics, immune surveillance, and telomere length between humans and mice may significantly narrow or widen the window, and we can only explore with low doses.
3. **Management of the risk of "giving up halfway"**: Ohnishi 2014 suggests that stopping reprogramming midway is more dangerous than continuing it. However, clinically "when to stop" is determined by the rhythm plan, and individual differences (transduction efficiency, immune clearance speed) may cause some individuals to actually be in a "suspended state".
4. **Enhancement vs Treatment**: Once ophthalmology/liver disease indications are approved, the regulatory and ethical boundaries of the same technology slipping into "anti-aging beauty" and "healthy person prevention" are extremely blurred; the FDA currently has no definition for "aging" indications.
5. **Controversy**: Some researchers believe that the human translation of the OSK system is "too early" because all evidence of its benefits comes from mice/in vitro, and the regenerative capacity and immune surveillance of mice are much stronger than that of humans - the life extension data (+109% remaining life span) may be systematically overestimated.

## 9. References

1. Takahashi K, Yamanaka S. Induction of pluripotent stem cells from mouse embryonic and adult fibroblast cultures by defined factors. Cell. 2006;126(4):663-676.
2. Okita K, Ichisaka T, Yamanaka S. Generation of germline-competent induced pluripotent stem cells. Nature. 2007;448(7151):313-317.
3. Nakagawa M, Koyanagi M, Tanabe K, et al. Generation of induced pluripotent stem cells without Myc from mouse and human fibroblasts. Nat Biotechnol. 2008;26(1):101-106.
4. Abad M, Mosteiro L, Pantoja C, et al. Reprogramming in vivo produces teratomas and iPS cells with totipotency features. Nature. 2013;502(7471):340-345.
5. Ohnishi K, Semi K, Yamamoto T, et al. Premature termination of reprogramming in vivo leads to cancer development through altered gene expression. eLife. 2014;3:e01685.
6. Ocampo A, Reddy P, Martinez-Redondo P, et al. In vivo amelioration of age-associated hallmarks by partial reprogramming. Cell. 2016;167(7):1719-1733.
7. Horvath S. DNA methylation age of human tissues and cell types. Genome Biol. 2013;14(10):R115.
8. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. Nature. 2020;588(7839):124-129.
9. Macip CC, Hasan R, Hoznek V, et al. Gene therapy mediated partial reprogramming extends lifespan and reverses age-related changes in aged mice. bioRxiv. 2021 (preprint, official publication status to be verified).
10. Chondronasiou D, Gill D, Mosteiro L, et al. Multi-omic rejuvenation of naturally aged tissues by a single cycle of transient reprogramming. Nat Aging. 2022;2(10):1001-1016.
11. Sarkar TJ, Quarta M, Mukherjee S, et al. Transient non-integrative expression of nuclear reprogramming factors promotes multifaceted amelioration of aging in human cells. Nature. 2020;584(7822):589-593.
12. Hacein-Bey-Abina S, Von Kalle C, Schmidt M, et al. LMO2-associated clonal T cell proliferation in two patients after gene therapy for SCID-X1. Science. 2003;302(5644):415-419.
13. Mingozzi F, High KA. Immune responses to AAV vectors: overcoming barriers to successful gene therapy. Blood. 2013;122(1):23-36.
14. Life Biosciences. Announcement of the world’s first human administration of ER-100 (NAION indication, AAV2-OSK + doxycycline switch). 2026-06.
15. NewLimit. Company financing and pipeline announcement (Series C, $435 million, alcohol-related liver disease indication). 2025 (reported in BioSpace).
16. Babraham Institute. Transient reprogramming at the mature stage reverses the biological age of human skin cells by approximately 30 years and maintains identity. 2025 (reported in ScienceDaily, journal details to be verified).
