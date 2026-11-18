# Epigenetic Reprogramming 02: Animal Evidence - Empirical Chain of Partial Reprogramming in vivo Extending Lifespan and Restoring Tissue

> Special Topic: Epigenetic Reprogramming · Article 2 / Total 4 Articles
> Positioning: Animal evidence chain (2013 optic nerve regeneration concept pioneered → 2016 first certificate of premature aging and life extension → 2020 milestone → 2024-2026 gene therapy and toxicity warning)
> Pre-reading: 01-concept.md (OSKM/OSK factors, partial vs complete reprogramming, apparent clock molecular switch); please see 01-foundations/03-no-basics.md for the mainline NO/NAD⁺ network of this library

## 1. Core concepts

In vivo partial reprogramming refers to the transient, periodic or tissue-localized expression of Yamanaka factors (OSKM/OSK) in living animals, which can turn back the epigenetic clock and restore tissue function without erasing cell identity. Animal experiments bear the core proving task in the entire field: **"Can transient, localized factor expression restore the function of aging tissues in vivo?"** Since the inception of the concept of optic nerve regeneration in 2013, the chain of evidence has covered four major types of models - progeria mice (Hutchinson-Gilford progeria syndrome model Lmna^G609G, ZMPSTE24-deficient mice, telomerase-deficient Terc^-/- mice), naturally aging wild-type mice, tissue injury models (optic nerve pinch, glaucoma, myocardial infarction, muscle injury) and recent large animal exploration. Ocampo 2016 (*Cell*) demonstrated for the first time that periodic OSKM expression can extend the lifespan of progeria mice by about 30%; Lu 2020 (*Nature*) used intraocular injection of AAV-OSK to restore visual function in glaucoma mice and demonstrated its dependence on TET demethylase; Macip 2024 used AAV9-OSK in 124-week-old elderly mice, extending the remaining median lifespan by about 109%. At the same time, Abad 2013, Ohnishi 2014, and Parras 2023 repeatedly warned: **Continuous, uncontrolled expression can lead to teratomas, tissue failure, and premature death—"Periodic rather than continuous" thus becomes the iron rule of safety**. The significance of the animal evidence is to establish the principle proof of "aging reversibility": apparent information loss is not only a sign of aging, but also an interventionable driving factor.

## 2. The entire chain of molecular mechanisms: from factor expression to tissue function recovery

### 2.1 Two effect pathways

The mechanism of reprogramming in vivo can be broken down into two parallel pathways: **① Cell-autonomous pathway** - factors enter the cell nucleus to directly rewrite the epigenome, making the cell itself "younger"; **② Non-cell-autonomous pathway** - the secretome of reprogrammed cells reshapes the microenvironment and drives adjacent cells and immune cells through paracrine (skin research in 2025 shows that unreprogrammed cells are "preactivated", see below for details). Both pathways share the same upstream: rewriting of chromatin accessibility by transcription factors.

### 2.2 Full chain path diagram

```
Delivery (AAV/transgene induction/mRNA/small molecules)
│
▼
OSK/OSKM enters the nucleus (Oct4/Sox2 binds distal enhancers; Klf4 recruits chromatin remodeling complexes;
c-Myc recruits BRD4 and histone acetyltransferase)
│
▼
Chromatin opening (H3K27ac↑, H3K4me1/me3↑, partial release of heterochromatin H3K9me3)
│
▼
Pluripotency seed network activation (NANOG, Lin28, ESRRB, Dppa family - low level, not full)
│
▼
Recruit TET1/2 dioxygenase: 5mC → 5hmC → 5fC → 5caC → active/passive demethylation
│ (Lu 2020: The regeneration effect disappears after knocking down TET - irrefutable proof of cause and effect)
▼
DNA methylation clock rollback (Horvath 353 CpG clock/mouse multi-tissue clock)
│
▼
Silencing of aging genes and restoration of youthful gene expression
├──► Cell autonomy: autophagy↑, mitochondrial renewal, SASP↓, senescent cell clearance
└──► Non-cell autonomous: secretome remodeling → Preactivation of adjacent cells and rejuvenation of the immune microenvironment
▼
Tissue function recovery: axon regeneration, myocardial contraction, muscle regeneration, liver regeneration, cognitive improvement, life extension
```

