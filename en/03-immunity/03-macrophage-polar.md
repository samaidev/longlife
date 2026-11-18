# Macrophage-Po larization Imbalance: The M1/M2 Switch and Anti-Aging Interventions

> Macrophage polarization was **added as the 10th hallmark of aging** in the updated framework published by López-Otín’s team in *Cell* in 2023 (“Hallmarks of Aging: An Expanding Universe”). This article follows the full chain from origin → polarization categories → signaling mechanisms → metabolic reprogramming → age-related imbalance → disease consequences → interventions, while integrating the NO-centered perspective of this collection.

---

## I. Core Concept

**In one sentence:** Macrophage polarization is the plastic process by which, in response to microenvironmental signals, macrophages differentiate toward either the pro-inflammatory, antimicrobial **M1 phenotype (classically activated)** or the anti-inflammatory, tissue-repairing **M2 phenotype (alternatively activated)**. Aging disrupts this balance, with stronger M1 bias and declining M2 repair function, driving chronic inflammation and tissue fibrosis.

**Why it matters:** Macrophages are central effectors of innate immunity and hubs for tissue homeostasis, injury repair, and metabolic regulation. Polarization imbalance is not an isolated event: it amplifies **chronic inflammation (the 12th hallmark)**, is an important source of **cellular-senescence SASP (the 7th hallmark)**, and directly participates in atherosclerosis, obesity, fibrosis, cancer, and neurodegenerative disease (see Section VII). Listing it as a separate hallmark in 2023 marks the transition of research at the intersection of immunity, metabolism, and tissue injury from “describing a phenomenon” to “identifying an intervention target.”

**Relevance to anti-aging:** Polarization is one of the few aging-related processes that is **bidirectionally reversible**. Repolarization strategies can reverse fibrosis and improve metabolic and vascular function in animal models. Since the core effector molecule of M1 is **NO produced by iNOS** (see Section V), macrophage polarization naturally intersects with this collection’s NO theme: NO is both an M1 weapon and an M2 regulatory signal; its concentration and source determine its role.

---

## II. Macrophage Origins: Tissue-Resident vs. Monocyte-Derived

The traditional “mononuclear phagocyte system” (MPS) theory held that all macrophages differentiated from bone-marrow monocytes. The **lineage-tracing (fate-mapping) revolution** around 2010 overturned this view:

| Feature | Tissue-resident macrophages (TRMs) | Monocyte-derived macrophages (MDMs) |
|---|---|---|
| Embryonic origin | Yolk sac and fetal-liver hematopoiesis | Bone-marrow hematopoietic stem cells → monocytes |
| Developmental timing | Primitive yolk-sac hematopoiesis at E8.5 / fetal liver at E12.5 | Continuously replenished after birth |
| Self-renewal | Local proliferation (M-CSF/IL-34 dependent) | Depends on infiltration of circulating monocytes |
| Lifespan | Months to years | Days to weeks |
| Examples | Microglia, Kupffer cells, alveolar macrophages, skin Langerhans cells | Inflammatory infiltrating macrophages, some tumor-associated macrophages |

**Key examples:** Microglia arise entirely from the yolk sac and depend very little on bone-marrow replenishment; bone-marrow chimeras therefore do not readily eliminate them. Kupffer cells (liver) and alveolar macrophages (lung) are likewise maintained at steady state by self-renewal of embryonic precursors and are replaced in large numbers by monocyte-derived macrophages only after tissue injury. This distinction has important **aging implications**: TRMs are exposed to their tissue microenvironment for long periods and accumulate epigenetic changes and damage with age. MDM replenishment depends on bone-marrow output; aging bone marrow shifts toward myeloid hematopoiesis (see clonal hematopoiesis, CHIP, in 04-immunosenescence.md), giving infiltrating macrophages an intrinsically pro-inflammatory tendency.

**Coupling of origin and phenotype in aging:** Alveolar macrophages in aged lungs show an M1 shift (CD11c↑, TNF-α↑), while TRM self-renewal declines (weaker response to IL-34). In the aged brain, microglia enter a “primed/dystrophic” state and disease-associated microglia (DAM) subpopulations accumulate. These are tissue-level starting points for macrophage-polarization imbalance (strong animal association; supported by human observations).

---

## III. Definition and Classification of Polarization: From a Binary Model to a Continuum

### 3.1 Classical Classification

The concept of polarization grew out of Mosmann’s 1986 Th1/Th2 dichotomy and was later applied to macrophages by Gordon, Mills, and others:

- **M1 (classically activated):** Induced by **IFN-γ** (from Th1 or NK cells) or **LPS** (a TLR4 ligand), and driven by **STAT1, IRF5, and NF-κB**. Markers: CD86, CD80, MHC-II↑, iNOS (mouse), IL-1β, IL-6, TNF-α, CXCL9/10/11. Functions: antimicrobial activity, antitumor activity, and pro-inflammatory signaling.
- **M2 (alternatively activated):** Induced by **IL-4/IL-13** and driven by **STAT6, PPARγ, and KLF4**. IL-10, TGF-β, and glucocorticoids can also induce M2-like phenotypes. Markers: CD206 (mannose receptor, MRC1), Arg1, Ym1 (mouse), FIZZ1 (mouse), IL-10, and TGF-β. Functions: anti-inflammatory activity, tissue repair, immunosuppression, and promotion of fibrosis.

