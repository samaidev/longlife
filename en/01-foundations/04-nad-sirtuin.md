#NAD⁺/SIRT1 Longevity Network

> NAD⁺ (nicotinamide adenine dinucleotide) is both a core coenzyme for cellular redox (the electron carrier for hundreds of dehydrogenases) and the only substrate for the **sirtuin deacetylase family**. The decline of tissue NAD⁺ with age is regarded as an important driver of metabolic decline and aging, and supplementing NAD⁺ precursors (NMN/NR) has become one of the most concerned anti-aging interventions in the human body. NAD⁺ is not a simple "energy molecule", but a hub connecting energy metabolism, DNA repair, inflammation and circadian rhythm - its synthesis and consumption constitute a dynamically balanced "reservoir", and imbalances at either end will be amplified into systemic metabolic and functional changes through the sirtuin family.

---

## 1. Synthetic pathway of NAD⁺

### 1.1 Three synthetic pathways

| Pathways | Starting substrates | Rate-limiting enzymes | Relative contribution in humans |
|---|---|---|---|
| **De novo synthesis** | Tryptophan (Trp) | IDO/TDO → Quinolinic acid (QA) | Minor (limited by tryptophan intake) |
| **Salvage** | Niacinamide (NAM) | **NAMPT (rate limiting)** | Dominant (>90%) |
| **Preiss-Handler** | Niacin (niacin/NA) | NAPRT1 | Moderate (dietary niacin dependent) |

```
De novo synthesis: Trp → N-formylkynurenine → kynurenine → 3-hydroxykynurenine
            → 3-hydroxyanthranilic acid → α-amino-β-carboxymuconic acid-ε-semialdehyde
            → Quinolinic acid (QA) → Quinolinic acid phosphoribosyltransferase (QPRT) → NAMN → NMN → NAD⁺

Remedy: NAM ──NAMPT (speed limit)──► NMN ──NMNAT1-3──► NAD⁺
            ↑ │
            └────── NAD⁺ consumes enzyme by-product NAM ◄──────┘
                   (SIRT/CD38/PARP hydrolyzes NAD⁺ to release NAM)

Preiss-Handler: NA ──NAPRT1──► NAMN ──NMNAT──► NAAD ──NADSYN1──► NAD⁺
```

- **De novo synthesis**: Tryptophan generates quinolinic acid through the kynurenine pathway, and then enters the NAD⁺ skeleton through QPRT. Humans have limited tryptophan intake, so this pathway contributes little, and the kynurenine pathway itself is related to immune regulation (IDO) - IDO is induced during inflammation and shifts tryptophan to kynurenine instead of NAD⁺. This suggests that chronic inflammation not only consumes NAD⁺ through CD38, but also inhibits the supply of raw materials for de novo synthesis, constituting a double blow.
- **Rescue Pathway**: NAD⁺ is hydrolyzed by consumption enzymes (SIRT1-7, CD38, PARP) to release **nicotinamide (NAM)**, NAM is recycled by **NAMPT** to generate NMN, and then NMNAT adds adenylate to generate NAD⁺. **NAMPT is the rate-limiting enzyme in overall NAD⁺ metabolism** and its activity/expression determines NAD⁺ pool size. The three isoforms of NMNAT are divided into compartments: **NMNAT1 is localized in the nucleus** (mainly serving the NAD⁺ requirement of SIRT1/PARP in the nucleus), **NMNAT2 is located in the Golgi apparatus/cytoplasm** (particularly important in neurons, where loss leads to axonal degeneration), **NMNAT3 is located in the mitochondria** (serves SIRT3-5 and mitochondrial respiration). This compartmentalization means that "total NAD⁺ levels" cannot fully represent "available NAD⁺ within the nucleus or mitochondria" - it is the relative changes in different subcellular pools that determine specific functional directions. NAMPT comes in two forms: an intracellular enzyme (iNAMPT) and a secreted extracellular enzyme (eNAMPT, which can enter the circulation to regulate distant tissues). **Imai's research group found that SIRT1 in the hypothalamus can "direct" systemic NAD⁺ levels by regulating eNAMPT secretion** - This established the framework of "central control of peripheral NAD⁺" (Yoshida 2019), and suggested that the concentration of eNAMPT in plasma decreases with age and is related to insulin sensitivity.
- **Preiss-Handler**: Niacin (vitamin B3) enters NAD⁺ through the three steps of NAPRT1 → NMNAT → NADSYN1, which is a cheap and effective way to increase NAD⁺, but the skin flushing caused by niacin (prostaglandin-mediated) limits compliance.

