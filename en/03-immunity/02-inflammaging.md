# Chronic Inflammation and Aging (Inflammaging)

> Inflammaging—low-grade, chronic, sterile, systemic inflammation that accompanies aging—is one of the 12 hallmarks of aging (the expanded López-Otín 2023 version) and the shared “soil” for cardiovascular disease, type 2 diabetes, neurodegeneration, cancer, and other age-related diseases. It does not arise from a single pathogen, but from a persistent, inefficient immune response to endogenous damage signals (DAMPs, SASP, and metabolic stress). Understanding its full molecular cascade is the key to understanding “why anti-inflammatory treatment is not simply equivalent to anti-aging.”

---

## Core Concept

The term **inflammaging** was formally introduced in 2000 by Italian immunologist Claudio Franceschi (*Ann N Y Acad Sci*). It refers to a **low-grade, chronic, sterile, systemic inflammatory state** that develops with age: no identifiable pathogen infection and none of the redness, swelling, heat, or pain of acute inflammation, but persistently mildly elevated baseline serum pro-inflammatory cytokines (IL-6, TNF-α, IL-1β) and acute-phase proteins (CRP, fibrinogen) that systematically drive tissue damage and age-related disease. Franceschi also proposed an evolutionary explanation, the “antigenic load theory”: the lifetime accumulation of antigenic stimuli (pathogens, self-antigens, damage molecules, and dietary components) continually consumes immune reserves. The immune system faces a dilemma between “defense” and “self-damage,” ultimately paying the cost of low-grade inflammation to maintain homeostasis. In 2013, López-Otín et al. proposed nine hallmarks of aging without listing inflammation separately; the 2023 expanded version formally added **chronic inflammation as the 12th hallmark** and macrophage-polarization imbalance as the 10th. Inflammation is no longer viewed as an incidental accompaniment of aging, but as an amplifier and effector connecting damage, compensation, and functional decline (see 01-foundations/01-aging-hallmarks.md).

## I. The Fundamental Difference from Acute Inflammation

| Dimension | Acute inflammation | Inflammaging |
|---|---|---|
| Triggers | Pathogen infection, tissue injury | Sterile DAMPs, SASP, metabolic stress, endotoxin |
| Intensity and duration | Intense; days to weeks; may resolve completely | Low-grade; persists for months or a lifetime |
| Typical signs | Redness, swelling, heat, pain, fever | No local signs; only mildly elevated laboratory markers |
| Dominant cells | Neutrophils, infiltrating monocytes | Macrophages (M1 bias), senescent cells, microglia |
| Outcome | Pathogen clearance, tissue repair, restoration of homeostasis | Accumulation of microdamage, fibrosis, functional decline |
| Biological meaning | Host defense (beneficial) | “Compensatory but ultimately harmful” immune activation |

Three points are important. First, although inflammaging is low intensity, **exposure is continuous and systemic**—an IL-6 increase of only 2–4-fold can predict a doubling of mortality, showing that “chronicity” can be more destructive than “intensity.” Second, inflammaging and immunosenescence (see 03-immunity/04-immunosenescence.md) are two sides of the same process: immunosenescence weakens pathogen clearance and tissue repair, allowing antigens and DAMPs to persist and continuously ignite inflammation. Third, the recent concept of **trained immunity** (Netea, 2016) adds a cellular basis: following an initial stimulus, monocytes/macrophages undergo epigenetic reprogramming (H3K4me3 and H3K27ac deposited at promoters of pro-inflammatory genes such as TNF and IL-6), acquiring “innate immune memory.” This makes older individuals’ responses to subsequent stimuli more intense and persistent, giving inflammaging self-amplifying dynamics.

## II. The Full Molecular Cascade

### 2.1 The Inflammatory Hub: NF-κB Signaling

Signals from nearly all inflammatory sources converge on the transcription factor NF-κB (p65/RelA–p50 heterodimer), the hub of the inflammatory clock. The full cascade is:

```
Upstream stimuli (TNF-α/TNFR, IL-1β/IL-1R, LPS/TLR4, DAMP/RAGE)
        │
        ▼
Adaptor proteins TRAF2/6, MyD88, TRIF
        │
        ▼
IKK complex (IKKα/IKKβ/IKKγ=NEMO) ── IKKβ phosphorylates IκBα (Ser32/36)
        │
        ▼
SCF-βTrCP E3 ligase → IκBα ubiquitination (Lys48) → degradation by 26S proteasome
        │
        ▼
NF-κB (p65/p50) exposes nuclear-localization sequence → enters nucleus → binds κB motifs
        │
        ▼
Transcription of hundreds of inflammatory genes: IL-6, TNF-α, IL-1β, COX-2, iNOS,
ICAM-1/VCAM-1, MCP-1, PAI-1, MMP-9…
```

Three abnormalities occur in this pathway during aging: (a) **more upstream stimulation**—SASP factors, oxidized mtDNA, LPS, and AGEs are continually supplied; (b) **impaired negative feedback**—NF-κB normally induces resynthesis of IκBα to limit its own activity, but this feedback weakens in aging tissues (associated with sustained IKK activation and delayed IκBα resynthesis); and (c) **failure of the deacetylation brake**—as NAD⁺ declines, SIRT1/SIRT6 activity falls, p65 K310 acetylation rises, and NF-κB transcriptional activity increases (see Section V). Nuclear NF-κB DNA-binding activity rises several-fold in the heart, liver, and brain of aged rats (Helenius 1996, etc.), and this increase precedes tissue pathology, suggesting that NF-κB is a driver, not merely a follower. NF-κB is also the master transcriptional regulator of SASP (in cooperation with C/EBPβ), locking “cellular senescence” and “systemic inflammation” into the same circuit.

### 2.2 The NLRP3 Inflammasome: From Sensor to Pyroptosis

The NLRP3 inflammasome is a “molecular amplifier” that converts diverse damage signals into IL-1β/IL-18 release and pyroptosis. Its activation follows a **two-signal model**:

```
Signal 1 (priming): TLR/NF-κB → transcriptional upregulation of NLRP3, pro-IL-1β, pro-IL-18
Signal 2 (activation; any one may suffice):
  ├─ K⁺ efflux (universal trigger; ATP/P2X7, pore-forming toxins, particulates can all act this way)
  ├─ Increased mitochondrial ROS / release of oxidized mtDNA
  ├─ Lysosomal damage → leakage of cathepsin B
  └─ Uric acid/cholesterol crystals, amyloid-β (Aβ), alum, and other particles
        │
        ▼
NLRP3 recruits NEK7 (required downstream of K⁺ efflux) → oligomerizes → recruits ASC
        │
        ▼
ASC helical filaments polymerize → form an “ASC speck” (one large cytoplasmic aggregate)
        │
        ▼
pro-caspase-1 is recruited and oligomerizes/autocleaves → active caspase-1
        │
        ├──► Cleaves pro-IL-1β → mature IL-1β (major amplifier)
        ├──► Cleaves pro-IL-18 → mature IL-18 (promotes IFN-γ)
        └──► Cleaves gasdermin D (GSDMD) → N-terminal domain forms pores in plasma membrane
                 → IL-1β/IL-18 released through pores + pyroptosis (lytic death)
```

Key points: **K⁺ efflux is a universal trigger of NLRP3 activation** (Muñoz-Planillo 2013: bacterial toxins, particulates, and ATP converge on intracellular K⁺ reduction); **NEK7 is the essential adaptor between K⁺ efflux and NLRP3** (He 2016, *Nature*); an **ASC speck** is a morphological marker of inflammasome activation and can aggregate into a single micron-sized focus within a cell; and **gasdermin D pore formation** allows non-classical release of IL-1β and triggers pyroptosis. Cellular contents released by pyroptosis act as DAMPs, further activating inflammation—a positive-feedback loop. IL-1β is a “master amplifier” of the inflammatory network: it activates endothelium, recruits neutrophils, and induces hepatic acute-phase proteins (CRP is downstream). NLRP3 activity rises with age in multiple tissues and is directly related to the pathology of gout, atherosclerosis, Alzheimer’s disease, and type 2 diabetes. The CANTOS trial showed that targeting this axis with the anti-IL-1β antibody canakinumab can improve human cardiovascular and cancer outcomes (see Section IV). The NLRP3/IL-1β axis is currently one of the hottest targets in drug development for anti-inflammatory and anti-aging therapies.

