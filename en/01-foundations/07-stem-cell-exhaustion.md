#Stem Cell Exhaustion

## Core concepts

Stem cell exhaustion refers to the process in which the self-renewal and differentiation potential of adult stem cells (ASCs) decline with age, leading to a decline in tissue regeneration and homeostasis maintenance capabilities. It is one of the nine hallmarks of aging proposed by López-Otín et al. in "The Hallmarks of Aging" in 2013, and is retained as the eighth "Integrative Hallmark" in the 2023 expanded version (12 items) - that is, it is the final functional collapse at the tissue level after years of accumulation of upstream damage and compensatory responses (genomic instability, epigenetic drift, mitochondrial disorders, and cellular senescence). Lineages such as hematopoietic stem cells, muscle satellite cells, neural stem cells, intestinal stem cells, and mesenchymal stem cells each show specific exhaustion trajectories, but their common characteristics are: the balance between self-renewal and differentiation is broken, quiescent state (quiescence) maintains inability, DNA damage and aging programs accumulate, and the microenvironment (niche) that supports them synchronously degrades. Stem cell exhaustion is the upstream driving event of aging-related tissue degeneration (immune decline, sarcopenia, anemia, aplasia, osteoporosis, cognitive decline), and therefore has become a key target for intervention in aging - whether and how to restore stem cell function is directly related to whether "healthspan" can be achieved. From the main line of anti-aging in this library, stem cell exhaustion is deeply coupled with the NO (nitric oxide)/NAD+ network: eNOS/NO maintains vascular niche and stem cell quiescence, and NAD+/SIRT1 determines the metabolism and apparent status of stem cells (see 01-foundations/03-no-basics.md and 04-nad-sirtuin.md for details).

```
Upstream damage (genomic/epigenetic/mitochondrial/senescent cells)
        │  accumulated over years
        ▼
  Stem cell self-renewal imbalance (quiescence loss/differentiation bias)
        │  compounded by
        ▼
  Niche degeneration (vascular aging/fibrosis/inflammation/SASP)
        │
        ▼
  Stem cell pool exhaustion → tissue regeneration failure → organ function decline
        │
        └── Interventionable nodes: epigenetic reprogramming, senolytics,
            NAD+/NO, young circulating factors, exercise
```

## 1. Panoramic view of adult stem cell system

The regenerative capacity of various human tissues is supported by different types of adult stem cells. They share the dynamic balance of "quiescence-self-renewal-differentiation", but their responses to damage and aging are significantly different.

### 1.1 Hematopoietic Stem Cell (HSC)

HSCs are located in the bone marrow and are the source of blood system regeneration and immune reconstruction. They are also the system with the most in-depth research on stem cells. The vast majority of HSCs in adult bone marrow are in a deep quiescent state (G0 phase), with only about 1–2% actively dividing at any one time. HSCs divide predominantly asymmetrically—one daughter cell remains self-renewed while the other undergoes differentiation, thereby maintaining blood homeostasis over decades. The characteristic changes of aging include: **myeloid bias** - HSC differentiation tilts towards the myeloid lineage (granulocytes, monocytes), while the production of lymphoid lineage (T/B cells) decreases, resulting in a "myeloid-dominated" pattern of the elderly immune system; **clonal hematopoiesis (CH)** - neutral phenotype clones carrying DNMT3A/TET2/ASXL1 mutations expand with age (approximately 70 years old and above) 10% of the population), although mostly benign, increase the risk of myeloid tumors and cardiovascular disease. HSC senescence is an important upstream of immunosenescence, anemia, and weakened vaccination response.

### 1.2 Muscle Satellite Cell (MuSC)

Satellite cells are located between the basement membrane and sarcolemma of mature muscle fibers and express Pax7 at rest. After activation by exercise or injury, Pax7⁺ cells proliferate, divide asymmetrically, and produce myoblasts (myoblasts) that fuse and repair muscle fibers. With age, the number of satellite cells decreases (30–60% in old muscle), their self-renewal capacity decreases, and they tend to undergo fibro-adipogenic differentiation (fibro-adipogenic transformation), directly driving sarcopenia. Human muscle biopsies confirmed significantly reduced satellite cell density and MyoD/Myf5 activation in elderly subjects.

