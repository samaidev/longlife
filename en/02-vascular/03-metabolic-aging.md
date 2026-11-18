# Metabolic Aging: Insulin Resistance, Dysregulated Nutrient Sensing, and Longevity

> Metabolic aging refers to the systemic metabolic remodeling that occurs with age: declining insulin sensitivity, disordered lipid metabolism, reduced mitochondrial function, and imbalance in the AMPK/mTOR nutrient-sensing network. It is both a consequence and a driver of aging—metabolic dysfunction accelerates other hallmarks by promoting inflammation, epigenetic drift, and organ damage, and is a common upstream factor in several chronic diseases of aging (type 2 diabetes, cardiovascular disease, NAFLD, and sarcopenia). This chapter proceeds from “signaling pathways → tissue metabolism → intervention strategies.”

---

## 1. Insulin Signaling and Insulin Resistance

### 1.1 The Full Insulin-Signaling Cascade

Insulin initiates signaling through the insulin receptor (IR). The canonical pathway is IRS-1/PI3K/Akt:

```
Insulin ──► IR (tyrosine-kinase autophosphorylation)
             │
             ▼
        IRS-1/2 (Tyr phosphorylation)
             │
             ▼
        PI3K (p85/p110) ──► PIP2 → PIP3
                                │
                                ▼
                            PDK1 → Akt (Thr308)
                              │  mTORC2 → Akt (Ser473)
                              ▼
                     ┌────────┴────────┐
                     ▼                 ▼
                GLUT4 translocation   FoxO1 exits nucleus
              (AS160/TBC1D4)          (gluconeogenic genes↓)
                     │
                     ▼
               Glucose uptake↑
```

- **IRS-1**: The first adaptor protein downstream of IR; its Tyr phosphorylation recruits PI3K. **Ser phosphorylation (e.g., Ser307/Ser312) is a key switch in insulin resistance**: after phosphorylation by JNK, IKKβ (inflammation), mTOR/S6K (over-nutrition), or PKC (lipotoxicity), IRS-1 dissociates from IR and is degraded, interrupting the signal.
- **PI3K/Akt**: Akt phosphorylates AS160/TBC1D4, relieving inhibition of Rab GTPases and driving **GLUT4** vesicle translocation to the plasma membrane—the rate-limiting step in insulin-stimulated glucose uptake by skeletal muscle and adipose tissue.
- **Another branch of Akt signaling**: Phosphorylation of FoxO1 keeps it in the cytoplasm and suppresses expression of hepatic gluconeogenic genes (PEPCK, G6Pase), another mechanism by which insulin lowers blood glucose.

### 1.2 How Insulin Resistance Develops

| Driver | Molecular event | Outcome |
|---|---|---|
| Inflammation (TNF-α, IL-6) | JNK/IKKβ activation → IRS-1 Ser phosphorylation | Signaling interrupted |
| Lipotoxicity (DAG/ceramide) | PKCθ/ε activation → IRS-1 Ser phosphorylation | Signaling interrupted |
| ER stress | PERK/JNK activation | Signaling interrupted |
| Mitochondrial ROS | Altered phosphatase (PTEN/PTP1B) activity | Increased negative regulation |
| Hyperglycemia/over-nutrition | mTOR/S6K negative-feedback phosphorylation of IRS-1 | Signaling interrupted |

**Key quantitative point:** In healthy people, insulin stimulation increases skeletal-muscle glucose uptake approximately 5–10-fold; in insulin-resistant individuals (such as first-degree relatives of people with type 2 diabetes), the increase may fall to 2–3-fold. The **hyperinsulinemic-euglycemic clamp** is the gold standard for measuring insulin sensitivity; the M value (mg/kg/min) declines significantly with age and obesity.

## 2. Lipid Metabolism and Adipose-Tissue Aging

### 2.1 Age-Related Remodeling of Adipose Tissue

- **Redistribution**: Subcutaneous fat decreases while visceral and ectopic fat increase. Visceral adipose tissue (VAT) adipocytes are larger and more prone to releasing free fatty acids (FFAs) and pro-inflammatory factors.
- **Adipocyte senescence**: Senescent adipocytes (p16/SA-β-gal positive) secrete SASP factors (IL-6, TNF-α, MCP-1), recruiting macrophages (M1 polarization). Local inflammation drives systemic insulin resistance; senolytics (senescent-cell clearance) improve metabolic phenotypes in animals.
- **Dysregulated lipolysis**: With age, adipose tissue becomes less sensitive to insulin’s suppression of lipolysis → plasma FFAs rise → ectopic deposition.

