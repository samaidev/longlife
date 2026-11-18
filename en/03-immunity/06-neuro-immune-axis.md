# The Neuro-Immune Axis

## Core concept

The neuro-immune axis is the persistent, bidirectional communication network between the nervous and immune systems. The brain sends regulatory signals to the immune system through autonomic nerves and neuroendocrine pathways (“top-down”), while immune cells report their status back to the brain through cytokines and neuroactive metabolites (“bottom-up”). Physiologically, the immune system is integrated into the homeostatic “braking” framework of the autonomic and endocrine systems: during inflammation the vagus nerve acts as a reflexive brake against excessive inflammation; during stress the HPA axis releases glucocorticoids to restrain immune activation; and the sympathetic nervous system finely regulates immune-cell mobilization and polarization through catecholamines. In health, this axis maintains precise inflammatory thresholds. With age or chronic stress, neuroimmune regulation becomes unbalanced—vagal tone falls, the HPA axis becomes blunted, and sympathetic activity becomes excessive—so the inflammatory “brakes” fail and pro-inflammatory states are amplified. The neuro-immune axis is the neural interface through which “chronic stress promotes inflammation → accelerates aging,” and a regulatory hub for two of the 12 hallmarks of aging: chronic inflammation and altered intercellular communication (see 01-foundations/01-aging-hallmarks.md). Its anti-aging relevance is that vagal tone, cortisol rhythms, and sympathetic activity are all intervention targets for behavior (exercise, meditation, breathing) and medicine/devices (vagus-nerve stimulation, α7nAChR agonists), making it a direct bridge between brain–body biology and practical anti-aging.

## The complete molecular mechanism

### 1. The inflammatory reflex and cholinergic anti-inflammatory pathway (CAP)

The central discovery in neuroimmune biology was the “inflammatory reflex,” proposed by Tracey’s laboratory in 2000: peripheral inflammatory signals ascend through vagal afferents to the nucleus tractus solitarius (NTS) in the brainstem; after central integration, vagal efferents descend to suppress peripheral inflammation. In 2002, Borovikova et al. (Tracey’s team) published the landmark *Nature* study establishing the **cholinergic anti-inflammatory pathway (CAP)**:

```
Peripheral inflammation (IL-1β/TNF-α) ──▶ vagal afferents → NTS → dorsal motor nucleus of the vagus
                                                     │ descending vagal efferents
                                                     ▼
                                      spleen/celiac sympathetic ganglia (catecholamines)
                                                     │
                                                     ▼
                                      splenic CD4⁺ T cells release acetylcholine (ACh)
                                                     │
                                                     ▼
                                      macrophage α7nAChR (α7 nicotinic receptor)
                                                     │
                         ┌───────────────────────────┤
                         ▼                           ▼
                 JAK2/STAT3 activation       NF-κB inhibition (SIRT1/deacetylation)
                         │                           │
                         ▼                           ▼
          (still debated; some studies suggest      TNF-α/IL-1β/IL-6 release↓
          a weak association of α7 signaling         relative IL-10↑
          with JAK2–STAT3)
```

Key molecular nodes:
- **α7nAChR** (α7 nicotinic acetylcholine receptor) is the principal effector receptor of CAP and is expressed mainly on macrophages, microglia, and dendritic cells. The anti-inflammatory effect of vagal stimulation disappears completely in α7nAChR-knockout mice (Wang 2003), strong evidence for CAP.
- **Splenic T cells are the intermediary:** Vagal stimulation does not act directly on macrophages. Instead, the splenic nerve releases norepinephrine (NE), which activates β2-adrenergic-receptor-expressing CD4⁺ T cells in the spleen. These cells release acetylcholine (ACh), which then acts locally on α7nAChR on neighboring macrophages (Rosas-Ballina 2011). This explains why cutting the splenic nerve or removing T cells abolishes vagal anti-inflammatory effects.
- **Downstream signaling:** α7nAChR is a ligand-gated ion channel. Its anti-inflammatory mechanism involves JAK2/STAT3 activation and NF-κB inhibition. Recent work (de Jonge 2005) emphasizes α7nAChR-mediated JAK2→STAT3 phosphorylation and inhibition of NF-κB p65 nuclear translocation; other evidence suggests a role for SIRT1-mediated deacetylation, although this detail is not fully settled.

