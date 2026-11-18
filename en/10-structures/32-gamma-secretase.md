# Molecular Structure Deep Dive 32: γ-Secretase — The “Aβ Scissors” of Alzheimer’s Disease and an Intramembrane Protease

> **Topic placement**: Article 32 in 10-structures (Molecular Structure Deep Dive), examining the three-dimensional structure of γ-secretase: how an intramembrane protease cleaves transmembrane proteins, how the PS1 catalytic subunit works, and its role as the “Aβ scissors” in Alzheimer’s disease (AD) and aging. It provides a structural basis for the neurodegeneration theme ([08-frontiers](../08-frontiers/README.md)) and connects proteostasis with neurodegeneration.
> **Related articles**: 20S proteasome ([20-proteasome.md](20-proteasome.md)), a proteolysis comparison; IRE1 ([31-ire1.md](31-ire1.md)), a membrane/ER-related protein; cGAS–STING ([30-cgas-sting.md](30-cgas-sting.md)), neuroinflammation; TFEB ([28-tfeb.md](28-tfeb.md)), lysosomal clearance of aggregates.

---

## 0. Structural overview

**In one sentence:** γ-Secretase is an intramembrane protease that cuts transmembrane proteins such as APP and Notch within the cell membrane. APP cleavage produces Aβ peptides, components of AD amyloid plaques; Notch cleavage contributes to development and cancer. It is an underwater pair of scissors in the membrane: it produces both “good peptides” (Notch signaling) and “bad peptides” (Aβ).

```text
γ-secretase architecture:
  PS1 (catalytic subunit, aspartyl protease) — NCT (substrate recognition) — APH-1 (scaffold) — PEN-2 (stabilization)
                    │
  Assembly: four subunits, 1:1:1:1 → transmembrane complex (~170 kDa)
                    │
  Catalysis: two PS1 aspartates (D257/D385) → intramembrane aspartyl protease
                    │
  Substrates: APP (cleavage → Aβ) / Notch (cleavage → signaling) / other transmembrane proteins
```

**Three structural features that define its function:** (1) PS1, a nine-pass transmembrane catalytic subunit whose two aspartates (D257/D385) form the active site; (2) the large extracellular domain of NCT, which recognizes the extracellular portion of substrates; and (3) the horseshoe-like arrangement of PS1 transmembrane helices, with the active site on the concave side.

**Core pathway for APP processing (amyloidogenic route):**

```text
α-secretase cleavage → sAPPα (non-amyloidogenic; no Aβ produced)
β-secretase (BACE1) cleavage → sAPPβ + C99 (transmembrane fragment)
γ-secretase cleavage of C99 → Aβ (38–43 aa) + AICD
In AD: increased Aβ42 (aggregation-prone) → oligomers/plaques → neurotoxicity
```

**Mnemonic:** γ-Secretase is the Aβ scissors inside the membrane: PS1 supplies the blades (aspartates), NCT recognizes the material, and APH-1/PEN-2 assemble the complex. It works like digging a small pool of water in oil to cut transmembrane proteins. Modulate it precisely (GSM), rather than disabling it wholesale (GSI).

---

## 1. Why γ-secretase structure matters

γ-Secretase is a central target in AD research. It cleaves APP to produce Aβ, which aggregates into amyloid plaques. Most familial AD (FAD) mutations occur in PS1, altering cleavage and often increasing Aβ42. But γ-secretase also cleaves Notch, a key signal in development and cell fate; complete inhibition blocks Notch and causes toxicity, including in the gut and immune system. Thus the enzyme produces both harmful and essential products.

Aβ aggregation is central to AD pathology, and γ-secretase modulation that lowers Aβ42 is a therapeutic direction. Aβ clearance depends on lysosomes/autophagy ([28-tfeb.md](28-tfeb.md)); accumulation is linked to proteostasis failure. γ-Secretase inhibitors and modulators (GSI/GSM) are the “brake” and “tuning” options: GSIs failed in part because of Notch toxicity, whereas GSMs aim to alter Aβ42 production while preserving other functions.

Structural studies address three questions: how can a protease cut a transmembrane protein in the membrane’s hydrophobic environment; how do PS1’s two aspartates work; and how is substrate specificity (APP versus Notch) achieved? Structures such as 5A63 (2015) and 5FN5 (a conformational state, 2015) help answer them.

---

## 2. Structural anatomy of γ-secretase

### 2.1 PS1 catalytic subunit: the underwater scissors