### 1.3 Neural Stem Cell (NSC)

Adult neurogenesis is mainly limited to the subgranular layer (SGZ) of the hippocampal dentate gyrus and the subventricular zone (SVZ) of the lateral ventricles. NSCs mostly exist in a slow-cycling resting state in the SGZ, and neurogenesis decreases significantly with age (rodent hippocampal neurogenesis decreases by 80–90% with age), and the NSC pool is gradually exhausted. This is associated with memory and cognitive decline and hippocampal volume shrinkage. Although adult neurogenesis in humans is controversial (some studies suggest that human hippocampal neurogenesis is minimal and almost disappears with age), the evidence is strong in rodents, and NSC function can be partially restored by environmental enrichment, exercise, and epigenetic reprogramming.

### 1.4 Intestinal Stem Cell (ISC)

Lgr5⁺ columnar cells (crypt base columnar cells (CBC)) at the base of the intestinal villus crypts are rapidly cycling intestinal stem cells that complete self-renewal every 2–3 days and are the fastest-renewing adult stem cells in mammals. With age, the number of Lgr5⁺ stem cells decreases, Wnt signaling response weakens, and DNA damage accumulates, leading to decreased crypt regeneration capacity and intestinal barrier function. Because ISCs cycle extremely fast, they are under great pressure to repair DNA damage and are prone to accumulate mutations—which is also the basis for the high incidence of intestinal tumors.

### 1.5 Mesenchymal Stem Cell (MSC)

MSCs exist in bone marrow, fat, synovial membrane and other tissues, can differentiate into bone, cartilage, fat, muscle cells, and secrete a variety of nutritional/immune regulatory factors. The number of bone marrow MSCs decreases with age (approximately 10-fold decrease in old age), their proliferation ability is weakened, and osteogenic differentiation is biased towards adipogenic differentiation - which is directly related to osteoporosis and delayed fracture healing. MSC are also the most active adult stem cell type in cell therapy research.

## 2. Stem cell resting state and self-renewal balance

### 2.1 Molecular gatekeeping in Quiescence

The quiescent state is not "dormancy", but a reversible, strictly regulated cell cycle pause (G0 phase). It is the core strategy of stem cells to protect their own genome and prevent exhaustion. Characteristics of resting HSC: Cyclin-dependent kinase (CDK) activity is inhibited (high expression of p21Cip1 and p57Kip2), protein synthesis rate is low (but translation selectively retains self-renewal genes), mitochondrial oxidative phosphorylation activity is low and glycolysis is dominant (low ROS), and telomerase activity exists but does not continuously extend telomeres.

Key regulatory factors:
- **FoxO family**: Loss of FoxO1/3/4 causes HSCs to enter hyperactive divisions, ROS rise, and self-renewal collapse. FoxO is a downstream inhibitory target of PI3K/AKT signaling and a substrate for SIRT1 deacetylation—constituting a coupling point for nutrient sensing, metabolism, and stem cell maintenance.
- **p53/p21**: Mild activation protects the genome and maintains quiescence; excessive/long-term activation drives exhaustion or senescence.
- **Notch signaling**: maintains the undifferentiated state of HSC and inhibits myeloid differentiation bias.
- **SIRT1**: NAD+-dependent sirtuin, deacetylates FoxO and p53, maintaining stem cell stress resistance.

### 2.2 How inactivity/activation imbalance leads to exhaustion

A typical mistake of senescent stem cells is **spontaneous entry into the cell cycle** (quiescence loss): they no longer wait for damage signals, but divide frequently. This comes at a double cost: each division introduces DNA replication errors and shortens telomeres; it also depletes the "reserve of self-renewal potential." At the epigenetic level, increased H3K4me3 modifications in aging HSCs lead to early activation of the differentiation program, while H3K27me3 repression of differentiation genes is weakened—"epipolarization" causes stem cells to commit to differentiation prematurely and impairs the ability to return to a stemness state.