### 2.3 Node-by-node disassembly

**Upstream delivery** determines the controllability of "dose × time", which is the biggest difference between in vivo experiments and in vitro experiments. Three mainstream paradigms: ① **Transgene induction system** - four factors (4F) or six factors (6F, OSKM+Lin28a+Nanog) are placed under the tetO promoter, and doxycycline (doxycycline) switch controls the expression timing. It is the gold standard for dosimetry research (Ocampo 2016, Browder 2022, Parras 2023 all belong to this category); ② **AAV Delivery** - tissue-specific or systemic, closer to future human drug delivery methods (Lu 2020 intraocular, Macip 2024 tail vein AAV9), but there are issues with vector genome persistence and immunogenicity; ③ **Non-integrated/transient delivery** - free vector (episome, Sarkar 2020) and mRNA (six-factor mRNA delivery in vivo is being explored), the highest safety but limited expression level and tissue coverage.

The core of **midstream epigenetic rewriting** is "partial demethylation". After activation of the pluripotent seed network by OSK, TET dioxygenases progressively oxidize 5-methylcytosine and the DNA methylation profile dials back toward the embryonic/young state. The key lies in the **dose-response threshold**: low-level, short-term expression only dials back senescence-related methylation sites (thousands of CpGs), while sustained high expression crosses the threshold, drives full activation of OCT4/NANOG, and cells cross the "identity loss critical point" and enter dedifferentiation - which is the starting point of complete reprogramming and teratoma. In vivo studies also reveal that aging tissues themselves provide "reprogramming permission signals": Mosteiro 2016 (*Science*) found that tissue damage and cell senescence (p16/p21, SASP) actually promote the reprogramming efficiency of adjacent cells, suggesting that the aging microenvironment is a "tailwind" for reprogramming, which explains why aged tissues are particularly sensitive to partial reprogramming.

**Downstream Phenotypic Restoration** consists of two layers: cell autonomous and non-cell autonomous. Cell-autonomous level: aging cell cycle exit is reversed, autophagic flux is restored, mitochondrial quality control is improved (Sarkar 2020 observed rejuvenation of mitochondrial morphology and membrane potential in human cells), SASP cytokines (IL-6, IL-1α, etc.) secretion is decreased. Non-cell autonomous level: Reprogrammed cells change the secretome and activate the "pre-regenerative" state of adjacent fibroblasts, endothelial cells and immune cells. This has been repeatedly confirmed in muscle (Wang 2021 Myofiber paracrine remodeling of satellite cell microenvironment) and skin (2025 Mosaic reprogramming study).

### 2.4 "Cyclic vs Continuous" Safety Dosimetry

The most important pharmacological principle established by animal experiments is **periodic pulse administration**. Ocampo 2016 used a cycle of "2 days on, 5 days off" (reported protocol); Browder 2022 cyclically induced six factors starting from 15 months of age; while sustained expression proved lethal in multiple laboratories - Abad 2013 (*Nature*) sustained induction of multi-organ teratomas and iPSCs in vivo; Ohnishi 2014 (*Cell*) found that "reprogramming aborted" cells caused by continued expression carried abnormal epigenetic states and progressed to Wilms tumor-like kidney tumors and liver dysplasia; Parras 2023 (*Nat Aging*) confirmed that persistent OSKM leads to premature death through liver failure and intestinal failure. **Periodic expression allows cells to repeatedly oscillate between "setting back the apparent clock" and "regaining the ability to proliferate" without crossing the pluripotent state threshold** - This is the molecular essence that distinguishes partial reprogramming from oncogenic transformation.

### 2.5 Organizational differences