**Three M2 subtypes** (Mantovani’s 2004 classification):

| Subtype | Inducing signals | Markers | Function |
|---|---|---|---|
| M2a | IL-4, IL-13 | CD206, Arg1, Ym1 | Tissue repair, Th2 immunity |
| M2b | Immune complexes + TLR ligands | IL-10↑, IL-1β↑, TNF-α↑ | Immune regulation, Th2 polarization |
| M2c | IL-10, TGF-β, glucocorticoids | IL-10, TGF-β, MerTK | Immunosuppression, matrix deposition |

### 3.2 The Continuum Debate: Limitations of the Binary Model

The M1/M2 dichotomy is a powerful conceptual tool but has systematic limitations:

1. **Species differences in markers:** iNOS is a reliable M1 marker in mice, but **human macrophages express very little iNOS and it is difficult to induce** (human M1 is commonly defined by IL-1β and CXCL9/10). Arg1 expression is also weak in human macrophages. Directly applying mouse M1/M2 markers to humans has clear limitations.
2. **In vitro induction ≠ in vivo state:** Macrophages in vivo are exposed to mixed signals. Single-cell sequencing shows that tissue macrophages have a **continuous transcriptional spectrum**, not two discrete poles (for example, adipose-tissue macrophages may express both M1 and M2 markers).
3. **Phenotypic plasticity:** M1 and M2 can interconvert within hours; polarization is not terminal differentiation. Multiple intermediate states exist, such as Mox (induced by oxidized LDL) and Mhem (induced by heme; anti-atherosclerotic).

The current consensus is that **M1 and M2 are reference endpoints on a continuum**, useful for describing tendencies rather than assigning labels. This article retains M1/M2 terminology but emphasizes its heuristic nature—important for intervention design: **polarization is not a switch for “killing M1” or “manufacturing M2,” but a rebalancing of overall phenotype weights.**

---

## IV. The Full Molecular Cascade: Signals → Transcription → Effectors

### 4.1 M1 Polarization Signals and Transcriptional Program

```
Upstream signals                      Transcription factors            Effector output
──────────────────────────────────────────────────────────────────────────────────────
LPS ── TLR4 ── MyD88 ── IRAK1/4 ── TRAF6
      └── TRIF (late IRF3 pathway)              │
                                                ▼
IFN-γ ── IFNGR ── JAK1/JAK2 ── STAT1 (Y701 phosphorylation) ── dimerization/nuclear entry
                                                │
TNF-α ── TNFR1 ── RIPK1 ── IKKα/β ── IκBα degradation ── NF-κB (p65/p50) nuclear entry
                                                │
                                                ▼
                          STAT1 + IRF5 + NF-κB cooperatively bind promoters
                                                │
                                                ▼
        iNOS(NOS2) / IL-1β / IL-6 / TNF-α / CXCL9/10 / IL-12
        (+ NLRP3 inflammasome assembly → caspase-1 → IL-1β/IL-18 maturation)
```

**Key nodes:**

- **Dual TLR4 pathways:** LPS activates the MyD88-dependent pathway through TLR4 (early NF-κB, producing TNF-α/IL-6) and the TRIF-dependent pathway (late IRF3 → IFN-β, which amplifies IFN-γ-like signaling through autocrine action). This explains why LPS-induced M1 polarization is “both rapid and persistent.”
- **STAT1 is the core M1 switch:** IFN-γ activates JAK1/JAK2-mediated phosphorylation of STAT1 at Tyr701; STAT1 homodimerizes and enters the nucleus. STAT1, IRF5, and NF-κB cooperate at the iNOS promoter; all three are required—STAT1 knockout alone can markedly weaken the M1 transcriptional program.
- **NLRP3 inflammasome:** In M1 macrophages, Signal 1 (NF-κB upregulates NLRP3 and pro-IL-1β) plus Signal 2 (ATP, crystals, or ROS trigger assembly) → caspase-1 activation → cleavage of IL-1β/IL-18 and pyroptosis. “Sterile inflammation” in aging tissues is one source of Signal 2 (damage-associated molecular patterns, DAMPs, such as HMGB1 and free mtDNA).

### 4.2 M1 Effectors: iNOS/NO and Pro-Inflammatory Cytokines

**iNOS is the signature effector enzyme of M1** (see 03-immunity/01-no-immune.md). Its effector cascade is:

```
L-arginine ──iNOS(NOS2)──▶ NO + L-citrulline
   │                        │
   │                        ├─▶ reacts with O₂⁻ ──▶ ONOO⁻ (peroxynitrite)
   │                        │      └─ oxidizes iron–sulfur clusters → inactivates aconitase/ETC complexes I, II
   │                        │      └─ nitrates tyrosine (3-NT) → protein damage
   │                        │      └─ consumes GSH, damages DNA (8-oxoG)
   │                        ├─▶ high NO directly inhibits pathogen metabolic enzymes (S-nitrosylation)
   │                        └─▶ activates soluble guanylate cyclase (sGC) → cGMP
   │
   └─▶ (competes with Arg1 for the same substrate; see 4.4)
```