```
Healthy young stem cells: deep quiescence → activation on demand → self-renewal/differentiation → return to quiescence
                                    ↑ (dynamically reversible)
Aged stem cells:    spontaneous cycling → frequent division → differentiation bias → quiescence loss
                                    ↓
                    DNA damage/ROS/telomere attrition accumulate → p16/p53 activation
                                    ↓
                            senescence/apoptosis → stem cell pool exhaustion
```

## 3. The whole chain of molecular mechanism

Stem cell exhaustion is not caused by a single pathway, but is the result of multiple intrinsic and extrinsic mechanisms intertwined. The following is expanded from five levels: intrinsic damage, apparent drift, metabolic changes, niche degradation, and systemic factors.

### 3.1 DNA damage accumulation and stem cell self-renewal crisis

Adult stem cells are exposed to endogenous ROS and exogenous sources of damage throughout their lives. Although they have stronger DNA repair capabilities than differentiated cells (especially NHEJ repair), damage continues to accumulate. Key evidence: Increased γ-H2AX foci (marker of DNA double-strand breaks) in aging HSCs; premature HSC senescence in patients with Werner syndrome (WRN helicase deficiency). **Telomeres** are the core node - HSC telomeres shorten with age (human HSCs shorten by about 40–50 bp per year), and too short telomeres are recognized as DNA damage → activate p53/p21 or p16INK4a → cells enter replicative senescence. Terc⁻/⁻ (telomerase-deficient) mice exhibit collapse of HSC self-renewal and hematopoietic failure.

### 3.2 Epigenetic Drift

- **DNA Methylation**: HSCs exhibit global hypomethylation (repetitive element activation) but specific differentiation gene promoter hypermethylation with age. TET2 mutations (most common in clonal hematopoiesis) lead to abnormal maintenance of methylation.
- **Histone modifications**: Shift in the balance between H3K4me1/me3 (activating mark) and H3K27me3 (repressive mark) - H3K4me3 increases on lymphoid differentiation genes in aging HSCs, "locking" the cells in myeloid bias. EZH2 (H3K27 methyltransferase) activity decreases with age, disrupting differentiation inhibition.
- **Chromatin remodeling**: Heterochromatin in aging stem cells relaxes (H3K9me3 is lost), and repeated element (LINE-1, Alu) transposition is activated, further creating genomic instability.
- **Feasibility of epigenetic reprogramming**: Partial expression of OSKM (Oct4/Sox2/Klf4/c-Myc) can reverse these epigenetic changes in vivo – a central hope for intervention to restore stem cell function (see Section 5).

### 3.3 Metabolic changes and the role of mitochondria in fate determination

Stem cells’ metabolic patterns determine their fate:
- **Young quiescent stem cells** are mainly glycolytic, have a small number of mitochondria but maintain fused state, and low ROS - protecting the genome and maintaining stemness.
- **Aging stem cells** shift toward oxidative phosphorylation (OXPHOS), excessive mitochondrial fragmentation (Drp1-led fragmentation), and increased ROS. ROS oxidizes DNA/protein → activates p16/p53 → senescence; at the same time, high ROS forces stem cells to exit quiescence prematurely and enter differentiation, accelerating reservoir depletion.
- **Asymmetric distribution of mitochondria in asymmetric division**: When stem cells divide asymmetrically, the daughter cells that maintain stemness inherit the "old" low-activity mitochondria, and the differentiated daughter cells inherit newer, highly active mitochondria. This "mitochondrial polarity" is damaged with age - stem cells can no longer eliminate damaged mitochondria and their ability to self-renew decreases.

### 3.4 Aging pathway: depletion of stem cell pool by p16INK4a/p53

