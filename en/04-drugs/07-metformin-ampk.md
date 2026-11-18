# Metformin and AMPK: An Anti-Aging Pioneer through Drug Repurposing

> This is a core article in the LongLife knowledge base’s “metabolic anti-aging interventions” series, cross-referenced with 02-vascular/03-metabolic-aging.md (metabolic aging), 01-foundations/03-no-basics.md (NO pathway), and 04-drugs/05-molecular-mech.md (eNOS/sGC molecular mechanisms). Metformin is the only marketed drug to have entered a large registered anti-aging clinical trial (TAME). Its central mechanism is activation of AMPK, the cellular energy sensor, which in turn influences mTORC1, autophagy, mitochondrial biogenesis, and the NO and NAD+ networks.

---

## Core Concepts

Metformin (chemical name: dimethylbiguanide) is the world’s most widely prescribed oral glucose-lowering drug, with hundreds of millions of prescriptions annually, low cost, and a safety record spanning more than 60 years. It is also **the only marketed drug to have entered a large registered anti-aging clinical trial (TAME)** and is regarded by the longevity-research community as a flagship drug-repurposing candidate. Its signature molecular target is AMPK (AMP-activated protein kinase), a highly evolutionarily conserved cellular energy sensor. AMPK detects increases in the AMP/ATP and ADP/ATP ratios. Once activated, it shuts down energy-consuming anabolism (protein, lipid, and cholesterol synthesis and mTORC1) and turns on energy-producing catabolism (glucose uptake, fatty-acid oxidation, autophagy, and mitochondrial biogenesis), while upregulating stress resistance and inflammatory-clearance programs. The anti-aging rationale follows: one hallmark of aging is “dysregulated nutrient sensing” (AMPK activity falls with age while mTORC1 becomes overactive). Metformin reverses this imbalance by “mimicking energy scarcity,” while also increasing NO production through AMPK→eNOS, thus providing vascular protection. It is important to emphasize that human anti-aging evidence is still mainly observational; randomized controlled evidence (TAME) had not been reported as of 2026. The most accurate characterization is “proven for glucose lowering, unproven for anti-aging.”

## 1. History: From French Lilac to a Global Blockbuster

Metformin’s story is a classic path from folk remedy to chemical synthesis to clinical rediscovery:

- **Traditional use**: The natural precursor of metformin comes from **French lilac (*Galega officinalis*, goat’s rue)**, which was used in medieval Europe to treat polyuria and symptoms of diabetes. Its active compounds are guanidine alkaloids, especially galegine, an isoprenyl derivative of guanidine.
- **The chemical era**: Systematic study of guanidine-based glucose-lowering drugs began in the 1920s. Werner and Bell first synthesized metformin (dimethylbiguanide) in 1922, but clinical exploration began in earnest with Slotta and Tschesche’s 1929 screening of biguanide compounds. Guanidine and synthalin were abandoned in the 1920s–1930s because of liver toxicity, and the biguanides then fell into obscurity.
- **Clinical rediscovery**: In the 1950s, French physician **Jean Sterne** reassessed metformin in 1957 under the brand name Glucophage (“glucose eater”), establishing its clinical role. Phenformin (DBI) was marketed around the same time but was withdrawn in many countries during the 1970s because of its high fatal lactic-acidosis rate (about 50 per 100,000 person-years, far higher than metformin’s). This episode profoundly shaped metformin’s regulatory pathway and the fear of lactic acidosis, whose risk has in fact been overestimated for a long time.
- **Global adoption**: The US FDA approved metformin for type 2 diabetes in 1994; publication of UKPDS in 1998 established its first-line status. The TAME trial was designed and approved in 2016, formally entering the anti-aging arena. Metformin remains on the WHO Model List of Essential Medicines and typically costs less than 100 RMB per year.

**Historical lesson and anti-aging implication**: Phenformin’s demise stigmatized all biguanides with “lactic-acidosis risk,” but evidence indicates metformin’s risk is not significantly higher than that of sulfonylureas or placebo (see the adverse-effects section). This also reminds anti-aging researchers that drug toxicity must be assessed according to evidence grading, not inherited from the history of related compounds.

## 2. Pharmacokinetics: Transporters Determine Everything

Metformin is highly water-soluble, not protein-bound, not metabolized by the liver, and excreted unchanged by the kidneys. Its distribution in the body is determined largely by the **organic cation transporter (OCT)** family:

| Parameter | Value | Key point |
|---|---|---|
| Oral bioavailability | About 50–60% | Absorbed mainly in the upper small intestine; wide individual variation (25–90%) |
| Plasma peak concentration (Cmax) | About 10–40 µM (usual doses) | Liver concentrations may be tens of times higher than plasma (can exceed 100 µM) |
| Time to peak | 1–3 h (immediate-release tablets) | Delayed to 4–8 h with extended-release formulations |
| Volume of distribution | About 300–500 L | Enriched in liver, kidneys, and intestinal wall |
| Plasma half-life | About 6.2 h (4–8.7 h) | Tissue half-life is longer, about 17.6 h |
| Excretion | Unchanged via glomerular filtration and tubular secretion | No CYP metabolism; few drug interactions |

**Transporter overview** (the “gatekeepers” of metformin’s fate in the body):

```
Intestinal absorption: PMAT (SLC29A4, apical intestinal epithelium) + OCT3 (SLC22A3)
   ↓
Hepatic uptake: OCT1 (SLC22A1, hepatocyte basolateral membrane) ← main entry route for suppression of hepatic glucose output
   ↓
Renal excretion: OCT2 (SLC22A2, basolateral membrane of proximal tubule) → apical MATE1/MATE2-K (SLC47A1/A2) secretion into urine
```

- **OCT1 (hepatic uptake)**: Genetic polymorphisms (e.g., reduced-function variants such as R61C and G401S) lower hepatic uptake in roughly 7–10% of people and weaken the glucose-lowering response. This is a genetic basis for why the same dose has different effects in different people and suggests that hepatic, not plasma, concentration may be the key determinant of efficacy.
- **OCT2/MATE (renal excretion)**: OCT2 inhibitors (e.g., cimetidine, some NSAIDs, and dolutegravir) reduce tubular secretion and may raise blood concentrations. Metformin is contraindicated in renal impairment with eGFR <30 mL/min/1.73 m²; between 30 and 45, the dose should be reduced and use approached cautiously.
- **Drug interactions**: Because metformin does not depend on cytochrome P450, it has far fewer interactions than most glucose-lowering drugs—one advantage for long-term use in older adults.

**Concentration–effect paradox (important)**: Plasma metformin concentrations (10–40 µM) are far below the millimolar concentrations needed to inhibit mitochondrial complex I in vitro. This has led to longstanding debate about the main molecular target at physiological concentrations (see the mechanisms section). Tissue concentrations, especially in the liver, are much higher than plasma concentrations, but even so, the 2022 PEN2 lysosomal-pathway study repositioned the molecular target based on the finding that “lower concentrations are effective.”

## 3. Full Molecular Mechanistic Chain

### 3.1 AMPK: the cellular energy sensor

AMPK is a heterotrimer composed of **α (catalytic), β (scaffold), and γ (regulatory) subunits**. Mammals have multiple isoforms of each (α1/α2, β1/β2, γ1/γ2/γ3), producing more than 12 possible heterotrimers with different tissue distributions (e.g., skeletal muscle is enriched in α2β2γ3, whereas liver contains mainly α1/α2β1γ1). Its core regulatory logic is as follows:

- The **γ subunit** contains four tandem CBS (cystathionine β-synthase) domains forming four nucleotide-binding pockets (Bateman domains), which competitively bind **AMP, ADP, and ATP**—the molecular basis of AMPK’s ability to sense the “exchange rate” of cellular energy currency.
- **Thr172** in the activation loop of the α subunit is the critical site phosphorylated by upstream kinases to activate AMPK (other regulation also occurs, such as interactions between the α-subunit autoinhibitory domain [AID] and carbohydrate-binding module [CBM]).
- The **β subunit** contains a glycogen-binding domain (CBM), allowing AMPK to anchor to glycogen particles and directly sense glycogen levels.

**AMP activates AMPK by three mechanisms** (textbook energy-sensing biology):

```
Energy scarcity (AMP↑ / ATP↓)
   │
   ▼
AMP binds γ subunit ──┬─→ ① allosteric activation (modest increase in enzyme activity, ~2–5-fold)
                      ├─→ ② protects Thr172 from dephosphorylation by PP2C/PP2A (“anti-dephosphorylation”)
                      └─→ ③ makes Thr172 more susceptible to phosphorylation by upstream kinase LKB1 (“pro-phosphorylation”)
   │
   ▼
Thr172 phosphorylation → kinase activity rises >100-fold → phosphorylation of downstream substrates
```

There are two upstream kinases: **LKB1** (a tumor suppressor that forms a complex with STRAD/MO25) is the main kinase under energy scarcity; **CaMKK2 (CaMKKβ)** responds to increased Ca²⁺ (e.g., muscle contraction or neuronal excitation), allowing energy and calcium signals to converge. Dephosphorylation is carried out by phosphatases such as PP2Cα. **ADP also protects Thr172 but does not cause allosteric activation**, while ATP antagonizes both; AMPK therefore senses both AMP/ATP and ADP/ATP ratios.

