# Molecular Structure Deep Dive 02: sGC and H-NOX Heme Sensors—The Atomic Mechanism of NO Sensing

> **Topic placement**: Article 2 in 10-structures (Molecular Structure Deep Dives)—anatomy of how soluble guanylate cyclase (sGC) “smells” NO with picomolar sensitivity and amplifies the signal 200–400-fold. This is the structural basis of the “signal-receiving end” of the NO pathway.
> **Related articles**: NO signaling pathway: [01-foundations/03-no-basics.md](../01-foundations/03-no-basics.md), Section 2; sGC pharmacology: [04-drugs/05-molecular-mech.md](../04-drugs/05-molecular-mech.md), Section 2; NO and cardiovascular biology: [02-vascular/01-no-cardiovascular.md](../02-vascular/01-no-cardiovascular.md); NOS structure: [01-nos-structures.md](01-nos-structures.md) in this series.

---

## 1. Core concept: A heme protein with a “space reserved for NO”

sGC is the central receptor for mammalian NO signaling: after NO binds its heme, enzyme activity rises 200–400-fold, converting GTP into the second messenger cGMP. Its structural design revolves around one core strategy—**leaving the sixth coordination site of heme iron vacant, specifically to reserve it for NO**.

This design involves three atomic-level features:

1. **Five-coordinate heme**: In the resting state, Fe²⁺ coordinates only with proximal His; the sixth site is vacant (unlike the six-coordinate heme in oxyhemoglobin);
2. **High-affinity NO binding**: NO binds at picomolar-to-nanomolar concentrations, forming a transient six-coordinate complex;
3. **Signal amplification through His-bond cleavage**: NO binding triggers Fe–His bond cleavage → the heme “domes” → the conformational change propagates through the protein → the catalytic domain is activated.

## 2. Overall architecture: Domain organization of the H-NOX sensor

sGC is an α/β heterodimer (mainly α1β1, with α2β1 also present), with each subunit weighing approximately 70–80 kDa. Its domain organization from the N- to the C-terminus is:

| Domain | Position (β1 numbering) | Function |
|---|---|---|
| H-NOX domain (heme-binding) | β1 1–190 | NO sensing (heme) |
| PAS domain | β1 ~200–250 | Protein interaction/regulation |
| Coiled-coil domain (CC) | β1 ~250–360 | Dimerization + conformational transmission |
| Catalytic domain (GC) | β1 ~360–619 | GTP→cGMP (forms the catalytic unit with α subunit) |

The **H-NOX (Heme-Nitric Oxide/OXygen binding) domain** is the sensing core and belongs to an ancient family of bacterial signaling proteins (H-NOX also occurs in NO-sensitive prokaryotes). **Key point: the heme-binding pocket of the H-NOX domain is designed to be “NO-specific.”** An empty sixth coordination site plus the geometry of a hydrophobic pocket give it much higher affinity for NO than for O₂ (in contrast to differences in O₂ sensitivity among bacterial homologues of soluble guanylate cyclase).

## 3. Heme pocket of the H-NOX domain: Atomic-level anatomy

### 3.1 Heme coordination state

```text
Resting state (five-coordinate):
  His105(β1)─Nε ── Fe²⁺ ── (sixth site vacant, reserved for NO)
                 │
              Porphyrin ring (heme b)

NO-bound state (transient six-coordinate):
  His105─Nε ── Fe²⁺ ── NO (axial binding)
                 │
              Porphyrin ring
```

- **Proximal ligand**: The imidazole Nε of **His105** in the β1 subunit coordinates axially to heme Fe²⁺ (five-coordinate, high-spin state);
- **Vacant distal site**: The sixth coordination site is empty, “designed” as a dedicated NO-binding site. Hydrophobic pocket residues (Phe, Leu, Ile, etc.) exclude water, so NO can bind without having to “displace water” (lowering the binding-energy barrier);
- **After NO binds**: A transient six-coordinate state forms (His–Fe–NO), after which the His–Fe bond breaks (His is “pushed away”) and heme becomes five-coordinate Fe²⁺–NO—**His dissociation is the key step that generates the signal**.