- **p16INK4a**: Age-specific up-regulation in stem cells of multiple tissues (bone marrow, muscle, brain, skin). p16 inhibits CDK4/6 → Rb hypophosphorylation → blocks G1/S. p16⁺ Stem cells are not necessarily "senescent cells," but excessive p16 renders stem cells less regeneratively responsive. Eliminating p16⁺ cells (senolytics) or inhibiting p16 partially restores aged HSC and satellite cell function.
- **p53/p21**: The dosage effect of p53 is subtle - moderate activation protects the genome, overactivation (e.g. under long-term DNA damage stress) leads to irreversible quiescence/senescence. High p21 expression is associated with HSC functional decline.
- **SASP's bystander effect**: IL-6, TNF-α, TGF-β, etc. secreted by senescent stem cells/niche cells induce senescence or biased differentiation of neighboring stem cells through paracrine, forming "senescence spread".

### 3.5 Microenvironment (Niche) degradation - external determinism

Stem cells cannot be discussed separately from niche. Aging of bone marrow, muscle, intestinal crypts, and perivascular niches is an important (or primary) driver of stem cell exhaustion:
- **Vascular niche (vascular pericytes/endothelial cells)**: Endothelial cell senescence → Decreased eNOS activity → Decreased NO production → Changes in vascular permeability and reduced blood flow, weakening the nutrition and oxygen supply to HSCs/MSCs. This is the core intersection of the NO pathway and stem cell depletion (see Section 7).
- **Fibrosis**: Bone marrow fibrosis (COL1A1 deposition), muscle fiber fatification, tissue stiffness (ECM cross-linking) compress stem cell space and alter mechanotransduction (YAP/TAZ), inducing changes in stem cell function.
- **Inflammation/SASP**: Inflammatory factors reshape the niche microenvironment and inhibit stem cell regeneration.
- **Paracrine signaling attenuation**: Downregulation of niche-derived factors such as Notch ligands (Jagged, Delta), Wnt, bone morphogenetic protein (BMP), etc.

### 3.6 Stem maintenance signal: Wnt / Notch / Hedgehog

- **Wnt/β-catenin**: Wnt binds Frizzled/LRP → stabilizes β-catenin → enters the nucleus and activates self-renewal genes. Wnt signaling responses decrease in senescent stem cells, resulting in insufficient HSC self-renewal. But overactivation of Wnt can lead to malignant proliferation—dose balance is key.
- **Notch**: Notch is activated by adjacent cell contact → the intracellular domain NICD enters the nucleus → transcribes Hes/Myc to maintain undifferentiation. Notch signaling is decreased in aged HSCs, associated with reduced lymphopoiesis.
- **Hedgehog (Shh)**: Involved in the activation of MSC osteoblasts and satellite cells, the signal weakens with age, affecting bone and muscle regeneration.

### 3.7 Systemic (circulating) factors—the discovery of heterochronic symbiosis

**Heterochronic parabiosis** experiments reveal the system-level regulation of stem cells by circulating factors: Conboy's team demonstrated in *Nature* in 2005 that after conjoined circulation of old and young mice, the proliferation ability of old muscle satellite cells and liver stem cells was restored. The reverse experiment (young mice connected to old blood) accelerated the aging of stem cells in young mice. This demonstrates that stem cell exhaustion is at least partially **reversible**, driven by circulating "youth/aging factors." Identified candidate factors include GDF11 (controversial), osteopontin (Osteopontin), CCL11 (pro-aging), TGF-β, and others.

## 4. Grading of evidence