CAP’s significance is that it places the immune system within a reflex-arc framework: inflammation is not merely local, but a systemic process continuously monitored and regulated by the central nervous system. This is the most important conceptual breakthrough in neuroimmune biology.

### 2. The HPA axis and glucocorticoids

The hypothalamic–pituitary–adrenal (HPA) axis is the main neuroendocrine pathway for stress:

```
Stress (physical/psychological) ──▶ hypothalamic paraventricular nucleus (PVN) releases CRH
                                             │
                                             ▼
                                    anterior pituitary releases ACTH
                                             │
                                             ▼
                                    adrenal cortex releases cortisol
                                             │
                                             ▼
                                    glucocorticoid receptors (GRs) widely expressed
                                    inhibit NF-κB/AP-1 transcriptional activity
                                    → TNF-α/IL-6/IL-1β down, anti-inflammatory
```

- **GR anti-inflammatory mechanisms:** Cortisol binds intracellular glucocorticoid receptors (GRs), which translocate to the nucleus and suppress inflammation in two ways: (1) they compete with NF-κB/AP-1 for coactivators such as CBP/p300, producing “transcriptional antagonism”; (2) they directly induce anti-inflammatory factors (IL-10 and IκBα, the NF-κB inhibitory protein). GRs also rapidly suppress inflammation through membrane-associated, non-genomic signaling.
- **Circadian rhythm:** Cortisol has a characteristic diurnal rhythm, peaking in the morning (the cortisol awakening response, CAR, about 30 minutes after waking) and reaching a low point at night. The suprachiasmatic nucleus (SCN) drives the rhythm. Immune cells, especially macrophages, express GRs and clock genes. Cortisol rhythms make immune responses time-dependent: pro-inflammatory capacity is stronger in the morning (mobilization), while anti-inflammatory activity predominates at night (repair). **Cortisol rhythms flatten with age** (lower peaks, higher troughs, and a weaker CAR). In older age, the HPA response to acute stress is blunted (less hypothalamic CRH release and altered peripheral feedback sensitivity), producing a mismatch of relatively high baseline cortisol with inadequate stress responses. Chronically high cortisol suppresses immune surveillance (thymic atrophy and lymphopenia), while an insufficient acute response undermines the anti-inflammatory “sprint.”
- **The double edge of chronic stress:** An acute cortisol rise is a protective anti-inflammatory response. But **chronic high cortisol** accelerates thymocyte apoptosis through GRs, reduces naïve T-cell output, and decreases NK cytotoxicity and phagocytic function. It also promotes visceral fat accumulation, whose tissue releases inflammatory mediators, forming a vicious cycle: “stress → high cortisol → immunosuppression + abdominal obesity → inflammation.”

### 3. The sympathetic nervous system and catecholamines

The sympathetic nervous system (SNS) richly innervates the spleen, lymph nodes, bone marrow, and thymus; sympathetic fibers in secondary lymphoid organs directly contact T and B cells. Its effector molecules, peripheral norepinephrine (NE) and adrenal-medulla epinephrine (E), regulate immunity through α- and β-adrenergic receptors:

```
NE/E ──┬── β2-adrenergic receptor (β2-AR, highly expressed on immune cells)
        │       Acute: NK-cell mobilization into blood, macrophage phagocytosis↑ (mobilization/pro-inflammatory)
        │       Chronic excess: Th1/cell-mediated immunity suppressed, Th2 shift, Treg changes
        │
        └── α-adrenergic receptors (α1/α2-AR)
                vasoconstriction, altered local perfusion
                α2 participates in anti-inflammatory regulation under certain conditions
```