**A double-edged dose:** M1 macrophages produce **micromolar (μM) NO** via iNOS for hours to days (iNOS calmodulin binds constitutively with very low Ca²⁺ affinity; once induced, it produces NO continuously at high levels). High NO reacts with superoxide to form ONOO⁻, providing broad-spectrum antimicrobial activity. The same mechanism damages tissue, as shown by 3-nitrotyrosine deposition in rheumatoid synovium and atherosclerotic plaques. **The key paradox:** iNOS-knockout mice are markedly susceptible to intracellular pathogens (mycobacteria, Leishmania, Listeria) because antimicrobial function is lost. Yet clinical trials of nonselective NOS inhibitors in sepsis have shown no benefit and may even cause harm—the double-edged nature of high NO has been repeatedly validated in humans.

**Other M1 effects:** IL-1β amplifies local inflammation via IL-1R and activates endothelium; IL-6 drives the acute-phase response (CRP elevation) and Th17 polarization; TNF-α induces endothelial adhesion molecules (ICAM-1/VCAM-1) and promotes leukocyte infiltration; ROS from NADPH oxidase NOX2 directly kill pathogens. **Net effect:** M1 is the “clearance” phenotype—it removes pathogens, tumor cells, and necrotic tissue, but excessive or sustained activation damages host tissue.

### 4.3 M2 Polarization Signals and Transcriptional Program

```
Upstream signals                   Transcription factors               Effector output
──────────────────────────────────────────────────────────────────────────────────────
IL-4/IL-13 ── IL-4Rα/IL-13Rα1 ── JAK1/JAK3 ── STAT6 (Y641 phosphorylation) ── dimerizes/enters nucleus
      │                                                                     │
      │                                                                     ▼
      └─ IL-4Rα can also activate IRS2 ── PI3K ── AKT (pro-survival)     STAT6 + PPARγ + KLF4
                                                                            │
IL-10 ── IL-10R ── JAK1/TYK2 ── STAT3 ── SOCS3 inhibits inflammation       ▼
                                                                        Arg1 / CD206(MRC1) /
TGF-β ── TGFBR ── Smad2/3 (+ noncanonical pathways)                     Ym1 / FIZZ1 / IL-10 /
                                                                        TGF-β / VEGF / EGF
Glucocorticoids ── GR ── transrepression of NF-κB (protein–protein interaction)
```

**Key nodes:**

- **STAT6 is the core M2 switch:** IL-4/IL-13 activate JAK-mediated phosphorylation of STAT6 at Tyr641. STAT6 homodimerizes, enters the nucleus, and drives M2 genes such as Arg1, CD206, and Ym1. STAT6-knockout mice completely lose the capacity for alternative activation.
- **PPARγ couples metabolism to transcription:** PPARγ is a lipid-activated transcription factor that cooperates with STAT6 to regulate M2 genes. Its agonists (thiazolidinediones, e.g., rosiglitazone) promote M2 polarization in vitro and in animals, at the cost of fat accumulation (PPARγ is itself a master regulator of adipogenesis).
- **KLF4’s supporting role:** KLF4 cooperates with STAT6 to activate M2 genes while suppressing NF-κB-dependent M1 genes (KLF4 competes with NF-κB for coactivators). KLF4 deficiency shifts macrophages toward M1.

### 4.4 M2 Effectors and the Arginine-Competition Switch

**Core M2 effects:** (a) **Arg1 (arginase 1)** converts L-arginine → ornithine + urea; ornithine feeds polyamine (cell proliferation) and proline (collagen synthesis) production, the metabolic basis of M2-mediated tissue repair and fibrosis; (b) **CD206 (mannose receptor)** mediates glycoprotein clearance and modulates antigen presentation; (c) **IL-10** inhibits pro-inflammatory genes and upregulates SOCS3 through STAT3; (d) **TGF-β** activates stromal cells and deposits collagen; and (e) **VEGF** promotes angiogenesis—the same pathway serves wound repair and tumor vascularization.

**Arginine competition is a metabolic switch for polarization** (the “arginine switch” hypothesis proposed by Mills in 2000):

```
                  L-arginine (shared substrate)
                 ┌───────────┴───────────┐
             iNOS (M1)                 Arg1 (M2)
                 │                        │
            NO + citrulline         Ornithine + urea
                 │                        │
     Microbicidal/inflammation/     Polyamines (proliferation) +
       nitrosative stress                proline (collagen)
                 └──── compete for the same substrate pool ────┘
     Microenvironment determines: Th1 cytokines → iNOS dominance → M1
                                 Th2 cytokines → Arg1 dominance → M2
```

The significance of this competition is that **polarization is not “idle gene expression,” but reallocation of substrate flux**. M1 burns arginine into NO to kill pathogens; M2 converts it into polyamines and collagen to repair tissue. Their relative activity determines whether tissue moves toward “clearance + injury” or “repair + fibrosis.” Supplementing exogenous arginine cannot simply “boost” one side—it feeds both pathways, and the actual effect depends on the strength of polarization signals in the microenvironment (see Section VI and the links to NO).

---

## V. Metabolic Reprogramming: The “Fuel System” of Polarization

Macrophage polarization is accompanied by **profound metabolic reprogramming**. Metabolic state is both a result and a cause of polarization (positive feedback):

