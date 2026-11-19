# Molecular Structure Deep Dive 22: Ribosome—Protein Synthesis Machine and the "Synthesis-Degradation" Balance

> **Topic Positioning**: 10-structures (Molecular Structure Deep Dive) Part 22—Dissecting the 3D structure of the ribosome, understanding "how proteins are synthesized", "the coordinated work of tRNA/mRNA/ribosome", and the ribosome's role in the "synthesis-degradation balance" during aging. This is the structural foundation of the knowledge base's proteostasis mainline ([06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md)), forming a "synthesis-degradation" balance with the 20S proteasome ([20-proteasome.md](20-proteasome.md)), and acting as the downstream executor of mTOR ([04-mtor-structure.md](04-mtor-structure.md)).
> **Related Articles**: For proteostasis see [06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md); for 20S proteasome see [20-proteasome.md](20-proteasome.md); for mTOR see [04-mtor-structure.md](04-mtor-structure.md); for AMPK see [03-ampk-structure.md](03-ampk-structure.md); for FOXO3 see [16-foxo3-structure.md](16-foxo3-structure.md).

---

## 0. Structure Overview

**In one sentence**: The ribosome is the cell's "protein synthesis factory"—a macromolecular machine made of RNA (rRNA) and proteins that "translates" the genetic information of mRNA into proteins—"the cell's 'translation factory', where mRNA is the blueprint, amino acids are the raw materials, and the ribosome is the machine tool." It is one of the largest molecular machines in the cell (~4 MDa), composed of two subunits: the small subunit (40S, decoding) and the large subunit (60S, peptide bond formation)—"the small subunit reads the blueprint, the large subunit welds."

```text
Eukaryotic ribosome (80S) structure:
  40S small subunit (decoding):  18S rRNA + 33 proteins
                    Decoding center: mRNA codon ↔ tRNA anticodon pairing
  60S large subunit (peptide bond formation):  28S/5.8S/5S rRNA + 47 proteins
                    Peptidyl transferase center (PTC): peptide bond formation between amino acids
                  │
  Coordinated work:  mRNA passes between the two subunits → tRNA enters sequentially (A/P/E sites)
            → amino acid chain elongates stepwise → nascent protein exits through the exit tunnel
```

**Three Major Structural Features** (the atomic basis determining its function):
1. **RNA as the core**: rRNA is the catalytic main body (ribozyme)—"the machine tool's blade is made of RNA";
2. **Division of labor between subunits**: 40S decodes + 60S forms peptide bonds—"reading the blueprint and welding are separated";
3. **Three tRNA sites**: A (entry) / P (peptide bond formation) / E (exit)—"three workstations, assembly line operation".

**Core Regulatory Mechanism**:

```text
mTOR activation → 4E-BP phosphorylation releases eIF4E → Cap-dependent translation initiation↑
        → S6K activation → Ribosome biogenesis↑ → Translation capacity↑
        │
AMPK/Stress → eIF2α phosphorylation → Translation initiation↓ (Global inhibition)
        → Selective translation (stress proteins prioritized) → Cell protection
```

---

## 1. Why Ribosome Structure Is Important

The ribosome is the most core machine of life:

- **"Translation factory"**: All proteins are synthesized by ribosomes—"without ribosomes, there is no life";
- **"Synthesis-degradation balance"**: Proteostasis = the balance between synthesis (ribosome) and degradation (proteasome [20-proteasome.md](20-proteasome.md) / autophagy [18-lc3-autophagy.md](18-lc3-autophagy.md))—"building on one side, demolishing on the other";
- **Anti-aging evidence**: Translation rate is correlated with lifespan (slow translation extends lifespan, e.g., rpS6 phosphorylation↓ / downregulation of translation elongation factors)—"slower machine tool speed, longer lifespan";
- **"Translation fidelity"**: Translation errors (wrong amino acid incorporation) → erroneous proteins → proteotoxicity—"poor machine tool precision, more defective products";
- **Dialogue with mTOR**: mTOR is the "commander-in-chief" of ribosome biogenesis/translation initiation ([04-mtor-structure.md](04-mtor-structure.md))—"the growth switch orders the factory to open";
- **Antibiotic targets**: Many antibiotics (tetracyclines/macrolides) target bacterial ribosomes—"attacking the enemy's machine tools".

