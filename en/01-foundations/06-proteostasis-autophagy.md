# Proteostasis & Autophagy: Aging and Intervention in Protein Quality Control Networks Proteostasis & Autophagy

## Core concepts

Proteostasis refers to the dynamic balance in which cells maintain the correct folding, positioning and degradation of proteins. It is collaboratively maintained by the protein quality control network (PQC network) composed of three major subsystems: molecular chaperones, ubiquitin-proteasome system (UPS) and autophagy-lysosome pathway. This concept was proposed by Balch, Morimoto, Dillin and Kelly in the *Science* system in 2008 ("Adapting proteostasis for disease intervention"): the PQC network is a highly integrated, mutually compensatory "folding-refolding-degradation" decision-making system. During aging, the overall PQC network collapses (proteostasis collapse) - the activity of the synthetic end is reduced, the degradation end is overloaded, and the endoplasmic reticulum stress response is slowed - misfolded proteins accumulate and aggregate, directly driving neurodegenerative diseases such as Alzheimer's disease (AD), Parkinson's disease (PD), and amyotrophic lateral sclerosis (ALS). It is the ** No. 4 in the aging hallmark framework of "Cell" by López-Otín et al. in 2013/2023. No. Primary Injury Marker**. The special thing about the loss of proteostasis is that it is one of the most interventionable signs of ** drugs at present (rapamycin, spermidine, and NAD+ precursors all work by enhancing degradation or repair networks), and it is also the core hub connecting nutrient sensing (mTOR/AMPK), mitochondrial function (mitophagy) and chronic inflammation (aggregate activation of NLRP3).

## 1. The whole chain of molecular mechanism

### 1. Folding network: from nascent peptides to native conformations

Newly synthesized proteins expose hydrophobic residues in an unfolded state in the ribosome exit channel, making them prone to incorrect aggregation. The first step of folding is completed by the **HSP70 system**: Hsp40 (DnaJ family, about 40 species) recognizes and delivers the unfolded substrate to Hsp70 (HSPA1A/1B), stimulating its ATPase activity, converting Hsp70 from an ATP-bound state (low affinity) to an ADP-bound state (high affinity), stabilizing the hydrophobic core of the substrate and preventing aggregation. The substrate can then be taken over by the **HSP90 system** to complete late folding - HSP90 relies on ATP hydrolysis to drive conformational maturation, and is assembled into a mature complex through auxiliary chaperones (co-chaperones) such as HOP and p23. Its client proteins include steroid hormone receptors, kinases (Akt, CDK4) and other about 10% of the protein group; while the **chaperone protein TRiC/CCT** (containing TCP-1 The barrel-shaped structure) is responsible for the de novo folding of about 10% of cytosolic proteins such as actin and tubulin. Proteins that fail to fold are determined to enter the degradation branch by the E3 ligase CHIP (STUB1, which contains a TPR domain and can bind Hsp70/Hsp90 at the same time) - **The shunt decision of "refolding or degradation" occurs at the Hsp70/CHIP node**.

Aging makes the folding network bear the brunt: HSF-1 (heat shock transcription factor 1) activity decreases with age, leading to a decrease in Hsp70/Hsp90/Hsp40 transcription; at the same time, aggregates absorb a large number of chaperone proteins through a "sponge effect", further depleting the available chaperone pool (sequestration), forming a vicious cycle.

```
   Ribosome exit ──> Hsp40/Hsp70 ──> Hsp90 ──> Native conformation
                     │  (ADP state high affinity)   │ failure
                     │ refolding attempt            ▼
                     └────────── CHIP(Hsp70/E3) ──> K48-polyubiquitin chain ──> 26S proteasome
                     (folding-degradation triage decision node)
```

### 2. Degradation channel one: Ubiquitin-proteasome system (UPS)

UPS is responsible for degrading approximately 80% of intracellular proteins (short-lived proteins and soluble misfolded proteins) and is the "main degrader" of PQC. The degradation chain is a three-stage enzymatic cascade:

**E1 (UBA1, activating enzyme) → E2 (about 40 kinds, conjugating enzymes, such as UbcH5) → E3 (ligases, more than 600 kinds, determine substrate specificity) → 26S proteasome. **