- **Biphasic effects: acute versus chronic:** Sympathetic catecholamines have a “bell-shaped” dose response. Acute stress (brief NE release) mobilizes NK cells into the blood and increases cytotoxicity—an evolutionary immune-preparation response for “fight or flight.” In contrast, **chronic sympathetic overactivity** (persistently high NE), through downstream β2-AR/cAMP/PKA signaling, suppresses Th1-mediated cellular immunity, promotes a Th2 shift and Treg expansion, and weakens clearance of intracellular pathogens and tumors.
- **Changes with age:** Sympathetic activity rises systemically in older age (higher baseline NE, reduced baroreflex sensitivity), while β2-AR sensitivity declines. This creates an imbalance of “sympathetic overactivity + β-receptor desensitization”: inadequate mobilization in response to acute stimuli but persistent immune suppression under chronic stimulation.
- **Vagal–sympathetic antagonism:** Under normal conditions, parasympathetic vagal and sympathetic activity tonically oppose one another to maintain autonomic balance. With age, vagal tone falls and sympathetic activity becomes relatively dominant, tilting the autonomic balance toward the “pro-inflammatory–sympathetic” side. Heart-rate variability (HRV), a measurable indicator of autonomic balance, declines accordingly.

### 4. Regulation of immunity by neuropeptides

Beyond classical neurotransmitters, sensory nerve endings communicate extensively with immune cells through neuropeptides:

| Neuropeptide | Source | Immune regulation | Age/disease association |
|---|---|---|---|
| Substance P (SP) | Sensory nerves (TRPV1⁺ C fibers) | Pro-inflammatory: enhances mast-cell degranulation, macrophage activation, and vascular permeability | Elevated in chronic inflammation, asthma, and arthritis |
| Calcitonin gene-related peptide (CGRP) | Sensory nerves | Biphasic: acutely anti-inflammatory (inhibits NF-κB), may be pro-inflammatory chronically; regulates DCs | Migraine; complex immune effects |
| Vasoactive intestinal peptide (VIP) | Parasympathetic/enteric nerves | Anti-inflammatory: suppresses macrophage activation, promotes Th2/Treg, inhibits Th1/Th17 | VIP signaling falls in neuroimmune dysregulation |
| Neuropeptide Y (NPY) | Co-released by sympathetic nerves | Immunomodulatory: acts with NE, regulates NK cells and monocytes | Stress-related immunosuppression |
| Bradykinin/nerve growth factor (NGF) | Inflamed tissue/sensory nerves | Pro-inflammatory; increases sensory-nerve sensitization (neurogenic inflammation) | Chronic pain–inflammation coupling |

**Neurogenic inflammation:** When sensory nerve endings, especially TRPV1⁺ C fibers, are stimulated, they release SP and CGRP antidromically. These directly cause vasodilation, plasma extravasation, and mast-cell activation. This “nerve → inflammation” pathway does not depend on a classical reflex arc; it is mediated locally by axon reflexes and plays important roles in migraine, arthritis, and irritable bowel syndrome.

### 5. Microglia and innate immunity in the CNS

The central nervous system (CNS) was once considered “immune privileged,” but microglia—its resident macrophage-like cells—are central on the brain side of the neuro-immune axis:

```
Normal: microglia in “sentinel” state (branched) — surveillance, synaptic pruning, clearance
Aging/stress: “activated” states
     ┌── Classical (M1-like): pro-inflammatory cytokines↑ (TNF-α/IL-1β/IL-6), iNOS/NO↑
     └── Alternative (M2-like): repair, IL-10, clearance
     ┌── Homeostatic imbalance: phagocytosis/clearance↓, abnormal synaptic pruning → neuroinflammation
```

- **Microglial senescence:** With age, microglia shift toward a “pro-inflammatory but inefficient” phenotype: fewer remain in a resting state, they overreact to normal signals, their ability to clear Aβ and myelin debris declines, and they secrete SASP-like inflammatory factors. These changes interact with Alzheimer’s disease (AD) pathology (Aβ deposition and tau tangles). The TREM2 receptor is a key molecule for microglial Aβ clearance, and its signaling is impaired with age.
- **Neuroinflammation is a common substrate for neurodegenerative disease:** Chronic neuroinflammation occurs in AD, Parkinson’s disease (PD), and amyotrophic lateral sclerosis (ALS), with microglial activation as a central mediator. In older age, blood–brain barrier (BBB) permeability rises (tight-junction protein claudin-5 falls), allowing peripheral inflammatory cytokines to enter the brain more readily and drive neuroinflammation—the “periphery → brain” bottom-up route.
- **α7nAChR on microglia:** Microglia express α7nAChR, and cholinergic signals (from central cholinergic neurons and indirect influences of the vagus–brain pathway) suppress their pro-inflammatory activation. A “CAP within the brain” provides a molecular explanation for the coupling between age-related/AD cholinergic-system degeneration and neuroinflammation.