### 2.3 Source 1: SASP and the Positive Feedback of Cellular Senescence

Senescent cells (the 7th hallmark of aging) continuously secrete IL-6, IL-8, TNF-α, IL-1α/β, PAI-1, MMPs, and chemokines through the senescence-associated secretory phenotype (SASP). Through paracrine signaling, SASP induces senescence in neighboring cells (the bystander effect); the growing number of senescent cells in turn increases SASP supply, creating a self-amplifying “inflammation–senescence” loop. SASP transcription is driven mainly by NF-κB and C/EBPβ and partly depends on cGAS–STING (cGAS is activated by chromatin fragments accumulated in the cytoplasm of senescent cells). Short-term SASP has physiological functions (wound healing and tumor suppression), but chronic accumulation turns it into a systemic inflammatory engine. Senolytics (see 04-drugs/03-senolytics.md) clear senescent cells, reducing inflammatory burden and delaying aging phenotypes; senomorphics (see 04-drugs/04-senomorphics.md) suppress SASP secretion without killing cells.

### 2.4 Source 2: mtDNA Leakage from Damaged Mitochondria Activates cGAS–STING

With age, mitophagy (the PINK1/Parkin pathway) declines → damaged mitochondria accumulate → oxidized mtDNA leaks into the cytoplasm through BAX/BAK pores, the mitochondrial permeability transition pore (mPTP), or outer-membrane rupture → detected by the cytosolic DNA sensor **cGAS** → catalysis of 2′3′-cGAMP → activation of **STING** on the endoplasmic reticulum → recruitment of TBK1 → phosphorylation and activation of IRF3 and NF-κB → transcription of type I interferons (IFN-α/β) and pro-inflammatory factors. Oxidized mtDNA can also directly act as signal 2 to activate NLRP3 (Shimada 2012). Animal studies show that STING signaling increases with age, while cGAS/STING deficiency reduces inflammation in old tissues and partly delays aging phenotypes (multiple mechanistic studies). TFAM depletion (loosening mtDNA packaging) alone can trigger this pathway. “Mitochondrial stress → innate immune activation” is a deep source of inflammation.

### 2.5 Source 3: Gut Dysbiosis and Metabolic Endotoxemia

Gut-microbial diversity declines with age: beneficial short-chain fatty acid (SCFA)-producing bacteria (especially butyrate producers) decrease, while potentially pathogenic bacteria (e.g., Proteobacteria) increase. Meanwhile, intestinal epithelial tight junctions deteriorate and permeability rises (“leaky gut”) → low-dose **LPS (lipopolysaccharide)**, a component of Gram-negative bacterial outer membranes, enters the blood continuously → TLR4–MyD88 activates monocytes/macrophages → IL-6 and TNF-α rise mildly but persistently. Cani et al. (2007) coined “metabolic endotoxemia” for this mechanism in obesity/high-fat-diet models; it also applies to the aging gut. Butyrate and other SCFAs normally exert anti-inflammatory effects through GPR43 signaling and histone-deacetylase (HDAC) inhibition, so dysbiosis also removes this “brake.” In addition, latent infections such as cytomegalovirus (CMV), carried and periodically reactivated throughout life, create chronic antigenic load and raise the inflammatory baseline alongside immunosenescence.

### 2.6 Source 4: Adipose-Tissue Inflammation and Macrophage-Polarization Imbalance

Adipose tissue is a significant source of systemic inflammation in older individuals, particularly those with abdominal obesity: adipocyte hypertrophy and hypoxia → release of the chemokine MCP-1 → recruitment of monocytes → macrophage infiltration and polarization toward the **pro-inflammatory M1 phenotype** (driven by NF-κB/STAT1; secretes TNF-α, IL-1β, IL-6, and iNOS). Macrophages form “crown-like structures” around necrotic adipocytes. TNF-α phosphorylates IRS-1 serine sites (Ser307), suppressing insulin signaling and causing insulin resistance (Hotamisligil 1993 first demonstrated the association of adipose-tissue TNF-α with obesity-related diabetes). The anti-inflammatory, tissue-repairing **M2 phenotype** (driven by STAT6/PPARγ; secretes IL-10, TGF-β, and arginase) declines with age. In addition, the ability of older macrophages to clear apoptotic cells (efferocytosis via MerTK/MFG-E8) falls; retained apoptotic cells undergo secondary necrosis and sustain inflammation. M1/M2 imbalance is the 10th hallmark added in the 2023 version (see 03-immunity/03-macrophage-polar.md). Inflammation burden is substantially greater in visceral than in subcutaneous fat.