### 2.2 Ectopic Deposition and Lipotoxicity

```
Subcutaneous fat-storage capacity↓ / lipolysis↑
        │
        ▼
Plasma FFA↑ ──► skeletal-muscle DAG/ceramide↑ ──► PKCθ ──► IRS-1 Ser-P ──► insulin resistance
        │
        ├─► hepatic DAG↑ ──► PKCε ──► IRS-2 inhibition ──► hepatic glucose output↑ (NAFLD)
        │
        └─► β-cell lipid↑ ──► lipoapoptosis/dysfunction ──► insulin secretion↓
```

**Lipotoxic molecules:** **Diacylglycerol (DAG)** is a recognized mediator of muscle and hepatic insulin resistance: through PKCθ/ε it phosphorylates IRS serine sites. **Ceramide** activates PP2A/PKCζ, inhibits Akt, and induces β-cell apoptosis. Oxidized LDL and free cholesterol damage blood vessels and pancreatic islets.

## 3. AMPK–mTOR Nutrient Sensing

### 3.1 AMPK: The Energy-Deficit Sensor

AMPK is a heterotrimer (α catalytic subunit + β and γ regulatory subunits); the γ subunit contains AMP/ADP-binding sites:
- **Activation**: A rise in the AMP/ATP ratio (energy deficit) → AMP binds the γ subunit → conformational change plus phosphorylation of the α subunit at **Thr172** by an upstream kinase, LKB1 (or CaMKKβ) → activation.
- **Downstream effects**: Phosphorylates and inhibits anabolic processes (ACC1/2 → fatty-acid synthesis↓; mTORC1 inhibition); activates catabolism (ULK1 initiates autophagy, PGC-1α increases mitochondrial biogenesis, GLUT4 translocation↑).
- **Age-related changes**: AMPK activity declines with age in multiple tissues (weaker upstream LKB1 signaling and inhibition by chronic inflammation), consistent with loss of metabolic flexibility.

### 3.2 mTORC1: The Master Switch for Anabolism

- **Activation**: Amino acids (leucine via Sestrin2/GATOR2 → Rag GTPase), growth factors (PI3K/Akt → TSC2 inhibition), and energy sufficiency (AMPK inactivation).
- **Downstream effects**: S6K1/4E-BP1 (protein synthesis↑), SREBP1 (lipid synthesis↑), and autophagy inhibition.
- **Age-related changes**: mTORC1 activity rises or becomes dysregulated with age (especially in a tissue-specific manner), driving SASP and loss of proteostasis. **Rapamycin inhibition of mTORC1 extends lifespan in several model organisms** (9–14% in mice; confirmed by the NIA ITP study in 2012).

```
      Energy deficit             Nutrient sufficiency/growth factors
           │                                 │
           ▼                                 ▼
         AMPK ────────────────────────────► inhibits ──► mTORC1
           │                                         │
           ├─► autophagy↑                            ├─► protein synthesis↑
           ├─► PGC-1α↑                               ├─► lipid synthesis↑
           └─► ACC inhibition (fat synthesis↓)       └─► autophagy↓
```

**Balance matters:** AMPK and mTORC1 oppose one another. In aging, the combination “AMPK↓ + mTORC1↑” promotes excessive anabolism, insufficient autophagy, inflammation, and insulin resistance. Restoring balance is a core metabolic anti-aging strategy (see Section 6).

## 4. Metabolic Flexibility

Metabolic flexibility is the ability to **switch rapidly between glucose and fat oxidation**, a core measure of metabolic health:
- **Healthy state**: After eating, glucose is the main fuel (insulin↑ suppresses fat oxidation); during fasting/exercise, the body switches to fat oxidation (FFA↑).
- **Aging/obesity**: Switching capacity declines. Whether fasting or fed, the body tends to oxidize glucose (“glucose dependence”); fat oxidation is impaired, reflected by reduced day-night variation in respiratory quotient (RQ) and a lower fat-oxidation rate.