The reprogrammability of different tissues varies significantly: retinal ganglion cells, cardiomyocytes, mature muscle fibers, hepatocytes, and dentate gyrus neurons have all been proven to be partially reprogrammed; while the bone marrow hematopoietic system and intestinal epithelium (proliferative tissue) are the most sensitive to sustained OSKM and the most susceptible to failure (Parras 2023), and the liver is both a toxic target and a regenerative beneficiary organ (Hishida 2022 Enhanced liver regeneration vs Parras 2023 liver failure), suggesting that **tissue-specific delivery and tissue-specific dose windows** are key design variables for clinical translation.

## 3. Evidence classification

| Phenomenon | Level of evidence | Key documents |
|---|---|---|
| Cyclic OSKM extends the lifespan of progeria mice (Lmna^G609G) by about 30%, restores skin/spleen/kidney histology, and reduces SASP | Real hammer (transgenic induction, independent phenotypic verification) | Ocampo 2016 *Cell* |
| Intraocular delivery of AAV-OSK restores RGC axon regeneration and visual function in glaucoma mice, dependent on TET enzyme | Real Hammer (Genetic Causality: TET knockdown control) | Lu 2020 *Nature* |
| The expression of periodic six factors reverses the apparent age of blood and tissue in natural aging mice | Real Hammer (multi-tissue methylome) | Browder 2022 *Nat Aging* |
| A single injection of AAV9-OSK increases median remaining lifespan in 124-week-old mice by +109% | Strong association (single center, limited sample size) | Macip 2024 *Cell Reprogramming* |
| Myocardial/muscle/liver tissue-specific partial reprogramming enhances regeneration | Real hammer (functional endpoint of injury model) | Chen 2021 *Science*; Wang 2021 *Nat Commun*; Hishida 2022 *Cell Rep* |
| In vivo OSKM restores youthfulness to dentate gyrus neurons and improves memory | Strong correlation (behavioral + apparent indicators) | Rodríguez-Matellán 2020 *Stem Cell Rep* |
| Non-integrated transient reprogramming of human senescent cells (including centenarians) reverses apparent age | Real hammer (in vitro, multiple cell types) | Sarkar 2020 *Nat Commun* |
| Sustained OSKM expression causes teratoma/carcinogenesis/tissue failure and premature death | Real hammer (consistent among multiple laboratories, borderline toxicity) | Abad 2013 *Nature*; Ohnishi 2014 *Cell*; Parras 2023 *Nat Aging* |
| Tissue damage and aging promote reprogramming efficiency in vivo | Strong correlation (mechanism study) | Mosteiro 2016 *Science* |
| Safety/effectiveness of in vivo reprogramming in monkeys and other large animals | Preliminary (case report, to be verified) | ER-100 monkey experiment (2025, to be verified) |
| OSK expression in humans (gene therapy) | Not in progress (regulatory/ethical pending) | — |

Description of the level of evidence: solid = genetic causation or independent replication by multiple laboratories; strong association = clear functional endpoints but limited samples/centers; preliminary = individual cases or preprints; undeveloped = no published human data yet.

## 4. Clinical/experimental evidence details

### 4.1 Premature aging model: three types of "fast-forward clocks"

① **Lmna^G609G knock-in mice** (Osorio 2011, *Sci Transl Med*): simulate the classic splicing mutation of Hutchinson-Gilford Progeria Syndrome (HGPS), resulting in the accumulation of truncated progerin protein. The mice develop growth arrest, hair loss, skin atrophy, bone and vascular abnormalities at 6-8 weeks of age, and the median life span is about 5-6 months. Ocampo 2016 crossed it with an inducible OSKM strain to obtain "LAKI" mice; ② **Zmpste24^-/- mice** (Pendás 2002, *Nat Genet*): The lamin A precursor protein processing protease is missing, and the accumulation of prelamin A leads to a premature aging phenotype that is highly similar to HGPS. It is a complementary model for mechanism research (for details, see 04-drugs/01-rentosertib.md related discussion); ③ **Terc^-/- telomerase-deficient mice**: multisystem premature aging driven by telomere depletion occurs in the late generation (G4+). It should be pointed out that life extension research on partial reprogramming is mainly completed in the first two types of lamin mutation models; the key evidence given by the telomere model comes from **telomerase reactivation** - Jaskelioff 2011 (*Nature*) Conditional reactivation of telomerase in late-generation Terc^-/- mice reversed neurodegeneration (recovery of olfactory dysfunction), restored spleen/testis/intestinal proliferation and extended lifespan, proving for the first time that "the aging phenotype of adult mammals can be reversed by molecular intervention". This "reversibility principle" is complementary to epigenetic reprogramming: complete reprogramming (iPSC generation) up-regulated by TERT lengthens telomeres, while the direct effect of partial reprogramming on telomere length has been poorly studied (to be verified).