### 2.7 Overview of the Inflammatory Network

```
  Sources              Amplifiers             Effects
┌──────────────┐    ┌──────────────────┐    ┌────────────────────┐
│ SASP/senescent│───▶│                  │───▶│ Atherosclerosis    │
│ cells         │───▶│ NF-κB hub        │───▶│ Insulin resistance/│
│ mtDNA/cGAS    │───▶│ (transcriptional │───▶│ fatty liver        │
│ Gut LPS       │───▶│ amplification)  │───▶│ Neurodegeneration  │
│ Adipose M1    │───▶│ NLRP3            │───▶│ (microglia)        │
│ macrophages   │───▶│ inflammasome     │───▶│ Sarcopenia/bone loss│
│ Latent viruses│───▶│ (IL-1β/pyroptosis)│───▶│ Tumor microenvironment│
└──────────────┘    └──────────────────┘    └────────────────────┘
      ↕ Positive feedback: inflammation induces senescence; senescence secretes
        inflammation; pyroptosis releases DAMPs
```

## III. Evidence Grading

| Finding | Evidence grade | Key references |
|---|---|---|
| Serum IL-6, TNF-α, and CRP rise with age (baseline IL-6 in healthy older adults is 2–4× that of young adults) | Established (consistent across multiple population cohorts) | Cohen 1997; Ferrucci 1999/2005 |
| Inflammatory markers predict disability, frailty, cardiovascular events, and all-cause mortality | Established (prospective cohorts; independent of traditional risk factors) | InCHIANTI; Whitehall II |
| NF-κB activity rises with age in tissues | Strong association (multiple animal tissues + human samples) | Helenius 1996, etc. |
| Clearance of p16⁺ senescent cells reduces inflammation and extends lifespan | Animal causality (transgenic clearance models) | Baker 2016, *Nature* |
| Anti-IL-1β (canakinumab) lowers cardiovascular events and cancer mortality | Human RCT (causal) | Ridker 2017, *NEJM* |
| Aspirin provides no disability-free survival benefit in healthy older adults | Human RCT (negative result) | ASPREE 2018/2019 |
| Low-dose colchicine reduces coronary events | Human RCT | LoDoCo2 2020 |
| mtDNA–cGAS–STING drives inflammaging | Animal causality + in vitro mechanism | Shimada 2012; Dou 2017 |
| Gut microbiota → LPS → inflammation (aging) | Animal causality + human association | Cani 2007, etc. |
| Metformin lowers CRP and inhibits NF-κB | RCT/observational evidence (metabolic populations) + mechanism | Multiple studies |
| NLRP3 inhibitor (dapansutrile) | Mechanistically established + early clinical studies | Marchetti 2018, *PNAS* |

Evidence-grade definitions: “Established” = consistent across multiple cohorts/species with a clear mechanism; “strong association” = animal causality or consistent human associations; “mechanistic hypothesis” = supported by in vitro/mechanistic studies, with human evidence pending. Overall, **“inflammatory markers rise with age and predict adverse outcomes” is the highest-level human observational evidence, whereas “anti-inflammatory interventions improve aging outcomes” has RCT support only for specific targets (IL-1β, colchicine). Broad anti-inflammation (aspirin) is negative in healthy older adults**—the evidence itself points to heterogeneity within “inflammation.”

## IV. Clinical and Experimental Evidence in Detail