**Molecular basis:** Impaired regulation of CPT1, the rate-limiting enzyme of fatty-acid oxidation (inhibited by malonyl-CoA); reduced mitochondrial content and quality (PGC-1α downregulation); and imbalance in substrate competition (the Randle cycle, in which fatty-acid oxidation inhibits glucose oxidation).

```
Metabolically flexible (healthy): fed ──► mainly glucose oxidation ──► fasting ──► mainly fat oxidation
Metabolically inflexible (aging): fed ──► glucose oxidation ──► fasting ──► still glucose-dependent (impaired fat oxidation)
```

**Measurement:** Indirect calorimetry (respiratory quotient), hyperinsulinemic clamps plus substrate tracers, and FFA kinetics before and after exercise. Exercise training, low-carbohydrate/ketogenic diets, and intermittent fasting can each partly restore metabolic flexibility.

## 5. Mitochondrial Metabolism and ROS

- **TCA cycle**: Acetyl-CoA enters the tricarboxylic acid cycle (citrate synthase, isocitrate dehydrogenase, α-KG dehydrogenase, succinate dehydrogenase, etc.), generating NADH/FADH₂ and metabolic intermediates (α-KG is also a substrate for epigenetic enzymes).
- **Oxidative phosphorylation**: NADH/FADH₂ pass through the electron-transport chain (complexes I–IV), pumping protons; ATP synthase (complex V) uses the proton gradient to synthesize ATP. Complete oxidation of one glucose molecule yields a net approximately 30–32 ATP molecules.
- **ROS generation**: Electron leakage occurs mainly at complexes I and III (1–4% of oxygen is reduced by a single electron to superoxide); the leakage fraction rises with age. ROS damage mtDNA, proteins, and lipids, forming a positive-feedback loop of “mitochondrial aging.”
- **Metabolism and aging**: Mitochondrial dysfunction causes inadequate energy supply (sarcopenia and declining brain function), increased ROS, and imbalanced metabolic intermediates (changes in acetyl-CoA and α-KG affect epigenetics). It mediates metabolic aging and acceleration of biological age (see the dedicated mitochondrial chapter, 04).

## 5.1 Metabolic Aging and the NO Pathway: A Molecular Bridge of Bidirectional Deterioration

Metabolic dysfunction and declining NO bioavailability are deeply coupled at the molecular level, forming a vicious “metabolism–vascular” cycle:

- **Insulin resistance → NO decline**: Insulin promotes NO production by phosphorylating eNOS-Ser1177 through PI3K/Akt (see [01-no-cardiovascular](01-no-cardiovascular.md)). In insulin resistance this branch is impaired, reducing NO production and increasing endothelin-1. “Selective insulin resistance” disrupts vascular tone and is a direct mechanism of endothelial dysfunction in diabetes/metabolic syndrome.
- **Hyperglycemia → eNOS uncoupling**: High glucose, through PKC activation, AGE formation, and oxidative stress, oxidizes BH4, converting eNOS into a superoxide producer (uncoupling) and further reducing NO. “Glucotoxicity” and “NO depletion” reinforce one another.
- **Lipotoxicity → arginase upregulation**: TNF-α/IL-6 released by visceral fat upregulates arginase (which competes with eNOS for L-arginine) and inhibits DDAH (which degrades ADMA). Plasma ADMA rises 1.5–2-fold and directly inhibits eNOS.
- **NO decline → metabolic deterioration**: NO promotes skeletal-muscle glucose uptake (through AMPK/GLUT4 translocation); insufficient NO weakens exercise-induced metabolic adaptation. NO also regulates adipose-tissue blood flow (affecting lipolysis and substrate transport) and brown-fat thermogenesis (UCP1-dependent NO signaling).

**Clinical significance:** Improving metabolism (weight loss, exercise, glucose control) and restoring NO (dietary nitrate, exercise, smoking cessation) amplify one another. “Metabolic health” and “vascular youth” are two sides of the same coin. This also explains why Mediterranean-diet/exercise interventions improve insulin sensitivity, FMD, and blood pressure together (see [07-interventions/03-nutrition.md](../07-interventions/03-nutrition.md)).

## 6. Fasting and Ketogenic Diets