### 5.1 M1: Glycolysis + Pentose Phosphate Pathway + Succinate

```
Glucose ──▶ glycolysis (HK2/PKM2 upregulated) ──▶ pyruvate ──▶ lactate (Warburg-like)
              │                                      │
              ▼                                      ▼
       Pentose phosphate pathway (PPP)        Mitochondrial “break”: interrupted
       (G6PD upregulated)                       TCA cycle (IDH downregulated)
              │                                      │
              ▼                                      ▼
       NADPH supply                         Citrate → itaconate accumulates
       (for NOX2 ROS and                    Succinate → stabilizes HIF-1α
        iNOS NO production)                         │
                                                     ▼
                                           Pro-inflammatory gene transcription (e.g., IL-1β)
```

- **Upregulated glycolysis:** M1 macrophages markedly increase glycolytic flux (similar to the Warburg effect in tumors). Although energetically inefficient, this provides rapid ATP and biosynthetic intermediates; HK2, PFKFB3, and PKM2 are key enzymes that rise.
- **Upregulated PPP:** Glucose-6-phosphate dehydrogenase (G6PD) drives the PPP and generates **NADPH**—a cofactor for both iNOS (NO production) and NOX2 (ROS production), as well as the reducing power for glutathione regeneration (antioxidant defense). How NADPH is allocated determines the balance between M1 “attack” and “self-protection.”
- **TCA break and succinate:** In M1, reduced isocitrate dehydrogenase (IDH) interrupts the TCA cycle at isocitrate, allowing citrate to exit into the cytoplasm for lipid synthesis. Accumulating succinate **stabilizes HIF-1α** by inhibiting prolyl hydroxylase (PHD). HIF-1α in turn upregulates glycolytic enzymes and IL-1β transcription, forming a “succinate → HIF-1α → inflammation” loop.
- **Itaconate:** Produced from cis-aconitate by IRG1 (immune-responsive gene 1), it is an endogenous anti-inflammatory brake in M1 (inhibits SDH and alkylates KEAP1 to activate Nrf2)—M1 has its own negative feedback.
- **HIF-1α’s dual role:** In M1, HIF-1α stabilization drives glycolysis and inflammation; but HIF-1α also upregulates VEGF and arginine-metabolism enzymes, so its net effect depends on signaling context.

### 5.2 M2: Fatty-Acid Oxidation (FAO) + Oxidative Phosphorylation

```
Fatty acids ──▶ CPT1 (carnitine shuttle) ──▶ mitochondrial β-oxidation ──▶ acetyl-CoA ──▶ TCA ──▶ OXPHOS
                       ▲                                                           │
                       │ (CD36, FABP4 uptake upregulated)                            ▼
              STAT6/PPARγ transcription upregulated                         Abundant ATP + low ROS
                                                                         (“quiet” electron-transport chain)
```

- M2 macrophages rely primarily on FAO + OXPHOS, producing ample energy but responding more slowly. PPARγ jointly drives FAO and M2 genes, molecularly bridging lipid metabolism and the anti-inflammatory phenotype.
- **Mitochondrial dynamics:** M2 shows increased mitochondrial fusion (Mfn1/2) and intact cristae; M1 shows mitochondrial fragmentation (Drp1-dependent). Macrophages with impaired mitophagy tend toward pro-inflammatory M1, directly linking polarization to age-related decline in autophagy (see 01-foundations/06-proteostasis-autophagy.md).

### 5.3 Metabolism–Polarization Positive Feedback and Aging

Aging strikes metabolism–polarization coupling in three ways: (a) **NAD⁺ decline** → lower SIRT1 activity → weaker SIRT1 regulation of NF-κB (p65 K310 deacetylation) and PPARγ → M1 is disinhibited and M2 support declines; (b) **mitochondrial decline** → further amplifies M1’s succinate/HIF-1α pathway; and (c) **declining autophagy** → damaged mitochondria accumulate → oxidized mtDNA leaks and activates cGAS–STING → interferon signaling → pro-inflammatory state. **Result:** the metabolic fingerprint of aged macrophages shifts overall toward “glycolysis + inflammation.”

---

## VI. M1/M2 Imbalance in Aging

### 6.1 Manifestations of Imbalance

| Tissue | Age-related change | Evidence grade |
|---|---|---|
| Adipose tissue | M1 (CD11c⁺, iNOS) infiltration↑, M2 (CD206⁺, Arg1)↓, pro-inflammatory factors↑ | Established in aged mice; human observations |
| Liver | Kupffer cells become pro-inflammatory; M1/M2 ratio↑ | Strong animal evidence |
| Skeletal muscle | Intermuscular fat and infiltrating macrophages shift to M1; TNF-α↑ impairs satellite-cell regeneration | Strong animal + human observational evidence |
| Brain | Microglia become primed/dystrophic, DAM subpopulations accumulate, IL-1β/TNF-α↑ | Strong animal + human autopsy evidence |
| Lung | Alveolar macrophages shift to M1; repair capacity in aged lungs↓ | Supported by animals |
| Vasculature | Higher plaque M1/M2 ratio associated with plaque instability | Human observation (pathology specimens) |

### 6.2 Mechanisms: Why Aged Macrophages Skew Toward M1