| Phenomenon | Level of evidence | Key documents/experiments |
|---|---|---|
| Adult stem cell function declines with age (HSC/MuSC/NSC/ISC/MSC) | I (consistent across multiple species and tissues) | Rossi 2008; Schultz & McCormick 1994 |
| HSC myeloid-biased differentiation and clonal hematopoiesis | I (human + mouse) | Beerman 2010; Jaiswal 2014 |
| Loss of HSC quiescence, spontaneous entry into cycles | II (mouse causation + human association) | Rossi 2007; Flach 2014 |
| Metachronic symbiosis restores aged stem cell function | II (mouse causality) | Conboy 2005 *Nature* |
| niche/vascular senescence drives stem cell exhaustion | II (mouse transplantation experiment) | Kopp 2005; Maryanovich 2018 |
| p16 clearance/inhibition restores stem cell function | II (mouse) | Baker 2016; Sousa-Victor 2014 (satellite cells) |
| OSKM partial reprogramming to restore stem cells | II (mouse, human in vitro) | Ocampo 2016 *Cell*; Lu 2020 *Nature* |
| eNOS knockout impairs HSC function | II (mouse) | North 2004 |
| NAD+ precursors restore stem cell function | II (mouse) | Zhang 2016 (NSC); Sun 2021 |
| Exercise improves satellite cell/NSC function in the elderly | I (human muscle biopsy + imaging) | Multiple RCTs |
| Mesenchymal stem cell "anti-aging" treatment | III (mechanism speculated, clinical evidence is weak) | Controversy |
| Human stem cell transplantation for anti-aging | IV (no evidence, high risk) | — |

Level of evidence: I=consistent across multiple species/multiple studies; II=animal causation + human association; III=human observation/mechanism speculation; IV=individual case/in vitro.

## 5. Clinical and experimental evidence details

### 5.1 OSKM partial reprogramming restores stem cell function (epigenetic reprogramming)

In 2016, Ocampo et al. reported in *Cell* that transient (2-4 day periodic) expression of four OSKM factors in vivo can reverse the epiclock in progeria mice (Lmna mutation, Zmpste24 deficiency), restore stem cell functions in various tissues, and extend the health period. The mechanism is to reset the epigenome (DNA methylation, histone modifications) to a youthful state without triggering tumorigenic dedifferentiation. Follow-up research expansion:
- **Lu 2020 (*Nature*)**: The axonal regeneration ability of mouse retinal ganglion cells was significantly restored after short-term expression of OSKM (the youthful apparent state supports the regeneration program), and vision was partially restored.
- **Chen 2021 (*Cell Stem Cell*)**: OSKM restores the regenerative capacity and muscle strength of muscle stem cells (satellite cells) in aged mice.
- **In vivo reprogramming involving CRISPR**: Multiple studies around 2023 exploring safer reprogramming strategies (single factors, transcription factor variants, non-tumorigenic combinations).
- **Risk**: Long-term/overexpression of OSKM can induce teratoma or cell transformation, and the safety margin is a core obstacle to transformation.

### 5.2 Heterochronic symbiosis and young circulating factors

- **Conboy 2005 (*Nature*)**: In old-young conjoined mice, the proliferation of old muscle satellite cells and liver cells returned to young levels.
- **GDF11 Controversy**: Loffredo 2015 (*Cell*) reported that GDF11 restored elderly heart and muscle function; however, multiple studies by Egerman 2015 and 2019 questioned whether GDF11 actually inhibits muscle regeneration, and the early results may be due to the detection method. The "young factor" status of GDF11 has been falsified, reminding that research on circulating factors requires rigorous verification.
- **Osteopontin (OPN)**: OPN in the bone marrow niche decreases with age, and OPN supplementation can partially restore the function of elderly HSCs (Stier 2005; Guidi 2017).
- **CCL11 (Eotaxin)**: Elevated CCL11 in the blood of older adults impairs neurogenesis (Villeda 2011, *Nature*) - the poster child for "aging factors".
- **GDF11, TGF-β**: Chronic activation of the TGF-β pathway inhibits satellite cell activation and inhibition of TGF-β receptors (SB-431542) restores aged muscle regeneration (Carlson 2008).
- **Plasma exchange**: 2020s mouse studies (Conboy team) show that diluting old blood with albumin buffer (simulating young circulation) can restore tissue regeneration, suggesting that "diluting pro-aging factors" rather than "replenishing youthful factors" may also be a viable strategy.

### 5.3 senolytics and p16 pathway intervention