### 6.0 The Big Picture of “Nutrient-Sensing Dysregulation” in Metabolic Aging

AMPK/mTOR imbalance is not an isolated event but part of broader dysregulation of the nutrient-sensing network. This network also includes **SIRT1** (an NAD⁺-dependent deacetylase that senses energy status), **insulin/IGF-1 signaling** (senses growth factors), **FGF21** (a liver-secreted metabolic-stress hormone), and **AMPK/mTORC1** (senses energy and amino acids). These five pathways drift together with age:

| Pathway | Direction with aging | Consequence |
|---|---|---|
| AMPK | Activity↓ | Autophagy↓, mitochondrial renewal↓ |
| mTORC1 | Activity↑ | Excess protein synthesis, autophagy↓, SASP↑ |
| SIRT1 | Activity↓ (NAD⁺ decline) | Epigenetic drift, mitochondrial function↓ |
| Insulin/IGF-1 | Sensitivity↓ (resistance) | Metabolic inflexibility, inflammation↑ |
| FGF21 | Elevated (compensatory) | Metabolic-stress signal (risk of muscle atrophy) |

**“Nutrient-sensing recalibration”** is therefore a central metabolic anti-aging strategy: fasting, calorie restriction, and exercise suppress mTORC1 and activate AMPK/SIRT1, mimicking metabolic signals of a “famine state.” This is the molecular basis of the calorie-restriction longevity hypothesis and the rationale for why a fasting–exercise combination may outperform either intervention alone.

### 6.1 Intermittent Fasting / Calorie Restriction

- **Mechanism**: Fasting → AMP/ATP↑ → AMPK activation → mTORC1 inhibition, autophagy initiation, PGC-1α upregulation; insulin falls and glucagon rises, mobilizing fat.
- **Evidence**: Calorie restriction (CR) extends lifespan in yeast, worms, fruit flies, mice, and in some monkey studies. Human RCTs (the CALERIE series) show that two years of CR improves metabolic measures and reduces aging-related biomarkers, but there is no direct evidence yet that “CR extends human lifespan.”
- **Intermittent fasting (IF)**: Regimens such as 16:8 and 5:2 improve weight, insulin sensitivity, blood pressure, and inflammation in RCTs; some benefits are partly independent of calorie intake.

### 6.2 Ketosis and β-Hydroxybutyrate

A ketogenic diet (very low in carbohydrates) prompts the liver to produce ketone bodies: **β-hydroxybutyrate (BHB)**, acetoacetate, and acetone. BHB does far more than provide fuel:

- **Energy substrate**: When glucose is scarce, the brain switches to BHB (transported by MCT1 and oxidized in mitochondria), improving neurometabolism.
- **Signaling molecule**: **Inhibits histone deacetylases (HDAC1/3)**—BHB is an endogenous HDAC inhibitor; it increases histone acetylation and activates expression of stress-response genes (e.g., FoxO3a and MT2), a molecular core of “ketogenic anti-aging.”
- **GPCR ligand**: Activates HCAR2 (GPR109A), suppressing lipolysis and inflammation.
- **Evidence**: Animal studies show that ketogenic diets/ketone esters improve cognition, metabolism, and longevity-associated pathways. Human RCTs show improvements in insulin sensitivity and inflammatory biomarkers, but long-term safety (lipids, kidney stones) still needs validation.

```
Fasting/low carbohydrate ──► liver glycogen↓ → fat mobilization → hepatic β-oxidation → ketones (BHB)
                                                                  │
                          ┌───────────────────────────────────────┼──────────────┐
                          ▼                                       ▼              ▼
                    HDAC inhibition                         HCAR2 activation   Energy substrate
                 (histone acetylation↑)                    (anti-inflammatory/   (brain/muscle)
                                                            lipolysis↓)
                          │
                          ▼
                FoxO3a/MT2 and other stress-response genes↑
```

## 7. Pharmacological Interventions: Metformin and GLP-1

### 7.1 Metformin