1. **Transcription-factor drift:** NF-κB activity rises in aged macrophages (DNA-binding activity rises several-fold in aged mouse liver/spleen), and basal STAT1 phosphorylation increases. PPARγ expression declines, especially in adipose tissue—the M1 driver rises while the M2 driver falls.
2. **Changes in microenvironmental signals:** Senescent-cell SASP (IL-6, IL-1β, TNF-α) continually stimulates macrophages toward inflammation; DAMPs in aged tissue (HMGB1, mtDNA) activate NF-κB via TLRs; sex hormones decline (estrogen promotes M2, relevant to increased inflammatory burden after menopause).
3. **Declining efferocytosis:** Macrophage clearance of apoptotic cells declines with age; expression of MerTK, MFG-E8, and TIM-4 is reduced. Incompletely cleared apoptotic cells undergo secondary necrosis → release DAMPs → sustain inflammation, creating a vicious cycle of “clearance failure → inflammation → more damage.” This is a **direct causal bridge** between macrophage-polarization imbalance and the chronic-inflammation hallmark.
4. **Epigenetic locking:** Promoter epigenetic marks drift in aged macrophages (e.g., H3K4me1 enrichment at pro-inflammatory genes and altered enhancer accessibility), making “polarization memory” more persistent and repolarization harder—the aging version of trained immunity.
5. **Declining NO bioavailability** (the central theme of this collection): eNOS activity declines with age → less low-concentration NO → NF-κB disinhibition → M1 bias. At the same time, iNOS induction capacity declines in aged macrophages (see 04-immunosenescence.md). M1’s microbicidal efficiency falls even as inflammatory output rises—a **functional mismatch**.

### 6.3 Net Consequences

Macrophages in aged tissues show a mismatch of **“high inflammatory output + low clearance efficiency + low repair capacity.”** They cannot effectively clear pathogens and apoptotic cells (weaker defense), yet continuously secrete pro-inflammatory factors (tissue injury), while repair is impaired (loss of M2 function). This mismatch is a core part of immunosenescence and a reason “macrophage-polarization imbalance” was listed separately from “chronic inflammation” as a hallmark of aging.

---

## VII. Polarization Imbalance and Disease

### 7.1 Atherosclerosis: The M1/M2 Contest within Plaques

Plaque macrophages are central cells in atherosclerosis: (a) early on, infiltrating monocytes differentiate, and oxidized LDL is taken up through CD36/SR-A to form foam cells; (b) during plaque progression, M1 predominates—IFN-γ and TNF-α promote secretion of matrix metalloproteinases (MMP-9/12) → fibrous-cap degradation → plaque instability; M1-derived tissue factor (TF) promotes thrombosis; (c) M2 (especially the Mhem subset) is relatively enriched in stable plaques and secretes collagen that protects the fibrous cap. **Human evidence:** M1/M2 ratios are significantly higher in symptomatic/ruptured plaques (consistent immunohistochemical pathology studies); 3-NT (a marker of nitrosative stress) colocalizes with M1 cells in plaques. **Intervention implication:** Repolarizing plaque macrophages toward M2/Mhem, rather than lipid lowering alone, is one strategy for stabilizing plaques (see 02-vascular/06-lipid-atherosclerosis.md).

### 7.2 Tumor-Associated Macrophages (TAMs): M2 “Co-opted”

The tumor microenvironment reprograms infiltrating macrophages into **TAMs**, with an M2-like phenotype (CD163⁺, CD206⁺, Arg1-related genes upregulated) and functions that promote angiogenesis (VEGF), immunosuppression (IL-10, TGF-β, PD-L1 expression, T-cell inhibition), and invasion/metastasis (EGF, MMPs). **Mechanism:** Tumors secrete CSF-1 (M-CSF), IL-4, IL-10, and lactate (a metabolic signal) → macrophages polarize toward M2; HIF-1α in hypoxic regions further supports TAM immunosuppression. **Clinical evidence:** High TAM density is associated with poor prognosis in many solid tumors (consistent meta-analyses). CSF-1R inhibitors (e.g., pexidartinib, approved for tenosynovial giant-cell tumor) can deplete/reprogram TAMs and act against tumors, but monotherapy has limited efficacy in solid tumors—TAM targeting may need combination with immune-checkpoint inhibitors. **Aging perspective:** The M2 bias of TAMs in older tumor microenvironments is more persistent and adds to age-related immune escape.

### 7.3 Obesity and Adipose-Tissue Macrophages (ATMs)

In obesity, adipose-tissue macrophages shift from a protective M2 phenotype (maintaining insulin sensitivity and clearing apoptotic adipocytes) toward pro-inflammatory M1 (CD11c⁺, TNF-α, IL-1β); they may account for over 40% of adipose-tissue cells. **Mechanism:** Adipocyte hypertrophy → hypoxia (HIF-1α↑) → chemokine CCL2 (MCP-1) recruits monocytes; lipotoxicity (saturated fatty acids activate NF-κB via TLR4); and necrotic adipocytes release DAMPs. **Causal evidence:** CCL2 or CCR2 knockout mice have fewer macrophages infiltrating during obesity and improved insulin sensitivity; **however,** CCR2 knockout also worsens adipose-tissue hypoxia, showing that ATM depletion is a double-edged sword (macrophages also buffer lipids). In humans, a higher adipose-tissue M1/M2 ratio in obesity is associated with insulin resistance (HOMA-IR), and the ratio falls after weight loss—**human evidence for polarization reversibility**.