### 3.2 Classical mechanism: complex I inhibition → AMP/ATP↑ → AMPK activation

The classic model of metformin-mediated AMPK activation (Zhou 2001; El-Mir 2000; Owen 2000) is:

```
Metformin (positively charged; accumulates in mitochondrial matrix driven by membrane potential)
   │
   ▼
Inhibits mitochondrial electron-transport-chain complex I (NADH:ubiquinone oxidoreductase)
   │ (mild inhibition, not lethal; slows the respiratory chain rather than stopping it)
   ▼
ATP production↓ → AMP/ATP ratio↑
   │
   ▼
AMP binds AMPKγ → LKB1 phosphorylates Thr172 → AMPK activation
   │
   ├─→ inhibits anabolism (mTORC1/ACC/HMGCR) ← see 3.4
   └─→ activates catabolism (autophagy/mitochondrial biogenesis/glucose uptake)
```

**Key detail**: Metformin is a lipophilic cation that **accumulates in the mitochondrial matrix**, driven by the inner-membrane potential (matrix levels may be 10–1,000 times cytosolic levels). This is the physical basis for inhibition of complex I. Inhibition is “mild and partial”: complete complex I inhibition would kill the cell, whereas metformin only slightly reduces respiratory efficiency and puts cells into “energy-saving mode.” This is accompanied by a **low-level increase in mitochondrial ROS**, which itself can act as a **hormetic** signal that induces antioxidant and stress-resistance programs (called mitohormesis in worm studies; De Haes 2014). Low-dose ROS activates transcription factors such as Nrf2/SKN-1, a potential component of metformin’s “fight fire with fire” anti-aging action.

### 3.3 AMPK-independent mechanisms: an expanded picture

Metformin still suppresses gluconeogenesis in mice lacking hepatic AMPK (Foretz 2010), demonstrating that **its primary glucose-lowering effect does not depend entirely on AMPK**. At least four AMPK-independent pathways have been identified:

| Pathway | Mechanism | Effect | Key reference |
|---|---|---|---|
| Rag GTPase pathway | Increased AMP (or direct action through the v-ATPase/Ragulator complex) changes Rag nucleotide state, preventing mTORC1 recruitment to the lysosomal membrane | Direct mTORC1 inhibition, bypassing AMPK→TSC2/Raptor | Kalender 2010, *Cell Metab* |
| mGPD inhibition | Inhibits mitochondrial glycerol-3-phosphate dehydrogenase (mGPD, GPD2), blocking transfer of cytosolic NADH into mitochondria and raising the cytosolic NADH/NAD+ ratio | Suppresses gluconeogenesis (lactate/glycerol→glucose), rapid glucose lowering | Madiraju 2014, *Nature* |
| Gut-microbiome remodeling | Alters microbial composition (Bacteroidetes/Firmicutes ratio; increased *Akkermansia muciniphila*) and improves glucose homeostasis through host–microbiome metabolism; metformin-mediated lifespan extension in worms depends on bacterial folate/methionine metabolism | Systemic metabolic improvement and anti-inflammation | Cabreiro 2013, *Cell*; Shin 2014, *Gut* |
| One-carbon metabolism/folate | Interferes with folate and methionine cycles (partly through inhibition of one-carbon enzymes such as MTHFD1), changing SAM/SAH ratios and the supply of epigenetic substrates | Alters methylation and nucleotide synthesis | Cabreiro 2013; mechanistic studies |

**PEN2 lysosomal pathway (2022 milestone)**: Ma et al. (*Nature*, 2022) found that **low, near-physiological concentrations** of metformin activate lysosome-localized AMPK through the lysosomal membrane protein **PEN2 → ATP6AP1 → v-ATPase**, coupled to an AXIN/LAMTOR complex, without significantly inhibiting complex I. This directly challenges the classical model that complex I is the sole primary target and suggests an integrated framework: **low doses act mainly through the PEN2 lysosomal pathway, while higher doses add complex I inhibition**. This echoes the dose-response finding in mice by Martin-Montalvo et al. (2013), where low doses extended lifespan and high doses were harmful. As of 2026, the relative in-vivo contributions of the two pathways remain actively debated.

### 3.4 Overview of AMPK downstream effects: anabolic brakes and catabolic accelerators

Once activated, AMPK acts in two phases, through **direct phosphorylation of metabolic enzymes** (seconds to minutes) and **phosphorylation of transcriptional/epigenetic regulators** (hours):