### 3.1a Why NO is “seen” but O₂ is not: Structural chemistry of ligand selectivity

The heme pocket of sGC faces a formidable chemical challenge: **NO and O₂ are similar in size and can both coordinate Fe²⁺, but sGC must “recognize NO and ignore O₂”**—otherwise, 21% O₂ in the blood would permanently activate sGC. How is this selectivity achieved? Structural chemistry gives three answers:

**First: kinetics rather than thermodynamics.** sGC has extremely high affinity for NO (picomolar), but O₂ makes only a “fleeting visit”—after binding, O₂ dissociates quickly and cannot trigger the conformational cascade leading to His dissociation. The key is that **pocket geometry prevents “stable binding” of O₂**: O₂ requires a distal hydrogen-bond donor (such as histidine) to stabilize the Fe–O₂ complex, as in hemoglobin/myoglobin. The sGC heme pocket **lacks such a distal hydrogen-bond network**—O₂ cannot “get a foothold” and cannot remain long enough to trigger a conformational change. NO is different: it is a strong π acceptor, and back-bonding with Fe (Fe→NO dπ–pπ* electron back-donation) stabilizes binding without dependence on distal hydrogen bonds.

**Second: NO signal specificity comes from His dissociation, not simple binding.** Even if O₂ briefly binds Fe²⁺, it does not cause His dissociation (the ligand-field effect of O₂ is insufficient to weaken the Fe–His bond). After NO binds, the trans effect greatly weakens the Fe–His bond and changes the porphyrin’s doming conformation, making His dissociation inevitable—**“binding” is only the first step; “His dissociation” is the signal, and His dissociation is unique to NO.**

**Third: bacterial H-NOX provides a “control experiment.”** The H-NOX of *Shewanella oneidensis* is O₂-sensitive (for oxygen sensing) and has a distal tyrosine (Tyr140) in its pocket that provides a stabilizing hydrogen bond for O₂. At the corresponding position, sGC-type H-NOX has a hydrophobic residue—**a difference of one residue can determine whether a protein is an “oxygen sensor” or a “nitric oxide sensor.”** This is one of the most elegant examples of structural evolution.

**Why is sGC’s response to NO switch-like?** NO binding + His dissociation → heme changes from a “planar” to a “domed” conformation → triggers a global rearrangement of the H-NOX domain. This is not a “graded” signal but an “all-or-none” conformational switch (like a transistor switching “on”). This explains the 200–400-fold activation of sGC: one NO molecule triggers a conformational cascade.

### 3.2 Pocket residues and NO selectivity

The high selectivity of the H-NOX pocket for NO results from a combination of geometry and chemistry:

| Feature | Structural detail | Function |
|---|---|---|
| Empty sixth coordination site | No endogenous distal ligand | NO binds without competition |
| Hydrophobic pocket | Phe4, Trp, etc. form a narrow cavity | Excludes water/O₂; favors NO |
| “Tension” on His105 | Angle between imidazole and porphyrin plane | Affects propensity for His dissociation |
| Pocket volume | Just accommodates NO (a small molecule) | Excludes larger ligands |
| Proximal hydrogen-bond network | His105 imidazole Nδ with Glu/water | Stabilizes proximal coordination |

**Why does NO binding trigger His dissociation?** NO is a strong π-acceptor ligand. After binding Fe²⁺, it greatly increases electron-density back-donation from Fe, strengthening the Fe–NO bond relative to the Fe–His bond. At the same time, the bent geometry of NO (Fe–N–O ~120°) creates steric conflict with the porphyrin plane and pushes His away from the axial position—**“NO pushing His away” is the atomic-level switch in this signaling system.**

### 3.3 Oxidative deafness: Structural “lockup” in the Fe³⁺ state

During aging/oxidative stress, heme Fe²⁺ is oxidized to Fe³⁺ (the ferric state):

- Fe³⁺ affinity for NO drops sharply (NO preferentially stabilizes the Fe²⁺ state);
- Fe³⁺–OH⁻ occupies the sixth coordination site (water/hydroxide coordination), physically blocking NO from binding;
- Result: sGC becomes “deaf” to NO—even abundant NO cannot activate it (“NO signal blind spot”).