E3 ligases are divided into three categories according to their structures: RING type (such as MDM2, SCF complex, CHIP - directly catalyzes the transfer of ubiquitin from E2 to the substrate), HECT type (such as NEDD4 - first forms the E3-ubiquitin thioester intermediate), and RBR type (such as Parkin - a mixed mechanism of RING and HECT). After the substrate is added with more than 4 polyubiquitin chains linked by **K48**, it is recognized by the 26S proteasome: the 19S regulatory particle (the Rpt1-6 ATPase loop of base is responsible for substrate unfolding and transport, and lid is responsible for deubiquitination) linearizes the substrate and sends it into the barrel cavity of the 20S core particle, which is composed of β1 (caspase-like), β2 (trypsin) Three catalytic subunits, β5 (chymotrypsin-like) and β5 (chymotrypsin-like), are degraded into peptide fragments of 3-22 amino acids. Among them, the **β5 subunit is the rate-limiting link** and is also the site of the most significant decrease in activity during aging (see below). p97/VCP acts as a "segregase" to extract ubiquitinated substrates from the endoplasmic reticulum (ERAD pathway) or membranes and deliver them to the proteasome - **VCP mutations directly cause inclusion body myopathy with Paget bone disease and frontotemporal dementia (IBMPFD)**, which is human genetic evidence of neurodegeneration caused by UPS deficiency.

### 3. Degradation channel two: autophagy-lysosome system

Autophagy handles cargo that is difficult for UPS to reach: protein aggregates, damaged organelles, and long-lived proteins. It is divided into three forms—macroautophagy, chaperone-mediated autophagy (CMA), and microautophagy**.

**Molecular cascade (core chain) of macroautophagy**:

```
Nutrient-rich: mTORC1 --phosphorylates--> ULK1(Ser757) ──inhibits──┐
                                                ▼
Energy-low/stress: AMPK --phosphorylates--> ULK1(Ser317/777) ──activates──> ULK1 complex
                                             (ULK1-FIP200-ATG13-ATG101)
                                                │ nucleation
                                                ▼
                                Beclin1-VPS34-VPS15-ATG14L (produces PI3P)
                                                │ membrane elongation
                                                ▼
              ATG12-ATG5-ATG16L1 conjugation system + LC3-II(ATG4 cleaves proLC3,
              ATG7/ATG3 catalyze LC3-I lipidation to LC3-II anchored on double membrane)
                                                │ cargo wrapping
                                                ▼
                    STX17-SNAP29-VAMP8 SNARE complex + Rab7/HOPS
                    Autophagosome fuses with lysosome ──> acid hydrolase degradation ──> amino acid recycling
```

Key regulatory node: **ULK1 is the intersection of mTORC1 and AMPK** - mTORC1 phosphorylates ULK1 Ser757 to inhibit the initiation of autophagy, and AMPK phosphorylates Ser317/777 to activate the initiation of autophagy (Kim et al. 2011 *Nat Cell Biol*). "Throttle and brake" directly collide. Selective autophagy is mediated by cargo receptors: **p62/SQSTM1** (UBA domain binds ubiquitination substrates, LIR domain binds LC3) mediates aggrephagy (aggrephagy); **PINK1-Parkin pathway** mediates mitophagy - after mitochondrial depolarization, PINK1 is stabilized in the outer membrane, recruits and phosphorylates and activates Parkin, and Parkin ubiquitinates MFN1/2, VDAC and other outer membrane proteins, and is p62/OPTN/NDP52 is linked to LC3 to complete clearance; OPTN mutations also cause ALS. **CMA** is recognized by cytosolic HSC70 as the KFERQ pentapeptide motif in the substrate, and is translocated into the lumen for degradation via the lysosomal membrane receptor LAMP-2A.

### 4. Endoplasmic reticulum stress and unfolded protein response (UPR three arms)

Secreted and transmembrane proteins (neuronal receptors, insulin of pancreatic β-cells, etc.) fold in the lumen of the endoplasmic reticulum (ER) and are particularly sensitive to imbalances in proteostasis. When unfolded proteins accumulate in the ER lumen, the molecular chaperone BiP/GRP78 dissociates from three sensors and activates **three signaling arms**:

- **IRE1α arm**: RNase active splicing of XBP1 mRNA produces active transcription factor XBP1s, which upregulates chaperone and lipid synthesis genes; at the same time, it degrades erroneous mRNA on the ER through the RIDD mechanism. IRE1α is the most conserved and earliest evolved arm.
- **PERK arm**: Phosphorylated eIF2α → global translation pause (reduced protein influx) + selective translation of ATF4 → up-regulation of CHOP and amino acid metabolism genes; if stress persists, CHOP drives a pro-apoptotic program (CHOP/Bax axis).
- **ATF6 arm**: translocates to the Golgi apparatus and is cleaved by S1P/S2P proteases to release active transcription factors and upregulate ERAD components and partners.

The biological logic of the UPR is "compensate first, then abandon the car to save the handsome": During acute stress, the three arms work together to restore homeostasis (adaptive UPR), while chronic irreversible stress turns to apoptosis (terminal UPR). **Ageing blunts the UPR response (UPR activation threshold increases and amplitude weakens)**, and the folding load of secretory cells (neurons, β cells) cannot be compensated for a long time - Taylor and Dillin found that specific overexpression of XBP1s in C. elegans neurons can extend lifespan by about 30-40%, proving that UPR activity itself is one of the determinants of longevity (*Cell* 2013). The mitochondrial counterpart UPRmt (ATF5, HSP60, LONP1, etc.) is responsible for the quality monitoring of mitochondrial matrix proteins, and together with mitophagy, constitutes a double-layer defense line for mitochondrial PQC.

### 5. Collapse nodes of the proteostasis network in aging

Combining multi-species evidence, PQC decline with age does not decay uniformly, but is concentrated at the following identifiable nodes:

| Nodes | Changes with age | Consequences |
|---|---|---|
| HSF-1 transcriptional activity | ↓ (approximately 30-50%) | Insufficient chaperone protein synthesis |
| 26S proteasome activity | ↓ (actually measured decrease in human tissue is 30-50%, mainly β5 subunit) | Degradation of short-lived proteins slows down, and oxidative damage proteins accumulate |
| Lysosomal acidification | v-ATPase function decreases → lysosomal pH increases | Acid hydrolase activity decreases significantly, and the "last mile" of degradation fails |
| Lipofuscin | accumulates year by year and occupies the lysosomal cavity (old myocardium/neurons can occupy 30-70% of the volume) | Physically blocks autophagosome-lysosome fusion and degradation |
| CMA (LAMP-2A) | LAMP-2A receptor levels decreased by approximately 50% (Cuervo & Dice 2000) | CMA substrate (GAPDH, α-synuclein, etc.) clearance decreased |
| TFEB nuclear translocation | mTORC1 phosphorylates TFEB(Ser211), causing it to remain in the cytoplasm, and nuclear translocation is blocked | Insufficient transcription of lysosome biogenesis genes (the "master switch" for lysosome production) |
| Autophagosome-lysosome fusion | Decreased function of SNARE (STX17) and Rab7 | Autophagosome accumulation without increased degradation (a sign of decreased flux) |

Key concept: **Autophagic flux** refers to the net clearance rate of the entire process of "formation-fusion-degradation", not the number of autophagosomes - aging and most pathological conditions are characterized by **increased autophagosome formation (compensation) and blocked fusion and degradation**. Measuring only the total amount of LC3-II will misjudge an increase in flux, and a chloroquine/bafilomycin blocking experiment or mCherry-GFP-LC3 tandem fluorescent reporter gene is required to distinguish. The increase in lysosomal pH is the core hub of flux decline: it simultaneously reduces hydrolase activity, weakens autophagosome fusion and CMA efficiency, and is causally related to lipofuscin accumulation - damaged lysosomes release cathepsins into the cytosol to activate the NLRP3 inflammasome, directly linking the loss of protein homeostasis with markers of chronic inflammation.

## 2. Misfolded protein aggregation and neurodegeneration

The most serious consequence of PQC collapse is the phase separation and aggregation of **amyloid-rich β-sheet conformations** across the energy barrier of "soluble-oligomer-fibril-mature fibril":