- **Mechanism**: Mild inhibition of mitochondrial complex I → AMP/ATP↑ → **AMPK activation**. It also activates AMPK by inhibiting lysosomal v-ATPase via the target PEN2; it improves hepatic glucose output, intestinal glucose uptake, and the gut microbiota.
- **Anti-aging evidence**: Epidemiology (mortality/cancer risk in people with diabetes lower than expected) and animal studies (lifespan extension in worms and mice, with AMPK-dependent mechanisms) support the possibility that “metformin may slow aging.” The **TAME trial** (Targeting Aging with Metformin, a multicenter RCT in people without diabetes) is underway and is a key study for testing anti-aging efficacy in humans; results have not yet been reported.
- **Known adverse effects**: Gastrointestinal symptoms, vitamin B12 deficiency (long-term), and lactic acidosis (rare).

### 7.2 GLP-1 Receptor Agonists

- **Mechanism**: GLP-1 is an incretin. It promotes insulin secretion in a glucose-dependent manner, suppresses glucagon, delays gastric emptying, and centrally suppresses appetite, activating cAMP/PKA through GLP-1R.
- **Evidence**: Semaglutide and related drugs produce substantial weight loss (RCTs: mean loss of 10–15%), improve cardiovascular outcomes (SELECT trial: major adverse cardiovascular events ↓20%), and improve renal outcomes. Metabolic improvements resulting from weight loss indirectly improve insulin resistance and inflammation.
- **Anti-aging potential**: Weight loss, anti-inflammatory effects, and improved β-cell function may indirectly slow metabolic aging. Direct anti-aging evidence remains insufficient; long-term safety issues (loss of muscle mass, gastrointestinal events) warrant attention.

## 7.3 Clinical Assessment of Metabolic Aging: From “Checkup” to “Metabolic Age”

There is no single gold standard for metabolic aging. Clinical assessment relies on a combination of measures, ranked by evidence strength:

- **Insulin sensitivity (gold standard)**: Hyperinsulinemic-euglycemic clamp (M value)—the research gold standard, but technically complex. Alternatives: HOMA-IR (fasting glucose × insulin/22.5, for screening) and dynamic OGTT curves (two-hour glucose and insulin responses).
- **Body composition and fat distribution**: DEXA/bioelectrical impedance for VAT and muscle mass; waist circumference and waist-to-hip ratio are inexpensive alternatives. **People with “metabolically obese but normal weight” (MONW) especially need body-composition assessment**: those with normal weight but high visceral fat may have risks comparable to people with obesity.
- **Full lipid profile**: Triglycerides, HDL-C, non-HDL-C, and ApoB. **ApoB is the most direct measure of the number of atherogenic particles** and reflects cardiometabolic risk better than LDL-C.
- **Inflammation and organ burden**: hsCRP (chronic inflammation), ALT/AST (hepatic steatosis), creatinine/eGFR (kidneys), and uric acid (a component of metabolic syndrome). Multiple abnormal measures suggest clustering of “metabolic syndrome.”
- **The concept of metabolic age**: “Metabolic age” based on these measures (a composite of metabolic flexibility, VO₂max, and visceral fat) can represent the metabolic dimension of biological age and complement epigenetic clocks (see [02-aging-clocks](../01-foundations/02-aging-clocks.md)).

**Screening significance:** Early signs of metabolic aging (increased visceral fat, higher HOMA-IR, elevated ApoB) often appear 5–10 years before abnormal blood glucose. **A “metabolic age” that runs ahead of disease diagnosis marks a golden window for intervention.** This is why annual checkups after age 40 should include the measures above.

## 8. The Metabolic Clock: DunedinPACE

**DunedinPACE** (Dunedin Pace of Aging Calculated from the Epigenome, 2022, Belsky group) is a new-generation “pace-of-aging” clock:

- **Construction**: The Dunedin birth cohort of 954 people was followed for 20 years (ages 26–45) across 19 organ/metabolic-function measures (BMI, blood pressure, HbA1c, lung function, periodontal health, renal function, inflammatory biomarkers, etc.). Longitudinal slopes defined each person’s “pace of aging”; blood DNA methylation was then used to model it. The final clock uses **173 CpG sites** to output the number of biological aging years corresponding to each chronological year (PACE).
- **Difference from traditional clocks**: Horvath/Hannum estimate “age” (DNAmAge), whereas DunedinPACE estimates **“pace”**—the multiple of biological aging per unit time. It is more sensitive to interventions and more strongly associated with functional decline.
- **Validation**: Higher PACE is associated with faster functional decline, chronic-disease onset, and mortality (per 1 SD, all-cause mortality HR≈1.4–1.5). It can detect short-term effects of lifestyle interventions (exercise, weight loss), making it a promising endpoint for metabolic anti-aging interventions.
- **Limitations**: Built from a single New Zealand birth cohort, so generalizability remains to be validated; the functional significance of the CpG sites is unknown (it is a readout, not a mechanism); response over very short time windows also needs validation.