**This explains the structural difference between sGC stimulators (riociguat) and sGC activators (cinaciguat)**: stimulators act synergistically with NO when heme is intact (Fe²⁺); activators can directly activate the catalytic domain when heme is oxidized or absent (Fe³⁺ or heme-free)—activators “bypass” the damaged sensor.

### 3.3a The “cellular battleground” of heme redox: Dynamic balance between Fe²⁺/Fe³⁺

The redox state of sGC heme (Fe²⁺ vs. Fe³⁺) is not static, but a “battleground” dynamically regulated by the cellular environment:

**Sources of oxidation.** (1) Reactive oxygen species (O₂⁻, H₂O₂) directly oxidize heme iron; (2) peroxynitrite (ONOO⁻, the product of NO + O₂⁻) is an even stronger oxidant. **Ironically, overactivation of the NO pathway (high NO production by iNOS during inflammation) can generate ONOO⁻, which oxidizes sGC heme**, creating a negative-feedback loop of “excess NO → sGC deafness” (explaining blunted NO signaling in chronic inflammation); (3) increased oxidative stress in aging tissues raises the Fe³⁺ fraction.

**Routes of reduction.** Can Fe³⁺ sGC be reduced back to Fe²⁺? Studies indicate that (1) intracellular ascorbate (vitamin C) can reduce Fe³⁺ sGC (in vitro); (2) the glutathione system may also participate; but (3) **reduction efficiency is limited**—oxidative “lockup” tends to accumulate in aging/chronic inflammatory tissues. The “fraction of oxidized sGC heme” therefore rises with age/disease and is a structural marker of “NO resistance.”

**Clinical relevance.** (1) A partial mechanism of nitroglycerin tolerance: chronic nitrate use → sustained high NO → oxidative stress → sGC heme oxidation → reduced response to NO (a structural explanation for “tolerance”); (2) the proportion of oxidized sGC is elevated in heart failure (oxidative stress + inflammation), explaining why sGC activators (targeting the Fe³⁺ state) may be preferable to stimulators in advanced heart failure; (3) **“NO resistance” in older people**: even with normal NO bioavailability (good eNOS function), heme oxidation reduces sGC responsiveness—“there are two vulnerable points in the NO signaling chain” (reduced NO production by eNOS + failure of sGC to sense NO). Anti-aging strategies need to repair both ends (exercise/nitrates target the eNOS end; antioxidants/activators target the sGC end).

## 4. Conformational transmission: The signal path from heme to catalytic domain

NO binding + His dissociation → change in heme-planarity conformation → H-NOX rearrangement → transmission across the coiled-coil domain → rotation and closure of the catalytic domains. Key structural event:

### 4.1 A rigid-body rotation of 26°

Based on superposition analysis of PDB 3UVJ (human sGC α/β catalytic-domain heterodimer, 2.08 Å, Allerston 2013) and the active conformation of adenylyl cyclase: **the α subunit undergoes an approximately 26° rigid-body rotation relative to the β subunit**, switching from an “inactive conformation” to an “active conformation.” Active-site residues contributed by the interface between the two subunits align precisely during this rotation.

### 4.1a The “domino chain” of conformational transmission: From heme to cGMP

Conformational transmission in sGC is a precise domino chain, with each step amplifying the signal:

**Domino one: Heme “doming.”** After NO binds and His105 dissociates, heme iron “arches” out of the porphyrin plane (doming), changing the iron–porphyrin geometry—this is the “initial push” for signal transmission in heme proteins.

**Domino two: H-NOX rearrangement.** Heme doming changes helix-loop contacts within H-NOX, shifting the domain’s α helices (especially the F helix)—a “millimeter-scale deformation of heme” is amplified into an “angstrom-scale rearrangement of the H-NOX domain.”

**Domino three: “Unlocking” the coiled coil.** The movement of H-NOX is transmitted to the C-terminal coiled-coil domain. The coiled coil is the “drive shaft” between the two subunits; its relative sliding/rotation changes the spatial relationship between the α and β subunits. **At rest, the coiled coil “locks” the catalytic domains in an inactive conformation; the NO signal “unlocks” them through the coiled coil.**