**Three key questions for structural research**:
1. How does the ribosome "read" mRNA (atomic mechanism of decoding)?
2. How does it "weld" amino acids (atomic mechanism of peptide bond formation)?
3. How is translation regulated (initiation/elongation/termination switches)?

These questions were answered in structures such as 4V6X (human 80S), 5AJ0 (translating polyribosome).

---

## 2. Structural Anatomy of the Ribosome

### 2.1 40S Small Subunit — The "Decoder"

- Composition: 18S rRNA (~1900 nt) + 33 proteins—"the blueprint-reading components";
- Decoding center: mRNA codon pairs with tRNA anticodon here—"blueprint and parts matched";
- Fidelity mechanism: The decoding center checks codon-anticodon pairing (geometric/chemical check) → extremely low error rate (~10⁻⁴)—"extremely strict quality inspection";
- mRNA binding: mRNA passes through the 40S channel (mRNA channel)—"blueprint passes through the card reader";
- 40S functions: Initiation (binding eIF factors/Met-tRNA), decoding—"opening the book + matching parts".

### 2.2 60S Large Subunit — The "Peptide Bond Forming Machine"

- Composition: 28S/5.8S/5S rRNA (~5000 nt) + 47 proteins—"welding components";
- Peptidyl transferase center (PTC): Catalyzes peptide bond formation between amino acids (rRNA catalysis, ribozyme)—"the welding gun";
- Exit tunnel: Nascent polypeptide chain exits the ribosome through the tunnel from the PTC (~100 Å long)—"finished product exit channel";
- Tunnel function: Influences co-translational folding (folding begins within the tunnel)—"rough assembly before leaving the factory";
- 60S functions: Peptide bond formation (elongation), peptide chain release (termination)—"welding + shipping".

### 2.3 Three tRNA Sites — The "Assembly Line"

- **A site (aminoacyl)**: New tRNA (carrying amino acid) enters—"new part arrives";
- **P site (peptidyl)**: tRNA holding the peptide chain—"part being welded";
- **E site (exit)**: Empty tRNA leaves—"used part exits";
- Cycle: A entry → peptide bond formation (peptide chain on P transfers to A) → translocation (tRNA moves A→P→E) → mRNA advances one codon—"assembly line cycle".

---

## 3. The Molecular Logic of Translation: From Structure to Chemistry

### 3.00 The Engineering Wisdom of "Ribozymes": Why the Catalytic Core Uses RNA, Not Protein

The previous section covered the ribosome's division of labor; this section delves into **the most counterintuitive design: why the ribosome uses RNA as a catalyst (ribozyme) rather than protein**. Behind this lies life's "archaeological layer":

**Relics of the "RNA World."** Early life (RNA world hypothesis): RNA both stored information and catalyzed reactions (ribozymes)—the ribosome's PTC is catalyzed by rRNA, a living fossil of the "RNA world"—"the machine tool's blade is a design hundreds of millions of years old."

**Characteristics of "RNA Catalysis":** ① RNA can form complex three-dimensional structures (pseudoknots/three-way junctions) → creating catalytic pockets—"RNA can also fold into tools"; ② RNA's 2'-OH participates in catalysis (metal-ion assisted)—"RNA's chemical toolbox"; ③ RNA catalysis is slower (than protein enzymes)—but the ribosome compensates with "high concentration/multiple sites"—"old blades are slow, but the factory has many of them."

**"Why wasn't it replaced by protein?"** ① PTC function is deeply coupled with rRNA structure (the tRNA substrate is itself RNA)—"RNA substrate paired with RNA catalyst, a match made in heaven"; ② The ribosome's overall architecture uses rRNA as its scaffold (proteins are merely "decoration")—"changing the scaffold = major renovation, high evolutionary barrier"; ③ rRNA catalysis is "good enough" (speed is slow but fidelity relies on decoding, not peptide bond formation)—"the bottleneck isn't at welding, it's at quality inspection."

**The significance of "RNA scaffold + protein decoration":** Ribosomal proteins (RPs) mainly "stabilize structure/regulate" and do not participate in catalysis—"proteins are scaffolding, RNA is the machine tool"—this explains why ribosomal protein mutations primarily affect "assembly/regulation" rather than "catalysis"—"the scaffold collapses, but the machine tool remains."