### 1.2 Decline with age: about 50% (tissue differences)

- NAD⁺ levels in multiple human tissues (skin, liver, muscle, brain) decrease with age by about **30–50%**, and accelerate after the age of 60; the decline in different tissues varies (muscle/brain is more obvious, liver is relatively preserved).
- **Mechanism** (superposition of three factors):
  1. **NAMPT activity/expression is reduced** (the salvage pathway is weakened, and the NAD⁺ "reproduction" ability is reduced);
  2. **CD38 upregulation** (NAD⁺ hydrolase expression increases with age in macrophages/immune cells and is the main consumer);
  3. PARP (DNA Repair Depleting NAD⁺) is activated during inflammation/injury.
- **Specific data on tissue differences**: Human skin NAD⁺ decreases by approximately 40–50% at age 60–70 compared to age 20–30; skeletal muscle decreases by approximately 30%; liver decreases to a smaller extent (approximately 10–20%); brain and adipose tissue also decrease significantly. The decline is not linear—some studies suggest it begins to accelerate after age 40, and the decline in endothelium-related NAD⁺-dependent function is more pronounced in postmenopausal women. **Differences in detection methods** (tissue biopsy vs blood cells, LC-MS vs enzymatic method) will cause differences in reported values, and cross-study data need to be interpreted with caution.
- Consequences: Decreased NAD⁺ → Decreased SIRT1 activity → Impaired function of deacetylation substrates (PGC-1α, FOXO, eNOS, etc.) → Overall decline in mitochondrial function, metabolism, and vascular function. It should be emphasized that NAD⁺ levels in blood and NAD⁺ in tissues are not always synchronized** because the entero-liver axis and blood cell metabolism will consume or transform precursors first, which explains the phenomenon of "significant increase in blood NAD⁺ but limited tissue benefit" in many human trials.

---

## 2. NAD⁺ consuming enzymes: SIRT1-7, CD38, PARP

NAD⁺ is not only a coenzyme but also a substrate for many enzymes. Depleting enzymes compete for the same NAD⁺ pool:

| Enzyme families | Members | Reactions | Subcellular localization | Aging-related changes |
|---|---|---|---|---|
| **Sirtuin** | SIRT1-7 | NAD⁺ + Acetyl Lysine → Deacetylation + NAM + O-acetyl-ADP-ribose | Nuclear/Cytoplasmic/mitochondria | Activity decreases with NAD⁺ |
| **CD38** | Transmembrane glycoprotein | NAD⁺ → cADPR/ADPR + NAM (NADase) | Plasma membrane, extracellular | **Up-regulated with age (major NAD⁺ consumer)** |
| **PARP** | PARP1/2 | NAD⁺ → poly(ADP-ribose) modification | Nuclear | Activated upon damage/DNA breakage |

**Prominence of CD38**: CD38 expression is upregulated in aging tissues (due to inflammatory macrophage infiltration), and knocking out CD38 in mice or using a CD38 inhibitor (e.g., 78c) restores NAD⁺ and improves mitochondrial function (Chini et al.; Camacho-Pereira 2016 demonstrated that CD38 is the primary enzymatic cause of age-related decline in NAD⁺). CD38 is also a major gate for extracellular hydrolysis of NMN after it enters cells—which directly affects the oral bioavailability of NMN. It is worth noting that the product of CD38, cADPR (cyclic adenosine diphosphate ribose), is itself a second messenger for calcium release from the endoplasmic reticulum and is involved in immune cell activation. Therefore, "inhibiting CD38 to preserve NAD⁺" may simultaneously weaken part of the calcium signaling function, which needs to be weighed when designing CD38 inhibitors.

**Competitive relationship of consumption enzymes**: SIRT1, CD38, and PARP share the same NAD⁺ pool, and the three constitute a "distribution game" - DNA damage (PARP activation) and chronic inflammation (CD38 upregulation) will crowd out the NAD⁺ available for SIRT1. This is an important indirect mechanism for "SIRT1 activity decrease" in aging. On the contrary, both PARP inhibitors and CD38 inhibitors can "release" NAD⁺ to SIRT1 in animals, forming an intervention idea. This "enzymatic competition" also explains why simply replenishing precursors (increasing supply) has limited effect in certain inflammatory/injury states - because the upregulation of CD38/PARP on the consumption side will "eat" the newly replenished NAD⁺. **This suggests that "open source" (supplementing precursors) and "throttling" (inhibiting CD38/PARP) need to be coordinated**, which is the logical basis for current joint intervention research.