**Domino four: 26° rotation of the catalytic domain.** Finally, the α subunit rotates about 26° relative to β—active-site residues at the subunit interface change from “misaligned” to “aligned,” allowing GTP to enter and cyclize into cGMP.

**The “lever” of signal amplification**: from a single NO molecule (~1.5 Å in diameter), through a 26° domain rotation, to a 200–400-fold increase in activity—each domino is a structural “lever.” This also explains how sGC works at picomolar NO concentrations: **it relies not on “quantity” (binding many molecules) but on “leverage” (one molecule triggering a cascade)**—a “single-photon detector”-like design for biological signal transduction.

**“Two-metal catalysis” of cGMP generation**: Once the active site is aligned, two Mg²⁺ ions cooperate in GTP cyclization—Mg²⁺-A coordinates the α-phosphate of GTP and stabilizes the leaving group; Mg²⁺-B coordinates the β/γ-phosphates and activates the 3′-OH for nucleophilic attack. **“Two metals position the substrate + 3′-OH attacks the α-phosphate”** is the general catalytic chemistry of cyclases (adenylyl/guanylyl cyclases). The rate of cGMP production rises hundreds-fold after NO activation—“the enzyme is the same; conformation determines flux.”

### 4.2 “Two-subunit active site” of the catalytic domain

The active site of the sGC catalytic (GC) domain is **formed jointly by residues at the interface between the α and β subunits**, following the “two-monomer active site” arrangement of adenylyl cyclase:

```text
β subunit contributes: GTP-binding residues (phosphate groups, ribose recognition)
α subunit contributes: catalytic metal (Mg²⁺/Mn²⁺)-coordinating residues (Asp/Glu)
Alignment of both → 3′-OH of GTP nucleophilically attacks α-phosphate → cyclization → cGMP
```

- Metal ions (Mg²⁺) are coordinated by aspartate/glutamate residues from the α subunit, while the phosphate groups of GTP are stabilized by arginine/lysine residues from the β subunit;
- The 26° rotation changes these residues from “misaligned” to “aligned”—the structural basis for the 200–400-fold increase in activity;
- Production of cGMP depends on cooperation between two Mg²⁺ ions (the classical two-metal mechanism).

### 4.3 Pseudosymmetric allosteric site

The 3UVJ structure also revealed a cavity **pseudosymmetric** to the active site. Located nearby and surrounded by mirror-image residues, it lacks key catalytic residues—**it may serve as an allosteric regulatory site**. This offers a structural lead for “regulating sGC from a non-active site” (some sGC activators may bind there).

## 5. Structural basis of pharmacology: How three drug classes act on sGC

| Drug class | Representative | Binding/action site | Structural mechanism |
|---|---|---|---|
| NO donor | Nitroglycerin | Heme Fe²⁺ (releases NO) | NO binding → His dissociation → activation |
| sGC stimulator | Riociguat, vericiguat | Near heme (H-NOX domain) | Stabilizes NO-bound state / directly enhances activity in Fe²⁺ state |
| sGC activator | Cinaciguat | Heme pocket (when oxidized/absent) | Mimics heme conformational effect, bypassing Fe³⁺ lockup |

The clinical benefits in the **VICTORIA trial (vericiguat, heart failure) and PATENT trial (riociguat, pulmonary hypertension)** fundamentally reflect “using drugs to compensate for impaired sGC sensing when NO signaling is insufficient (endothelial dysfunction, oxidative stress)”—closely related to age-associated eNOS↓/NO↓/heme oxidation (see [01-no-cardiovascular](../02-vascular/01-no-cardiovascular.md), Section 5).

## 6. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| sGC α/β catalytic-domain heterodimer structure | ★★★★★ Definitive | PDB 3UVJ, 2.08 Å |
| 26° rigid-body rotation creates active conformation | ★★★★ Strong | Superposition analysis + functional validation |
| Two-subunit active site (residues contributed by α/β) | ★★★★★ Definitive | Crystal structure + mutagenesis |
| Five-coordinate heme in H-NOX (His105) | ★★★★★ Definitive | Bacterial H-NOX crystals + sGC spectroscopy |
| NO binding triggers His dissociation | ★★★★ Strong | Resonance Raman + structural modeling |
| Fe³⁺ oxidation causes NO deafness | ★★★★★ Definitive | Spectroscopy + function |
| Pseudosymmetric allosteric site | ★★★ Moderate | Structural observation (function awaits validation) |