**(1) Inflammatory burden and aging outcomes (observational):** Baseline IL-6 is approximately 1–2 pg/mL in healthy young adults and 2–4 times higher in healthy older adults; median hsCRP rises from <1 mg/L to 2–3 mg/L. Cohen et al. (1997, community-dwelling older adults) found a significant association between elevated plasma IL-6 and functional disability. The InCHIANTI cohort (Ferrucci et al., older adults in Tuscany) showed that elevated IL-6 and CRP independently predict mobility limitation and mortality; each standard-deviation increase in IL-6 was associated with roughly a 60–70% higher risk of mobility limitation. Whitehall II and other cohorts confirmed independent associations of CRP/IL-6 with all-cause and cardiovascular mortality. The association between inflammation and epigenetic clocks is also clear: the PhenoAge epigenetic clock (Levine 2018) directly incorporates CRP, albumin, glucose, and other inflammatory/nutritional markers in its DNA-methylation age model—inflammation is “written into” biological age, and people with high IL-6/CRP show epigenetic age acceleration.

**(2) CANTOS: First causal evidence in humans** (Ridker 2017, *NEJM*): Among 10,061 patients with previous MI and hsCRP≥2 mg/L, canakinumab (anti-IL-1β monoclonal antibody, 150 mg every three months) was given for a median 3.7 years. MACE: HR 0.85 (95% CI 0.74–0.98), independent of lipid lowering; people whose hsCRP fell to <2 mg/L benefited most. Secondary analyses showed reductions in lung-cancer incidence and mortality (HR 0.61/0.33, respectively). This was the first demonstration in humans that “anti-inflammatory treatment alone (without lipid lowering)” could reduce cardiovascular and cancer endpoints, directly supporting a causal role of inflammation in age-related disease.

**(3) ASPREE: A cautionary example of broad anti-inflammation** (McNeil 2018, *NEJM* / 2019, *JAMA*): Among 19,114 healthy adults aged ≥70, aspirin 100 mg/day for a median of 4.7 years provided no disability-free survival benefit and significantly increased major bleeding risk (HR≈1.38); all-cause mortality actually rose (HR 1.14, driven mainly by cancer-related deaths). The core message of ASPREE is that low-grade inflammation in healthy older adults should not be suppressed “as early and as much as possible.” The net benefit of long-term, broad, non-targeted anti-inflammatory treatment was negative. Anti-inflammatory treatment should target specific pathways (IL-1β, NLRP3) and selected populations (those with high inflammatory burden).

**(4) Colchicine and metformin:** LoDoCo2 (2020, *NEJM*) included 5,522 people with chronic coronary disease; colchicine 0.5 mg/day produced a cardiovascular-event HR of 0.69, suggesting that low-dose inhibition upstream of NLRP3 (related to microtubules/ASC assembly) is effective in secondary prevention. Metformin activates AMPK and inhibits NF-κB and NLRP3; RCTs in people with type 2 diabetes show significant CRP reduction. The TAME trial (led by Barzilai) is testing metformin for anti-aging purposes (see 04-drugs/07-metformin-ampk.md).

**(5) Human senolytic trials:** Dasatinib plus quercetin (D+Q) in patients with diabetic kidney disease (Hickson 2019, *EBioMedicine*) and idiopathic pulmonary fibrosis (Justice 2019) reduced circulating SASP factors (IL-6, MMPs, etc.) after a single treatment course and reduced senescent cells in adipose tissue. This was the first demonstration in humans of the feasibility of cutting off SASP supply at its source.

**(6) Effect sizes of lifestyle interventions:** Regular aerobic plus resistance exercise produces moderate reductions in resting CRP/IL-6 (multiple meta-analyses; CRP falls by approximately 15–30%). Mechanisms include the anti-inflammatory effect of muscle-derived IL-6 through IL-10 (IL-10 rises after exercise) and eNOS activation by shear stress. Daily 1–3 g EPA+DHA (omega-3) moderately lowers CRP. The Mediterranean diet in PREDIMED reduced cardiovascular events and also improved inflammatory markers.

**(7) Centenarians as a “natural control” for inflammation:** Healthy centenarians often show lower inflammation than ordinary older adults, providing an observational “reverse validation.” Studies of Italian centenarians (Franceschi group) found smaller increases in IL-6 and CRP than in unhealthy peers of similar age, and a cytokine-genotype combination biased toward inflammatory control (e.g., IL-6 −174GC and high-expression IL-10 variants), suggesting that genetically determined inflammatory regulation is associated with extreme longevity. Mechanistic research shows that IL-6 signals through two routes: membrane-bound receptor classic signaling (anti-inflammatory/regenerative) and soluble-receptor sIL-6R trans-signaling (pro-inflammatory). The former relatively weakens with age while the latter strengthens; thus, elevated serum IL-6 in aging acts more through trans-signaling. This explains why “total IL-6 level” is only a crude proxy for inflammatory state. Soluble gp130 (sgp130) can neutralize trans-signaling and is under investigation as an intervention.