---

## 3. SIRT1: NAD⁺-dependent deacetylase

### 3.1 Structure and Catalysis

- **Domain**: SIRT1 contains an N-terminal regulatory domain and a highly conserved **catalytic core domain (sirtuin domain, about 275 aa)**, which is divided into two subdomains: **Rossmann fold domain (binding NAD⁺)** and zinc-binding domain (binding acetylated substrate peptide); the gap between the two subdomains is the active site.
- **Catalysis**: The nicotinamide moiety of NAD⁺ is transferred to the acetyl group to generate **O-acetyl-ADP-ribose + NAM** (the product NAM is also a NAMPT substrate and is recycled in a closed loop); this reaction **strictly depends on the NAD⁺ concentration**, Km is about 100–300 μM, so NAD⁺ physiological fluctuations directly modulate SIRT1 activity. Because the physiological concentration of NAD⁺ (approximately hundreds of μM) falls well within the sensitive range of SIRT1, subtle fluctuations in cellular NAD⁺ can proportionally change the rate of deacetylation—the molecular basis for "NAD⁺ is the sirtuin switch."
- **Activity regulation**: NAD⁺ provided by NAMPT is the main control; in addition, SIRT1 expression is induced by AMPK and inhibited by miR-34a and others. The endogenous inhibitor DBC1 (deleted in breast cancer 1) can bind to the catalytic domain of SIRT1 to inhibit its activity. During DNA damage, DBC1 competitively binds to PARP1, thereby derepressing SIRT1 during stress. This "competitive inhibition switch" suggests that SIRT1 activity is finely regulated by protein-protein interactions and is not simply determined by NAD⁺ concentration.

### 3.2 Full spectrum of deacetylated substrates (site + effect)

| Substrate | Primary acetylation site | Desacetylation effects | Biological consequences |
|---|---|---|---|
| **PGC-1α** | Lys779 (and K13/K609, etc.) | Activate transcriptional co-activation function | Mitochondrial biogenesis↑, gluconeogenesis regulation, oxidative metabolism↑ |
| **FOXO1/3a** | FOXO1 K262/K265; FOXO3a K242/K259 | Prefer antioxidant genes (MnSOD, Catalase, GADD45) rather than apoptosis | Antioxidant defense↑, cell survival↑ |
| **NF-κB (p65/RelA)** | Lys310 | Inhibits NF-κB transcriptional activity | Anti-inflammatory (downregulates TNF-α, IL-6) |
| **p53** | Lys382 (and K320/K373) | Inhibit p53 transcriptional activity | Anti-apoptosis, cell cycle checkpoint downregulation |
| **eNOS** | Lys496/Lys506 (human sequence) | Enhance eNOS activity | NO production ↑ → vasodilation (see §6) |
| **HSF1** | Lys298/Lys524 | Enhance the binding of HSF1 to HSE | Expression of heat shock proteins (HSP70, etc.) ↑ → Protein homeostasis |

- Full spectrum of more than 60 substrates: also includes STAT3, HIF-1α, SREBP, PPARγ, Ku70, LKB1, etc., covering each axis of metabolism, inflammation, stress, and DNA repair. Deacetylation of LKB1 enhances its ability to activate AMPK, forming an amplification circuit of "SIRT1→AMPK"; deacetylation of HIF-1α inhibits its stability and affects angiogenesis in the context of hypoxia/tumor - this suggests that SIRT1 is not blindly "anti-aging" and may become a "double-edged sword" in certain pro-angiogenesis and pro-proliferation situations.
- **Tissue specificity**: SIRT1 plays a significant role in metabolically active tissues - liver (gluconeogenesis, lipid metabolism), fat (fat mobilization), muscle (mitochondria), hypothalamus (feeding regulation); endothelium (eNOS) is its vascular-specific function. In the hypothalamus, SIRT1 also regulates the activity of POMC and AgRP neurons, thereby affecting appetite and energy consumption. It is another entrance to "central metabolism regulation".