### 6. Meningeal immunity and the glymphatic system

Recent discoveries have reshaped our understanding of “immune privilege” in the brain:

- **Meningeal lymphatic vessels:** In 2015, Louveau et al. (*Nature*) found functional lymphatic vessels in the dura mater that drain brain macromolecules and immune cells to deep cervical lymph nodes. The CNS thus has a lymphatic “exit to the immune system,” an anatomical bridge for the neuro-immune axis.
- **The glymphatic system:** Described by Iliff et al. in 2012 (*Sci Transl Med*), this cerebrospinal-fluid (CSF) “glial lymphatic” clearance pathway involves periarterial CSF influx, interstitial convection driven by astrocytic AQP4 water channels, and perivenous clearance. It is most efficient during sleep, especially slow-wave sleep (about 60% more efficient than during wakefulness), and clears metabolic waste such as Aβ and tau.
- **Age-related decline:** Glymphatic clearance falls by roughly 40–60% with age (associated with impaired AQP4 polarization and weaker arterial pulsatility), and poor sleep worsens the decline—linking “sleep–clearance–neuroinflammation.” Meningeal lymphatic function also deteriorates with age, potentially weakening antigen presentation from the CNS to the immune system and immune surveillance.
- **Meningeal T cells:** The leptomeninges contain T cells, macrophages, and B cells. In neuroinflammation and autoimmunity (e.g., multiple sclerosis), the meninges are both a “battlefield” and a “traffic hub.” Age-related meningeal immune imbalance may worsen neuroinflammation and cognitive decline.

### 7. The gut–brain–immune axis

The gut is the largest interface of the neuro-immune axis. It contains about 100 million neurons (the enteric nervous system, ENS), millions of immune cells (gut-associated lymphoid tissue, GALT), and trillions of microbes. These are tightly coupled through the vagus nerve, circulation, and metabolites:

```
Gut microbiota/metabolites (SCFAs: butyrate/propionate)
     │
     ├── Vagal afferents (“direct gut–brain line”)
     │      Enteroendocrine-cell (L-cell) hormones + microbial signals → vagus → NTS → brain
     ├── Short-chain fatty acids (SCFAs) enter blood
     │      → bind GPR43/41 → regulate Tregs/macrophages → anti-inflammatory
     │      → affect neuroinflammation across BBB (butyrate inhibits microglial activation)
     └── Neurotransmitter precursors/hormones
            Gut microbes produce serotonin precursors, GABA, dopamine metabolites → affect brain
```

- **Gut microbes regulate microglia:** Germ-free mice have impaired microglial development and function (Erny 2015, *Nat Neurosci*); SCFA supplementation partly restores them—direct evidence for a “microbiota–brain immunity” pathway.
- **The vagus is the main gut–brain pathway:** More than 80% of vagal fibers are afferent, transmitting satiety, inflammatory, and microbial signals from the gut. Vagotomy removes some effects of gut microbiota on brain behavior in animal studies.
- **Age-related changes:** Gut microbial diversity declines in older adults, beneficial microbes (bifidobacteria and butyrate producers) decrease, and pro-inflammatory microbes increase. The proposed cascade “dysbiosis → leaky gut → circulating lipopolysaccharide (LPS) → systemic inflammation → neuroinflammation” is a microbiome–immunity–neural hypothesis of aging (moderate evidence; still debated).

### 8. Overall age-related imbalance of the neuro-immune axis

```
Aging/chronic stress
   │
   ├── Vagal tone↓ (HRV↓, weaker resting parasympathetic activity) ──▶ failed inflammatory-reflex brake → inflammation amplified
   ├── Blunted HPA axis (flattened cortisol rhythm) ──▶ failed anti-inflammatory response + chronic immunosuppression
   ├── Sympathetic overactivity (baseline NE↑) ──▶ chronic Th1/cellular immune suppression and immune aging
   ├── Glymphatic/meningeal lymphatics↓ ──▶ neuroinflammatory waste accumulation → cognitive decline
   ├── Pro-inflammatory microglia ──▶ amplified neuroinflammation, higher neurodegeneration risk
   ├── Dysbiosis/leaky gut ──▶ systemic inflammation (LPS/SCFA imbalance) → feedback to CNS
   └── Altered neurotransmitter-receptor expression in immune cells ──▶ blunted response to neural signals
        ──▶ neuroimmune dysregulation ⇄ positive-feedback loop with inflammaging
```