**Key references:** Belsky DW et al. *eLife* 2022;11:e73420 (DunedinPACE) / Human calorie-restriction RCT: Ravussin E et al. *Cell Metab* 2015;22(3):427–437 (CALERIE 2) / Rapamycin ITP: Harrison DE et al. *Nature* 2009;460:392–395 / Epel ES et al. *PNAS* 2004 (telomeres and stress) / Newman JC, Verdin E. *Science* 2017;356:493–494 (BHB review).

## 8.1 Aging Clocks for Metabolic Organs

In addition to blood-based epigenetic clocks, organ-level metabolic aging can be quantified: **liver** (NAFLD progression and liver-fibrosis risk scores), **pancreas** (β-cell functional decline; HOMA-β falls with age), **skeletal muscle** (sarcopenia; grip strength/gait speed as clinical proxies), and **adipose tissue** (visceral/subcutaneous ratio and SASP biomarkers). OrganAge (2023, *Nature*) used organ-specific plasma proteins to estimate the age of individual organs; accelerated aging of metabolism-related organs (pancreas, muscle, fat) was independently associated with risks of type 2 diabetes and sarcopenia. The clinical value of metabolic clocks is to **identify individuals with accelerated metabolic aging several years before disease develops**, creating a window for lifestyle or pharmacological intervention—also a central reason DunedinPACE is being considered in clinical-trial endpoint design.

## 8.2 Metabolic Aging, Sarcopenia, and Cognitive Decline: The “Metabolism–Organ Axis”

The consequences of metabolic aging extend beyond glucose and lipids: through the “metabolism–organ axis,” it amplifies whole-body aging:

- **Sarcopenia**: Muscle is the largest metabolic organ (40% of body weight and 20% of resting energy expenditure). Metabolic aging and sarcopenia are mutually causal: insulin resistance reduces muscle protein synthesis (abnormal mTORC1 signaling), declining mitochondrial function weakens muscle energy supply, and chronic inflammation promotes muscle-protein breakdown. The vicious cycle of “less muscle → worse metabolism → even less muscle” is a core pathway to frailty in older adults. Grip strength/gait speed are clinical screening measures (Asian Working Group for Sarcopenia, AWGS criteria); DEXA muscle-mass measurement confirms the diagnosis. The core intervention is **resistance training plus adequate protein (1.2–1.5 g/kg/day)**; leucine/vitamin D supplementation has supportive evidence.
- **Type 2 diabetes**: Incidence rises with age (approximately 20–30% among people over 65), and diabetes in older adults commonly coexists with sarcopenia, cognitive decline, and cardiovascular disease (“geriatric diabetes syndrome”). Glycemic targets should be individualized to avoid hypoglycemia and falls from over-treatment.
- **Cognitive decline**: Although small (2% of body weight), the brain consumes 20% of the body’s glucose—**the brain is a “metabolically dependent” organ**. Insulin resistance is associated with Alzheimer’s disease risk (some studies have called AD “type 3 diabetes”). Metabolic disorders (hyperglycemia, dyslipidemia, inflammation) contribute to neurodegeneration through blood–brain barrier damage, tau phosphorylation, and impaired β-amyloid clearance. Improving metabolism (exercise, Mediterranean diet, glucose control) is an actionable cognitive-protection strategy (see [07-interventions/03-nutrition.md](../07-interventions/03-nutrition.md)).
- **NAFLD and liver aging**: Nonalcoholic fatty liver disease progresses with age (approximately 30–40% over age 50). Steatosis → steatohepatitis → fibrosis → cirrhosis is a continuum of “liver aging.” The liver is also a metabolic hub (gluconeogenesis, lipid metabolism, drug metabolism); declining hepatic function amplifies systemic metabolic dysfunction—“protecting the liver = protecting metabolism.”