- **Aβ (AD)**: APP is sequentially cleaved by β-/γ-secretase to produce Aβ40/Aβ42, which is more hydrophobic and easier to aggregate; APP gene duplication and PSEN1/PSEN2 mutation (increased Aβ42/40 ratio) genetically confirm that Aβ is the initial driver of AD (amyloid cascade hypothesis).
- **Tau (AD/FTD)**: MAPT gene mutations directly cause frontotemporal lobe dementia; in AD, Tau is hyperphosphorylated (PHF-tau) to form neurofibrillary tangles and exhibit "prion-like" anatomical spread (Braak stage).
- **α-synuclein (PD)**: SNCA gene duplication/triploidy and A53T mutation cause PD; Lewy bodies have α-synuclein fibers as the core, and S129 phosphorylation is a pathological hallmark.
- **TDP-43 (ALS/FTD)**: Abnormal nuclear-cytoplasmic transport, cytosolic TDP-43 forms stress granule-like aggregates and loses nuclear function.
- **Huntingtin (HD)**: The HTT gene CAG repeat expansion produces polyQ protein, and R6/2 transgenic mice are the classic model.

Classic evidence of **genetic causal chain** (aggregates → neurodegeneration): mice with essential autophagy knockout genes directly develop neurodegeneration - Hara et al. and Komatsu et al. reported in *Nature* at the same time in 2006 that mice with neural-specific knockout of Atg5 or Atg7 developed movement disorders, ubiquitin-positive inclusions and neuronal death; Komatsu 2007 further proved that p62 is a key adapter molecule for inclusion formation. On the contrary, **individuals with genetically enhanced autophagy have not been found in humans, but Atg7 overexpression has been shown to improve age-related pathologies in some mouse models** (mechanistic research stage). Toxic form debate: Multiple lines of evidence point to soluble oligomers (rather than mature fibers) as the primary toxic entity - oligomers insert into membranes, aberrantly activate NMDA receptors/synaptic receptors, recruit and misfold native proteins (seeding); this explains why simple removal of fibers (antibodies such as Aduhelm) has limited clinical benefit (see details of the evidence).

## 3. Evidence classification

| Phenomenon | Level of evidence | Key documents |
|---|---|---|
| PQC network (chaperones/UPS/autophagy) overall declines with age | Solid hammer (consistent across species: yeast-nematode-drosophila-mouse-human tissue) | Balch 2008 Science; Cuervo & Dice 2000 |
| Deletion of genes essential for autophagy (Atg5/Atg7 KO) causes neurodegeneration | Real hammer (mouse genetics cause and effect) | Hara 2006 Nature; Komatsu 2006 Nature |
| Autophagy induction (CR/rapamycin/spermidine) extends the lifespan of model organisms | Real hammer (cross-species, rapamycin is double-blindly verified by NIA ITP) | Harrison 2009 Nature; Eisenberg 2009 |
| Chaperone/UPR transcription factor overexpression (HSF-1, XBP1s) extends lifespan | Real Hammer (Caenorhabditis elegans Genetics) | Hsu 2003 Science; Taylor & Dillin 2013 Cell |
| Proteasome activity decreases by 30-50% with age | Strong correlation (actual measurement in human tissue, clear mechanism direction) | Series of studies by Grune and others |
| Aggregated proteins are causally linked to neurodegeneration | Strong (genetics APP/SNCA/MAPT/HTT + pathology; but "clear is gain" translation is poor) | van Dyck 2023 NEJM (lecanemab has limited effect) |
| Autophagy inducers improve human cognition/metabolism | Preliminary (small RCT, marker level, small sample to be repeated) | Schwarz 2022 JAMA Netw Open; Kars 2010 Diabetes |
| Rebuilding the rejuvenated PQC network reverses the aging phenotype | Moderate (animal model: restoring CMA improves liver function in the elderly) | Zhang & Cuervo 2015 Sci Transl Med |

Description of evidence level: I=randomized control/consistent across multiple species; II=animal model causation + human correlation; III=human observation/mechanism speculation; IV=case/in vitro.

## 4. Clinical/experimental evidence details