This synchronized, multi-node imbalance means that aging of the neuro-immune axis is not the failure of one pathway but systemic breakdown across the autonomic, endocrine, and immune systems. Restoring neuroimmune balance therefore requires coordinated action on multiple targets.

## Evidence grading

| Phenomenon | Evidence level | Key evidence/literature |
|---|---|---|
| Vagal stimulation suppresses peripheral inflammation (CAP exists) | Established (multiple animal models) | Borovikova 2002 (*Nature*); anti-inflammatory vagal stimulation in sepsis, arthritis, and IBD models |
| α7nAChR is the key CAP receptor | Established (gene knockout) | Wang 2003: vagal anti-inflammatory effect absent in α7nAChR-KO mice |
| Splenic T cells are CAP intermediaries | Established in animals | Rosas-Ballina 2011: splenic CD4⁺ T cells release ACh to mediate vagal anti-inflammation |
| Chronic stress raises inflammatory markers in humans | Strong association (prospective cohorts) | CRP/IL-6 and chronic psychological stress (Kiecolt-Glaser 2010 review); elevated cortisol/inflammation in caregivers |
| Cortisol diurnal rhythm flattens with age | Strong association (human cohorts) | Weaker CAR and reduced rhythm amplitude in older adults (multiple cross-sectional/longitudinal studies) |
| Chronic sympathetic overactivity and immunosuppression | Strong association (human + animal) | NK activity↓ and vaccine response↓ under chronic stress (Glaser/Kiecolt-Glaser) |
| Glymphatic function declines with age | Strong association (human MRI + animals) | Clearance is more efficient during sleep; clearance↓ in older age (Iliff 2012; Xie 2013) |
| Gut microbiota regulate neuroinflammation/microglia | Strong association to established in animals | Impaired microglia in germ-free mice (Erny 2015); restoration with SCFAs |
| Meditation/mindfulness improves inflammatory outcomes | Moderate (small RCTs) | NF-κB gene downregulation in transcriptomic studies (Black 2013); small CRP/IL-6 effects |
| Vagus-nerve stimulation (VNS) is anti-inflammatory | Moderate (small human trials) | Phase I RA/Crohn’s disease studies show lower TNF and disease activity (Koopman 2016) |
| α7nAChR agonists are anti-inflammatory | Established in animals; human efficacy uncertain | GTS-21 had good safety but unclear efficacy endpoints |
| Exercise increases vagal tone and lowers inflammation | Strong association (cohorts + small RCTs) | Regular exercise increases HRV, lowers CRP/IL-6 (multiple studies) |
| Anti-inflammatory diet/omega-3 | Strong association (partly RCT-supported) | Mediterranean diet lowers CRP; EPA/DHA lower inflammatory markers |
| HRV (vagal tone) predicts all-cause mortality in older adults | Strong association (large cohorts) | Low HRV associated with higher cardiovascular/all-cause mortality (multiple meta-analyses) |

## Details of clinical and experimental evidence

**Anti-inflammatory vagus-nerve stimulation (VNS)—from concept to humans:** Koopman 2016 (*Arthritis Rheumatol*, open-label phase I trial) implanted cervical VNS devices in 17 patients with treatment-resistant rheumatoid arthritis (RA), stimulating 1–4 times daily. After 12 weeks, 6 patients (35%) achieved at least moderate EULAR response, and serum TNF-α and IL-6 fell significantly. Small inflammatory-bowel-disease (Crohn’s disease) trials show similar trends. Mechanistic studies confirm cholinergic innervation of the human spleen and α7nAChR expression on splenic macrophages (Rosas-Ballina reproduced the splenic pathway in humans). VNS is approved for treatment-resistant epilepsy and depression; anti-inflammatory indications (RA, IBD, sepsis) remain clinical research. Human evidence for splenic VNS-mediated anti-inflammation is weaker than animal evidence: splenectomy/splenic-nerve-blockade evidence is limited to animals, and human “spleen dependence” has not been directly demonstrated (see Open questions).