```
AMPK activation (Thr172-P)
   │
   ├─ Inhibits anabolism ─────────────────────────────────────
   │   ├─→ phosphorylates Raptor (Ser792) → 14-3-3 binding → mTORC1 substrate recruitment↓ → protein synthesis↓
   │   ├─→ phosphorylates TSC2 (Ser1387) → activates TSC1/2 → Rheb-GAP → Rheb-GDP (inactive) → mTORC1↓
   │   ├─→ phosphorylates ACC1 (Ser79)/ACC2 (Ser221) → malonyl-CoA↓ → fatty-acid synthesis↓, β-oxidation↑
   │   ├─→ phosphorylates HMGCR (Ser872) → cholesterol synthesis↓
   │   └─→ phosphorylates SREBP1c → lipid-synthesis gene transcription↓
   │
   └─ Activates catabolism ─────────────────────────────────────
       ├─→ phosphorylates ULK1 (Ser317/Ser777) → initiates autophagy/mitophagy (cooperates with PINK1-Parkin)
       ├─→ phosphorylates PGC-1α (Thr177/Ser538) + subsequent SIRT1 deacetylation → mitochondrial biogenesis↑
       ├─→ promotes GLUT4 translocation → glucose uptake↑ in skeletal muscle/adipose tissue
       ├─→ phosphorylates eNOS (Ser1177) → NO production↑ (see section 7)
       ├─→ activates TFEB → lysosome biogenesis and autophagic flux↑
       ├─→ phosphorylates PFKFB3 → glycolytic flux↑
       └─→ phosphorylates p53/FOXO → stress resistance and cell-cycle checkpoints
```

**Correspondence with hallmarks of aging**: mTORC1 inhibition counters “dysregulated nutrient sensing” (hallmark 8); autophagy/mitophagy counters “disabled autophagy” (hallmark 11) and “mitochondrial dysfunction” (hallmark 3); PGC-1α promotes mitochondrial biogenesis; eNOS/NO supports vascular and endothelial health; anti-inflammation (NF-κB inhibition) counters “chronic inflammation” (hallmark 10) and the SASP (the secretory phenotype of hallmark 12, cellular senescence). AMPK is thus a **pleiotropic hub spanning all 12 hallmarks of aging**.

## 4. Evidence Grading

| Finding | Evidence level | Key reference |
|---|---|---|
| Glucose lowering and fewer microvascular/macrovascular complications in type 2 diabetes | Established (RCT) | UKPDS 34, *Lancet* 1998 |
| Prevention of progression from prediabetes to diabetes | Established (RCT, DPP) | *NEJM* 2002; *Diabetes Care* 2019 |
| Longer lifespan and healthspan in mice | Animal support (positive in some models) | Martin-Montalvo 2013 *Nat Commun*; Anisimov 2008 |
| Longer lifespan in worms (depends on bacterial folate metabolism/AMPK) | Animal support (mechanism and microbiome dependence; negative reports exist) | Onken 2010; Cabreiro 2013; De Haes 2014 |
| Lower all-cause/cardiovascular mortality among users | Strong association (observational, substantial confounding) | Bannister 2014; Campbell 2017 |
| Survival in metformin-treated diabetics comparable to or better than non-diabetics | Observational (high risk of healthy-user bias) | Bannister 2014 |
| Lower cancer risk | Association (meta-analyses suggest ~10% reduction; serious confounding) | Evans 2005 *BMJ*; Noto 2012 |
| Anti-aging in healthy older adults (composite endpoint) | Mechanistic hypothesis/trial underway | TAME (designed by Barzilai 2016; results unpublished) |
| Improved endothelial function/NO-dependent vasodilation | Animal and small human studies | Mather 2001; Chen 1999 |
| SASP inhibition/anti-inflammatory effect | Strong in vitro/animal; indirect human evidence | Moiseeva 2013; Cameron 2016 |
| Vitamin B12 deficiency with long-term use | Established (4-year RCT follow-up) | de Jager 2010 *BMJ* |
| Lactic acidosis in people with normal renal function | Established as “very low risk” (not higher than placebo) | Salpeter 2010 Cochrane |

## 5. Anti-Aging Evidence in Detail: From Worms to TAME

### 5.1 Animal models