**A “tiered philosophy” of structural evidence**: The evidence grading in this article illustrates the distinctive epistemology of structural biology. A crystal structure itself is “hard evidence” (★★★★★), but every inference from structure to function (how His dissociation is transmitted, whether 26° rotation is sufficient for activation, whether the pseudosymmetric site has a ligand) needs biochemical/mutational/kinetic validation (downgraded to ★★★★ or ★★★). **“Structure generates hypotheses; functional experiments test them”** is standard practice in structural biology—and why [08-frontiers/04-ai-drugs/01-ai-discovery.md](../08-frontiers/04-ai-drugs/01-ai-discovery.md) emphasizes that “AI-predicted structures must be experimentally confirmed.”

## 7. Connections to the knowledge base’s main themes

- **NO–sGC–cGMP pathway** ([03-no-basics](../01-foundations/03-no-basics.md), 2.1): this article adds “atomic-level” details—His105 dissociation, 26° rotation, and two-metal catalysis;
- **sGC pharmacology** ([05-molecular-mech](../04-drugs/05-molecular-mech.md), Section 2): the structural difference between stimulators and activators is explained at the atomic level here;
- **Vascular aging** ([01-no-cardiovascular](../02-vascular/01-no-cardiovascular.md)): heme oxidation (Fe³⁺) is the structural source of the “NO signal blind spot.” The increasing fraction of oxidized sGC heme with age is the second vulnerable point in the decline of the NO pathway (the first is reduced NO production by eNOS);
- **Anti-aging strategies targeting sGC**: repurposing older drugs such as vericiguat/riociguat to improve vascular stiffness in older people is based on clear structure–mechanism logic; what is missing is validation in trials using aging clocks as endpoints.

## 8. Open questions

1. **High-resolution structure of full-length sGC**: A full-length cryo-EM snapshot of the complete conformational-transmission chain from H-NOX to the catalytic domain is lacking (only separate-domain structures are currently available);
2. **Kinetics of His dissociation**: The transition-state structure from NO binding to His bond cleavage has not been captured (requiring time-resolved crystallography/femtosecond spectroscopy);
3. **Restoration of the oxidized state**: Can Fe³⁺ sGC be regenerated by in vivo reducing systems (e.g., ascorbate)? Is oxidative “lockup” reversible?
4. **Function of the pseudosymmetric site**: Does a physiological ligand for allosteric regulation exist?
5. **Tissue-specific β2 isoform**: Structural differences between α2β1 and α1β1 and the functional significance of their tissue distribution.

## 8.1 Allosteric regulation and drug development for sGC: From structure to clinic

The distinctive structure of sGC (a heme sensor plus a druggable catalytic domain) makes it an important cardiovascular drug target; structural studies have directly advanced drug development:

- **sGC stimulators (riociguat, vericiguat)**: These bind an allosteric site near heme and can partially activate the enzyme even without NO. Structurally, they stabilize the “NO-bound” conformation of H-NOX (even at low NO concentrations) or directly enhance basal activity in the Fe²⁺ state. Riociguat was approved for pulmonary arterial hypertension (PATENT trial), and vericiguat for heart failure (VICTORIA trial, *NEJM* 2020)—clinical validation of “sGC stimulators = compensation for insufficient NO signaling”;
- **sGC activator (cinaciguat)**: Targets oxidized (Fe³⁺) or heme-deficient sGC. In tissues with oxidative stress/aging (where the proportion of oxidized heme is high), an activator can still “bypass” the damaged sensor and directly activate the catalytic domain. This structural rationale gives it unique potential in “NO-resistant” states (advanced heart failure, diabetic vascular disease);
- **Clinical significance of NO-independent activation**: In endothelial dysfunction (eNOS↓/NO↓), sGC is the “second damaged point” in the signaling chain (first, reduced NO production by eNOS; second, heme oxidation and loss of NO sensing)—**sGC stimulators/activators target the second damaged point**, complementing exercise/nitrates (targeting the first) (see the comparison of “NO supplementation strategies” in [01-no-cardiovascular](../02-vascular/01-no-cardiovascular.md), Section 7.2).