**Meditation/mindfulness and inflammation:** In Black 2013 (*Psychoneuroendocrinology*, RCT n=40), older female caregivers were randomized to eight weeks of mindfulness-based stress reduction (MBSR). Compared with controls, the intervention group showed lower expression of peripheral-blood NF-κB-related inflammatory genes (including COX-2 and IL-6) and higher expression of stress-related signaling-pathway genes. A systematic review (Bower 2015) of multiple RCTs found that meditation has an overall small effect on inflammatory markers such as CRP/IL-6 (Cohen’s d about 0.2–0.4), with substantial heterogeneity. The direction of the “meditation is anti-inflammatory” effect is plausible, but the dose–response relationship is not established.

**HRV as a measurable window on neuroimmune balance:** HRV is a noninvasive indicator of parasympathetic (vagal) tone and sympathetic activity; indices such as SDNN/RMSSD decline substantially with age. Large prospective cohorts (e.g., ARIC and Framingham) and meta-analyses consistently associate low HRV with increased cardiovascular events and all-cause mortality (all-cause mortality HR≈1.3–1.8 for low RMSSD). Low HRV also co-occurs with elevated inflammatory markers (CRP, IL-6). HRV has been called an “outpatient probe of the neuro-immune axis”; its age-related decline can itself be regarded as quantitative evidence of declining vagal tone.

**Exercise as a vagal-tone enhancer:** Regular aerobic exercise (≥150 minutes/week of moderate-intensity activity) increases HRV (parasympathetic tone), lowers resting inflammatory markers (CRP by about 10–20%, IL-6 by about 10%), raises the proportion of naïve T cells, and reduces CD28⁻ senescent T cells (multiple exercise-immunology cohorts; see 04-immunosenescence.md). Its dual improvement of vagal tone and inflammation makes exercise the only mature intervention that acts both “top-down” on the neuro-immune axis and peripherally on immunosenescence.

**The HPA axis/cortisol and stress–immunity:** Human evidence for the immunological consequences of chronic stress is substantial. Caregivers (Kiecolt-Glaser 2003) have weaker antibody responses after influenza vaccination and poorer cellular immune measures. People under long-term caregiving stress show flattened cortisol rhythms, elevated inflammatory markers, and reduced NK activity. Cognitive behavioral therapy and social support have moderate evidence for reducing stress-related inflammation.

**Evidence for gut–brain interventions:** Clinical evidence that probiotics/prebiotics modulate neuroinflammation and mood is still early (some RCTs show mood improvement and lower inflammatory markers, with small effect sizes). Mediterranean diets (rich in SCFA-producing fiber and omega-3) have more robust evidence for reducing systemic inflammation (lower CRP); direct neuroimmune benefits are mostly inferred indirectly through systemic inflammation and microbiota.

## Connections to NO, NAD⁺, and longevity networks

- **Coupling of NO to vagal anti-inflammatory signaling:** Vagal stimulation increases eNOS/NO in the spleen and inflamed tissues. NO suppresses NF-κB through sGC/cGMP/PKG signaling and promotes anti-inflammatory effects. α7nAChR signaling is functionally coupled to NO production (α7nAChR activation can induce NO release from endothelial and immune cells), so some vagal anti-inflammatory effects may be NO-mediated. Conversely, eNOS deficiency weakens vagal anti-inflammation. The “vagus → NO → anti-inflammation” pathway is a direct intersection of neuroimmune and NO biology (see 01-foundations/03-no-basics.md).
- **The iNOS/NO paradox in neuroimmunity:** During chronic stress and neuroinflammation, high iNOS expression in inflamed tissues and microglia generates large amounts of NO. High NO reacts with superoxide to form peroxynitrite (ONOO⁻), causing protein nitration and worsening neurodegeneration. At the same time, systemic eNOS/NO supply declines due to endothelial dysfunction. This is an imbalance of “systemic NO deficiency + local nitrosative stress,” consistent with the “double-edged sword” of NO discussed in immunosenescence, but here focused on the brain and neuroimmune interface.
- **NO regulates microglia and T cells:** Microglial iNOS-derived NO is a means of killing and immune regulation, but chronic excess is neurotoxic. T cells respond biphasically to NO: low NO promotes Th1 differentiation/proliferation, while high NO suppresses cells through S-nitrosylation. Neuroimmune imbalance disrupts the spatial and temporal distribution of NO, further worsening immune polarization.
- **eNOS/NO and cerebral blood flow:** eNOS maintains cerebral microvascular perfusion and BBB integrity. With age, eNOS downregulation → reduced cerebral blood flow and increased BBB permeability → peripheral inflammatory cytokines enter the brain → neuroinflammation. NO is the vascular gatekeeper for the “peripheral inflammation → brain” pathway.
- **NAD⁺/SIRT1 crosstalk:** NO activates SIRT1 (and eNOS is also regulated by NAD⁺-dependent enzymes). NAD⁺ decline → SIRT1↓ → increased NF-κB acetylation (pro-inflammatory) and microglial polarization imbalance. Some benefits of NAD⁺ precursors (NMN/NR) for neuroinflammation and cognition may be mediated by SIRT1 anti-inflammatory activity and maintenance of NO supply. Cortisol also interacts with SIRT1 (GR activity is regulated by SIRT1 deacetylation), creating multi-point coupling of “NO–NAD⁺–SIRT1–glucocorticoids” within the neuro-immune axis.