**Contrast with the proteasome:** The proteasome ([20-proteasome.md](20-proteasome.md)) uses protein (Thr1) for catalysis, while the ribosome uses RNA catalysis—"one protein blade, one RNA blade"—two "molecular machines" demonstrate two catalytic strategies of life—"evolution isn't picky; it uses whichever solution works."

### 3.0 Atom by Atom: Why "Decoding" Must Be So Strict

Many people ask: why must the translation error rate be extremely low (~10⁻⁴)? Can't it be "close enough"? The answer lies in "the cost of errors":

**"The cost of one wrong amino acid."** Protein function depends on precise sequence—one amino acid error may: ① alter folding (misfolded protein); ② alter activity (enzyme inactivation); ③ produce toxicity (aggregation propensity)—"one wrong character, and the whole article changes flavor."

**"Dual checking of decoding."** ① Initial pairing (codon-anticodon hydrogen bonding/geometry check, fast but coarse); ② Induced fit (correct tRNA induces 40S conformational change, slow but precise)—"coarse check + fine check, two gates"—incorrect tRNAs are "turned away" (kinetic selection)—"the guard first checks the face (coarse), then checks the ID (fine)."

**"Peptide bond formation check."** The PTC has directional requirements for "tRNA-amino acid" (aminoacyl-tRNA must be correctly oriented) → further reducing errors—"verify the materials once more before welding."

**"Error rate and lifespan."** Translation fidelity declines with age (ribosome damage/oxidation) → more erroneous proteins → proteotoxicity—"the machine tool ages, defect rate rises"—this is one of the important mechanisms of aging.

### 3.1 "The Regulatory Switches of Translation": Initiation Is the Most Critical Knob

Translation regulation is mainly at "initiation" (not elongation)—"starting is hard, once running it's fast":

**"eIF4E/4E-BP switch" (cap-dependent initiation).** mTOR phosphorylates 4E-BP → releases eIF4E → eIF4E binds mRNA cap → initiation complex assembly → translation initiation—"the growth switch opens the factory gates" ([04-mtor-structure.md](04-mtor-structure.md));

**"eIF2α switch" (global initiation).** Stress (amino acid deprivation/ER stress/viral infection) → eIF2α phosphorylation → eIF2-GTP-Met-tRNA cycling blocked → global translation inhibition—"the whole factory shuts down during stress";

**"Selective translation."** During global inhibition, certain mRNAs (containing uORFs) areare instead translationally enhanced (e.g., ATF4) → stress proteins prioritized—"shutdown but key workshops keep running";

**"Ribosome biogenesis."** mTOR regulates rRNA transcription/ribosomal protein synthesis → determines "number of factories"—"the growth switch decides how many factories to open."

**"The significance of regulation"**: Translation initiation is an "energy-intensive" process → cells use initiation switches for "on-demand production"—"when energy is low, shut down production, save resources and survive"—this is the convergence point of AMPK ([03-ampk-structure.md](03-ampk-structure.md))/mTOR/stress signaling.

### 3.20 "eIF2α's Choice": The "Global-Local" Switch of Translation During Stress

eIF2α phosphorylation is the "master switch" of translation regulation—its "global inhibition + local activation" strategy is a classic cellular stress response:

**"What is eIF2α."** eIF2 delivers Met-tRNAᵢ to the 40S (essential for initiation); eIF2α phosphorylation → eIF2-GDP cannot be recycled by eIF2B → Met-tRNAᵢ supply↓ → global translation initiation↓—"initiator lacks parts, whole factory shuts down."

**"Four kinases, one outcome."** eIF2α kinases: PERK (ER stress), GCN2 (amino acid deprivation), PKR (viral infection), HRI (heme deficiency)—"four alarms, all pulling the same lever"—"regardless of the stress, first shut down and survive."

**"uORF selective translation."** During global inhibition, mRNAs containing upstream open reading frames (uORFs) (e.g., ATF4/CHOP) areare instead translationally enhanced—mechanism: uORFs are short, normally the ribosome "reads through" and reinitiates; with eIF2α-P, the ribosome "skips" the uORF and directly translates the main ORF—"during shutdown, key workshops (stress genes)instead work overtime."

**"Integrated stress response (ISR)."** eIF2α phosphorylation → ATF4 and other transcription factors → upregulate stress genes (amino acid synthesis/antioxidant/autophagy) → cellular adaptation—"shutdown is not the goal, transformation is"—ISR dysregulation is linked to aging/neurodegeneration—"when transformation fails, cells die."