PS1 crosses the membrane nine times and has an intramembrane aspartyl-protease fold. Its catalytic dyad consists of D257 and D385 in TM6/TM7. Structure 5A63 revealed considerable flexibility in TM2/TM6—a “plastic” active site able to accommodate different substrates. Many FAD mutations cluster in the centers of two four-helix bundles (TM bundles A/B), where they can alter substrate cleavage.

### 2.2 NCT extracellular domain: the material-recognition inlet

NCT has a large (~700-aa) extracellular domain and one transmembrane segment. Its large beta-propeller-like domain recognizes the extracellular portion of substrates and helps determine substrate specificity and timing. In 5A63, NCT undergoes a conformational change after substrate recruitment, opening to allow the substrate to enter.

### 2.3 APH-1/PEN-2: scaffold and rivet

APH-1 is a seven-pass transmembrane scaffold. It anchors NCT’s transmembrane helix and supports PS1’s flexible conformation. PEN-2 is a small transmembrane protein that stabilizes PS1 maturation and complex assembly. PS1, NCT, APH-1, and PEN-2 assemble in a 1:1:1:1 ratio into the functional complex.

---

## 3. Molecular logic of an intramembrane protease: from structure to chemistry

### 3.00 The engineering logic of “digging a pool in oil”: why γ-secretase locally creates a water environment

Aspartyl proteases (including pepsin and cathepsin D) use two aspartates and a water molecule for catalysis. γ-Secretase inherited this catalytic chemistry: water is required, but the membrane interior is hydrophobic. Its solution is to form a hydrophilic cavity between transmembrane helices, lined by polar residues, creating a local aqueous environment. It does not turn the whole membrane into water; it digs a small well in the oil.

Stabilizing polar residues inside the membrane has a cost, but allows membrane proteins such as APP and Notch to be processed without first extracting them from the membrane. Soluble proteases work in an aqueous environment already; γ-secretase brings its own water. Evolution retained the same catalytic chemistry but adapted its working environment.

### 3.10 The mystery of substrate “unwinding”: straightening a transmembrane helix

Transmembrane substrates such as C99 and Notch are α-helices, with peptide bonds inaccessible to the protease. Before cleavage, the helix must be unwound into an extended chain so that the peptide bond is exposed. The substrate enters from a lateral opening between transmembrane helices; the PS1 active site lies on the concave side of the horseshoe (5A63). As the helix is forced into the hydrophilic cavity, it locally unwinds.

Breaking helix-stabilizing hydrogen bonds costs energy. γ-Secretase can use substrate-binding energy—NCT recognition plus interaction with the PS1 pocket—to pay that cost: tight binding helps straighten the helix. This contrasts with the proteasome ([20-proteasome.md](20-proteasome.md)), which uses an ATP-powered motor to mechanically unfold substrates. γ-Secretase uses binding energy rather than ATP: mechanical unfolding versus chemical “leverage.”

### 3.20 The logic of Aβ length: why the γ cut determines toxicity

γ-Secretase performs processive cleavage. It first cuts at the ε site near the membrane-proximal C terminus, then trims back through ζ and γ sites, producing Aβ peptides of different lengths (Aβ48/46/43/42/40/38, among others). Aβ42 has two additional hydrophobic residues (IA) relative to Aβ40, making it more prone to aggregation and toxic oligomer formation.

FAD mutations in PS1 can cause cleavage to terminate early or shift the γ-site, increasing the Aβ42 fraction and aggregation. The Aβ42/40 ratio is a readout of γ-secretase “tuning.” A γ-secretase modulator (GSM) can shift processing toward shorter Aβ38/40 and reduce Aβ42 without destroying the enzyme or its Notch function. GSMs are a precision “tuning knob,” not a dismantling of the scissors.

A conceptual AD/healthy-aging strategy is to reduce Aβ burden at several points: modulate γ-secretase (lower Aβ42), inhibit BACE1 (supply less substrate), and improve clearance (autophagy/lysosomes). This complements SIRT6’s genome-protection role: reduce harmful peptides while protecting the genome.

The same mechanism can be summarized as follows: aspartyl-protease chemistry needs water; PS1 creates a water-filled cavity within the membrane; the substrate helix must unwind so its peptide bond can reach that cavity; and sequential ε→ζ→γ cleavage yields Aβ peptides of different lengths. Aβ42 is especially aggregation-prone. Unlike the proteasome, which acts on unfolded soluble proteins in the cytosol, γ-secretase processes transmembrane proteins inside a hydrophobic bilayer by creating a local aqueous pocket.

### 3.1 APP processing and pathway choice: α versus β versus γ