## Intervention directions and actionable recommendations

**Behavior and lifestyle (most actionable; strongest evidence):**
1. **Regular aerobic exercise** (≥150 minutes/week of moderate-intensity activity): the only mature intervention that simultaneously increases vagal tone (HRV↑), lowers resting inflammation, and delays immunosenescence (naïve T cells↑, senescent T cells↓)—the behavioral “gold standard” for the neuro-immune axis.
2. **Breathing, meditation, and yoga:** Slow deep breathing, especially at 4–6 breaths/min, directly increases vagal efferent tone and HRV. Mindfulness meditation has small-to-moderate effects on transcriptomic and inflammatory markers (NF-κB inflammatory genes downregulated). It is a low-cost complement to exercise, although the relation between dose (duration/frequency) and effect is unsettled.
3. **Optimize sleep:** Sleep is a high-efficiency window for glymphatic clearance (about 60% more efficient than wakefulness) and a regulator of immune homeostasis. Ensuring 7–8 hours, including adequate deep sleep, directly supports neuroimmune balance and clearance.
4. **Anti-inflammatory diet:** A Mediterranean-style diet (rich in SCFA-producing fiber, omega-3s, and polyphenols), with less refined sugar and saturated fat. RCTs support omega-3 (EPA/DHA) for lowering inflammatory markers.

**Medicines/devices (more frontier-stage evidence):**
5. **Vagus-nerve stimulation:** Approved for treatment-resistant epilepsy/depression; anti-inflammatory indications (RA, IBD) are in clinical trials. Noninvasive transcutaneous auricular VNS (taVNS) is a lower-risk research direction.
6. **α7nAChR agonists/positive allosteric modulators:** Strong preclinical anti-inflammatory effects; human trials show good safety but uncertain efficacy. This is a potential oral anti-inflammatory drug strategy, with selectivity versus cholinergic side effects a key bottleneck.
7. **Stress management:** Cognitive behavioral therapy and social support have moderate evidence for reducing stress-related inflammation. Limiting chronic cortisol exposure and preserving cortisol rhythms are core endocrine strategies for the neuro-immune axis.

**Evidence-level reminder:** Human efficacy evidence for VNS, α7nAChR agonists, and meditation is weaker than that for exercise, sleep, and diet. Behavioral interventions (exercise, sleep, breathing) are currently the most pragmatic anti-aging tools for the neuro-immune axis because they act on both vagal tone and immunity.

## Open questions and controversies