- **INK-ATTAC mice** (Baker 2016, *Nature*): Transgenic elimination of p16⁺ senescent cells extends the median lifespan by about 25% and delays functional decline in tissues such as kidneys, heart, fat, etc. - indirectly supporting the elimination of senescent stem cells/niche cells to preserve stem cells.
- **Satellite cell-specific p16 regulation**: Sousa-Victor 2014 (*EMBO J*) demonstrated increased p16/p21 expression and decreased self-renewal in aging muscle satellite cells, and inhibition of p16 restored its function.
- **Human senolytics**: Dasatinib + quercetin (D+Q) has been shown to clear senescent cells and reduce inflammatory markers in small-scale trials such as idiopathic pulmonary fibrosis; however, there are no direct human trials on "stem cell exhaustion" itself.

### 5.4 Clinical status of stem cell transplantation and cell therapy

- **Hematopoietic stem cell transplantation (HSCT)**: Clinically mature (for the treatment of leukemia, lymphoma, aplastic anemia, some immune deficiencies), but lacks evidence as an "anti-aging" intervention and is extremely risky (pre-treatment chemotherapy toxicity, GVHD, infection). **Autologous HSC transplantation to improve immune senescence** is still under preclinical exploration.
- **Mesenchymal stem cell (MSC) therapy**: There are a large number of clinical trials around the world (osteoarthritis, graft-versus-host disease, myocardial infarction, spinal cord injury, etc.). MSC mainly function through **paracrine** (secretion of nutritional factors, immune regulation) rather than direct differentiation into target tissues. **Anti-Aging Applications**: Intravenous infusion of MSCs improves age-related phenotypes in multiple organs in animals, but human evidence is limited, lacks standardization (source, dose, batch), and carries risks such as pulmonary embolism. Most of the "stem cell anti-aging" products on the market are exaggerated marketing, so be careful.
- **iPSC-derived cells**: Induced pluripotent stem cells (iPSC) can differentiate into HSCs, dopaminergic neurons (Parkinson's treatment has entered early clinical trials), retinal pigment epithelium (macular degeneration, Japan's RIKEN has carried out), cardiomyocytes, β-cells, etc. iPSCs provide a source of "younger" cells (apparent reprogramming to an embryonic state), but have risks of tumorigenicity (residual undifferentiated cells) and immune rejection, and are extremely costly.
- **CAR-T cell therapy**: Autologous T cells are genetically engineered in vitro and reinfused to treat hematological tumors, which is the most successful example of cell therapy. The decline in T cell function (quiescence, expansion, memory) in elderly patients affects the efficacy of CAR-T - which inversely indicates the constraints of immunosenescence on cell therapy.

### 5.5 Exercise and lifestyle intervention (strongest evidence in humans)

- **Exercise**: Endurance and resistance training significantly increase the number and activation capacity of satellite cells in aged muscles (human biopsy evidence); aerobic exercise promotes markers related to hippocampal neurogenesis (increased brain-derived neurotrophic factor BDNF). Exercise also improves bone marrow niche blood flow and vascular function.
- **Caloric restriction**: CR animals prolong HSC self-renewal and improve resting maintenance; human CR (CALERIE trial) improves multiple metabolic and immune indicators.
- **NAD+ precursor**: NMN/NR restores muscle stem cell and neural stem cell function in mice (SIRT1-dependent), and the long-term effects in humans await RCT.

## 6. Contact with NO / NAD+ / longevity network

Stem cell depletion forms a triple coupling with the NO and NAD+ pathways, which is the intervention lever emphasized in this library:

### 6.1 NO maintains vascular niche and HSC quiescence

- **Enecessity of eNOS/NO for HSCs**: North 2004 (*Nature*) demonstrated that eNOS knockout mice had impaired HSC homing and self-renewal, and failed hematopoietic reconstitution; eNOS-mediated NO is a key signal for HSC mobilization from bone marrow to peripheral blood.
- **NO maintains HSC quiescence**: NO inhibits HSC from spontaneously entering the cycle through the cGMP-PKG pathway and maintains deep quiescence; NO bioavailability decreases with age → HSC quiescence is lost → depletion is accelerated.
- **Vascular-Stem Cell Axis**: Endothelial cells are the components of the HSC/MSC niche, and decreased eNOS activity (endothelial senescence) directly weakens the hematopoietic support function of the niche. Exercise up-regulates eNOS → NO↑ → improves niche blood flow and stemness maintenance - one of the molecular explanations of "exercise anti-aging".
- **NO Antioxidant Protection**: Low concentrations of NO inhibit mitochondrial complex IV (reversibly), reduce electron leakage and ROS, and protect stem cell genomes from oxidative damage.