- **Worms (*C. elegans*)**: Onken and Driscoll (2010) reported that metformin extended worm healthspan through AMPK (aak-2) and SKN-1/Nrf2 pathways, producing a dietary-restriction-like state. Cabreiro et al. (2013, *Cell*) further showed that its lifespan effect **depends on bacterial folate/methionine metabolism**: the effect disappeared in germ-free worms or when bacterial folate metabolism was blocked, bringing the microbiome into metformin’s anti-aging mechanism for the first time. Note that negative reports and lifespan shortening also exist, and effect size depends on dose, worm strain, and bacterial genotype.
- **Mice**: **Martin-Montalvo et al. (2013, *Nat Commun*)** is a key study. B6C3F1 mice fed 0.1% metformin had **about 5.8% longer mean lifespan in males and 4.3% in females**, with healthspan also extended, alongside enhanced resistance to oxidative stress and improved mitochondrial function. **A crucial finding was a biphasic dose response: 1% high-dose metformin shortened lifespan**, showing that “more is better” is a fallacy. Anisimov et al. (2008) also observed lifespan extension in female SHR mice. In contrast, testing by the US **ITP** in genetically heterogeneous UM-HET3 mice did not reproduce significant lifespan extension, suggesting dependence on strain/genetic background.
- **Interpretation**: Overall, animal evidence is “partially supportive, dose-sensitive, and mechanistically complex.” Compared with rapamycin’s cross-strain lifespan effects in ITP, metformin’s animal evidence is weaker and more background-dependent.

### 5.2 Human evidence: UKPDS, DPP, and observational cohorts

- **UKPDS 34 (1998, *Lancet*)**: Intensive metformin treatment versus conventional treatment in overweight people with type 2 diabetes reduced diabetes-related endpoints by **32%** (RR 0.68), all-cause mortality by **36%** (RR 0.64), and myocardial infarction by **39%** (RR 0.61). Ten-year follow-up (Holman 2008, *NEJM*) found a **legacy effect**: even after glycemic control later converged, the metformin group continued to have lower risks of myocardial infarction (RR 0.67) and all-cause death (RR 0.73). **The effect exceeded glucose lowering alone**, the strongest clinical hint that metformin might act on aging itself.
- **DPP/DPPOS (from *NEJM*, 2002)**: In people with prediabetes, 850 mg twice daily reduced diabetes incidence by **31%** versus placebo over three years; cumulative incidence was 18% lower at 15 years in DPPOS. **Adults over 60 benefited more (approximately 71% reduction, much greater than in younger groups)**—a counterintuitive “greater benefit with older age” finding often cited by anti-aging researchers.
- **Observational cohorts (beware confounding)**: Bannister et al. (2014), using 78,241 UK CPRD records, found all-cause mortality among diabetic patients starting metformin was **lower than in matched non-diabetic controls** (roughly 15% lower, HR≈0.85) and significantly lower than among those starting sulfonylureas. Campbell et al. (2017) similarly found in a large US cohort that metformin users had survival comparable to or better than non-diabetic controls. These results create the striking picture that “metformin users outlive even healthy controls,” but **healthy-user bias and confounding by indication** (people who tolerate metformin may already be healthier) cannot be ruled out; causal conclusions are unwarranted.
- **TAME (Targeting Aging with Metformin)**: The first registered RCT directly designed to target aging, conceived by Nir Barzilai’s team (Cell Metab 2016), planned to enroll about 3,000 non-diabetic adults aged 65–79 and administer metformin 1,500 mg/day. The primary endpoint is a **composite of new age-related diseases (cardiovascular disease, cancer, dementia, death, etc.)**, operationalizing “slowing aging” as “delaying multimorbidity.” The design was approved in 2016 but repeatedly delayed by recruitment and funding issues; as of 2026 results had not been reported. A positive result would be the first registered-level evidence that a metabolic drug delays human biological aging; a negative result would substantially downgrade the metformin anti-aging narrative.

## 6. Adverse Effects and Safety: Overestimated Fears and Underestimated Limitations

| Adverse effect | Incidence/risk | Key point |
|---|---|---|
| Gastrointestinal effects (diarrhea, nausea, bloating) | About 20–30% early on | Most common; low starting dose, administration with food, and extended-release formulations can help; most people adapt |
| Vitamin B12 deficiency | Significantly more likely with long-term use (≥4 years); blood B12 may fall by roughly 15–25% | Mechanism involves calcium-dependent intestinal absorption of B12–intrinsic-factor complexes; can cause peripheral neuropathy, difficult to distinguish from diabetic neuropathy; periodic monitoring or preventive supplementation is advisable |
| Lactic acidosis | **Very rare** (about 1–4 cases per 100,000 person-years), with no significant difference from placebo/other glucose-lowering drugs (Salpeter 2010 meta-analysis) | Mainly occurs with eGFR <30, acute kidney injury, decompensated heart failure, liver disease, sepsis, and other conditions that impair lactate clearance; negligible risk with normal renal function |
| Contrast-associated kidney injury | Requires management | Hold metformin before iodinated contrast according to guidelines (often recommended if eGFR <60) |
| Interaction with exercise | Controversial | Konopka 2019 suggests it may blunt exercise-induced mitochondrial adaptation in older adults (see controversies) |