### 4.2 Ocampo 2016 (*Cell* 167:1719-1733): The first evidence of life extension in vivo

The Belmonte team at the Salk Institute used doxycycline to periodically induce OSKM (2 days on/5 days off, reported protocol). In LAKI progeria mice: ① **The median lifespan was extended by about 30%** (control group vs. treatment group, see the original text for specific weeks); ② The thickening of the skin dermis, the lymphatic follicular structure of the spleen, and the morphology of the kidney glomeruli restored youthful histology; ③ The plasma inflammatory factor profile (SASP) decreased significantly; ④ **Whole transcriptome comparison** showed that the gene expression profiles of multiple tissues in the treatment group clustered towards young mice. In 12-month-old wild-type mice, cyclic OSKM expression for 8 weeks improved recovery from cardiotoxin-induced muscle damage and restored streptozotocin-induced diabetic pancreatic function. No teratoma was found throughout the procedure. The warning of Ohnishi 2014 in the same period was both positive and negative, establishing the "cyclical" paradigm.

### 4.3 Lu 2020 (*Nature* 588:124-129): A decisive experiment in apparent information theory

The Harvard Sinclair team used AAV to deliver **Oct4/Sox2/Klf4 three factors intraocularly (knocking out c-Myc to reduce the risk of cancer)**: ① In glaucoma (trabecular meshwork blocked by microbeads) and optic nerve pinch injury models, the DNA methylation profile of retinal ganglion cells (RGC) restored a youthful state; ② Axons regenerate across the injury site, visual evoked potentials and optokinetic responses are restored, and visual function is regained behaviorally; ③ **The regeneration and demethylation effects disappear after knocking down TET1/2** - directly proving that "restoring youthful apparent information" is a causal mechanism for functional recovery, rather than a concomitant phenomenon. This article is the strongest experimental support for the "epigenetic information loss drives aging" hypothesis (on the cover of *Nature* in the same year), and also established the standard paradigm of OSK three-factor + tissue-localized delivery.

### 4.4 Browder 2022 (*Nat Aging* 2:243-253): Molecular dialback in natural aging

Belmonte's team induced doxycycline-induced **factor six (OSKM+Lin28a+Nanog)** transgenic mice periodically from about 15 months of age to old age: the DNA methylation clocks in blood and liver, kidney, skin and other tissues were significantly set back, and the gene expression characteristics of old age were reversed without teratomas or sudden weight loss; while the sustained expression group experienced weight loss and early death. This study advances the evidence from "premature aging model" to "physiological natural aging" and systematically demonstrates for the first time **multi-tissue apparent age dialback** (the specific dialback amplitude and survival benefit are subject to the original text).

### 4.5 Macip 2024 (*Cell Reprogramming* 26:24-32): Gene therapy to extend life in old age

The Rejuvenate Bio team delivered AAV9 through the tail vein to induce OSK in male mice **single injection** to 124 weeks of age (approximately 77-80 years old in humans): median remaining lifespan increased from 8.86 weeks to 18.5 weeks (**+109%**) and improved frailty scores and age-related molecular markers. The significance is that: ① There is still a significant remaining lifespan benefit in the elderly (but not the premature aging model); ② The systemic delivery route of AAV is closest to the human administration method. Limitations are single center, male single sex, and limited sample size (n see original text).

### 4.6 Tissue-specific reprogramming: heart/muscle/liver/skin/pancreas