### 6.2 NAD+/SIRT1 determines stem cell metabolism and appearance

- **NAD+ decrease**: NAD+ levels decrease by about 50% in aging (PARP, CD38, NMNAT activity changes), and SIRT1/3 activity decreases accordingly.
- **SIRT1 and stem cells**: SIRT1 deacetylates FoxO, p53, and PGC-1α, maintaining HSC stress resistance and quiescence; SIRT1 decreases → FoxO hyperacetylation → HSC quiescence is lost. NAD+ precursor (NMN) restores HSC and muscle stem cell function in mice via SIRT1.
- **SIRT3 (mitochondria)**: deacetylates and activates SOD2 and complex I, reducing stem cell ROS and protecting stemness. NAD+ precursor increases SIRT3 activity → stem cell mitochondria return to fusion state and ROS decreases.
- **Epiphanic reprogramming and NAD+**: SIRT1 is one of the important mediators of OSKM partial reprogramming, and NAD+ can fully improve the efficiency and safety of reprogramming.

### 6.3 Crossover node between NO and NAD+

eNOS produces NO while maintaining vascular health; NAD+/SIRT is an important effector of NO signaling (NO activates sGC→cGMP→PKG, indirectly upregulating NAD+ synthesis and SIRT activity); and NO protects the NAD+ pool by maintaining mitochondrial function. The three form a positive feedback "blood vessel-mitochondria-stem cell" protective loop (see 01-foundations/03-no-basics.md and 06-mitochondria.md for details). In terms of intervention strategies, exercise (dual activation of eNOS/NO and mitochondrial biogenesis) is the safest means to simultaneously improve NO and NAD+ status.

## 7. Intervention directions and executable suggestions

### 7.1 Lifestyle (the strongest evidence and safest)
1. **Exercise** (aerobic + resistance): Increase satellite cell activation, improve bone marrow and muscle niche blood flow (eNOS/NO↑), and promote neurogenesis. ≥150 minutes of moderate intensity + 2 resistance sessions per week.
2. **Caloric restriction/intermittent fasting**: Improve HSC resting maintenance and reduce metabolic load; animal evidence is sufficient, and human benefits are mainly metabolic and immune indicators.
3. **Sleep and Stress Reduction**: Chronic stress increases glucocorticoids and inhibits HSC/satellite cell proliferation; ensure 7–8 hours of sleep.
4. **Avoid cumulative damage**: quit smoking (cigarette ROS/inflammation accelerates stem cell depletion), limit alcohol, and control blood sugar fluctuations (AGEs damage niche).

### 7.2 Drugs and nutritional supplements (based on animal evidence, please be cautious with humans)
5. **NAD+ precursor** (NMN/NR): Improves SIRT1/3 activity and restores stem cell metabolism and appearance; long-term human safety awaits RCT.
6. **Senolytics** (D+Q, Fisetin, etc.): remove senescent niche cells and indirectly protect stem cells; human body evidence is early and cannot be used by yourself.
7. **mTOR inhibition/AMPK activation** (rapamycin, metformin, spermidine): restore nutrient sensing balance, which is beneficial to stem cell quiescence and autophagy cleanup.
8. **NO Supply**: Regular exercise is optimal; evidence for stem cell protection from nitrate/arginine supplementation is limited.