## V. Connections to NO / NAD⁺ / Longevity Networks

**NO is a representative endogenous anti-inflammatory molecule, with a complete molecular chain of action:**

```
Low-concentration NO (from eNOS/nNOS)
  ├─► S-nitrosylates IKKβ (Cys179) → inhibits IKK kinase activity → blocks NF-κB activation (Reynaert 2004, PNAS)
  ├─► S-nitrosylates p65 (Cys38) → reduces its DNA-binding ability
  ├─► Activates SIRT1 → deacetylates p65 (K310) → suppresses NF-κB transcription (Yeung 2004, EMBO J)
  └─► Downregulates ICAM-1/VCAM-1 → inhibits leukocyte–endothelial adhesion/infiltration (De Caterina 1995)
        └─► Net effect: SASP secretion↓, M2 macrophage maintenance, vascular anti-inflammation
```

**NO deficiency and inflammation form a vicious cycle of bidirectional causation:** Chronic inflammation → oxidative stress → BH4 oxidation (BH4→BH2) → eNOS uncoupling → less NO and more superoxide → failure of the anti-inflammatory brake → further inflammatory amplification. At the same time, NF-κB transcription induces **iNOS** (whose promoter contains multiple inflammation-responsive elements) → macrophages continuously produce high concentrations of NO (µM range) → NO reacts with superoxide at a near 1:1 ratio to form peroxynitrite (ONOO⁻; diffusion-controlled rate ~10⁹–10¹⁰ M⁻¹s⁻¹) → deposition of nitrated tyrosine (3-NT), inhibition of mitochondrial complexes, and renewed NF-κB activation. **NO shifts from anti-inflammatory to pro-inflammatory depending on concentration and timing** (see 01-foundations/03-no-basics.md). eNOS-knockout mice have higher inflammatory burden and faster endothelial aging; in humans, endothelial dysfunction (lower FMD) occurs alongside elevated CRP/IL-6. Both support the idea that reduced NO bioavailability is an upstream condition for inflammatory amplification.

**The NAD⁺ axis welds inflammation to longevity networks:** NAD⁺ declines with age → SIRT1 activity↓ → p65 K310 acetylation↑ → NF-κB transcription↑ → inflammation↑. SIRT6 also suppresses transcription at NF-κB target-gene promoters by deacetylating H3K9. Conversely, NLRP3 activation and DNA-damage responses consume NAD⁺ (PARP1 consumes one NAD⁺ for each repaired break)—inflammation itself accelerates NAD⁺ depletion. In animal experiments, NMN/NR supplementation lowers inflammatory markers in aged tissues and improves metabolism. This creates a **four-way interlocked loop: “inflammation ↔ cellular senescence ↔ NAD⁺/SIRT ↔ NO.”** Increasing NO (exercise, dietary nitrate) and supplementing NAD⁺ precursors (NMN/NR) can be regarded as upstream anti-inflammatory strategies, while clearing senescent cells is a “source-cutting” strategy. Both routes act on the same network (see 01-foundations/03-no-basics.md and 04-drugs/05-molecular-mech.md).

## VI. Intervention Directions and Actionable Recommendations

**Tier 1: Lifestyle (strongest evidence, minimal adverse effects; first choice)**
- Regular aerobic and resistance exercise (≥150 minutes/week of moderate-intensity activity): lowers CRP/IL-6, promotes M2 polarization, activates eNOS through shear stress, and improves NO and NAD⁺;
- Mediterranean-style anti-inflammatory diet: plenty of vegetables and fruit, olive oil, oily fish (1–3 g omega-3 daily), and whole grains; limit refined sugar and processed foods high in AGEs (AGEs activate NF-κB through RAGE);
- Calorie restriction/intermittent fasting: AMPK↑, mTOR↓, autophagy↑ → clears damaged mitochondria and senescent cells and inhibits NLRP3;
- Sleep, stress management, and oral health: excessive HPA-axis activation and periodontitis (chronic bacterial antigen load) are both modifiable sources of inflammation.