**Rapamycin (NIA ITP project, the strongest evidence for autophagy-induced life extension)**: Harrison et al. reported in *Nature* in 2009 that feeding genetically heterogeneous (UM-HET3) mice with an immunosuppressive dose of rapamycin (14 ppm feed) starting from 600 days of age (approximately equivalent to 60 years old in humans) extended the median lifespan of males by 9% and females by 14% (Miller 2011 reported from 9 Dosing at 1 month of age increases the prolongation by 18% for females and 10% for males). Mechanistically, rapamycin binds to FKBP12 and inhibits mTORC1, relieves its phosphorylation inhibition of ULK1(Ser757) and TFEB, and reverses translation flux - this is the strongest pre-human evidence for "life extension through enhanced proteostasis" in a randomized, multicenter (3 ITP sites) setting. Bjedov et al. 2010 demonstrated that rapamycin also extends lifespan in Drosophila and is dependent on the autophagy gene (deficient in Atg mutants).

**Spermidine**: Eisenberg et al. reported in *Nature Cell Biology* in 2009 that spermidine extends the lifespan of yeast (replication lifespan by about 4 times), nematodes, and fruit flies through the autophagy mechanism, and is ineffective when Atg is deficient; the mechanism is to inhibit acetyltransferase EP300, allowing autophagy proteins (such as the ATG family) to maintain a deacetylation active state (Pietrocola et al. *Cell Death Differ* 2015). 2016 *Nature Medicine*: Drinking water supplemented with spermidine extends the lifespan of mice by about 10% and improves heart function (reduces myocardial fibrosis and improves diastolic function); human epidemiology shows that those with high dietary spermidine intake have lower all-cause mortality. Human RCT (Schwarz 2022, JAMA Netw Open): In elderly people with subjective cognitive decline, oral spermidine at about 300 mg/day for 3 months was better than placebo in episodic memory indicators (n about 90, medium effect size, needs to be repeated with a larger sample).

**Human Translational Lessons from Aβ Antibodies**: lecanemab (Clarity AD Trial, 2022, n=1795) slowed CDR-SB (Clinical Dementia Rating Scale) decline by ~27% (absolute difference 0.45 points) over 18 months, while PET confirmed significant clearance of amyloid plaques - the first time **confirmatory clinical trial positive results** for "clearance of aggregates" have been obtained**, but the magnitude is limited and concomitant ARIA (amyloid-related imaging abnormality, cerebral edema/hemorrhage) risk; Aduhelm was withdrawn from the market due to controversy over benefit-risk ratio. This contrast supports the hypothesis of "oligomer toxicity and limited benefit from removal of large fibers" and also suggests that single-target removal is not sufficient to reverse established neurodegeneration.

**UPR pharmacology (human evidence)**: Tauroursodeoxycholic acid (TUDCA, chemical chaperone) 1750 mg/day × 12 weeks improves liver and muscle insulin sensitivity in obese men (Kars et al. *Diabetes* 2010); 4-phenylbutyric acid (4-PBA) shows downregulation of UPR markers in metabolic diseases. Restoring CMA: Zhang & Cuervo (2015, *Sci Transl Med*) restored LAMP-2A expression in the liver of aged mice, improving liver cell function and stress resistance - **direct evidence that "rebuilding rejuvenated PQC" is feasible in animals**. Metformin (AMPK→ULK1) extends the lifespan of mice by approximately 6% (Martin-Montalvo 2013, *Nat Commun*, male), and UKPDS follow-up shows that metformin reduces all-cause mortality in older adults with type 2 diabetes. Caloric restriction human trial CALERIE (Redman 2018, *Cell Metab*): Approximately 12% caloric restriction lasting 2 years achieved approximately 10% weight loss, and significant reductions in oxidative stress damage markers (8-oxo-dG, F2-isoprostane)—improvement of autophagy flux is one of its candidate mechanisms (direct measurement of flux in humans is still difficult and relies mostly on p62/LC3 circulating markers, and the specific effect size needs to be verified).

## 5. Contact with NO/NAD+ Longevity Network