**Division of labor between SIRT1 and other sirtuins**: SIRT1 is located in the nucleus and cytoplasm, and is the most intensively studied member of aging; SIRT2 is mainly in the cytoplasm (microtubules, metabolism); SIRT3/4/5 is in the mitochondria (SIRT3 deacetylase mitochondrial enzyme, is the main switch of mitochondrial NAD⁺ sensing); SIRT6/7 is in the nucleus (genome stability, rDNA transcription). The families share NAD⁺-dependent mechanisms but different substrate profiles, so the consequences of "NAD⁺-drop" are network-wide and not just SIRT1. In particular, SIRT3 is highly expressed in cardiac and skeletal muscles and is responsible for deacetylating and activating most mitochondrial respiratory chain complexes. It is a downstream executor of "SIRT1 down-regulation of mitochondria"; SIRT6 maintains chromatin stability in the telomeric region by deacetylating H3K9/H3K56 and is positively related to genome integrity and lifespan (overexpression of SIRT6 in mice extends lifespan).

---

## 4. Interaction between circadian rhythm and SIRT1/NAMPT

NAD⁺ metabolism is not constant but oscillates with circadian rhythms. **The core circuit of the mammalian circadian clock (CLOCK/BMAL1 and PER/CRY) directly controls the transcription of NAMPT**: CLOCK/BMAL1 binds to the E-box element in the NAMPT promoter, causing NAMPT expression to peak during the active phase, thereby driving rhythmic fluctuations in NAD⁺ and SIRT1 activity. In turn, **SIRT1 deacetylates BMAL1 and PER2**, inhibiting circadian clock gene expression, forming a negative feedback loop of "circadian clock → NAMPT → NAD⁺ → SIRT1 → circadian clock".

The aging significance of this interaction is: **The amplitude of the circadian clock in older individuals is attenuated, and the rhythmic peak value of NAMPT is reduced, resulting in blunting of the daily fluctuation of NAD⁺**, thereby weakening the rhythmic activation of SIRT1. Animal experiments show that day-night reversal (chronic jet lag) can accelerate NAD⁺ metabolic disorders and promote metabolic diseases; restoring regular work and rest and time-restricted eating (limiting the eating window to the active phase) can partially restore the rhythmic expression of NAMPT and NAD⁺ levels. This provides a molecular explanation for "regular sleep/time-restricted eating can resist aging", and also directly connects lifestyle intervention with the NAD⁺/SIRT1 pathway (see 07-interventions/05-sleep-optimization.md for details).

---

## 5. NMN/NR Supplement: Absorption, Human Data, Controversy

### 5.1 Absorption mechanism and Slc12a8 controversy

- **NR (nicotinamide ribose)**: directly enters cells via the balanced nucleoside transporter (ENT1/ENT2), or is first dephosphorylated extracellularly by CD73; after entering the cell, it is phosphorylated to NMN by NRK1/NRK2. **The entry pathway of NR into cells is basically clear**.
- **NMN (nicotinamide mononucleotide)**: It was once considered that it must be dephosphorylated into NR outside the cell before entering the cell (CD73 pathway); in 2019 **Grozio et al. proposed that Slc12a8 is the direct transporter of NMN** (Science sub-journal), but subsequent laboratories failed to repeat it, and the expression of Slc12a8 in human tissues is extremely low——**"Slc12a8 is NMN The transporter "is currently in a state of controversy**, and the mainstream view is still that "extracellular dephosphorylation → NR → entry into the cell" dominates. Cantó 2012 and Yoshino 2011 respectively established the NAD⁺ potency of NR and NMN in mammals, laying the foundation for subsequent human trials.
- **Intestinal flora conversion**: Orally administered NMN/NR is enzymatically converted by flora and intestinal epithelium in the intestine; part of NMN is dephosphorylated into NR in the small intestine for reabsorption. Other studies suggest that NMN can be absorbed through intestinal transporters and increase liver NAD⁺ (Yoshino 2018). The composition of the bacterial flora can affect the conversion efficiency of precursors to NAD⁺, and individual differences are large - this also means that there are obvious "individual differences in the bacterial flora" in the efficacy of supplements, and the increase in NAD⁺ at the same dose in different people may vary several times.
- **Pharmacokinetics points**: The plasma peak of NMN appears about 10-15 minutes after oral administration (some data suggest rapid clearance), and NR requires NRK phosphorylation after being transported into the cell via ENT; both circulate in the blood as metabolites, and the proportion of intact NMN entering the blood by direct measurement is very low - most evidence supports that "the precursor is rapidly transformed and utilized in the enterohepatic axis, rather than entering the circulation in its original form." This suggests that delivery form (extended-release, enteric-coated) may influence tissue NAD⁺-boosting efficiency more than the dose itself**.

### 5.2 Human trial data (pivotal RCT)