**"Anti-aging insights"**: ① Moderate stress (CR/exercise) → mild ISR → adaptation (hormesis)—"small shutdown, big transformation"; ② Chronic stress (long-term inflammation/ER stress) → persistent eIF2α-P → harmful—"prolonged shutdown, cell atrophy"; ③ ISR modulators (e.g., ISRIB) restore eIF2α cycling → improve cognition (animals)—"repair the initiator"—"translation's 'factory-wide shutdown' is a double-edged sword: brief is protective, prolonged is harmful."

---

## 4. Ribosome and Aging: The "Synthesis-Degradation Balance" from a Structural Perspective

### 4.1 Age-Related Changes in Translation

- **Global translation rate decline**: Aged tissues show decreased translation rate (mTOR signaling↓/ribosome damage)—"factory operating rate drops";
- **Translation fidelity decline**: Ribosome oxidative damage/modification → error rate↑—"machine tool precision drops";
- **Ribosomal protein (RP) modifications**: RP phosphorylation/oxidation changes with age → altered ribosome function—"machine tool parts aging";
- **Consequences**: Erroneous proteins↑ + repair protein synthesis↓ → proteotoxicity accumulation—"more defective products, less maintenance."

### 4.2 Evidence for "Slow Translation Extends Lifespan"

- **Model organisms**: rpS6 phosphorylation-deficient mice (translation↓) → extended lifespan + muscle preservation; translation elongation factor downregulation (nematodes/fruit flies) → extended lifespan—"slower machine tool, longer life";
- **Caloric restriction**: CR inhibits mTOR → translation↓ → lifespan extension—"run fewer machines, do more maintenance";
- **Rapamycin** ([06-mtor-rapamycin](../04-drugs/06-mtor-rapamycin.md)): Inhibits mTOR → translation↓ → lifespan extension (mice)—"drug-induced speed reduction";
- **"Paradox" explanation**: Translation "quantity" decreases but "quality" is maintained (fidelity prioritized) → fewer erroneous proteins + saved energy for repair—"slow work yields fine products, saved money repairs machines."

### 4.20 Molecular Details of "Translation Fidelity": The Ribosome's "Quality Inspection System"

Translation fidelity is the cornerstone of proteome health—the ribosome's "quality inspection" has three layers:

**First layer: Decoding quality inspection (tRNA selection).** The 40S decoding center's "geometric check"—correct tRNA induces 40S closed conformation (domain closure) → stable; incorrect tRNA cannot induce → dissociates—"the guard verifies 'ID' (anticodon) before allowing passage." This is the main fidelity force (error rate ~10⁻⁴)—"primary quality inspection at the entrance."

**Second layer: Peptide bond formation quality inspection (PTC orientation).** The PTC has strict requirements for the 3' end orientation of aminoacyl-tRNA (C74/C75 precise alignment with P-site tRNA) → erroneous incorporation is "stuck" at the peptide bond formation step—"verify materials before welding." This is the second gate—"secondary quality inspection at the workstation."

**Third layer: Release quality inspection (termination).** Release factors (eRF1) recognize stop codons → peptide chain release; erroneous readthrough is "proofread"—"check the code before shipping."

**"Quality inspection system degrades with age"**: ① Ribosome oxidative damage (rRNA/RP oxidation) → decoding/peptide bond formation precision↓; ② Ribosomal protein modifications (phosphorylation, etc.) → assembly/function changes; ③ Erroneous tRNA charging errors (aminoacyl-tRNA synthetase aging) → substrate errors—"quality inspectors become farsighted, defective products slip through."

**"Fidelity enhancement" anti-aging approaches**: ① Reduce oxidative damage (antioxidants/mitochondrial health, [12-complex1-structure.md](12-complex1-structure.md)) → protect ribosomes—"less rust"; ② Moderate stress (exercise/CR) → induce adaptive ribosome quality control—"quality inspectors get sharper with practice"; ③ Clear erroneous proteins (proteasome/autophagy) → safety net—"even if defective products slip through, the demolition team collects them"—"three quality checks + safety net recycling ensures proteome integrity."

### 4.3 Anti-aging Insights from the "Synthesis-Degradation Balance"