### 7.4 Fibrosis: The “Overdoing” of M2 Repair

M2 macrophages execute tissue repair, but persistent/excessive M2 polarization drives fibrosis: TGF-β activates myofibroblasts → collagen deposition → organ stiffening. **Idiopathic pulmonary fibrosis (IPF)** is a classic example: pro-fibrotic macrophages (expressing SPP1/osteopontin) are enriched in IPF lungs. **A key connection highlighted in this collection:** Rentosertib (INS018_055), a TNIK inhibitor developed with AI by Insilico Medicine, has shown anti-fibrotic efficacy in IPF. Its preclinical and proteomic analyses suggest **macrophages shift from pro-inflammatory/pro-fibrotic toward a reparative phenotype** (see 04-drugs/01-rentosertib.md). This is a landmark case of “repolarization intervention” entering clinical proof-of-concept (Phase III began in 2026). **Important tension:** Treating fibrosis requires “inhibiting the pro-fibrotic side of M2,” not simply “promoting M2.” Distinguishing M2 subtypes (repair-oriented M2a versus matrix-depositing M2c) is critical to treatment design; a simplistic “promote M2” slogan is hazardous in fibrotic disease.

### 7.5 Alzheimer’s Disease: Microglia’s Double-Edged Role

Microglia (brain TRMs) in Alzheimer’s disease: (a) Aβ-clearance capacity declines with age (changes in CD33 and TREM2 pathways); (b) chronic Aβ stimulation shifts toward inflammation (IL-1β, TNF-α, and complement C1q-mediated excessive synaptic pruning); and (c) DAM subsets (TREM2–APOE pathway) accumulate around plaques, with functions between clearance and inflammation. **Evidence:** Loss-of-function TREM2 variants (R47H) raise AD risk approximately 2–3-fold (established human genetics); TREM2-knockout mice also show reduced Aβ clearance. Microglial activation is therefore a balance between “insufficient clearance” and “excess inflammation,” consistent with the broader macrophage-polarization framework. **Intervention:** TREM2 agonist antibodies (e.g., AL002) have entered clinical trials, with the goal of “enhancing clearance rather than simply suppressing inflammation.”

---

## VIII. Summary Table of Evidence Grades

| Proposition | Evidence grade | Key basis |
|---|---|---|
| Macrophages exhibit M1/M2 plasticity | Established (mechanistic consensus) | In vitro polarization + in vivo lineage tracing (Gordon 2003 review framework) |
| Polarization is driven by STAT1/NF-κB (M1) and STAT6/PPARγ (M2) | Established (mechanistic) | Clear phenotypes in STAT1/STAT6 knockout mice |
| Aged tissues show M1 bias and reduced M2 | Strong association (animals) + observation (humans) | Increased M1 markers in aged mouse fat/liver/brain; pathology of human plaques/adipose tissue |
| Efferocytosis declines with age | Strong animal evidence + limited human evidence | MerTK/MFG-E8 downregulation in aged mice; human evidence needs expansion |
| Polarization imbalance drives atherosclerosis/obesity/fibrosis | Animal causality + human association | CCR2 knockout, CSF-1R inhibition, plaque pathology, IPF clinical studies |
| M2-promoting drugs can reverse aging-related phenotypes in model systems | Animal support | PPARγ agonists, IL-4 delivery, statin effects on M2 |
| Long-term human benefit from repolarization interventions | Early/exploratory | Rentosertib Phase II (exploratory anti-aging endpoints), TREM2 antibody Phase I/II |
| Repolarization is safe and effective in humans | Not established | No large RCT; M2 promotion may worsen fibrosis/immunosuppression |

---

## IX. Connections to NO / NAD⁺ / Longevity Networks (A Distinctive Perspective)

### 9.1 iNOS/NO Is the Core M1 Effector Axis

Almost all of M1’s “killing function” is executed through iNOS-derived NO (see 03-immunity/01-no-immune.md). This creates **molecular-level coupling** between macrophage polarization and NO signaling:

```
M1 polarization ──▶ iNOS induction ──▶ μM NO ──▶ pathogen killing / nitrosative stress
                                         │
Age-related decline in NO bioavailability ──▶ NF-κB disinhibition ──▶ inflammation amplification (M1 bias)
                                         │
Low-dose NO (from eNOS) ──▶ S-nitrosylation of p65 (Cys38) / SIRT1-mediated p65 deacetylation
                          ──▶ NF-κB activity↓ ──▶ M1 suppression, M2 bias
```

### 9.2 Arginine Competition Is the “Metabolic Switch” for Polarization

Arg1 and iNOS compete for the same substrate, L-arginine (see 4.4)—the most direct metabolic intersection between NO signaling and polarization direction. **Intervention implication:** Simply supplementing arginine is not directional (it feeds both pathways); targeted modulation requires coordination between the “signaling level” (M2-promoting cytokines/drugs) and “metabolic level” (iNOS inhibition or Arg1 activation). **An interesting paradox:** iNOS inhibition may reduce nitrosative damage (anti-inflammatory side) but also weaken microbial killing (defensive side). This paradox has appeared in sepsis trials; interventions must distinguish “inflammatory M1” (pathological) from “microbicidal M1” (protective).