**Regulatory evolution**: In 2016 the FDA revised the labeling, replacing “abnormal creatinine” as a contraindication with eGFR <30 as contraindicated and eGFR 30–45 as a dose-reduction/caution range. This acknowledged that previous restrictions motivated by lactic-acidosis concerns had been overly conservative—a case of evidence-based medicine correcting a historical stigma.

## 7. Connections to NO, NAD+, and Longevity Networks (Distinctive Perspective)

**AMPK→eNOS→NO axis**: AMPK directly phosphorylates the activating site **Ser1177** of endothelial nitric oxide synthase (eNOS) (Chen 1999, *FEBS Lett*), the same “master-switch” site used by Akt. Metformin increases endothelium-dependent vasodilation through this pathway. Human evidence: Mather et al. (2001, *JACC*) observed improved flow-mediated forearm vasodilation (the NO-dependent component) in people with type 2 diabetes. Animal studies broadly support improved endothelial function and reduced atherosclerosis. This makes metformin a classic **metabolic drug that also protects blood vessels**—a modern mechanistic analogue of the traditional Chinese medicine concept of “boosting qi and activating blood,” converging on improved endothelial NO supply (see 01-foundations/03-no-basics.md).

**AMPK→NAD+→SIRT1 axis**: Cantó and Auwerx (2009, *Nature*) showed that AMPK activation increases **NAMPT** (the rate-limiting enzyme in NAD+ salvage synthesis), raising NAD+ and activating SIRT1. SIRT1-mediated deacetylation of PGC-1α cooperates with AMPK phosphorylation in a dual “phosphorylation + deacetylation” modification that amplifies mitochondrial biogenesis. Some studies also suggest that metformin itself can raise NAD+ through metabolic reprogramming of one-carbon metabolism, although the exact pathway requires verification. This closes the longevity-network loop **metformin→AMPK→NAD+/SIRT1→PGC-1α** (see section 4 of 02-vascular/03-metabolic-aging.md).

**NO’s double-edged-sword warning**: Mildly increased mitochondrial ROS from metformin (hormesis) and the generation of ONOO− from NO under oxidative stress (see 04-drugs/05-molecular-mech.md) show that any intervention that promotes NO or ROS must be understood in the context of redox balance. This is the theoretical anchor for interpreting metformin’s overall benefit: moderate stress induces adaptation; excessive stress causes damage.

## 8. Metformin and Cancer: Promising Supporting Evidence That Is Hard to Prove

Epidemiological interest began with Evans et al. (2005, *BMJ*), who found lower cancer risk among metformin users. Dozens of subsequent cohorts and meta-analyses broadly support an association of roughly a 10% reduction (Noto 2012, *PLoS One*), with relatively consistent subgroup signals for colorectal, breast, and prostate cancers. Mechanisms are plausible: AMPK→mTORC1 inhibition (mTORC1 drives tumor growth), AMPK→p53 signaling, lower insulin/IGF-1 levels (hyperinsulinemia is itself pro-cancer), and suppression of inflammation and SASP (Moiseeva 2013 showed metformin suppresses the SASP of senescent cells through interference with IKK/NF-κB). **However, confounding in observational evidence (disease stage, treatment duration, health behaviors) is severe.** Morales and Morris’s 2015 review noted that effects weaken substantially when more rigorous studies are included, and randomized trials with cancer endpoints are largely absent. Conclusion: plausible mechanisms, existing associations, but no established causality.

## 9. Intervention Directions and Practical Recommendations

**Priority populations** (ordered by strength of evidence):

1. **Type 2 diabetes, prediabetes, or metabolic syndrome**: strongest evidence and established indication; DPP found greater benefit in adults over 60.
2. **Obesity/insulin resistance without established diabetes**: may improve metabolic phenotypes beyond glucose lowering; moderate evidence.
3. **Healthy older adults without a metabolic indication**: only in clinical-trial settings (TAME); as of 2026 this is not a routine recommendation, and RCT results are awaited.

**Dose and use** (based on diabetes practice; anti-aging dose is undetermined): start at 500 mg once daily with food and increase after 1–2 weeks; usual maintenance is 1,000–2,000 mg/day in divided doses. Extended-release preparations reduce gastrointestinal effects. TAME uses 1,500 mg/day.