- **Heart**: Chen 2021 (*Science* 373:1537-1540, Max Planck Institute Braun team) Reversible expression of cardiomyocyte-specific OSKM driven by αMHC can reversibly dedifferentiate adult cardiomyocytes to the fetal sheep state. Both induction before and after myocardial infarction reduce infarct damage and improve cardiac function - breaking the dogma of "adult myocardium is non-regenerable"; there is another preprint report OSKM in 2021-2022. Apparent rejuvenation in cardiomyocytes (*bioRxiv* 2021.12.22.473302).
- **Muscle**: Wang 2021 (*Nat Commun* 12:3094) Partial reprogramming of muscle fibers in vivo activates satellite cells and promotes muscle regeneration by reshaping the stem cell niche (niche) - typical evidence of non-cell autonomous mechanisms.
- **Liver**: Hishida 2022 (*Cell Rep* 39:110730) shows that partial reprogramming in vivo enhances liver plasticity and regeneration after injury.
- **Skin/Fibrosis**: Doeser 2018 (*Stem Cells* 36:1216-1225) reported that partial reprogramming reduces wound fibrosis and scarring; the 2025 Korean POSTECH (*Nat Commun*) "Mosaic Partial Reprogramming/Mild Retrospection" study further showed that only a small part of skin cells are mildly reprogrammed, and the response to PI3K-AKT, EGFR, HIF-1α The pathway is activated and the entire skin enters "pre-regeneration mode", healing is accelerated and scars are reduced. It is also effective in diabetes models (details to be verified).
- **Pancreas**: Ocampo 2016 STZ Diabetes Recovery Trial provides pancreatic evidence; tissue-specific OSK studies specifically targeting the pancreas are lacking (to be verified).

### 4.7 Brain and Cognition: Hippocampal Reprogramming and Human Cells

- **Mouse**: Rodríguez-Matellán 2020 (*Stem Cell Rep* 15:1056-1066, Serrano/Ávila team) Cyclic expression of OSKM in dentate gyrus neurons: restores age-related decline in H3K9me3 heterochromatin, improves synaptic plasticity, and significantly improves object recognition memory. The 2024 Neuron Restricted Cycling OSKM study (*Commun Biol*) and the University of Barcelona Cortical Neuron Research further supports that "controlled cycling can restore cortical neuron vitality."
- **Human cells**: Sarkar 2020 (*Nat Commun* 11:1545, Stanford Sebastiano group) Transient OSKM expression using **non-integrating episomal vectors** in cells derived from elderly donors and centenarians: apparent clock setback ~2.5-3.5 years (reported range), aging and SASP Mark reversal, rejuvenation of mitochondrial function, and absence of pluripotency markers—bridging "in vivo mouse evidence" and "human cell viability."

### 4.8 Toxic warning: negative teaching material of safety boundary

Abad 2013 (*Nature* 502:340-345): Inducible sustained expression of OSKM in vivo → multi-organ teratomas and iPSCs in vivo. Ohnishi 2014 (*Cell* 156:663-677): Wild-type mice continue to express → Wilms tumor-like lesions in the kidneys and liver dysplasia, and the "reprogramming aborted" state is itself carcinogenic. Parras 2023 (*Nat Aging* 3:1509-1520): Sustained OSKM → sudden weight loss, hepatointestinal failure, premature death (intestinal microorganisms are involved, see BioProject PRJEB66275); supporting research in the same year (PMID 38012288) constructed **transgenic strains that avoid the liver and intestines** to significantly reduce toxicity - "tissue exemption" has become a new generation delivery design direction. It was further reported in 2026 that oxidative stress is a key driver of reprogramming liver failure in vivo (original article to be verified).

### 4.9 2025-2026 Latest Development

Altos Labs (*Cell* 2025) proposed the theory of "mesenchymal drift": aging is a common process of reduced ability to maintain cell identity, and partial reprogramming can reverse this drift; ER-100 showed the potential to restore vision in monkey experiments (cases/to be verified); exploration of mRNA delivery of six factors to restore the aging optic nerve is ongoing (to be verified). Overall trend: **Moving from "proven reversibility" to "engineered safety"** - tissue immunity, non-integrated delivery, and periodic pulses have become the three major design axes.