### 9.3 The NAD⁺/SIRT1 Axis Links Polarization to Metabolism

- SIRT1 deacetylates NF-κB p65 (K310) and suppresses its transcriptional activity → when NAD⁺ is sufficient, M1 is restrained;
- SIRT1 deacetylates and activates PGC-1α → mitochondrial biogenesis → supports the oxidative metabolic fingerprint of M2;
- Age-related NAD⁺ decline (NAMPT activity↓) weakens both effects and favors M1. Proteomic analysis of Rentosertib shows NAMPT↑→NAD⁺↑→Sirt1 activation accompanying macrophage M1→M2 repolarization (04-drugs/01-rentosertib.md), an initial indication of the “NAD⁺–polarization” axis in clinical samples.

### 9.4 Summary of Intervention Crossroads

| Intervention | Polarization effect | Connection to NO pathway |
|---|---|---|
| Dietary nitrate/NO donor | Low-dose NO → favors M2 repair polarization | Directly supplements NO pool |
| NAD⁺ precursors (NMN/NR) | SIRT1↑ → NF-κB inhibition → M1 suppression | Shares SIRT1–NO positive feedback |
| Exercise | Adipose M2↑, inflammation↓ | Shear stress activates eNOS |
| PPARγ agonist | Favors M2 | May act synergistically with NO anti-inflammatory effects (unconfirmed) |
| Senolytics | Removes SASP source → less inflammatory macrophage stimulation | Reduces signals inducing iNOS |
| Traditional Chinese medicine: benefit qi and activate blood (see 06-tcm/) | Astragalus/Salvia and others modulate macrophage polarization (preclinical) | Partly through NO/eNOS pathways |

---

## X. Intervention Directions and Actionable Recommendations

### 10.1 M2-Promoting Drugs (Mostly Preclinical)

| Category | Examples | Mechanism | Maturity | Risk |
|---|---|---|---|---|
| PPARγ agonists | Rosiglitazone, pioglitazone | Transcriptional promotion of M2 | Approved (for diabetes); polarization is ancillary | Fluid retention, weight gain, heart-failure risk |
| IL-4/IL-13 mimetics | IL-4 fusion proteins, IL-4Rα agonists | Activate STAT6 | Preclinical | Allergy/Th2 disease risk, pro-fibrotic effects |
| STAT6 activators | Small molecules (screening stage) | Activate M2 transcription | Preclinical | Specificity uncertain |
| Statins | Atorvastatin, etc. | Ancillary M2-promoting/anti-inflammatory effects | Approved | Safety validated at scale |
| Metformin | — | AMPK↑ → inhibits NF-κB | Approved | Safety validated at scale |
| TREM2 agonist antibody | AL002 | Enhances microglial clearance | Phase I/II (AD) | Immune-related adverse effects |

### 10.2 Actionable Anti-Aging Strategies (with Evidence Levels)

1. **Exercise** (human evidence, Level II): Moderate-intensity aerobic activity each week lowers circulating inflammatory markers (IL-6, CRP) in older adults; in animals it reverses M1 bias in adipose tissue. It is the most feasible first choice with the lowest risk.
2. **Calorie restriction/healthy diet** (human observational + animal): Improves adipose macrophage phenotype; Mediterranean diet lowers inflammatory burden.
3. **Senolytics** (established in animals, early in humans): After dasatinib plus quercetin clears senescent cells, aged tissues have fewer sources of inflammatory stimulation for macrophages (see 04-drugs/03-senolytics.md). Human use remains in trials; do not self-administer.
4. **NAD⁺ precursors** (early human evidence): NMN/NR supplementation raises NAD⁺ and theoretically supports M2 through SIRT1-mediated NF-κB inhibition. Human trial results are mixed (effects on inflammatory markers are inconsistent); evidence is insufficient for a clear recommendation.
5. **Dietary nitrate** (human Level II, vascular endpoints): Beetroot juice and similar sources increase NO bioavailability and improve endothelial function. Direct human evidence for effects on macrophage polarization is lacking; use as a reasonable indirect intervention on NO signaling (see 02-vascular/02-dietary-nitrate.md).
6. **Use anti-inflammatory drugs cautiously:** Long-term NSAID use carries cardiovascular and gastrointestinal risks (lesson of ASPREE); do not self-medicate long-term under the banner of “anti-inflammation.”

### 10.3 Intervention Windows and “Polarization Dosing”

The effects of repolarization depend on **timing and dose**: (a) during acute injury, M1 is needed to clear necrotic tissue (premature M2 promotion may impair healing); (b) during chronic phases, M2-mediated repair is needed (persistent M1 causes fibrosis). Aging is a classic chronic-phase setting, so M2 promotion may theoretically be reasonable—but caution is necessary regarding (i) the pro-fibrotic side of M2 (see 7.4), (ii) the immunosuppressive side of M2 (cancer risk), and (iii) individual variation in response to polarization interventions (genetics, microbiome, comorbidities). **“Polarization dosing”—targeted, stage-specific, and reversible—is a design principle for future personalized anti-aging interventions.**

---

## XI. Open Questions and Controversies