| Dimension | Synthesis (Ribosome) | Degradation (Proteasome/Autophagy) |
|---|---|---|
| Machine | 80S ribosome | 20S/26S proteasome + autophagy |
| Regulation | mTOR activation | AMPK/FOXO3 activation |
| Aging trend | Rate↓/Fidelity↓ | Activity↓ |
| Ideal state | Moderate + faithful | Efficient + selective |

**"Balance of the scale"**: Health = synthesis "moderate and faithful" + degradation "efficient and selective"; aging = synthesis "slow and sloppy" + degradation "weak and chaotic"—"both sides fail, proteome collapses." **Anti-aging strategies**: ① Synthesis side: moderately inhibit mTOR (intermittent fasting/rapamycin) → reduce speed and maintain quality—"slower machine tool, higher precision"; ② Degradation side: activate autophagy/proteasome (exercise/CR) → clear defective products—"the demolition team must be efficient"—"both sides need tuning for proteostasis to hold."

---

## 5. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| Ribosome consists of rRNA + protein | ★★★★★ Solid proof | 4V6X, etc. |
| rRNA is the main catalyst (ribozyme) | ★★★★★ Solid proof | PTC structure |
| 40S decoding + 60S peptide formation | ★★★★★ Solid proof | 4V6X/5AJ0 |
| A/P/E three tRNA sites | ★★★★★ Solid proof | Classic + structural |
| Decoding double-check (fidelity) | ★★★★★ Solid proof | Single-molecule + structural |
| rpS6 phosphorylation↓ extends lifespan (mice) | ★★★★ Strong | Animal studies |
| Translation rate declines with age | ★★★★ Strong | Multiple studies |
| CR/Rapamycin inhibits translation to extend lifespan | ★★★★ Strong | Model organisms |

---

## 6. Connection to Knowledge Base Mainline

### 6.0 Structural Panorama of "Protein Economy": Synthesis-Folding-Degradation

| Step | Molecule | Structure Chapter | Aging Trend |
|---|---|---|---|
| Synthesis | Ribosome | [22-ribosome.md](22-ribosome.md) | Rate↓/Fidelity↓ |
| Folding | Hsp70 (Chaperone) | (Not listed) | Inductive capacity↓ |
| Degradation (monomers) | 20S Proteasome | [20-proteasome.md](20-proteasome.md) | Activity↓ |
| Degradation (bulk) | LC3/Autophagy | [18-lc3-autophagy.md](18-lc3-autophagy.md) | Activity↓ |

**The Balance of "Protein Economy"**: The balance among the three steps of synthesis, folding, and degradation determines proteome health—a "closed loop of production, quality control, and recycling." During aging, all three steps undergo comprehensive degradation → proteome collapse (proteotoxicity)—"the entire industrial chain ages."

### 6.00 The Dialogue Between "Translation and Epigenetics": The Ribosome is Also an "Epigenetic Machine"

**"Acetylation/Phosphorylation of Ribosomal Proteins."** RPs can be modified by acetylation/phosphorylation → affecting ribosome assembly/function—"machine tool parts can be 'tuned'" (echoes [06-sirt1-structure.md](06-sirt1-structure.md));

**"rRNA Modifications."** 2'-O-methylation/pseudouridylation of rRNA (catalyzed by snoRNP) → affects translation accuracy/speed—"the blade of the machine tool can be 'sharpened'"—the rRNA modification profile changes with age → altered translation characteristics—"whether the blade gets duller or sharper with grinding depends on the modification";

**"Histone Inheritance in Translation."** Old histones (carrying epigenetic marks) are "redistributed" during DNA replication—involving the balance between new histone synthesis (ribosome) and old histone retention—"mixing new and old parts for epigenetic memory" (echoes [07-dnmt1-structure.md](07-dnmt1-structure.md));

**"Non-histone Acetylation."** Many translation-related factors (eIF5A, etc.) are modified by acetylation → regulating translation elongation (the hypusine modification of eIF5A is essential for elongation)—"the 'lubricant' of the translation machine also needs modification."