**Monitoring checklist**: eGFR at least annually (contraindicated below 30; dose reduction at 30–45); serum B12 every 1–2 years with long-term use (methylmalonic acid [MMA] is more sensitive if needed); consider preventive B12 supplementation; consider potential interaction when combining with exercise training (see controversies).

**Combination rationale (theoretical, not a clinical recommendation)**: Metformin (AMPK axis) and caloric restriction/exercise (endogenous activation of the same axis) or NAD+ precursors (downstream SIRT1 cooperation) are mechanistically complementary, but combination effects lack human data; do not self-stack these interventions.

## 10. Open Questions and Controversies

1. **TAME results remain pending**: A negative or weakly positive result would substantially reset the anti-aging narrative around metformin. The ethics and risk-benefit assessment of self-use by healthy people “off-label without an indication” also depend on the result.
2. **Healthy-user bias**: In observational cohorts, how much of the “exceptional survival” of metformin users is a drug effect, and how much reflects the fact that people able to tolerate and continue the drug were healthier to begin with? Mendelian randomization (using OCT1 genotype as an instrumental variable) offers partial support but cannot fully resolve this.
3. **Which mechanism predominates?** Complex I inhibition versus the PEN2 lysosomal pathway: which is the main target at physiological concentrations? What are the respective contributions of AMPK-dependent and -independent effects? These questions directly affect the design of next-generation metformin analogues.
4. **Biphasic dosing**: Low doses extend animal lifespan and high doses shorten it (Martin-Montalvo 2013). Does a similar “optimal dose window” exist in humans? Should an anti-aging dose be lower than a glucose-lowering dose?
5. **Interaction with exercise**: A randomized controlled study by Konopka et al. (2019, *Aging Cell*) found that metformin **blunted** exercise-training-induced mitochondrial adaptation in older adults (although insulin sensitivity still improved); other studies have not found this effect. Evidence remains conflicting for the realistic combination of “exercise + metformin.”
6. **Background dependence in animal models**: Negative findings in genetically heterogeneous ITP mice versus positive findings in single strains suggest genetic dependence. If so, stratifying human “responders” and “nonresponders” will be important.
7. **B12 and neuropathy paradox**: Epidemiology suggests metformin may reduce dementia risk, but metformin-associated B12 deficiency is linked to peripheral neuropathy. The net effect depends on dose, duration, and monitoring.

## References