**Tier 2: Pharmacological (requires clinician assessment; target population = high inflammatory burden)**
- Low-dose colchicine 0.5 mg/day: secondary prevention in coronary disease (LoDoCo2 evidence);
- Metformin: metabolic anti-inflammatory effects (AMPK/NF-κB axis); TAME is underway;
- Statins: in addition to lipid lowering, directly reduce hsCRP (JUPITER enrolled participants based on hsCRP).

**Tier 3: Emerging targeted approaches (clinical-trial stage)**
- NLRP3 inhibitors: dapansutrile (OLT1177) has entered Phase II for gout, acute MI, and osteoarthritis. Natural NLRP3 inhibitors such as isoliquiritigenin have inhibited ASC assembly and IL-1β maturation in macrophage and mouse inflammation models (mechanistic evidence; human evidence is pending);
- Anti-IL-1β (canakinumab): CANTOS established proof of concept, but increased infection risk and cost limit wider use;
- Senolytics (D+Q, fisetin) and senomorphics (rapamycin, metformin): reduce SASP at its source (see 04-drugs/03-senolytics.md and 04-drugs/04-senomorphics.md);
- Gut-microbiota interventions: prebiotics, butyrate supplementation, and fecal microbiota transplantation from healthy donors (effective in animals; human evidence pending).

**Explicitly not recommended:** Routine aspirin or long-term NSAID use in healthy older adults—ASPREE was negative and bleeding/GI/renal toxicity is clear; there is no evidence of lifespan extension.

**Additional traditional Chinese medicine perspective:** The “benefit qi and activate blood” approach used throughout this collection overlaps with anti-inflammatory biology at the molecular level. Mechanistic studies suggest that ingredients such as astragalus polysaccharides and tanshinones can downregulate NF-κB and NLRP3, inhibit IL-6/TNF-α secretion, and increase eNOS/NO bioavailability. The clinical pattern of “qi deficiency and blood stasis” (fatigue, dark tongue, choppy pulse) substantially overlaps with chronic low-grade inflammation (high CRP/IL-6, microcirculatory dysfunction), suggesting that these formulas may partly exert anti-inflammatory effects through the “restore NO → inhibit NF-κB” axis (see 06-tcm/01-yiqi-huoxue.md and 06-tcm/02-herbs.md). Most such evidence comes from mechanistic studies and small-to-moderate clinical observations and requires validation in more rigorous RCTs.

**Monitoring suggestions:** Measure hsCRP annually (<1 mg/L is ideal, 1–3 moderate, >3 high risk) and fibrinogen. Where available, combine with a PhenoAge epigenetic clock to assess “inflammatory age.” IL-6 has substantial diurnal variation and is mainly a research-level marker.

## VII. Open Questions and Controversies

1. **Causality is not fully closed:** Is increased inflammation a cause, accompaniment, or consequence of aging? CANTOS (benefit from anti-IL-1β) supports causality, while ASPREE (no benefit from broad anti-inflammatory treatment) argues against oversimplification. Their coexistence indicates substantial heterogeneity within “inflammation”: which type, at what stage, and with what intervention determines success.
2. **Balancing inflammation control with immune surveillance:** Systemic suppression may weaken antitumor immunity and anti-infective defenses (more fatal infections with canakinumab, more bleeding and cancer deaths in the aspirin group). Where is the “anti-inflammatory therapeutic window”? Low-grade inflammation still has physiological roles in tissue repair and tumor surveillance.
3. **NF-κB hub vs NLRP3 amplifier vs source clearance:** Which level is the best target? Long-term safety of NF-κB inhibition is questionable because of immunosuppression; NLRP3/IL-1β targeting is more specific but narrower; senolytics cut off the source, but long-term consequences of senescent-cell clearance are unknown.
4. **Clonal hematopoiesis (CHIP) as a confounder:** Age-related TET2/DNMT3A mutations cause clonal hematopoiesis, which raises inflammation (IL-1β) and independently increases cardiovascular risk. Does inflammation drive clonal expansion, or does clonal expansion drive inflammation? A post hoc CANTOS analysis found greater benefit from canakinumab in CHIP carriers, suggesting a bidirectional inflammation–hematopoiesis relationship.
5. **Individual heterogeneity and timing:** Inflammatory trajectories differ substantially by genetics, sex, obesity, and microbiome. Direct comparative evidence is lacking on when to begin anti-inflammatory treatment (midlife prevention versus treatment in older age).