Three routes determine how much Aβ is produced. In the **α-secretase pathway**, α-secretase cuts within the Aβ sequence to generate sAPPα and C83; γ-secretase then cuts C83 to produce p3, which does not aggregate into Aβ. This is the non-amyloidogenic route. In the **β-secretase pathway**, BACE1 cuts at the N terminus of the Aβ sequence, yielding sAPPβ and C99; γ-secretase then cuts C99 to produce Aβ. The final γ cleavage determines peptide length (Aβ40 versus Aβ42), with Aβ42 more aggregation-prone.

FAD-associated PS1 mutations can shift γ cleavage, raising the Aβ42/Aβ40 ratio and aggregation risk. Potential strategies include reducing Aβ production through BACE1 inhibition, modulating γ cleavage with GSMs to lower Aβ42, and enhancing lysosomal/autophagic clearance ([28-tfeb.md](28-tfeb.md)): make less and clear more.

---

## 4. γ-Secretase and aging: the scissors losing control

### 4.1 AD and aging through the γ-secretase lens

Aβ can accumulate with age when production through γ cleavage changes and clearance through autophagy/lysosomes declines. The amyloid-cascade hypothesis proposes that Aβ oligomers damage synapses, contribute to tau tangles, and drive neurodegeneration—Aβ is an upstream trigger. PS1 mutations cause early-onset FAD (often around age 50) through abnormal cleavage and increased Aβ42. In sporadic AD, impaired clearance ([28-tfeb.md](28-tfeb.md)) and inflammation (cGAS–STING, [30-cgas-sting.md](30-cgas-sting.md)) may contribute to Aβ accumulation.

### 4.2 Strategies to maintain precision

- **γ-Secretase modulators (GSMs):** alter cleavage preference rather than suppressing the whole enzyme, lowering Aβ42 while preserving Notch.
- **BACE1 inhibitors:** reduce C99 substrate and therefore Aβ supply; clinical development has faced dose-limiting toxicity.
- **Improve Aβ clearance:** lysosomes/autophagy ([28-tfeb.md](28-tfeb.md)) and exercise may help remove peptides.
- **Reduce inflammation:** modulate neuroinflammatory pathways such as cGAS–STING/NF-κB to limit injury.
- **Moderation:** complete γ-secretase inhibition (GSI) disrupts Notch and causes gut/immune toxicity, a lesson from clinical trials. The scissors should be tuned, not removed.

### 4.4 Neurodegeneration and proteostasis: why Aβ accumulation is part of proteome failure

Aβ aggregation is not an isolated AD lesion; it is one manifestation of proteostasis failure in the nervous system. The Aβ sequence contains a strongly hydrophobic C-terminal region and a propensity for beta-sheet formation, so it can self-aggregate at high concentration or when clearance falters. Autophagy/lysosomal function declines with age ([28-tfeb.md](28-tfeb.md)), lowering Aβ clearance and promoting aggregation.

Aβ oligomers can activate microglia and inflammation (cGAS–STING/NF-κB; [30-cgas-sting.md](30-cgas-sting.md)); inflammation damages neurons and may promote further aggregation, creating a self-amplifying cycle. Tau tangles, α-synuclein in Parkinson’s disease, and other aggregation disorders share a physical theme: abnormal protein assembly. A broad proteostasis approach therefore aims to prevent aggregation and clear aggregates efficiently.

### 4.5 γ-Secretase and Notch: balancing good and bad products

γ-Secretase cuts two important substrates. Notch cleavage releases NICD (the Notch intracellular domain), which enters the nucleus and alters transcription involved in development, stem cells, immunity, and the gut. Notch acts as a switch for development and regeneration, and changes in Notch signaling may affect regenerative capacity with age.

The “one-size-fits-all” GSI approach sought to lower Aβ by fully inhibiting γ-secretase, but also blocked Notch and caused gut and immune toxicity. The phase 3 semagacestat trial failed in 2013. GSMs instead aim to change cleavage preference (lower Aβ42) without broadly inhibiting the enzyme, preserving Notch. Structural studies (5A63/6IDF and related work) investigate how NCT and the PS1 pocket recognize different substrates such as APP and Notch.

The central principle is precision: preserve beneficial products while reducing harmful ones. The relevant pathway is γ-secretase production of Aβ → aggregation → inadequate lysosomal/autophagic clearance → inflammation → neurodegeneration. An integrated AD strategy is “make less” (modulate γ cleavage), “clear more” (autophagy), and “put out the fire” (limit inflammation).