### 7.3 Cutting-edge regenerative medicine (in clinical translation, not a daily recommendation)
9. **Appear reprogramming** (OSKM partial reprogramming): The most promising "rejuvenation" technology, but the safety margin (tumorigenicity) has not been resolved.
10. **iPSC-derived cell transplantation**: Specific tissue regeneration (neurons, β-cells, etc.) has entered clinical practice; anti-aging systemic application is still far away.
11. **MSC infusion**: There is some evidence for specific diseases (osteoarthritis, GVHD); as a "systemic anti-aging", the evidence is insufficient and the standards are missing.
12. **Young circulating factor/plasma exchange**: Exploratory, more human data are needed.

## 8. Open issues and controversies

1. **Reversibility Boundary**: Heterochronic symbiosis and epigenetic reprogramming demonstrate that stem cell exhaustion can be partially reversed, but the extent, tissue specificity, and duration of reversal are unknown. Is stem cell depletion reversible in all tissues?
2. **Safety of Reprogramming**: The tumorigenic risk of OSKM reprogramming in vivo, the long-term effects of apparent overresetting, and the impact on immune surveillance have not been addressed. How to reset the "age appearance" without triggering dedifferentiation?
3. **Causal hierarchy**: Is stem cell exhaustion an "integrated consequence"? Is it an inevitable result of upstream markers (genome, epitope, mitochondria, senescent cells), or is it an independent driver in itself? Can interfering with stem cells counteract upstream markers?
4. **Cell Therapy Bubble**: Most of the "stem cell anti-aging", "placental stem cells" and "umbilical cord blood transfusion" products on the market lack strict clinical evidence and are poorly regulated. How to distinguish formal cell therapy from marketing traps?
5. **Lessons from GDF11**: The discovery and "falsification" cycle of circulating factors exposes the reproducibility crisis in aging biology research - the lack of independent verification of many "young factors". This serves as a reminder to be cautious about anti-aging claims for any single factor.
6. **The Paradox of Clonal Hematopoiesis**: Clonal expansion of neutral mutations (CH) in aging HSCs not only carries the risk of malignant transformation, but may also reflect the body's compensatory "survivor clones" - will eliminating CH clones be counterproductive?

## References

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. The Hallmarks of Aging. *Cell* 2013;153:1194–1217.
2. López-Otín C, et al. Hallmarks of aging: An expanding universe. *Cell* 2023;186:243–278.
3. Conboy IM, et al. Rejuvenation of aged progenitor cells by exposure to a young systemic environment. *Nature* 2005;433:760–764.
4. Ocampo A, et al. In Vivo Amelioration of Age-Associated Hallmarks by Partial Reprogramming. *Cell* 2016;167:1719–1733.
5. Lu Y, et al. Reprogramming to recover youthful epigenetic information and restore vision. *Nature* 2020;588:124–129.
6. North TE, et al. Hematopoietic stem cell function is regulated by eNOS. *Nature* 2004;432:1096–1100.
7. Rossi DJ, et al. Deficiencies in DNA damage repair limit the function of haematopoietic stem cells with age. *Nature* 2007;447:725–729.
8. Baker DJ, et al. Naturally occurring p16(Ink4a)-positive cells shorten healthy lifespan. *Nature* 2016;530:184–189.
9. Villeda SA, et al. The ageing systemic milieu negatively regulates neurogenesis and cognitive function. *Nature* 2011;477:90–94.
10. Sousa-Victor P, et al. Geriatric muscle stem cells switch reversible quiescence into senescence. *Nature* 2014;506:316–321.
11. Flach J, et al. Replication stress is a potent driver of functional decline in aging haematopoietic stem cells. *Nature* 2014;512:198–202.
12. Jaiswal S, et al. Age-related clonal hematopoiesis associated with adverse outcomes. *N Engl J Med* 2014;371:2488–2498.
13. Zhang H, et al. NAD+ repletion improves mitochondrial and stem cell function and enhances life span in mice. *Science* 2016;352:1436–1443.
14. Ocampo A, et al. Stem cell exhaustion. *Cell* 2016 (Review of Partial Reprogramming) - Volume to be verified.
15. Maryanovich M, et al. Adrenergic nerve degeneration in bone marrow drives aging of the hematopoietic stem cell niche. *Nature Medicine* 2018;24:782–791.