## 8.2 Evolution of the H-NOX family and lessons from “oxygen sensitivity”

The H-NOX domain occurs across a wide range of species, from bacteria to humans, but **geometric differences in the heme pocket determine ligand selectivity**:

- **sGC-type H-NOX**: Empty sixth coordination site + hydrophobic pocket → NO selectivity (NO-binding affinity is much higher than that for O₂);
- **Bacterial O₂-sensitive H-NOX** (e.g., H-NOX from *Shewanella*): Pocket geometry accommodates O₂ (a hydrogen-bond network stabilizes Fe–O₂), enabling oxygen sensing (e.g., aerotaxis);
- **Implication of structural evolution**: The same H-NOX fold switches between NO and O₂ sensing through “small substitutions of residues within the pocket”—**a natural experiment in how structure determines ligand selectivity**, and a blueprint for engineering H-NOX (designing more specific NO sensors).

**The mystery of H-NOX “picomolar sensitivity”**: H-NOX from *Clostridium botulinum* has femtomolar affinity for NO (Nioche 2004, *Science*)—even higher sensitivity than sGC. Structurally, its more enclosed heme pocket and “dry cavity” without distal water molecules reduce the entropic cost of NO binding, producing ultrasensitive sensing. This provides a comparison for understanding the “picomolar” sensitivity of sGC (a structural principle: “the drier the pocket, the higher the sensitivity”).

## 9. References (published literature)

1. Allerston CK, von Delft F, Gileadi O. Crystal structures of the catalytic domain of human soluble guanylate cyclase. *PLoS One* 2013;8:e57644. (PDB 3UVJ)
2. Derbyshire ER, Marletta MA. Structure and regulation of soluble guanylate cyclase. *Annu Rev Biochem* 2012;81:533–559. (Review of sGC structure)
3. Pellicena P, Karow DS, Boon EM, et al. Crystal structure of an oxygen-binding heme domain related to soluble guanylate cyclases. *Proc Natl Acad Sci USA* 2004;101:12854–12859. (Bacterial H-NOX crystal structure)
4. Nioche P, Berka V, Vipond J, et al. Femtomolar sensitivity of a NO sensor from *Clostridium botulinum*. *Science* 2004;306:1550–1553. (Ultrasensitive H-NOX NO sensing)
5. Wedel B, Humbert P, Harteneck C, et al. Mutation of His-105 in the beta 1 subunit yields a nitric oxide-insensitive form of soluble guanylyl cyclase. *Proc Natl Acad Sci USA* 1994;91:2592–2596. (Mutational validation of the importance of His105)
6. Winger JA, Derbyshire ER, Lamers MH, et al. Crystal structure of soluble guanylate cyclase. *PLoS One* 2008;3:e1929. (sGC catalytic-domain structure)
7. Makino R, Park SY, Obayashi E, et al. Oxygen binding and redox properties of the heme in soluble guanylate cyclase. *J Biol Chem* 2011;286:15678–15687. (Heme redox)
8. Armstrong R, Ravi S, et al. A pseudosymmetric allosteric site in sGC. Structural analysis (supplementary material to 3UVJ).

## 10. Integrating sGC structure with NO-pathway disease

Structural research on sGC ultimately serves to understand disease and guide treatment:

- **sGC defects in heart failure**: Insufficient NO signaling (eNOS↓) + sGC heme oxidation (Fe³⁺) in chronic heart failure → reduced cGMP production → vasoconstriction and myocardial remodeling. Vericiguat (an sGC stimulator) improves outcomes by “compensating for NO signaling” (VICTORIA trial); its structural mechanism (stabilizing activity in the heme Fe²⁺ state) directly addresses the pathology of “insufficient NO signaling”;
- **Pulmonary arterial hypertension**: Pulmonary vascular endothelial dysfunction → NO↓ → pulmonary vasoconstriction/remodeling. Riociguat activates sGC to restore cGMP signaling (PATENT trial)—“sGC is a structural target for pulmonary hypertension treatment”;
- **Aging and sGC**: Oxidative stress rises with age → the proportion of oxidized sGC heme increases → an “NO-resistant” state. This explains why older people may respond less to NO donors (nitroglycerin; one mechanism of nitrate tolerance/failure); **sGC activators (targeting Fe³⁺) may have special value in older populations**—the concept of “age-specific drugs targeting structure”;
- **Negative regulation of cGMP signaling**: Phosphodiesterase 5 (PDE5, the target of sildenafil) hydrolyzes cGMP. The dynamic balance between “sGC producing cGMP” and “PDE5 eliminating cGMP” determines signal strength. PDE5 inhibitors amplify residual NO/sGC signaling by “reducing cGMP degradation” (the structural rationale for a “downstream amplification” strategy).

**The sGC–PDE5 “production–consumption balance” model**: cGMP signal strength = rate of sGC synthesis – rate of PDE5 hydrolysis. In normal endothelium, abundant NO → efficient cGMP production by sGC > PDE5 hydrolysis → net signal output. In aging/endothelial dysfunction, NO↓ → cGMP production by sGC↓; if PDE5 activity is unchanged, net cGMP output falls (weaker signal)—**even when NO is insufficient, PDE5 inhibitors can maintain cGMP levels by reducing degradation** (“if supply is low, conserve what you have”). This explains why sildenafil is effective in pulmonary hypertension/ED without requiring abundant NO. **Intervention is possible at both production and consumption ends**, offering multiple NO-pathway anti-aging targets (sGC stimulation/activation + PDE5 inhibition + upstream eNOS repair can be combined).

## 11. Guide to obtaining structural data

- **PDB entries**: 3UVJ (human sGC α/β catalytic domain, 2.08 Å), 2WZ1 (sGC-related), 4TOT and others (bacterial H-NOX family);
- **What to inspect in structures**: (1) The two-subunit interface of the catalytic domain (how residues contributed by α/β align); (2) Heme coordination in the H-NOX domain (proximal His105 + empty sixth site); (3) Comparison of the “active/inactive” conformations with a 26° rotation;
- **Source of H-NOX domain structures**: No high-resolution structure of the full-length mammalian sGC H-NOX domain is yet available; its atomic details come from bacterial H-NOX homologues (e.g., Pellicena 2004)—“homology modeling + spectroscopic validation” is the current research strategy;
- **How to validate His105**: The His105 mutation experiment by Wedel et al. (1994) (His→Phe makes sGC insensitive to NO) is a classic structure–function validation example—“key residues” predicted from structure must be confirmed by mutagenesis.

**The ultimate contribution of structural research to the NO pathway**: From eNOS (Article 01 in this series) to sGC (this article), the two core enzymes in the NO pathway now have atomic-level structures. Structural resolution of the enzyme that “produces NO” and the enzyme that “senses NO” turns the NO signaling chain from a “black-box pathway” into “computable molecular machines”: ligand affinity, conformational changes, and catalytic rates at every step have structural foundations. **This is a paradigm of “molecular structure driving mechanistic understanding,”** and the significance of upgrading this knowledge base from “pathway level” to “structural level”: rather than merely asking “what does NO do?”, we can ask “how does NO do it at the scale of an atom?”

> **Structural snapshot**: sGC = H-NOX (His105–Fe²⁺ five-coordinate, sixth site reserved for NO) + PAS + coiled coil + catalytic domain (α/β two-subunit active site). NO binding → His dissociation → 26° rotation → 200–400-fold activity increase. Fe³⁺ oxidation = NO deafness.

> **Bridge between structure and aging**: Oxidation of sGC heme (Fe³⁺) accumulates with age/oxidative stress and is the “second vulnerable point” in the NO signaling chain (the first is reduced NO production by eNOS). **Anti-aging strategies need repair at both ends**: exercise/nitrates (eNOS end) + antioxidants/sGC activators (sGC end). If the “fraction of oxidized sGC heme” could be measured noninvasively, it would be a structural-level marker of vascular aging—an additional perspective for assessing vascular aging in [02-vascular/01-no-cardiovascular.md](../02-vascular/01-no-cardiovascular.md).