**Anti-aging Implications of "Translation-Epigenetics"**: Epigenetic interventions (SIRT1 activation, etc.) may affect the proteome by modifying the translation machinery—"repairing epigenetics isn't just about changing gene expression, it also changes translation"—this suggests that the "epigenetic flow" ([05](05-tet-dna.md)/[06](06-sirt1-structure.md)/[07](07-dnmt1-structure.md)) and "protein flow" ([18](18-lc3-autophagy.md)/[20](20-proteasome.md)/[22](22-ribosome.md)) of the 10-structures series are intertwined at the molecular level—"the cell's two major information flows share a single modification language."

### 6.1 Mainline Chapter Dialogue

- **Proteostasis** ([06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md)): This chapter, along with the proteasome/autophagy, forms its structural foundation—"the synthesis-degradation balance";
- **20S Proteasome** ([20-proteasome.md](20-proteasome.md)): Degradation side—"the demolition team";
- **LC3/Autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Degradation side (bulk)—"the wrecking crew";
- **mTOR structure** ([04-mtor-structure.md](04-mtor-structure.md)): Commander-in-chief of translation initiation/ribosome biogenesis—"the growth switch manages the factory";
- **AMPK structure** ([03-ampk-structure.md](03-ampk-structure.md)): Stress inhibits translation (eIF2α)—"the energy switch manages shutdown";
- **FOXO3 structure** ([16-foxo3-structure.md](16-foxo3-structure.md)): FOXO3 regulates autophagy genes (degradation side)—"the survival switch manages recycling";
- **Rapamycin** ([06-mtor-rapamycin](../04-drugs/06-mtor-rapamycin.md)): mTOR inhibition → translation↓ + autophagy↑—"two-pronged approach."

---

## 7. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How does the ribosome synthesize proteins? | 40S decoding (codon-anticodon) + 60S peptide formation (PTC) + A/P/E assembly line |
| Why must translation fidelity be high? | One wrong amino acid → misfolding/inactivation/toxicity—"one wrong character ruins the whole text" |
| How is translation regulated? | Initiation is the critical knob (eIF4E/4E-BP + eIF2α)—"starting is hard, running is fast" |
| Why does "slow translation" extend lifespan? | Reduce speed and maintain quality + save energy for repair—"slow work yields fine products" |
| How to counter aging? | Moderately inhibit mTOR (intermittent fasting) + enhance degradation—"slow down the machine tool + efficient demolition" |

**Structural intuition beyond the five questions**: The ribosome story reveals the "scale philosophy of molecular machines"—**"the cell entrusts its most important, most expensive functions to the largest, most conserved machine."** The ribosome is the cell's largest molecular machine (~4 MDa), and the most evolutionarily conserved (archaea-human rRNA core is nearly unchanged)—"the most important factory uses the heaviest but most reliable machine tool." The meaning of this "conservation": **the ribosome's basic design (RNA catalysis/dual subunits/A-P-E) has not changed in billions of years**—indicating that the physicochemical constraints of "translation" (fidelity/speed/regulation) are already "locked" near the optimal solution—"the cost of major renovation is too high, fine-tuning is the norm." **Anti-aging insight**: Don't try to "modify the ribosome," but "maintain it" (antioxidants/moderate stress/clear defective products)—**"for the most conserved machine, the best strategy is maintenance, not modification"**—this again confirms the series' methodology of "repair switches, repair negative feedback, maintain networks"—"molecular structure knowledge tells us 'what can be changed and what can only be maintained.'"

---

## 8. Open Questions

1. **Dynamics of translation**: Conformational cycling of the ribosome during elongation (time-resolved cryo-EM);
2. **Co-translational folding**: Folding initiation of nascent peptides in the exit tunnel;
3. **Ribosome heterogeneity**: Translational selectivity of different ribosomes (ribosomal protein variants);
4. **Ribosome damage and aging**: Specific mechanisms and repair of oxidative damage to ribosomes;
5. **"Translation fidelity" drugs**: Can small molecules enhancing translation fidelity be developed;
6. **Ribosome and neurodegeneration**: Ribosomal mechanisms of erroneous protein production.

### 8.1 "Ribosomopathies and Aging": The Pathological Window of the Translation Machine

**"Ribosomopathies."** Ribosomal protein gene mutations → ribosome biogenesis defects → diseases: Diamond-Blackfan anemia (RPS19, etc.), 5q- syndrome (RPS14)—"machine tool missing parts, hematopoiesis paralyzed"—manifesting as developmental defects/cancer susceptibility—"bad machine tool, whole body suffers."