| Stage | Molecule | Structural article | Role |
|---|---|---|---|
| Peptide production | γ-secretase | [32-gamma-secretase.md](32-gamma-secretase.md) | Aβ generation |
| Aggregation | Aβ/Tau | Not listed | Pathological aggregation |
| Clearance | Lysosome/autophagy | [28-tfeb.md](28-tfeb.md) / [18-lc3-autophagy.md](18-lc3-autophagy.md) | Removal |
| Inflammation | cGAS–STING | [30-cgas-sting.md](30-cgas-sting.md) | Neuroinflammation |

---

## 5. Evidence grading

| Structural/biological fact | Evidence | Basis |
|---|---|---|
| γ-Secretase is an intramembrane aspartyl protease | ★★★★★ Established | 5A63 and related structures |
| PS1 is the catalytic subunit (D257/D385) | ★★★★★ Established | 5A63 (2015, *Nature*) |
| Four-subunit assembly (PS1/NCT/APH-1/PEN-2) | ★★★★★ Established | 5A63 |
| TM2/TM6 flexibility (“plastic” active site) | ★★★★★ Established | 5A63/5FN5 |
| PS1 four-helix bundles contain FAD mutation hotspots | ★★★★★ Established | 5A63 |
| γ-Secretase cleavage of APP produces Aβ | ★★★★★ Established | Classical biochemistry |
| FAD mutations alter the Aβ42/40 ratio | ★★★★★ Established | Genetics and biochemistry |
| GSIs failed due to Notch toxicity | ★★★★★ Established | Clinical trials |

---

## 6. Connections to the knowledge-base themes

### 6.0 Structural overview of proteolysis: three cellular “scissors”

| Machinery | Location | Substrate | Structural article |
|---|---|---|---|
| 20S proteasome | Cytosol | Unfolded proteins | [20-proteasome.md](20-proteasome.md) |
| γ-Secretase | Membrane | Transmembrane proteins | [32-gamma-secretase.md](32-gamma-secretase.md) |
| Lysosomal hydrolases | Lysosome | Contents, in acidic conditions | Related to [28-tfeb.md](28-tfeb.md) |

The proteasome handles individual cytosolic proteins, γ-secretase cuts transmembrane proteins in the bilayer, and lysosomes handle large cargo and organelles in an acidic compartment. These distinct locations require distinct processing systems. With aging, proteasome activity can decline ([20-proteasome.md](20-proteasome.md)), autophagy/lysosomes can falter ([18-lc3-autophagy.md](18-lc3-autophagy.md), [28-tfeb.md](28-tfeb.md)), and γ-secretase cleavage may shift toward Aβ42. The overall proteolytic system can therefore deteriorate, increasing aggregate-disease risk. Supporting proteasome function (including Nrf2-related pathways), autophagy initiation ([27-ulk1.md](27-ulk1.md), fasting), and lysosomal acidification ([29-v-atpase.md](29-v-atpase.md)) represents complementary ways to maintain clearance.

### 6.2 Connections to the neurodegeneration network

### 6.1 Connections to other central articles

- **20S proteasome** ([20-proteasome.md](20-proteasome.md)): cytosolic versus intramembrane proteolysis.
- **IRE1** ([31-ire1.md](31-ire1.md)): ER transmembrane sensor, another membrane protein.
- **TFEB** ([28-tfeb.md](28-tfeb.md)): lysosomal Aβ clearance.
- **cGAS–STING** ([30-cgas-sting.md](30-cgas-sting.md)): neuroinflammation triggered in the context of Aβ.
- **LC3/autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Aβ removal by cellular recycling.
- **Hsp70** ([23-hsp70.md](23-hsp70.md)): chaperone rescue and aggregate prevention.

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How can γ-secretase cut in a membrane? | PS1 aspartates + local water cavity + substrate unwinding: a pool in the oil |
| How is Aβ generated? | β cleavage creates C99; γ cleavage then releases Aβ, with the γ site determining length |
| Why is Aβ42 more toxic? | Its hydrophobicity favors aggregation and toxic oligomers |
| How do FAD mutations cause disease? | PS1 mutations shift γ cleavage and increase Aβ42: mis-tuned scissors |
| What may help in AD/aging? | GSM modulation + BACE1 inhibition + enhanced clearance + anti-inflammatory approaches |

---

## 8. Open questions

1. **Complete mechanism of substrate entry:** dynamics of transmembrane-substrate entry and unwinding.
2. **Processive γ-secretase cleavage:** molecular basis of sequential ε→ζ→γ cleavage.
3. **GSM binding site:** structural basis for how modulators change cleavage preference.
4. **Substrate specificity:** how APP and Notch are selected, including NCT’s role.
5. **γ-Secretase and lipids:** effects of the membrane lipid environment on activity.
6. **Early AD intervention:** optimal timing for Aβ clearance or modulation.