### 4.10 Bridging value of large animal models

In the transformation from rodents to humans, large animal (dog, pig, monkey) models are an indispensable intermediate station. Their unique value lies in:

- **Lifespan and physiological scale**: Mice have a lifespan of 2-3 years and strong regeneration ability, and the life extension and regeneration effects may be overestimated; the lifespan and organ scale of dogs (10-15 years), pigs (15-20 years), and monkeys (20-40 years) are closer to humans, which can more truly evaluate the long-term safety and dosage of "old-age initial intervention".
- **Large animal evidence available**: Preclinical validation of ER-100 includes ocular delivery studies in non-human primates (monkeys) (case reports show improvement in vision-related indicators, to be officially published and verified); exploration of canine epigenetic reprogramming (reprogramming sub-research under the Dog Aging Project framework) is starting - dogs are the only large companion animals that share a living environment with humans, and their natural aging research can be directly transferred to humans.
- **Immunogenicity Assessment**: The performance of immune responses (neutralizing antibodies, T cell responses) to AAV/mRNA delivery in primates is significantly different from that in mice, and large animal data is a key basis for selecting delivery platforms.
- **Regulatory requirements**: FDA's IND submission for gene therapy products usually requires toxicological and biodistribution data on at least one large animal - **long-term safety data on monkeys/dogs is a must for ER-100 products to enter human trials**.

**Status quo judgment**: Large animal reprogramming data are still sporadic cases (monkey eyes, dog exploration), and are far from forming a systematic evidence chain. This is one of the most obvious evidence gaps between epigenetic reprogramming from "animal proof" to "human registration", and it is also the most noteworthy transformation node in the next 3-5 years (echoing the timeline judgment of [04-roadmap](../01-reprogramming/04-roadmap.md)).

## 5. Contact with NO / NAD⁺ / longevity network

```
Partial reprogramming ──► Mitochondrial rejuvenation (autophagy↑, mtROS↓, OXPHOS recovery)
│
├──► eNOS conjugation retention ──► NO bioavailability ↑ ──► sGC/cGMP/PKG ──► Vasodilation/anti-inflammatory
│
├──► ROS↓ ──► ONOO⁻ Generation ↓ (to prevent NO from being hijacked by superoxide radicals)
│
SASP↓ ───► Chronic inflammation ↓ ──► Endothelial function protection ──► eNOS activity ↑
│
NO ───► S-nitrosylation DNMT/TET (mechanism study shows)──► Feedback regulation of DNA methylation ←──► Reprogramming epigenetic rewriting
```

There are four docking points for the main lines of this library (the first two are mechanism speculations and require experimental verification): ① **mitochondria-endothelial axis**: reprogramming restores mitochondrial quality control → decrease in reactive oxygen species → decrease in eNOS uncoupling → recovery of NO bioavailability, which may be the pathway basis for the "vascular rejuvenation" effect of reprogramming (Browder 2022 The apparent recovery of the vascular bed in kidney/skin rejuvenation can be used as indirect evidence, to be verified); ② **SASP-inflammation-NO axis**: Reprogramming reduces SASP → chronic inflammation subsides → protects eNOS, which is homologous to the vascular benefit mechanism of senolytics; ③ **NAD⁺/SIRT1 crossover**: NAD⁺ decreases with age → SIRT1 inactivation → eNOS deacetylation is reduced, and reprogramming can amplify NO signals if it can restore the SIRT1 network (see details 01-foundations/03-no-basics.md); ④ **NO reverse regulation of epigenetic machinery**: Mechanistic studies show that NO is modified by S-nitrosylation DNMT/TET to affect methylation, suggesting that there is a two-way dialogue between NO and reprogramming - NO is both a downstream beneficiary of reprogramming and may also be its upstream regulator (double-edged sword: ONOO when high NO is accompanied by high ROS⁻ Mediates nitrifying stress, backphaages apparent stability).

## 6. Intervention directions and executable suggestions