| Research | Design | NAD⁺ Enhancement | Key Findings | Security |
|---|---|---|---|---|
| Martens et al. 2018 (*Nat Commun*) | NR 1g/d, 12 weeks | Blood NAD⁺ ↑approximately 60–90% (dose dependent) | Elevated NAD⁺ metabolites; limited improvement in functional endpoints (blood pressure, etc.) | Good, no serious AEs |
| Airhart et al. 2017 | NR 250–1000 mg/d | Dose dependent ↑ | No significant anti-inflammatory/functional benefit | Good |
| Yoshino et al. 2021 (*Science*) | NMN 250 mg/d for 10 weeks (postmenopausal women with prediabetes) | Skeletal muscle NAD⁺↑approximately 21–25% | **Muscle insulin sensitivity↑** (glycogen synthesis↑, improved insulin signaling) | Good, no AEs |
| Igarashi et al. 2022 | NMN 250 mg/d, 12 weeks (healthy elderly men) | Increase in blood NAD⁺ | Improvement in physical fitness indicators such as grip strength and walking speed (small sample) | Good |
| Cognitive endpoints | A small number of trials suggest that NR/NMN may improve cognitive scores in older adults | — | The evidence is moderate (small samples, mostly open label) | Larger RCTs are needed |

- **Consensus**: Oral NR/NMN can safely and dose-dependently increase blood/tissue NAD⁺ (approximately 1.5–2-fold); however, benefits on functional endpoints (grip strength, insulin sensitivity, cognition) are **inconsistent**, with most large trials showing no significant improvement; long-term (>1 year) safety data are lacking. A systematic review by Amjad et al. in *Mol Metab* in 2021 further confirmed that precursor supplementation can indeed increase circulating NAD⁺ in most human studies, but the evidence for converting the increase in NAD⁺ into an improvement in clinical endpoints is still insufficient, suggesting that "NAD⁺ is only a necessary condition but not a sufficient condition."
- **Theoretical Risk**: Elevated NAD⁺ can theoretically enhance tumor cell DNA repair and proliferation (SIRT1/PARP dependent), that is, the "cancer feeding" hypothesis - there is currently no evidence of human causality and it is open to controversy. Rajman 2018 specifically discussed this double-edged sword attribute in the *Cell Metab* review, arguing that caution is needed in individuals with pre-existing precancerous lesions or high tumor risk.
- **Practice Points**: The peak plasma concentration of NMN/NR after oral administration occurs at 30-60 minutes, and the half-life is short. Animal experiments mostly use daily divided administration; in human studies, NR absorption is better than NMN (NR can be directly absorbed into the cells), but NMN’s NAD⁺-increasing efficiency in some tissues (liver) is not inferior to NR; the additive effect of the two combined with exercise and fasting has not been systematically verified in RCT. In terms of dosage, 250–1000 mg/day is commonly used in human studies. Below this dosage, the improvement is limited, and above this dosage, the marginal returns are diminishing. The hypothesis of "more is better" lacks evidence support.
- **Emerging directions (disease states such as COVID-19)**: A 24-week randomized controlled trial (58 patients with COVID-19) conducted at Massachusetts General Hospital in 2021–2023 suggested that NR supplementation (up to 20 weeks) may improve neurological symptoms such as fatigue and brain fog. In December 2025, the media reported its early results. This represents an extension of NAD⁺ precursors from "anti-aging in healthy people" to "intervention in disease states", but its mechanism (reduction of inflammation vs recovery of mitochondrial function) and universality still need to be verified with a larger sample, and it is temporarily classified as Level C evidence.

---

## 6. Coupling with NO: positive feedback loop

NAD⁺/SIRT1 and NO form a long-lived positive feedback loop:

```
NAD⁺ ──► SIRT1 ──deacetylates eNOS (K496/K506)──► eNOS activity↑
                                                  │
                                                  ▼
NO generated↑                                                  │
                 ┌────────────────────────────────┤
                 ▼                                ▼
sGC/cGMP → PKG AMPK activation (NO inhibition│ Complex I mildly activates AMPK)                 ▼                                │
Vasodilation, anti-inflammatory ▼SIRT1 expression↑ / NAD⁺ metabolism↑(Positive feedback closed loop)```