**"Ribosomal stress."** Ribosome biogenesis blocked → free RPs (e.g., RPL5/RPL11) bind MDM2 → stabilize p53 ([13-p53-structure.md](13-p53-structure.md)) → cell cycle arrest/apoptosis—"machine tool alarms, sounds the p53 alert"—this is the "ribosome-tumor suppression" connection—"the translation machine is p53's 'sensor'."

**"Ribosome and cancer."** Cancer cells require massive translation (rapid proliferation) → ribosome biogenesis↑ → targeting ribosomes is an anti-cancer strategy (e.g., RNA polymerase I inhibitors)—"attacking the cancer cell's machine tools."

**"Ribosome and aging" pathological window**: ① Ribosome damage → erroneous proteins → proteotoxicity (neurodegeneration/sarcopenia); ② Ribosomal stress → p53 activation → cellular senescence → tissue aging—"too many machine tool alarms, cells retire early"—**"the translation machine sits at the crossroads of 'synthesis-quality-stress,' an important node in aging."**

**"The anti-aging balance point"**: Neither "translation too fast" (more defective products/high energy consumption/mTOR overactivation) nor "translation too weak" (insufficient repair proteins/muscle loss/ribosomal stress)—"moderate speed reduction + maintain fidelity + avoid chronic stress"—"the machine tool should be slow and precise, not stopped, not racing."

---

## 9. Structural Data Acquisition Guide

- **PDB entries**:
  - 4V6X: Human 80S ribosome (cryo-EM)—human ribosome structure;
  - 5AJ0: Translating human polyribosome (POST state, cryo-EM)—translation cycle;
  - 4V6C/4V6D, etc.: Yeast/human ribosomes (classic cryo-EM);
  - 3J9Z, etc.: Mammalian ribosomes;
  - 1FFK, etc.: Bacterial 70S (classic X-ray);
  - 5A2L, etc.: Human 80S with eIF complexes;
  - AlphaFold: AF-P62913 (human RPL11 and other ribosomal proteins).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (Authentic Literature)

1. Khatter H, Myasnikov AG, Natchiar SK, Klaholz BP. Structure of the human 80S ribosome. *Nature* 2015;520:640-645. (First high-resolution human 80S structure)
2. Voorhees RM, Ramakrishnan V. Structural basis of the translational elongation cycle. *Annu Rev Biochem* 2013;82:203-236. (Elongation cycle structure)
3. Steitz TA. A structural understanding of the dynamic ribosome machine. *Nobel Lecture* 2009. (Ribozyme/ribosome)
4. Selman C, Tullet JM, Wieser D, et al. Ribosomal protein S6 kinase 1 signaling regulates mammalian life span. *Science* 2009;326:140-144. (rpS6 and lifespan)
5. Syntichaki P, Troulinaki K, Tavernarakis N. eIF4E function in somatic cells modulates ageing in Caenorhabditis elegans. *Nature* 2007;445:922-926. (eIF4E and lifespan)
6. Steffen KK, MacKay VL, Kerr EO, et al. Yeast life span extension by depletion of 60s ribosomal subunits is mediated by Gcn4. *Cell* 2008;133:292-302. (60S subunit and lifespan)
7. Anisimova AS, Meerson MB, Gerashchenko MV, Kulakovskiy IV, Dmitriev SE, Gladyshev VN. Multifaceted deregulation of gene expression and protein synthesis with age. *Proc Natl Acad Sci USA* 2020;117:15581-15590. (Translation and aging)

---

> **Structure Overview**: The ribosome is the cell's **"protein synthesis factory"**—40S small subunit (decoding) + 60S large subunit (peptide bond formation) working together, RNA is the catalytic main body (ribozyme), A/P/E three tRNA sites in assembly line operation (4V6X/5AJ0). **Translation fidelity** relies on dual decoding checks (~10⁻⁴ error rate); **initiation is the regulatory knob** (mTOR-eIF4E/stress-eIF2α). **During aging: translation rate↓ + fidelity↓ → erroneous protein accumulation**; **"slow translation extends lifespan"** (rpS6↓/eIF4E↓/CR/rapamycin)—"slow work yields fine products." **Anti-aging strategies**: moderately inhibit mTOR to reduce speed and maintain quality + enhance degradation to clear defective products—"slow down the machine tool to preserve precision, keep the demolition team efficient, and proteostasis holds."