Sorted by evidence strength: ① **Tissue limitation + periodic pulse**: Prioritize "low proliferation, high benefit" tissues such as the eye (Lu 2020 paradigm), myocardium (Chen 2021 paradigm), and adopt a 2-day on/5-day off cycle instead of continuous expression; ② **Non-integrated delivery priority**: mRNA/episomal vector avoids the risk of insertional mutation and continuous expression, and is the shortest path to the human body; ③ **Tissue exempt design**: Avoid liver and intestine (Parras 2023 toxicity target) or use tissue-specific promoters; ④ **Forced mechanism control**: Each indication study has a TET knockdown/inhibition control to verify the "apparent dialback-functional recovery" causal chain; ⑤ **Monitoring system**: Based on blood/tissue DNA methylation clock (Thompson 2018 mouse clock), single-cell transcriptome, SASP Spectrum is the end point, and the "cycle-callback-function" dose-response curve is tracked; ⑥ **Safety red line**: Any plan must use teratoma/dedifferentiation markers (NANOG full activation, OCT4 ectopic) as the stopping rule, and long-term carcinogenic follow-up cannot be omitted.

## 7. Open issues and disputes

1. **The gap between mice and humans**: Mice have short lifespans and strong regeneration capabilities, and the life extension and regeneration effects may be systematically overestimated; large animal (monkey) data are still sporadic cases; 2. **"Remaining life span" measurement**: Macip 2024's +109% is an increase in remaining life span, and the conversion into absolute life span and health life span benefits requires caution; 3. **Apparent dialback ≠ functional repair**: Methylation clock dialback is a readout change, and there is still a lack of direct evidence whether it can be converted into real tissue function (especially terminally differentiated cells such as myocardium and neurons); 4. **Tumor risk quantification**: There is no clear safety window data for the dose threshold of partial reprogramming and oncogenic transformation in the body, and the molecular boundaries of the "cycle" (what apparent states are irreversible) are unknown; 5. **Immunity and Tolerance**: The immunogenicity of viral vectors and ectopic transcription factors, and the tolerance of repeated administration have not been resolved; 6. **Disconnection between telomeres and epigenetic clocks**: Partial reprogramming dials back the methylation clock but does not necessarily lengthen telomeres. What the separation of the two "age readouts" means is unclear; 7. **Ethics and Regulation**: Changing the epigenome in the human body belongs to the category of gene therapy, and neither the regulatory path (FDA/EMA) nor the long-term follow-up framework has been established.

### Conversion list from animal evidence to humans (key verification nodes)

Comprehensive animal evidence chain, the verification nodes that need to be passed in order to transform into humans (each item has clear evidence level requirements):

| Node | Verification content | Current status | Achievement flag |
|---|---|---|---|
| 1. Safety window | Three-dimensional safety matrix of period × dose × tissue | Basic establishment of rodents | Large animal confirmation |
| 2. Delivery platform | Immunogenicity and tissue coverage of non-integrating vectors/AAV | AAV is the most mature in the eye | Long-term toxicology in large animals |
| 3. Functional endpoint | Causal binding of clock back and functional recovery | Stronger eyes/muscles/heart | Large animal functional data |
| 4. The onset of old age | Validity of old age (but not progeria) models | Browder/Macip Support | Large Animal Old Age Cohorts |
| 5. Immune monitoring | Tolerizing and neutralizing antibodies to repeated dosing | Deletions | Repeated dosing in primates |
| 6. Long-term follow-up | Decade safety of oncogenesis/dedifferentiation | Missing | Prospective registration cohort |