**NO→SIRT1→Autophagy axis**: SIRT1 is the hub connecting NO and autophagy - Lee et al. 2008 (*PNAS*) proved that SIRT1 is required for starvation-induced autophagy and directly deacetylates autophagy machinery proteins such as ATG5/ATG7/LC3 to maintain their activity; SIRT1 also deacetylates FoxO3a and upregulates BNIP3 to promote mitophagy (Kume et al. *J Biol Chem* 2010), and deacetylating TFEB promotes its nuclear translocation to activate lysosomal biogenesis. NO side: exercise → shear stress → eNOS → NO. NO upregulates SIRT1 expression and activity through two pathways, cGMP and AMPK (research on endothelial cell mechanisms shows), forming a closed loop of "exercise → NO → SIRT1 → autophagy → proteostasis"; low-dose NO donors promote mitophagy and cooperate with PGC-1α-mediated mitochondrial biogenesis to achieve mitochondrial renewal. NAD+ is the rate-limiting substrate of SIRT1: NAD+ decreases with age (approximately 30-50% decrease in old compared to young people in human tissue, site dependent) → SIRT1 activity decreases → Insufficient deacetylation of autophagy machinery - NAD+ precursor (NMN/NR) restores NAD+ and reactivates the SIRT1-autophagy axis (human NR experiments confirm that NAD+ increases by approximately 40-60%, Martens 2018 *Nat Commun*, n=30 middle-aged/elderly population).

**The other side of the double-edged sword of NO - ONOO⁻ direct damage to PQC**: high concentrations of NO react with superoxide to generate peroxynitrite (ONOO⁻), and nitrated protein tyrosine (3-nitrotyrosine, accumulated in the brain with age and neurodegeneration) directly damages chaperone and proteasome functions; the more classic one is **Parkin's S-nitrosylation** - Chung et al. 2004 (*Science*) proved that NO donor makes Parkin Nitrosylation at Cys323 inhibits its E3 ligase activity and impairs its protective function, which is directly related to PD pathology (increased nitrosylated Parkin in the PD brain). α-Synuclein itself is also an S-nitrosylation substrate, and nitrosylation promotes its oligomerization. Therefore, NO has a typical dose dependence on protein homeostasis: **Physiological low dose (eNOS source) promotes autophagy and maintains homeostasis via SIRT1/AMPK; pathological high dose (iNOS/inflammation) promotes aggregation via ONOO⁻/nitrosylation damage PQC** - completely consistent with the main line of "NO double-edged sword" of 03-no-basics.md.

**Longevity network intersection**: mTORC1 (inhibits autophagy, phosphorylates TFEB/ULK1) and AMPK/SIRT1 (promotes autophagy) constitute a "synthesis-decomposition" balance, and NO, NAD+, and caloric restriction all act on this balance; see 04-drugs/06-mtor-rapamycin.md and 04-nad-sirtuin.md for details. Research on the mechanism of traditional Chinese medicines for replenishing qi and activating blood circulation (astragaloside IV, ginsenoside Rg1, etc.) has shown that autophagy can be induced through activation of eNOS/NO↑ and AMPK to improve endothelial and cardiac protein homeostasis (mostly at the cell/animal level, human evidence needs to be verified), providing a PQC entry point for the cross-main line of traditional Chinese medicine in this library.

## 6. Intervention directions and executable suggestions

PQC intervention strategies ranked by strength of evidence:

1. **Lifestyle (strongest evidence and most actionable)**: caloric restriction/intermittent fasting (AMPK→ULK1, SIRT1 dependent), endurance exercise (eNOS/NO→SIRT1→autophagy + mitophagy), adequate sleep (removal of Aβ by the glial lymphatic system in the brain - 2012 *Science Translational Medicine* mechanism study, to be confirmed in humans). All three can be superimposed via the NO/NAD+ axis.
2. **Drugs with clinical data**: metformin (AMPK activation, TAME human anti-aging trial in progress); rapamycin/everolimus low-dose pulse administration (elderly immune improvement human trial: RAD001 improves influenza vaccine response by about 20%, see 04-drugs/06 for details); spermidine (food-grade supplement, RCT preliminary positive).
3. **Frontline pipeline (pre-human)**: NAD+ precursor NMN/NR (restores SIRT1-autophagy axis); Urolithin A (induces mitophagy, improves muscle mitochondrial markers in 4-week trial in elderly population); Trehalose (mTOR-independent autophagy inducer, improves mouse ALS/AD model); USP14 inhibitor IU1 (deubiquitinating enzyme inhibition → enhanced proteasome degradation, preclinical); PROTAC (targeted protein degradation technology, has entered clinical trials for tumors, and may be used to remove pathological aggregates such as tau/α-syn in the future - it is still envisioned); pharmacological partner (4-PBA/TUDCA, improves ER folding load, metabolic diseases have human data).
4. **Monitoring recommendations**: Currently there is no convenient direct measurement of autophagy flux in humans; alternative indicators that can be monitored include changes in circulating p62/LC3, oxidative damage markers (3-nitrotyrosine, 8-oxo-dG), LAMP-2A/cathepsin activity (tissue biopsy), and neurodegenerative blood markers (p-tau217, GFAP) as indirect readings of aggregation burden.