- **SIRT1 → eNOS → NO**: SIRT1 deacetylates Lys496/Lys506 of eNOS, enhancing its activity → NO production↑ → endothelial relaxation, anti-inflammatory, and anti-thrombotic. Mattagajasingh 2007 established this causal chain by directly demonstrating in *PNAS* that SIRT1 overexpression enhances eNOS activity and endothelial relaxation.
- **NO → SIRT1 activation**: NO upregulates SIRT1 expression and activity through the sGC/cGMP/PKG and AMPK pathways; NO itself also inhibits eNOS uncoupling and reduces oxidative stress damage to SIRT1. "Mild mitochondrial stress" (hormesis) caused by NO inhibition of mitochondrial complex I triggers AMPK activation, which in turn induces SIRT1 expression - this is a non-classical mechanism of "NO promotes SIRT1", which together with the antioxidant properties of NO form a closed loop (see 01-foundations/03-no-basics.md for details).
- **Pathological significance**: Age-related decrease in NAD⁺ → SIRT1 activity↓ → insufficient eNOS deacetylation → NO bioavailability↓ → endothelial dysfunction (an early sign of vascular aging); at the same time, NO↓ → SIRT1 downregulation, forming a **vicious cycle**. This explains why NAD⁺ supplementation partially restores endothelial NO function in animals (NMN treatment in mice restores aortic NO-dependent relaxation).
- **Clinical relevance**: Common SNPs in the SIRT1 promoter region (eg, rs7895833 and rs1467568) are associated with metabolic phenotypes, suggesting that interindividual genetic differences in this circuit may influence aging trajectories and responsiveness to NAD⁺ precursors. **Genetic-Environmental Interaction**: Endothelial NO function may respond differently to NAD⁺ precursors in individuals carrying specific SIRT1 SNPs—a potential direction for future "precision supplementation."

---

## 7. Cross-regulation with AMPK/mTOR

NAD⁺/SIRT1 is not an island, but the hub of the energy sensing network, forming a triple regulation with AMPK and mTOR:

- **SIRT1 ↔ AMPK mutual activation**: SIRT1 deacetylates LKB1 to enhance its ability to activate AMPK; AMPK activates SIRT1 by increasing the NAD⁺/NAD⁺H ratio and inducing NAMPT expression. The two form a positive feedback that "works together to burn fat and promote mitochondria when energy is scarce", which is the common molecular basis for the anti-aging effects of exercise and calorie restriction (see 04-drugs/07-metformin-ampk.md for details, metformin is an AMPK activator).
- **SIRT1 ↔ mTOR antagonism**: SIRT1 inhibits the mTOR pathway (in part by deacetylating TSC2 or modulating AMPK), whereas mTOR activation inhibits autophagy and promotes anabolism. When nutrients are sufficient, mTOR is dominant and inhibits autophagy; when nutrients are scarce/time-restricted feeding, SIRT1-AMPK is dominant, activating autophagy and mitochondrial biogenesis. **NAD⁺/SIRT1 is a "preferentially activated during fasting" pathway, and mTOR is a "preferentially activated during eating" pathway** - the trade-off between the two defines the direction of the cell's response to nutritional status (see 04-drugs/06-mtor-rapamycin.md for details).
- **Comprehensive perspective**: Anti-aging interventions (exercise, fasting, metformin, NAD⁺ precursors) often "increase SIRT1-AMPK and decrease mTOR" at the same time, rather than a single target. This also explains why a single supplement (which only raises NAD⁺) is less effective in humans than a combination of lifestyle interventions - because the latter act on multiple levers such as AMPK/mTOR simultaneously.
- **Connection with immunosenescence**: The bidirectional effect of NAD⁺ on immune cells is worth noting - SIRT1 inhibition of NF-κB can suppress chronic inflammation, but moderate NAD⁺/SIRT1 activity is a necessary condition for T cell activation and differentiation; immune cells (especially macrophages) themselves are the main source of CD38, so **The NAD⁺ demand and consumption of the immune system constitutes a self-feedback**: the more severe the inflammation, the higher the CD38, and the NAD⁺ The lower it is, the weaker the anti-inflammatory ability of SIRT1 and the more severe the inflammation. This makes NAD⁺/SIRT1 a hub connecting "metabolic aging" and "immunosenescence" (inflammaging) (see 03-immunity/02-inflammaging.md and 03-immunity/04-immunosenescence.md for details).

---

## 8. Intervention Strategies