**Core Judgment**: Animal evidence has fully proven the principle of "partial reprogramming reversible aging". The bottleneck of human transformation is not the principle but **engineering and supervision** - delivery safety, dosage window, and long-term follow-up are the keys to determine whether epigenetic reprogramming can become "the first true anti-aging therapy" in the next 5 years (echoing [01-concept](01-concept.md)'s ER-100 discussion and Rated 31/40 by [09-immortality/02-breakthrough-candidates](../../09-immortality/02-breakthrough-candidates.md)).

## References

1. Ocampo A, Reddy P, Martinez-Redondo P, et al. In Vivo Amelioration of Age-Associated Hallmarks by Partial Reprogramming. *Cell* 2016;167:1719-1733.e12. doi:10.1016/j.cell.2016.11.052
2. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. *Nature* 2020;588:124-129. doi:10.1038/s41586-020-2975-4
3. Browder KC, Reddy P, Yamamoto M, et al. In vivo partial reprogramming alters age-associated molecular changes during physiological aging in mice. *Nat Aging* 2022;2:243-253. doi:10.1038/s43587-022-00183-2
4. Cano Macip C, et al. Gene Therapy-Mediated Partial Reprogramming Extends Lifespan and Reverses Age-Related Changes in Aged Mice. *Cell Reprogramming* 2024;26(1):24-32.
5. Parras A, Vílchez-Acosta A, Desdín-Micó G, et al. In vivo reprogramming leads to premature death linked to hepatic and intestinal failure. *Nat Aging* 2023;3:1509-1520. doi:10.1038/s43587-023-00528-5
6. Chen Y, Lüttmann FF, Schoger E, et al. Reversible reprogramming of cardiomyocytes to a fetal state drives heart regeneration in mice. *Science* 2021;373:1537-1540. doi:10.1126/science.abg5159
7. Wang C, et al. In vivo partial reprogramming of myofibers promotes muscle regeneration by remodeling the stem cell niche. *Nat Commun* 2021;12:3094. doi:10.1038/s41467-021-23353-z
8. Hishida T, Yamamoto M, Hishida-Nozaki Y, et al. In vivo partial cellular reprogramming enhances liver plasticity and regeneration. *Cell Rep* 2022;39:110730.
9. Rodríguez-Matellán A, Alcazar N, Hernández F, Serrano M, Ávila J. In vivo reprogramming ameliorates aging features in dentate gyrus cells and improves memory in mice. *Stem Cell Rep* 2020;15:1056-1066.
10. Sarkar TJ, Quarta M, Mukherjee S, et al. Transient non-integrative expression of nuclear reprogramming factors promotes multifaceted amelioration of aging in human cells. *Nat Commun* 2020;11:1545. doi:10.1038/s41467-020-15174-3
11. Abad M, Mosteiro L, Pantoja C, et al. Reprogramming in vivo produces teratomas and iPS cells with totipotency features. *Nature* 2013;502:340-345.
12. Ohnishi K, Semi K, Yamamoto T, et al. Premature termination of reprogramming in vivo leads to cancer development through altered epigenetic regulation. *Cell* 2014;156:663-677.
13. Mosteiro L, Pantoja C, Alcazar N, et al. Tissue damage and senescence provide critical signals for cellular reprogramming in vivo. *Science* 2016;354:aaf4445.
14. Doeser MC, Schöler HR, Wu G. Reduction of fibrosis and scar formation by partial reprogramming in vivo. *Stem Cells* 2018;36:1216-1225.
15. Jaskelioff M, Muller FL, Paik JH, et al. Telomerase reactivation reverses tissue degeneration in aged telomerase-deficient mice. *Nature* 2011;469:102-106.
16. Osorio FG, Navarro CL, Cadinanos J, et al. Splicing-directed therapy in a new mouse model of human accelerated aging. *Sci Transl Med* 2011;3:106ra107.
17. Pendás AM, Zhou Z, Cadiñanos J, et al. Defective prelamin A processing and muscular and adipocyte alterations in Zmpste24 metalloproteinase-deficient mice. *Nat Genet* 2002;31:94-99.
18. Horvath S. DNA methylation age of human tissues and cell types. *Genome Biol* 2013;14:R115.
19. Thompson MJ, Chwiałkowska K, Rubbi L, et al. A multi-tissue full lifespan epigenetic clock for mice. *Aging (Albany NY)* 2018;10:2832-2854.
20. Takahashi K, Yamanaka S. Induction of pluripotent stem cells from mouse embryonic and adult fibroblast cultures by defined factors. *Cell* 2006;126:663-676.