1. Bailey CJ. Metformin: historical overview. *Diabetologia*. 2017;60(9):1566–1576.
2. Werner EA, Bell J. The preparation of methylguanidine, and of ββ-dimethylguanidine by the oxidation of adrenaline. *J Chem Soc Trans*. 1922;121:1790–1794.
3. UK Prospective Diabetes Study (UKPDS) Group. Effect of intensive blood-glucose control with metformin on complications in overweight patients with type 2 diabetes (UKPDS 34). *Lancet*. 1998;352(9131):854–865.
4. Holman RR, Paul SK, Bethel MA, Matthews DR, Neil HA. 10-year follow-up of intensive glucose control in type 2 diabetes. *N Engl J Med*. 2008;359(15):1577–1589.
5. Zhou G, Myers R, Li Y, et al. Role of AMP-activated protein kinase in mechanism of metformin action. *J Clin Invest*. 2001;108(8):1167–1174.
6. El-Mir MY, Nogueira V, Fontaine E, Avéret N, Rigoulet M, Leverve X. Dimethylbiguanide inhibits cell respiration via a specific effect on the electron transport chain. *J Biol Chem*. 2000;275(1):223–228.
7. Owen MR, Doran E, Halestrap AP. Evidence that metformin exerts its anti-diabetic effects through inhibition of complex 1 of the mitochondrial respiratory chain. *Biochem J*. 2000;348(Pt 3):607–614.
8. Hardie DG, Ross FA, Hawley SA. AMPK: a nutrient and energy sensor that maintains energy homeostasis. *Nat Rev Mol Cell Biol*. 2012;13(4):251–262.
9. Xiao B, Sanders MJ, Underwood E, et al. Structure of mammalian AMPK and its regulation by ADP. *Nature*. 2011;472(7342):230–233.
10. Martin-Montalvo A, Mercken EM, Mitchell SJ, et al. Metformin improves healthspan and lifespan in mice. *Nat Commun*. 2013;4:2192.
11. Cabreiro F, Au C, Leung KY, et al. Metformin retards aging in *C. elegans* by altering microbial folate and methionine metabolism. *Cell*. 2013;153(1):228–239.
12. Onken B, Driscoll M. Metformin induces a dietary restriction-like state and the oxidative stress response to extend *C. elegans* healthspan via AMPK, LKB1 and SKN-1. *PLoS One*. 2010;5(1):e8758.
13. De Haes W, Frooninckx L, Van Assche R, et al. Metformin promotes lifespan through mitohormesis via the peroxiredoxin PRDX-2. *Proc Natl Acad Sci USA*. 2014;111(24):E2501–E2509.
14. Anisimov VN, Berstein LM, Egormin PA, et al. Metformin slows down aging and extends life span of female SHR mice. *Cell Cycle*. 2008;7(17):2769–2773.
15. Foretz M, Hébrard S, Leclerc J, et al. Metformin inhibits hepatic gluconeogenesis in mice independently of the LKB1/AMPK pathway via a decrease in hepatic energy state. *J Clin Invest*. 2010;120(7):2355–2369.
16. Madiraju AK, Erion DM, Rahimi Y, et al. Metformin suppresses gluconeogenesis by inhibiting mitochondrial glycerophosphate dehydrogenase. *Nature*. 2014;510(7506):542–546.
17. Kalender A, Selman A, Comb WC, et al. Metformin, independent of AMPK, inhibits mTORC1 in a Rag GTPase-dependent manner. *Cell Metab*. 2010;11(5):390–401.
18. Ma T, Tian X, Zhang B, et al. Low-dose metformin targets the lysosomal AMPK pathway through PEN2. *Nature*. 2022;603(7900):159–165.
19. Shin NR, Lee JC, Lee HY, et al. An increase in the *Akkermansia* spp. population induced by metformin treatment improves glucose homeostasis in diet-induced obese mice. *Gut*. 2014;63(5):727–735.
20. Barzilai N, Crandall JP, Kritchevsky SB, Espeland MA. Metformin as a tool to target aging. *Cell Metab*. 2016;23(6):1060–1065.
21. Diabetes Prevention Program Research Group. Reduction in the incidence of type 2 diabetes with lifestyle intervention or metformin. *N Engl J Med*. 2002;346(6):393–403.
22. Diabetes Prevention Program Research Group. Long-term effects of metformin on diabetes prevention: identification of subgroups that benefited most. *Diabetes Care*. 2019;42(4):601–608.
23. Bannister CA, Holden SE, Jenkins-Jones S, et al. Can people with type 2 diabetes live longer than those without? *Diabetes Obes Metab*. 2014;16(11):1165–1173.
24. Evans JM, Donnelly LA, Emslie-Smith AM, Alessi DR, Morris AD. Metformin and reduced risk of cancer in diabetic patients. *BMJ*. 2005;330(7503):1304–1305.
25. Noto H, Goto A, Tsujimoto T, Noda M. Cancer risk in diabetic patients treated with metformin: a systematic review and meta-analysis. *PLoS One*. 2012;7(3):e33411.
26. Salpeter SR, Greyber E, Pasternak GA, Salpeter EE. Risk of fatal and nonfatal lactic acidosis with metformin use in type 2 diabetes mellitus. *Cochrane Database Syst Rev*. 2010;(4):CD002967.
27. de Jager J, Kooy A, Lehert P, et al. Long-term treatment with metformin in patients with type 2 diabetes and risk of vitamin B-12 deficiency: randomized placebo-controlled trial. *BMJ*. 2010;340:c2181.
28. Konopka AR, Laurin JL, Schoenberg HM, et al. Metformin inhibits mitochondrial adaptations to exercise in older adults. *Aging Cell*. 2019;18(1):e12880.
29. Moiseeva O, Deschênes-Simard X, St-Germain E, et al. Metformin inhibits the senescence-associated secretory phenotype by interfering with IKK/NF-κB activation. *Aging Cell*. 2013;12(3):489–498.
30. Cameron AR, Morrison VL, Levin D, et al. Anti-inflammatory effects of metformin irrespective of diabetes status. *Circ Res*. 2016;119(5):652–665.
31. Mather KJ, Verma S, Anderson TJ. Improved endothelial function with metformin in type 2 diabetes mellitus. *J Am Coll Cardiol*. 2001;37(5):1344–1350.
32. Chen ZP, Mitchelhill KI, Michell BJ, et al. AMP-activated protein kinase phosphorylation of endothelial NO synthase. *FEBS Lett*. 1999;443(3):285–289.
33. Cantó C, Gerhart-Hines Z, Feige JN, et al. AMPK regulates energy expenditure by modulating NAD+ metabolism and SIRT1 activity. *Nature*. 2009;458(7241):1056–1060.
34. Morales DR, Morris AD. Metformin in cancer treatment and prevention. *Annu Rev Med*. 2015;66:17–29.