### 8.2 Historical lessons from γ-secretase research: three decades from biochemistry to structural biology

The history of γ-secretase research illustrates the path from biochemistry to atomic-level understanding. In the 1990s, PS1 mutations were linked to FAD (1995), and biochemical experiments showed that PS1 is a γ-secretase catalytic subunit (1998–1999), including loss of activity after aspartate mutation. In the 2000s, the four-subunit complex was identified (PS1/NCT/APH-1/PEN-2, around 2003) and GSIs/GSMs were developed, but the active site remained a “black box” because membrane proteins were difficult to crystallize.

The cryo-EM breakthrough came in 2015: structure 5A63 (~3.4 Å) revealed the PS1 transmembrane bundle, catalytic aspartates, and horseshoe-like arrangement. Mapping FAD mutations onto the structure connected mutation sites to possible effects on substrate access and cleavage—moving from “where is the mutation?” to “how does it cause disease?” Structural biology turns a black box into a blueprint and can support rational precision-modulator design.

### 8.3 Beyond Aβ: Notch and aging

Notch cleavage by γ-secretase also matters in aging. Notch signaling supports stem cells in the gut, muscle, and nervous system; age-related changes in Notch could reduce regenerative capacity. Changes in γ-secretase activity or assembly could affect both APP cleavage (Aβ production) and Notch cleavage (regeneration). The lesson is balance: do not eliminate a molecule indiscriminately; tune its outputs. GSM-like modulation is preferable in principle to GSI-like shutdown. Structural knowledge makes such tuning conceivable because it identifies the relevant binding and cleavage regions.

---

## 9. Guide to structural data

- **PDB entries:**
  - **5A63**: atomic structure of human γ-secretase (3.4 Å cryo-EM; Bai 2015, *Nature*), showing PS1 catalysis and complex assembly.
  - **5FN2–5FN5**: γ-secretase conformational states (Bai 2015, *eLife*), illustrating the flexible active site.
  - **6IDF/6IDG** and related entries: γ-secretase with substrates/inhibitors.
  - **5XG3** and related entries: expanded human γ-secretase structural studies.
  - **AlphaFold**: AF-P49768, human PS1.
- **Viewing tools:** RCSB online 3D viewer, PyMOL, or ChimeraX.

---

## 10. References (published literature)

1. Bai X, Yan C, Yang G, et al. An atomic structure of human gamma-secretase. *Nature* 2015;525:212–217. (PDB 5A63)
2. Bai XC, Rajendra E, Yang G, Shi Y, Scheres SH. Sampling the conformational space of the catalytic subunit of human gamma-secretase. *eLife* 2015;4:e11182. (PDB 5FN5)
3. Wolfe MS, Xia W, Ostaszewski BL, Diehl TS, Kimberly WT, Selkoe DJ. Two transmembrane aspartates in presenilin-1 required for presenilin endoproteolysis and gamma-secretase activity. *Nature* 1999;398:513–517. (PS1 aspartates)
4. De Strooper B, Saftig P, Craessaerts K, et al. Deficiency of presenilin-1 inhibits the normal cleavage of amyloid precursor protein. *Nature* 1998;391:387–390. (PS1–γ-secretase)
5. Selkoe DJ, Hardy J. The amyloid hypothesis of Alzheimer’s disease at 25 years. *EMBO Mol Med* 2016;8:595–608. (Amyloid hypothesis review)
6. Yang G, Zhou R, Zhou Q, et al. Structural basis of Notch recognition by human gamma-secretase. *Nature* 2019;565:192–197. (Notch substrate recognition)
7. Doody RS, Raman R, Farlow M, et al. A phase 3 trial of semagacestat for treatment of Alzheimer’s disease. *N Engl J Med* 2013;369:341–350. (GSI clinical-trial lesson)

---

> **Structural overview:** γ-Secretase is an intramembrane protease: PS1 (aspartyl catalytic dyad D257/D385), NCT (substrate recognition), APH-1 (scaffold), and PEN-2 (stabilization) assemble as a four-subunit complex. Structure 5A63 reveals how it creates a local water cavity in the membrane to cleave transmembrane proteins. APP processing generates Aβ, with the γ cleavage site determining the Aβ42/40 ratio; Aβ42 aggregates readily. γ-Secretase also cleaves Notch, so it produces both beneficial and harmful outputs. FAD PS1 mutations can increase Aβ42; full inhibition with GSIs caused Notch toxicity. The principle is to tune, not dismantle, the scissors (GSM), while reducing substrate input (BACE1 inhibition), improving clearance (autophagy/lysosomes), and limiting inflammation.