## 7. Linkage between protein homeostasis and other aging markers

Loss of proteostasis is not an isolated event, but forms a positive feedback network with the other eleven markers: **and mitochondrial dysfunction** - damaged mitochondria are both objects to be cleared (mitophagy) and "accomplices" of aggregated proteins (mitochondrial ROS promotes the accumulation of misfolded and oxidatively modified proteins, and oxidatively modified proteins are substrates that are difficult to degrade by the proteasome); **and chronic inflammation** - aggregated proteins can be recognized by the NLRP3 inflammasome (Aβ, α-synuclein activates NLRP3 to promote IL-1β matures), and the high concentration of iNOS induced by inflammation damages PQC via ONOO⁻, forming a vicious cycle of "aggregation→inflammation→nitrolation damage→more aggregation"; **and cell senescence** - the proteostasis burden of senescent cells increases (SASP protein is synthesized in large quantities), and proteotoxic stress can induce p53/p21 to promote senescence; **and nutrient sensing imbalance** - mTORC1 It is both the core of nutrient sensing and the master switch of autophagy. This hub makes "eating too much→continuous activation of mTOR→autophagy inhibited→protein accumulation" become an intuitive causal chain of the metabolism-protein homeostasis axis. Understanding these intersections explains why a single PQC intervention (e.g., only clearing Aβ) has limited clinical benefit: only simultaneous relief of upstream damage (mitochondria, inflammation, nutritional signaling) can restore compensatory margins to the PQC network. This also echoes the main line of this library - the reason why NO and NAD+ are regarded as upstream intervention hubs is because they affect multiple mark chains at the same time (see 01-aging-hallmarks.md and 03-no-basics.md for details).

## 8. Open issues and controversies

1. **Toxicity Form Debate**: Oligomers vs Mature Fibers Who is the main toxic entity? The limited benefits and clear risks of Aβ antibody clearance of plaques suggest that the "clearance strategy" needs to be repositioned (preventive clearance vs therapeutic clearance; multimer-specific antibodies).
2. **The "optimal window" of autophagy**: Excessive autophagy can cause excessive consumption of organelles and type II programmed death (autophagic death), and tumor cells use autophagy to maintain survival. The balance point between the long-term risks (immunosuppression, metabolic side effects) and benefits of systemic strong autophagy induction (such as high-dose rapamycin) is unknown; it is still unclear whether "pulse" induction is better than continuous induction.
3. **Biphasic nature of UPR**: UPR is both a compensatory mechanism (life extension) and an apoptosis driver (CHOP). Is chronic low-grade ER stress "stress accumulation" or "compensation incapacitation" in aging? The mechanism (cell-autonomous vs. non-autonomous) by which XBP1s overexpression extends lifespan is still debated.
4. **Human translation gap**: All life extension evidence for PQC intervention comes from model organisms; the endpoint (death/disability) of human RCT is missing, and there is a lack of reliable biomarkers of autophagy flux in vivo, making it impossible to quantify "the role of autophagy inducers in the human body."
5. **Synthetic lethal risk**: UPS and autophagy compensate for each other, and simultaneous inhibition of dual channels (such as the combination of Bortezomib chemotherapy + chloroquine) can cause fatal proteotoxicity—intervention design must consider the compensatory network rather than a single node.