**Clinical implications:** Intervention for metabolic aging should be “multiorgan and coordinated”—glucose-lowering drugs alone or exercise alone address only part of the problem. The combination of **“resistance training + protein + aerobic exercise + Mediterranean diet + metabolic monitoring”** improves metabolism in muscle, liver, pancreas, and brain simultaneously, making it a high-value metabolic anti-aging prescription (see [07-interventions/01-daily-checklist.md](../07-interventions/01-daily-checklist.md)).

## 9. Evidence Grading

| Proposition | Evidence grade |
|---|---|
| Insulin resistance increases with age | A (consistent across many populations) |
| DAG/ceramide mediate lipotoxic insulin resistance | A (mechanistic evidence + human muscle biopsies) |
| CR extends lifespan in model organisms | A (multiple species) |
| CR extends human lifespan | C (no direct evidence) |
| Fasting/ketogenic diets improve metabolic health | B (supported by RCTs; long-term safety undetermined) |
| Metformin as an anti-aging intervention in humans | C (TAME results unavailable) |
| GLP-1 weight loss/cardiovascular benefit | A (RCTs) |
| Metabolic interventions alter DunedinPACE | B (preliminary support) |

## 9.1 A Practical Pathway for Metabolic Anti-Aging: From Evidence to Action

Based on this chapter’s mechanisms and evidence, actionable metabolic anti-aging measures can be tiered by “strength of evidence × accessibility”:

**Tier 1 (strongest evidence; start now)**
- **Exercise**: Aerobic activity (more than 150 minutes per week) plus resistance training (2–3 times per week) simultaneously improves insulin sensitivity, mitochondrial function, muscle mass, and metabolic flexibility. It is the foundation of metabolic anti-aging (see [07-interventions/02-exercise.md](../07-interventions/02-exercise.md)).
- **Dietary pattern**: Mediterranean/anti-inflammatory diet plus glucose control (reduce refined carbohydrates and free sugars) improves lipids, glucose, and inflammation; dark-green vegetables provide dietary nitrate and support the NO pathway.
- **Weight management**: A 5–10% weight loss (if overweight) can substantially improve insulin sensitivity; reducing visceral fat is key.

**Tier 2 (moderate evidence; opportunities to optimize)**
- **Intermittent fasting** (16:8 or 5:2): activates AMPK/autophagy and improves metabolic biomarkers—but protein intake and muscle maintenance must be ensured; older adults should avoid extreme regimens.
- **Supplements (caution)**: Fish oil (for triglycerides), vitamin D (if deficient), and magnesium—evidence grades B/C; do not rely on them excessively.
- **Metformin** (for people with a metabolic indication, by prescription): activates AMPK; TAME results will inform its anti-aging evidence.

**Tier 3 (emerging monitoring)**
- **Annual metabolic monitoring**: HOMA-IR, ApoB, hsCRP, visceral fat, and VO₂max—use data to guide adjustments.
- **GLP-1 drugs** (for people with obesity/high cardiovascular risk): substantial weight loss and cardiovascular benefits, but a clinician should assess the risk of muscle loss.

**Core principle:** There is no “magic drug” for metabolic aging. The best-supported approach is the combined “punch” of **exercise + diet + weight management + monitoring**; drugs (metformin/GLP-1) complement rather than replace it. Metabolic health is the “foundation” of anti-aging: without it, benefits from advanced interventions such as reprogramming and senolytics are difficult to realize (echoing “Stage 1: interventions already ready” in [09-immortality/04-roadmap](../09-immortality/04-roadmap.md)). Starting early and sustaining the effort matter more than any single measure—metabolic aging is cumulative, so the earlier intervention begins, the greater the compounding benefit.

## 10. Open Questions

1. Which comes first, metabolic dysfunction or aging—is metabolic dysfunction a driver or an outcome?
2. What is the optimal fasting regimen and window (CR vs. IF vs. ketogenic diet, with individual variation)?
3. Can metformin truly slow human biological aging (awaiting TAME results)?
4. Can restoration of AMPK/mTOR balance reverse existing metabolic damage, or only prevent it?
5. Can the metabolic clock (DunedinPACE) serve as a clinical-grade anti-aging endpoint?
6. What are the limits of reversibility of lipotoxic damage, especially to β cells and the liver?