1. **Will the M1/M2 dichotomy be discarded?** The single-cell era has established a macrophage continuum, but the continuum framework has not yet yielded actionable treatment targets. The dichotomy remains the most practical “working model.” When does its simplification begin to mislead treatment design (for example, the adverse consequences of “promote M2” in fibrosis)?
2. **Is polarization imbalance a cause or an outcome?** M1 bias in old age and chronic inflammation are mutually causal. The causal weight of polarization imbalance as a distinct hallmark remains unclear; lineage-specific genetic manipulation in aged models is needed to show that correcting polarization can delay multisystem aging.
3. **How durable is repolarization?** M1↔M2 conversion is reversible in vitro and in animals, but does epigenetic “locking” (trained immunity) in aged tissues make repolarization unsustainable? Does the anti-aging signal from Rentosertib fall after treatment stops (no data available)?
4. **Cancer risk from M2 promotion:** M2 is the immunosuppressive TAM phenotype. Would systemic M2-promoting interventions increase tumor immune escape? How should cancer surveillance be designed around polarization therapy?
5. **The human–mouse marker gap:** iNOS/Arg1 expression is weak in human macrophages. Can repolarization results from mouse models be extrapolated to humans? Humanized models and single-cell data from clinical samples are needed.
6. **The iNOS-inhibition paradox:** Inhibiting iNOS reduces nitrosative damage (anti-inflammatory side) but also weakens antimicrobial defense. Can “inflammatory M1” and “microbicidal M1” be distinguished molecularly and selectively targeted?

---

## References

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of Aging: An Expanding Universe. *Cell*. 2023;186(2):243–278. (Macrophage-polarization imbalance added in the 2023 version.)
2. Gordon S. Alternative activation of macrophages. *Nat Rev Immunol*. 2003;3(1):23–35. (M2 concept and Arg1/CD206 marker framework.)
3. Mantovani A, Sica A, Sozzani S, et al. The chemokine system in diverse forms of macrophage activation and polarization. *Trends Immunol*. 2004;25(12):677–686. (M2a/M2b/M2c classification.)
4. Mills CD, Kincaid K, Alt JM, Heilman MJ, Hill AM. M-1/M-2 macrophages and the Th1/Th2 paradigm. *J Immunol*. 2000;164(12):6166–6173. (Arginine competition: iNOS vs. Arg1.)
5. Stuehr DJ, Nathan CF. Nitric oxide. A macrophage product responsible for cytostasis and respiratory inhibition in tumor target cells. *J Exp Med*. 1989;169(5):1543–1555. (Established the antimicrobial role of iNOS.)
6. Nathan C, Ding A. Nonresolving inflammation. *Cell*. 2010;140(6):871–882. (Persistent inflammation and pathological macrophage polarization.)
7. Luneng CN, Bodzin JL, Saltiel AR. Obesity induces a phenotypic switch in adipose tissue macrophage polarization. *J Clin Invest*. 2007;117(1):175–184. (M1/M2 switch in adipose-tissue ATMs.)
8. Murray PJ, Allen JE, Biswas SK, et al. Macrophage activation and polarization: nomenclature and experimental guidelines. *Immunity*. 2014;41(1):14–20. (M1/M2 nomenclature and continuum consensus.)
9. Van Dyken SJ, Locksley RM. Interleukin-4- and interleukin-13-mediated alternatively activated macrophages: roles in homeostasis and disease. *Annu Rev Immunol*. 2013;31:317–343. (Review of the IL-4/IL-13–STAT6 pathway.)
10. O’Neill LAJ, Kishton RJ, Rathmell J. A guide to immunometabolism for immunologists. *Nat Rev Immunol*. 2016;16(9):553–565. (M1 glycolysis/succinate/HIF-1α and M2 FAO metabolic reprogramming.)
11. Jaiswal S, et al. Age-related clonal hematopoiesis associated with adverse outcomes. *N Engl J Med*. 2014;371:2488–2498. (CHIP and myeloid inflammatory bias; HR≈1.4.)
12. Ren F, et al. GENESIS-IPF Phase 2a results (Rentosertib/INS018_055). *Nature Medicine*. 2025. (NCT05938920.)
13. Exploratory anti-aging proteomic analysis of Rentosertib (42 patients, 6 clocks, suggestion of macrophage M1→M2 repolarization). *Nature Biotechnology*. 2026-09-07. (See 04-drugs/01-rentosertib.md.)
14. Elliott MR, Koster KM, Murphy PS. Efferocytosis signaling in the regulation of macrophage inflammatory responses. *J Immunol*. 2017;198(4):1387–1394. (Efferocytosis and inflammation regulation.)
15. Keren-Shaul H, et al. A unique microglia type associated with restricting development of Alzheimer’s disease. *Cell*. 2017;169(7):1276–1290. (DAM subsets and microglial dual roles.)

---

*This document is part of the LongLife “Immunity and Aging” series. Cross-references: 03-immunity/01-no-immune.md (iNOS antimicrobial function), 03-immunity/02-inflammaging.md (chronic inflammation), 03-immunity/04-immunosenescence.md (immunosenescence), 01-foundations/01-aging-hallmarks.md (12 hallmarks of aging), and 04-drugs/01-rentosertib.md (TNIK inhibition and M1→M2 repolarization).*