| Intervention | Mechanism | Strength of Evidence |
|---|---|---|
| **NMN/NR supplementation** | Directly increases NAD⁺ → activates SIRT1 | Human RCT: Confirmed NAD⁺ elevation, inconsistent functional benefit (Grade B) |
| **Niacin (NA)** | Preiss-Handler Pathway | Cheap and effective NAD⁺, but flushing side effects limit compliance (Grade B) |
| **CD38 inhibitors** (e.g. 78c, apigenin) | Reduce NAD⁺ hydrolysis | Strong evidence in animals, early stage in humans (Level C) |
| **Motor** | Muscle AMPK↑ → NAMPT↑ → NAD⁺↑; eNOS activation | Strong (Grade A/B, mechanism confirmed) |
| **Caloric restriction/fasting** | Metabolic stress → Elevated NAD⁺/NAMPT → SIRT1 activation | Confirmed in animals, moderate in humans (Grade B) |
| **Light/circadian rhythm** | Biological clock (SIRT1–CLOCK interaction), moderate UV → cutaneous NO release | Emerging areas (Level C) |
| **SIRT1 activators such as resveratrol** | Direct activation/stabilization of SIRT1 (mechanism is controversial, some evidence points to indirect effects of AMPK) | Diverse animals, inconsistent in humans (Grade C) |

- **Exercise**: Endurance training significantly increases muscle NAMPT and NAD⁺, while activating eNOS (shear stress + AMPK). It is currently the most solid evidence for endogenous improvement. High-intensity interval training (HIIT) improves muscle mitochondrial function and NAD⁺ metabolism slightly better than moderate-intensity continuous training. The two-way effect of exercise in "raising NAMPT and lowering CD38" makes it better than simply supplementing precursors - because it "opens up sources" while also "throttling" (see 07-interventions/02-exercise.md for details).
- **Fasting/Calorie Restriction**: NAD⁺/NAMPT elevation and SIRT1 activation are one of the core mechanisms of CR mimetic effects (animal model). Alternate-day fasting and time-restricted eating (such as 16:8) can slightly increase blood NAD⁺ and improve metabolic indicators in preliminary human trials, but individual differences are large and long-term compliance is a major challenge. The reason why time-restricted eating is effective is likely related to the circadian mechanism of §4 - limiting eating to the active phase can amplify the rhythmic peak of NAMPT.
- **Light**: Ultraviolet A/B can cause the skin to photolyze nitrite to release NO (the skin is the NO reservoir in the body), suggesting that moderate sun exposure has vascular benefits; however, the mechanism and dose still need to be confirmed.

---

## 9. Evidence Grading and Open Questions

### Evidence Grading

| Hierarchy | Content |
|---|---|
| A (confirmation) | Three NAD⁺ synthesis pathways, NAMPT rate-limiting status; SIRT1 catalytic mechanism and substrate deacetylation; CD38 is a NAD⁺ consuming enzyme; exercise/CR upregulates NAD⁺; NAMPT-circadian clock interaction circuit |
| B (strong) | Tissue NAD⁺ decreases by 30–50% with age; CD38 upregulation is the main reason (animal knockout/suppression experiment); NMN/NR can safely increase NAD⁺ in humans; NAD⁺→SIRT1→eNOS→NO positive feedback chain (Mattagajasingh 2007 confirms eNOS link) |
| C (Moderate/Controversial) | Functional endpoint benefit (insulin sensitivity occasionally positive, mostly neutral); Slc12a8 transporter; long-term safety (tumor risk theory); the mechanism by which resveratrol directly activates SIRT1 is controversial |

### Open questions

1. **Optimal strategy for precursors**: The dosage, dosage form, administration timing and population stratification of NMN vs NR vs NA are still inconclusive; whether it is necessary to combine "source + throttling" with CD38/PARP inhibitors is still unclear.
2. **Is "NAD⁺ elevation = health benefit" true?**: There is a disconnect between NAD⁺ elevation and functional improvement in human RCT, suggesting that other bottlenecks may exist (such as SIRT1 expression, CD38 activity, tissue delivery efficiency). Amjad 2021’s systematic review points this out.
3. **Long-term cancer risk**: The "double-edged sword" controversy of NAD⁺/SIRT1 promoting DNA repair in tumor cells lacks human data.
4. **Tissue Targeting**: How to selectively increase NAD⁺ in specific tissues (muscle/brain/endothelium) rather than overall - the development of CD38 inhibitors and tissue-specific precursors is at the forefront.
5. **The causal direction of "decreased NAD⁺" and "decreased SIRT1 activity"**: It is still inconclusive whether SIRT1 activity will inevitably recover after CD38 inhibitors increase NAD⁺, or whether there is a regulatory bottleneck other than NAD⁺ (such as DBC1 inhibition, miR-34a expression).
6. **Dose-Response Relationship**: The "therapeutic window" for NAD⁺ elevation has not yet been defined - too low will be ineffective, and too high will cause desensitization or compensation. It is still unclear.