## References

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. The Hallmarks of Aging. *Cell* 2013;153:1194–1217.
2. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. *Cell* 2023;186:243–278.
3. Balch WE, Morimoto RI, Dillin A, Kelly JW. Adapting proteostasis for disease intervention. *Science* 2008;319:916–919.
4. Harrison DE, Strong R, Sharp ZD, et al. Rapamycin fed late in life extends lifespan in genetically heterogeneous mice. *Nature* 2009;460:392–395.
5. Miller RA, Harrison DE, Astle CM, et al. Rapamycin, but not resveratrol or simvastatin, extends life span of genetically heterogeneous mice. *J Gerontol A Biol Sci Med Sci* 2011;66:191–201.
6. Eisenberg T, Knauer H, Schauer A, et al. Induction of autophagy by spermidine promotes longevity. *Nat Cell Biol* 2009;11:1305–1314.
7. Eisenberg T, Abdellatif M, Schroeder S, et al. Cardioprotection and lifespan extension by the natural polyamine spermidine. *Nat Med* 2016;22:1428–1438.
8. Hara T, Nakamura K, Matsui M, et al. Suppression of basal autophagy in neural cells causes neurodegenerative disease in mice. *Nature* 2006;441:885–889.
9. Komatsu M, Waguri S, Chiba T, et al. Loss of autophagy in the central nervous system causes neurodegeneration in mice. *Nature* 2006;441:880–884.
10. Komatsu M, Waguri S, Koike M, et al. Homeostatic levels of p62 control cytoplasmic inclusion body formation in autophagy-deficient mice. *Cell* 2007;131:1149–1163.
11. Lee IH, Cao L, Mostoslavsky R, et al. A role for the NAD-dependent deacetylase Sirt1 in the regulation of autophagy. *Proc Natl Acad Sci USA* 2008;105:3374–3379.
12. Cuervo AM, Dice JF. Age-related decline in chaperone-mediated autophagy. *J Biol Chem* 2000;275:31505–31513.
13. Zhang C, Cuervo AM. Restoration of chaperone-mediated autophagy in aging liver improves cellular function and hepatic stress resistance. *Sci Transl Med* 2015;7:318ra197.
14. Walter P, Ron D. The unfolded protein response: from stress pathway to homeostatic regulation. *Science* 2011;334:1081–1086.
15. Taylor RC, Dillin A. XBP-1 is a cell-nonautonomous regulator of stress resistance and longevity. *Cell* 2013;153:1435–1447.
16. Kim J, Kundu M, Viollet B, Guan KL. AMPK and mTOR regulate autophagy through direct phosphorylation of Ulk1. *Nat Cell Biol* 2011;13:132–141.
17. Hsu AL, Murphy CT, Kenyon C. Regulation of aging and age-related disease by DAF-16 and heat-shock factor. *Science* 2003;300:1142–1145.
18. Chung KKK, Thomas B, Li X, et al. S-nitrosylation of parkin regulates ubiquitination and compromises parkin's protective function. *Science* 2004;304:1328–1331.
19. van Dyck CH, Swanson CJ, Aisen P, et al. Lecanemab in early Alzheimer's disease. *N Engl J Med* 2023;388:9–21.
20. Martin-Montalvo A, Mercken EM, Mitchell SJ, et al. Metformin improves healthspan and lifespan in mice. *Nat Commun* 2013;4:2192.
21. Redman LM, Smith SR, Burton JH, et al. Metabolic slowing and reduced oxidative damage with sustained caloric restriction support the rate of living and oxidative damage theories of aging. *Cell Metab* 2018;27:805–815.
22. Sardiello M, Ballabio A, et al. A gene network regulating lysosomal biogenesis and function. *Science* 2009;325:473–477.
23. Schwarz C, Benson GS, Horn N, et al. Effect of spermidine supplementation on cognitive function in older adults with subjective cognitive decline: a randomized clinical trial. *JAMA Netw Open* 2022;5:e2213875.
24. Kars M, Yang L, Gregor MF, et al. Tauroursodeoxycholic acid may improve liver and muscle but not adipose tissue insulin sensitivity in obese men and women. *Diabetes* 2010;59:1899–1905.
25. Martens CR, Denman BA, Mazzo MR, et al. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD+ in healthy middle-aged and older adults. *Nat Commun* 2018;9:1286.