- **Controversy over “spleen dependence” of human CAP:** Does vagal anti-inflammation in humans act through the spleen–α7nAChR pathway established in animals, or through effects in multiple organs? Splenectomy/splenic-nerve blockade evidence is animal-only; anti-inflammatory benefits of human VNS cannot be attributed to one pathway. More direct evidence is needed to reconstruct the human CAP pathway.
- **Drugging α7nAChR:** Can selective α7 positive allosteric modulators provide anti-inflammatory benefits while avoiding cholinergic adverse effects such as nausea and hypotension? Failures such as GTS-21 illustrate the difficulty of developing drugs against this target.
- **Are meditation/exercise effects greater than confounding by generally healthy lifestyles?** Differences often shrink in RCTs with active controls rather than inactive controls, so the independent anti-inflammatory effect of meditation may be overestimated. More rigorous control designs are needed.
- **Is neuroimmune imbalance a cause or an amplifier?** Are declining vagal tone and disrupted cortisol rhythms drivers of inflammaging or accompanying “amplifiers” of systemic inflammation during aging? Long-term intervention data are lacking to determine whether restoring vagal tone can truly reverse human immunosenescence.
- **Causality between glymphatic function and neurodegeneration:** Is reduced glymphatic clearance a cause, risk factor, or consequence of AD and other neurodegenerative diseases? The translational potential of enhancing clearance through meningeal lymphatics/VNS is unknown.
- **Causality and confounding in the gut–brain axis:** Most microbiota–brain–immune findings are associations, not proof of causality. Vagotomy and microbiota-transfer evidence is largely from animals; clinical benefits of human microbiota interventions (probiotics/fecal microbiota transplantation) for the neuro-immune axis remain uncertain.

## References

1. Borovikova LV, Ivanova S, Zhang M, et al. Vagus nerve stimulation attenuates the systemic inflammatory response to endotoxin. *Nature*. 2000;405(6785):458-462.
2. Tracey KJ. The inflammatory reflex. *Nature*. 2002;420(6917):853-859.
3. Wang H, Yu M, Ochani M, et al. Nicotinic acetylcholine receptor α7 subunit is an essential regulator of inflammation. *Nature*. 2003;421(6921):384-388.
4. Rosas-Ballina M, Olofsson PS, Ochani M, et al. Acetylcholine-synthesizing T cells relay neural signals in a vagus nerve circuit. *Science*. 2011;334(6052):98-101.
5. de Jonge WJ, van der Zanden EP, The FO, et al. Stimulation of the vagus nerve attenuates macrophage activation by activating the Jak2-STAT3 signaling pathway. *Nat Immunol*. 2005;6(8):844-851.
6. Koopman FA, Chavan SS, Miljko S, et al. Vagus nerve stimulation inhibits cytokine production and attenuates disease severity in rheumatoid arthritis. *Proc Natl Acad Sci USA*. 2016;113(29):8284-8289.
7. Louveau A, Smirnov I, Keyes TJ, et al. Structural and functional features of central nervous system lymphatic vessels. *Nature*. 2015;523(7560):337-341.
8. Iliff JJ, Wang M, Liao Y, et al. A paravascular pathway facilitates CSF flow through the brain parenchyma and the clearance of interstitial solutes, including amyloid β. *Sci Transl Med*. 2012;4(147):147ra111.
9. Xie L, Kang H, Xu Q, et al. Sleep drives metabolite clearance from the adult brain. *Science*. 2013;342(6156):373-377.
10. Erny D, Hrabě de Angelis AL, Jaitin D, et al. Host microbiota constantly control maturation and function of microglia in the CNS. *Nat Neurosci*. 2015;18(7):965-977.
11. Kiecolt-Glaser JK, Preacher KJ, MacCallum RC, et al. Chronic stress and age-related increases in the proinflammatory cytokine IL-6. *Proc Natl Acad Sci USA*. 2003;100(15):9090-9095.
12. Black DS, Cole SW, Irwin MR, et al. Yogic meditation reverses NF-κB and IRF-related transcriptome dynamics in leukocytes of family dementia caregivers in a randomized controlled trial. *Psychoneuroendocrinology*. 2013;38(3):348-355.
13. Bower JE, Crosswell AD, Stanton AL, et al. Mindfulness meditation for younger breast cancer survivors: a randomized controlled trial. *Cancer*. 2015;121(8):1231-1240.
14. Olofsson PS, Rosas-Ballina M, Levine YA, Tracey KJ. Rethinking inflammation: neural circuits in the regulation of immunity. *Immunol Rev*. 2012;248(1):188-204.
15. Pavlov VA, Tracey KJ. Neural regulation of immunity: molecular mechanisms and clinical translation. *Nat Neurosci*. 2017;20(2):156-166.