---

## 10. Summary of coupling with NO pathway

NAD⁺/SIRT1 shares the same longevity network with NO: **NAD⁺ → SIRT1 → eNOS deacetylation → NO → AMPK/cGMP → SIRT1↑**. The two pathways are synergistically attenuated in vascular aging, metabolism, and immunity, and together constitute molecular targets for intervention such as exercise, fasting, and supplements. In the knowledge base panorama, this pathway forms dense interconnections with [NO Basics](03-no-basics.md), [mitochondria and NO](../02-vascular/04-mitochondria.md), [chronic inflammation](../03-immunity/02-inflammaging.md), [metformin and AMPK](../04-drugs/07-metformin-ampk.md), [mTOR with rapamycin](../04-drugs/06-mtor-rapamycin.md), [Exercise Prescription](../07-interventions/02-exercise.md) and [12 Hallmarks of Aging](01-aging-hallmarks.md), jointly supporting the overall framework of "vasculature-metabolism-immunity" three-axis collaborative anti-aging. Understanding the complete mechanistic chain of NAD⁺/SIRT1 (synthesis → consumption → deacetylation → NO/AMPK/mTOR cross-over → circadian rhythm) is a prerequisite for evaluating the effectiveness of any "anti-aging supplement" and lifestyle intervention.
**References**:- Yoshino J, Mills KF, Yoon MJ, Imai S. Nicotinamide mononucleotide, a key NAD⁺ intermediate, treats the pathophysiology of diet- and age-induced diabetes in mice. *Cell Metab* 2011;14:528-536. (Establishing the NAD⁺-raising and metabolism-improving efficacy of NMN in mammals)
- Cantó C, Houtkooper RH, Pirinen E, et al. The NAD⁺ precursor nicotinamide riboside enhances oxidative metabolism and protects against high-fat diet-induced obesity. *Cell Metab* 2012;15:838-847. (Establishing the role of NR)
- Yoshino J, Baur JA, Imai SI. NAD⁺ intermediates: the biology and therapeutic potential of NMN and NR. *Cell Metab* 2018;27:513-528. (Review)
- Rajman L, Chwalek K, Sinclair DA. Therapeutic potential of NAD⁺-boosting molecules: the in vivo evidence. *Cell Metab* 2018;27:529-547. (review, including "double-edged sword" discussion)
- Martens CR, Denman BA, Mazzo MR, et al. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD⁺ in healthy middle-aged and older adults. *Nat Commun* 2018;9:1286. (NR Human Trial, Blood NAD⁺ ↑60–90%)
- Yoshino M, Yoshino J, Kayser BD, et al. Nicotinamide mononucleotide increases muscle insulin sensitivity in prediabetic women. *Science* 2021;372:1224-1229. (NMN Human Trials)
- Igarashi M, Nakagawa-Nagahama Y, Miura M, et al. Chronic nicotinamide mononucleotide supplementation elevates blood NAD⁺ and alters muscle function in healthy older men. *npj Aging* 2022;8:5. (NMN Elderly Men)
- Imai SI, Guarente L. NAD⁺ and sirtuins in aging and disease. *Cell Metab* 2014;20:957-963. (NAMPT/eNAMPT framework)- Amjad S, et al. Role of NAD⁺ in regulating cellular and metabolic signaling pathways. *Mol Metab* 2021;49:101195. (Systematic review)- Grozio A, Mills KF, Yoshino J, et al. Slc12a8 is a nicotinamide mononucleotide transporter. *Nat Metab* 2019;1:47-57. (Slc12a8, controversial)- Camacho-Pereira J, Tarragó MG, Chini CCS, et al. CD38 dictates age-related NAD⁺ decline and mitochondrial dysfunction. *Cell Metab* 2016;25:1127-1139.
- Mattagajasingh I, Kim CS, Naqvi A, et al. SIRT1 promotes endothelium-dependent vascular relaxation by activating endothelial nitric oxide synthase. *PNAS* 2007;104:14855-14860. (SIRT1 deacetylation eNOS)
- Cantó C, Auwerx J. Caloric restriction, SIRT1 and longevity. *Curr Opin Lipidol* 2009;20:91-96. (SIRT1 and metabolism)