## References

1. Franceschi C, Bonafè M, Valensin S, et al. Inflamm-aging. An evolutionary perspective on immunosenescence. *Ann N Y Acad Sci*. 2000;908:244–254.
2. Franceschi C, Campisi J. Chronic inflammation (inflammaging) and its potential contribution to age-associated diseases. *J Gerontol A Biol Sci Med Sci*. 2014;69 Suppl 1:S4–S9.
3. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. *Cell*. 2023;186(2):243–278.
4. Ferrucci L, et al. Serum IL-6 level and the development of disability in older persons. *J Am Geriatr Soc*. 1999;47(6):639–646. / Ferrucci L, et al. Inflammatory markers and the risk of mobility limitation in the elderly (InCHIANTI). *J Gerontol A Biol Sci Med Sci*. 2005;60(6):729–735.
5. Cohen HJ, et al. The association of plasma IL-6 levels with functional disability in community-dwelling elderly. *J Gerontol A Biol Sci Med Sci*. 1997;52(4):M201–M208.
6. Ridker PM, et al. Antiinflammatory therapy with canakinumab for atherosclerotic disease. *N Engl J Med*. 2017;377(12):1119–1131.
7. McNeil JJ, et al. Effect of aspirin on disability-free survival in the healthy elderly (ASPREE). *N Engl J Med*. 2018;379(16):1519–1528. / McNeil JJ, et al. Effect of aspirin on all-cause mortality in the healthy elderly. *JAMA*. 2019;321(4):385–394.
8. Nidorf SM, et al. Colchicine in patients with chronic coronary disease (LoDoCo2). *N Engl J Med*. 2020;383(19):1838–1847.
9. Baker DJ, et al. Naturally occurring p16(Ink4a)-positive cells shorten healthy lifespan. *Nature*. 2016;530(7589):184–189.
10. Hickson LJ, et al. Senolytics decrease senescent cells in humans: Preliminary report from a clinical trial of dasatinib plus quercetin in individuals with diabetic kidney disease. *EBioMedicine*. 2019;47:446–456.
11. Muñoz-Planillo R, et al. K⁺ efflux is the common trigger of NLRP3 inflammasome activation by bacterial toxins and particulate matter. *J Immunol*. 2013;190(7):3528–3536.
12. He Y, et al. NEK7 is an essential mediator of NLRP3 activation downstream of potassium efflux. *Nature*. 2016;530(7590):354–357.
13. Shi J, et al. Cleavage of GSDMD by inflammatory caspases determines pyroptotic cell death. *Nature*. 2015;526(7575):660–665.
14. Shimada K, et al. Oxidized mitochondrial DNA activates the NLRP3 inflammasome during apoptosis. *Immunity*. 2012;36(3):401–414.
15. Dou Z, et al. Cytoplasmic chromatin triggers inflammation in senescence and cancer. *Nature*. 2017;550(7676):402–406.
16. Cani PD, et al. Metabolic endotoxemia initiates obesity and insulin resistance. *Diabetes*. 2007;56(7):1761–1772.
17. Hotamisligil GS, Shargill NS, Spiegelman BM. Adipose expression of tumor necrosis factor-α: Direct role in obesity-linked insulin resistance. *Science*. 1993;259(5091):87–91.
18. Reynaert NL, et al. Nitric oxide represses inhibitory κB kinase through S-nitrosylation. *Proc Natl Acad Sci USA*. 2004;101(24):8945–8950.
19. Yeung F, et al. Modulation of NF-κB-dependent transcription and cell survival by the SIRT1 deacetylase. *EMBO J*. 2004;23(12):2369–2380.
20. Levine ME, et al. An epigenetic biomarker of aging for lifespan and healthspan. *Aging (Albany NY)*. 2018;10(4):573–591.
