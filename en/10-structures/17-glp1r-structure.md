# Molecular Structure Deep Dive 17: GLP-1 Receptor—The "Star Target" of Metabolic Anti-Aging and the Activation Logic of Class B GPCRs

> **Topic Positioning**: Part 17 of 10-structures (Molecular Structure Deep Dive)—Dissecting the 3D structure of the GLP-1 receptor (GLP-1R, Glucagon-Like Peptide-1 Receptor), understanding "how peptide agonists activate Class B GPCRs", "how Gs protein is recruited", and the structural basis for GLP-1 class drugs (like semaglutide) becoming "metabolic anti-aging stars". This is the structural foundation of the knowledge base drug mainline ([08-glp1](../04-drugs/08-glp1.md)), forming a "metabolic regulation" family alongside AMPK/mTOR/FOXO3.
> **Related Articles**: For GLP-1 drugs see [08-glp1](../04-drugs/08-glp1.md); for Metformin/AMPK see [07-metformin-ampk](../04-drugs/07-metformin-ampk.md); for mTOR structure see [04-mtor-structure.md](04-mtor-structure.md); for FOXO3 see [16-foxo3-structure.md](16-foxo3-structure.md); for metabolic aging see [03-metabolic-aging](../02-vascular/03-metabolic-aging.md).

---

## 0. Structural Overview

**In one sentence**: The GLP-1 receptor is the core receiver of "incretin" signals—after eating, the gut secretes GLP-1, which activates GLP-1R in pancreatic β cells → promoting insulin secretion (lowering blood sugar) + inhibiting glucagon + delaying gastric emptying + centrally suppressing appetite—"the 'full' signal, the body's 'weight loss switch'." Its structure belongs to **Class B GPCRs** (secretin family)—the extracellular domain (ECD) "captures" the peptide ligand, and the transmembrane domain (TMD) "transmits" the signal to the Gs protein—"two-step activation: catch first, then transmit."

```text
GLP-1R Structure: N-term ECD (Venus flytrap-like) — Hinge — 7-TM TMD — Intracellular loop (binds Gs) — C-term
                  │
   Ligand Binding:  C-term α-helix of GLP-1 peptide inserts into ECD hydrophobic groove (capture)
                    N-term of GLP-1 peptide inserts into TMD extracellular pocket (activate)
                  │
   Signal Transduction:  TMD conformational change → Intracellular loop opens → Gs protein binds → cAMP↑
```

**Three Major Structural Features** (the atomic basis determining its function):
1. **Extracellular Domain (ECD) "Venus Flytrap"**: Two lobes clamp down on the C-terminal helix of GLP-1—"catching the prey's tail first";
2. **Transmembrane Domain (TMD) "Activation Pocket"**: The N-terminus of GLP-1 inserts into the pocket between the 7 transmembrane helices—"the key inserted into the lock cylinder";
3. **Intracellular Gs Binding Interface**: The intracellular end of the TMD opens up → the α5 helix of the Gs protein inserts—"the handshake of signal transduction."

**Core Regulatory Mechanism**:

```text
Eating → Gut L cells secrete GLP-1 → Binds GLP-1R (pancreatic β cells)
    → GLP-1R activates → Gs recruited → Adenylyl cyclase → cAMP↑ → PKA activates
    → Insulin secretion↑ (glucose-dependent) + Glucagon↓ + Gastric emptying↓ + Appetite↓
```

---

## 1. Why the GLP-1 Receptor Structure is Important

The GLP-1 receptor is currently the "top-tier target" for metabolic anti-aging:

- **Target of "Miracle Weight Loss Drugs"**: Semaglutide (Wegovy/Ozempic), Tirzepatide (GLP-1/GIP dual agonist)—"GLP-1 class drugs are already among the world's best-selling medications";
- **The Fulcrum of "Metabolic Anti-Aging"**: GLP-1R activation → weight loss + blood sugar reduction + cardiovascular protection + potential neuroprotection—"one receptor, multi-organ benefits";
- **Anti-Aging Evidence**: GLP-1 receptor agonists show cardiovascular/renal/cognitive benefits in animals/humans, and weight loss improves metabolic aging—"repairing metabolism is repairing the engine of aging";
- **Dialogue with Aging**: Metabolic aging (insulin resistance/obesity) drives systemic aging; GLP-1R restores metabolic homeostasis—"repair metabolism, and the whole body benefits";
- **Structure-Drug Bridge**: Semaglutide and others are "modified versions" of GLP-1 (fatty acid modification extends half-life)—"structural modification determines drug efficacy";
- **Representative of Class B GPCRs**: GLP-1R is a Class B GPCR (secretin family)—the textbook example of "two-step activation"—"understanding GLP-1R means understanding the Class B GPCR family."

**Three key questions for structural research**:
1. How does the ECD "capture" GLP-1 (atomic mechanism of the Venus flytrap)?
2. How does the peptide N-terminus "activate" the TMD (key-in-lock mechanism)?
3. How is biased agonism (Gs vs β-arrestin) produced (different signals from different drugs)?

These questions were answered by structures such as 6B3J (GLP-1R+biased agonist+Gs, 2018) and 6ORV (GLP-1R+non-peptide agonist, 2020).

---

## 2. Structural Anatomy of the GLP-1 Receptor

### 2.1 Extracellular Domain (ECD)—The "Venus Flytrap" Capturer

- Location: GLP-1R N-terminus (~1-140 residues);
- Structure: **Venus flytrap-like** fold—two lobes flanking a ligand-binding groove—"two leaves clamping prey";
- Ligand binding: The C-terminal α-helix of GLP-1 (residues 20-30) inserts into the ECD's hydrophobic groove—"the prey's tail is clamped";
- Key contacts: Hydrophobic residues (Leu/Val/Ile) + polar residues form a composite interface—"the clamping force is hydrophobic + hydrogen bonds";
- Flexible hinge: The hinge region between ECD and TMD allows "close-open" movement—"the Venus flytrap's opening/closing joint";
- Structure-function: The ECD primarily provides "affinity" (capturing the ligand) but does not directly activate—"capture ≠ activation."

### 2.2 Transmembrane Domain (TMD)—The "Lock Cylinder" Transducer

- Location: GLP-1R middle segment (~140-400 residues);
- Structure: **7 transmembrane α-helices** (TM1-TM7, classic GPCR fold)—"seven pillars supporting a channel";
- Extracellular pocket: Formed by TM1/TM2/TM6/TM7—the N-terminus of GLP-1 (His7, etc.) inserts—"the tip of the key enters the lock cylinder";
- Activation conformation: TM6 swings outward → intracellular end opens → exposes the Gs binding surface—"the lock cylinder turns, the bolt opens";
- Key residues: Conserved residues on TM6 (P/R, etc.) participate in activation—"the spring of the lock cylinder";
- Biased agonism: Different agonists induce different conformational ensembles in the TMD → bias toward Gs or β-arrestin—"same lock, different keys turn at different angles."

### 2.3 Intracellular Gs Binding Interface—The "Handshake" Signal End

- Location: TMD intracellular end + intracellular loops (ICL2/ICL3);
- Structure: After the TMD intracellular end opens, the α5 helix of the Gs protein inserts—"the 'handshake' of signal transduction";
- Signaling: Gs activation → adenylyl cyclase → cAMP↑ → PKA—"the first link in the signal amplification chain";
- 6B3J details: The Gαs-α5 helix binding angle differs by 6° between biased agonist and GLP-1—"a slight adjustment in the handshake produces different signals."

---

## 3. Two-Step Activation: From Structure to Chemistry

### 3.00 The Engineering Wisdom of the "Venus Flytrap": Why the ECD Has Two Leaves

The previous section discussed how the ECD captures the C-terminus; this section understands **why the ligand-binding domain of Class B GPCRs is designed as a "Venus flytrap."** This is another "engineering" problem:

**Option 1: No ECD, peptide inserts directly into TMD.** For small molecule GPCRs (e.g., β-adrenergic receptors), ligands enter the TMD pocket directly, but peptides (30 amino acids) are too large—"a large key cannot be inserted directly into a small lock cylinder." Moreover, both the N-terminus and C-terminus of the peptide have functions (C-terminus for binding, N-terminus for activation)—"both ends of the key must be used, so it cannot be shoved in entirely."

**Option 2: ECD captures first, then guides insertion.** The ECD's Venus flytrap structure provides a "pre-binding platform"—① large interface (two leaves clamping the helix) provides high affinity; ② orientation (aligning the N-terminus with the TMD pocket); ③ flexibility (hinge allows opening and closing). **"Venus flytrap = a trinity design of high affinity + orientation + flexibility"**—"first invite the guest in (ECD captures), then guide the guest to the meeting room (N-terminus inserts into TMD)."

**Why "two leaves" instead of "one"?** Two leaves clamp the ligand, providing a large contact area (>1000 Å²) → high affinity (nM level)—"clamping with two leaves holds more firmly than pressing with one." At the same time, the opening and closing of the two leaves (hinge movement) can regulate binding kinetics—"the speed of leaf opening and closing dictates the rhythm of binding/dissociation."

**Physiological significance of "capture ≠ activation"**: The ECD provides affinity but does not activate—this allows GLP-1 analogs to "capture but activate slowly" (sustained release); it also allows "antagonists" to "capture but not activate" (occupying the site without turning the lock cylinder)—"separating capture and activation gives drug design two independent knobs"—this is the core degree of freedom in Class B GPCR drug design.

**Practical application of the "two knobs"**: Knob 1 (affinity knob)—modifying the C-terminus/ECD interface → regulating the firmness of "capture" (the foundation determining drug efficacy duration); Knob 2 (potency knob)—modifying the N-terminus/TMD interface → regulating the strength of "activation" (determining signal magnitude). Semaglutide turns both knobs simultaneously: C-terminal fatty acid (prolonging "capture") + DPP-4-resistant N-terminus (preserving "activation")—"turning both knobs together makes the drug effect both long-lasting and strong"—this is the most direct lesson from "structure to pharmacy," and a vivid example of "structural modification determining clinical fate."

### 3.0 Atom by Atom: Capture First, Then Activate

**Why do Class B GPCRs need a "two-step" process?** Because peptide ligands (GLP-1, 30 amino acids) are much larger than small molecules (a few hundred Daltons)—"a large key cannot be inserted directly into the lock cylinder; its direction must be calibrated first." The two-step design:

**Step 1: ECD captures the C-terminus.** The C-terminal helix of GLP-1 (residues 20-30) binds to the ECD—"calibrating the direction, aligning the N-terminus with the lock cylinder." This binding is a "pre-binding"—**"capture ≠ activation, just aligning the key with the keyhole."**

**Step 2: N-terminus inserts into TMD.** The N-terminus of GLP-1 (key residues like His7/Glu9) inserts into the extracellular pocket of the TMD → triggers TM6 swinging → activation—"the tip of the key turns the lock cylinder." The N-terminus is the "key to activation," and the C-terminus is the "anchor for binding"—**"the C-terminus is responsible for capture (affinity), the N-terminus for activation (potency)"**—"one ligand, two ends with different jobs."

**Evidence for the "two-site" model**: Truncated GLP-1 (C-terminus removed) shows greatly reduced affinity but retains activation capacity; N-terminus removed abolishes activation—"the C-terminus manages 'capture,' the N-terminus manages 'activation'"—this is the common logic of Class B GPCRs.

### 3.1 Structural Logic of "Biased Agonism": Same Lock, Different Keys

**What is biased agonism?** The same receptor can activate multiple downstream pathways (Gs→cAMP, β-arrestin→internalization/other signals). Different ligands preferentially activate different pathways—"the same switch, some keys mainly turn on the light, others mainly turn on the fan."

**Structural explanation (6B3J)**: After biased agonist (exendin-P5 class) binding, the TMD conformational change differs slightly from GLP-1—the Gαs-α5 helix binding angle differs by 6°—"a slight adjustment in the handshake"—leading to different Gs activation efficiencies. β-arrestin recruitment depends on the phosphorylation barcode (phosphorylation patterns of the receptor's intracellular domain)—"different keys write different 'phosphorylation notes'."

**Pharmacological significance**: If "weight loss + blood sugar reduction" mainly depends on Gs/cAMP, while "side effects" (nausea, etc.) are associated with β-arrestin/other pathways, then "Gs-biased agonists" may be better—"only turn on the desired lights, without disturbing the neighbors"—this is the design direction for next-generation GLP-1 drugs.

---

## 4. GLP-1 Class Drugs: From Structure to Pharmacy

### 4.1 Semaglutide's "Structural Modifications"

- **GLP-1's shortcoming**: Natural GLP-1 has a half-life of only ~2 minutes (rapidly degraded by DPP-4 enzyme)—"the natural key is too fragile";
- **Modification 1: DPP-4 resistance**: Position 8 alanine replaced with α-aminobutyric acid → not cleaved by DPP-4—"reinforcing the breakable point";
- **Modification 2: Fatty acid modification**: Position 26 lysine conjugated with C18 fatty acid chain → binds albumin → half-life extended to ~1 week—"equipping the key with an 'albumin tugboat' for slow release";
- **Result**: Semaglutide, once-weekly subcutaneous injection—"structural modification turns 'minutes' into 'weeks'."

### 4.2 From Peptide to Small Molecule: Structural Challenges of Oral GLP-1 Drugs

- **Why is oral delivery difficult?** Peptides are digested by the gastrointestinal tract, with extremely low bioavailability—"the key gets chewed up in the stomach";
- **Non-peptide small molecules (6ORV, TT-OAD2)**: Small molecule agonists bind the TMD extracellular pocket (partially replacing N-terminus function)—"without the key head, directly turning the lock cylinder";
- **6ORV discovery**: TT-OAD2 extends from the receptor core to interact with lipids/detergents → unique activation kinetics—"small molecules have their own 'turning method'";
- **Oral semaglutide**: Combined with SNAC (absorption enhancer) → orally available—"adding a 'shield' to the key to pass through the stomach";
- **Future**: Oral small molecule GLP-1 agonists (e.g., orforglipron, Eli Lilly)—"completely freeing from injections."

### 4.3 Dual/Triple Agonism: Beyond GLP-1

- **Tirzepatide**: GLP-1/GIP dual receptor agonist—"two keys, two switches";
- **Retatrutide**: GLP-1/GIP/GCG triple agonist—"three switches coordinated";
- **Structural basis**: GIP receptor/GCG receptor and GLP-1R all belong to Class B GPCRs, structurally similar but with different pockets—"same family, different lock cylinders"—multi-agonist design requires "one key opening multiple locks" (chimeric peptide design)—"using chimeric peptide 'mixed teeth' to open multiple locks."

---

## 5. GLP-1 and Aging: "Metabolic Anti-Aging" from a Structural Perspective

### 5.1 Metabolic Aging and GLP-1R

- **Insulin resistance increases with age** → metabolic aging ([03-metabolic-aging](../02-vascular/03-metabolic-aging.md)) → systemic accelerated aging;
- **GLP-1 secretion declines with age**: GLP-1 levels/sensitivity decrease in the elderly—"the 'full' signal weakens";
- **"Multi-organ benefits" of GLP-1R activation**:
  - Pancreas: Promotes insulin (lowers blood sugar);
  - Liver: Inhibits gluconeogenesis (lowers blood sugar);
  - Stomach: Delays emptying (weight loss);
  - Brain: Suppresses appetite (weight loss) + possible neuroprotection;
  - Heart/blood vessels: Cardiovascular protection (anti-inflammatory/improves endothelial function);
  - Kidneys: Protects renal function.
- **Logic of "metabolic anti-aging"**: Obesity/insulin resistance drives aging (inflammation, oxidative stress, mitochondrial dysfunction); GLP-1R activation → weight loss + blood sugar reduction + anti-inflammation → breaks the metabolism-aging vicious cycle—"repair the metabolic engine, and all parts benefit."

### 5.2 Another "Anti-Aging Switch" from a Structural Perspective

| Switch | Trigger | Effect | Aging Trend |
|---|---|---|---|
| GLP-1R | GLP-1 (after eating) | Insulin↑/Appetite↓/Metabolic repair | Sensitivity↓ |
| AMPK | Energy deficit | Catabolism/Autophagy | Activity↓ |
| mTOR | Nutrient abundance | Anabolism/Growth | Overactivation |
| FOXO3 | Nutrient deprivation/Stress | Survival program | Activity↓ |
| Nrf2 | Oxidative stress | Antioxidant | Activity↓ |
| NF-κB | Inflammatory signals | Inflammation | Activity↑ |

**Coordination of the "metabolic switch group"**: GLP-1R (satiety signal), AMPK (energy hunger signal), mTOR (nutrient abundance signal), FOXO3 (nutrient deprivation signal)—together form the "metabolic decision committee"—**"GLP-1R is the 'satiety' member, AMPK/FOXO3 are the 'hunger' members, mTOR is the 'growth' member"**—during aging, the committee becomes imbalanced (satiety signal blunted, growth member overactive)—"the meeting goes off track."

### 5.20 The "Blood Glucose-Insulin-GLP-1" Triangle: Why GLP-1R Is a "Smart Blood Sugar Switch"

GLP-1R's most fascinating structure-physiology property is **"glucose-dependent insulin secretion"**—it only promotes insulin when blood sugar is high, not when normal/low—"doesn't lower blood sugar excessively." The structural logic of this "smart" behavior:

**GLP-1R itself does not sense blood glucose.** GLP-1R is merely the receiver of the "full signal"—what truly senses blood glucose is the β cell's glucose sensor (GLUT2/KATP channel)—"GLP-1R is the 'horn', glucose is the 'accelerator'."

**"Accelerator + horn" synergy.** High blood sugar: Glucose metabolism → ATP↑ → KATP closes → membrane depolarization → insulin secretion (basal secretion); GLP-1 activates GLP-1R → cAMP/PKA → enhances secretion mechanism (amplifies secretion)—"blood sugar steps on the accelerator, GLP-1 adds turbo."

**"Hypoglycemia protection" structure-physiology logic**: When blood sugar is normal/low, glucose metabolism doesn't provide the "accelerator" → even if GLP-1 is present, insulin secretion doesn't increase—"if the accelerator isn't pressed, no matter how big the turbo is, the car won't move"—this is the fundamental reason for the low hypoglycemia risk of GLP-1 class drugs—"smart switch: only adds turbo when needed."

**Comparison: Sulfonylureas (traditional blood sugar drugs)**: Directly close KATP channels (regardless of blood sugar) → forced insulin secretion → high hypoglycemia risk—"pushing the car without pressing the accelerator, easy to crash."

**Structural perspective anti-aging insight**: GLP-1R's design philosophy is "respond to signals, don't replace rational judgment"—**"good metabolic intervention doesn't bypass physiological regulation, but amplifies the 'correct part' of physiological regulation"**—this echoes the recurring theme of the 10-structures series: "modify the periphery, repair negative feedback, restore rhythm"—"repair the switch, don't remove the switch."

### 5.3 "Drugs vs. Lifestyle" Structural Reflection

- **GLP-1 drugs**: Powerful, direct, "external"—"adding a powerful new member to the committee";
- **Lifestyle (diet/exercise)**: Gentle, indirect, physiological—"adjusting the meeting agenda, letting members naturally return to their roles";
- **Structural insight**: GLP-1R is a "post-eating" signal—**"drugs simulate the 'well-fed' signal, but lifestyle (eating less/eating right) is the natural source of the signal"**—"drugs are a crutch, lifestyle is the legs" (echoing [03-nutrition](../07-interventions/03-nutrition.md));
- **Long-term use issues**: Rebound after discontinuation (appetite returns), muscle loss (rapid weight loss), cost—"when the crutch is taken away, the legs aren't trained yet."

---

## 6. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| GLP-1R is a Class B GPCR (ECD+TMD) | ★★★★★ Confirmed | Multiple structures |
| ECD captures GLP-1 C-terminus in a Venus flytrap-like manner | ★★★★★ Confirmed | 6B3J, etc. |
| GLP-1 N-terminus inserts into TMD to activate | ★★★★★ Confirmed | Mutagenesis + structures |
| Gs protein α5 helix inserts into the intracellular end of TMD | ★★★★★ Confirmed | 6B3J |
| Biased agonism has a structural basis (6° difference) | ★★★★★ Confirmed | 6B3J (2018 *Nature*) |
| Non-peptide agonist binds the TMD pocket | ★★★★★ Confirmed | 6ORV (2020 *Nature*) |
| Semaglutide fatty acid modification extends half-life | ★★★★★ Confirmed | Pharmacology |
| GLP-1 receptor agonists provide weight loss/cardiovascular benefit | ★★★★★ Confirmed | Large-scale RCTs |

---

## 7. Connection to the Knowledge Base Main Thread

### 7.0 The Closed Loop of the "Metabolic Anti-Aging" Main Thread

The metabolic family of the 10-structures series now has five members—GLP-1R (satiety), AMPK (hunger), mTOR (growth), FOXO3 (survival), and Complex I (energy):

**Panorama of the "Metabolic Decision Committee"**:
- **After eating**: GLP-1R activated (satiety signal) + insulin↑ → mTOR on (anabolism) + FOXO3 off—"Fed, time to grow";
- **Fasting/exercise**: AMPK activated (energy deficit) → mTOR off + FOXO3 on + Complex I efficiency adjusted—"Hungry, time to repair";
- **Chronic imbalance**: Persistent overeating → mTOR constantly on + GLP-1R desensitized + insulin resistance → metabolic aging—"The committee is hijacked by the 'growth faction'."

**Structural logic of anti-aging strategies**: Restore the "satiety-hunger" rhythm (intermittent fasting/exercise) → Allow GLP-1R to regain sensitivity + give AMPK/FOXO3 a window to operate—"Let the committee reconvene, rather than being monopolized by one faction." GLP-1 drugs = "an external satiety signal"; lifestyle = "restoring endogenous rhythm"—**"The best intervention restores the natural rhythm of signaling; drugs are a crutch before rhythm is restored."**

### 7.1 Dialogue with Main Thread Chapters

- **GLP-1 drugs** ([08-glp1](../04-drugs/08-glp1.md)): This article is their structural foundation—"From molecule to pharmacy";
- **Metformin/AMPK** ([07-metformin-ampk](../04-drugs/07-metformin-ampk.md)): AMPK and GLP-1R are complementary (hunger vs. satiety signals)—"One hunger, one satiety, two switches";
- **mTOR structure** ([04-mtor-structure.md](04-mtor-structure.md)): GLP-1R (satiety) → insulin → mTOR—"The downstream of the satiety signal is the growth switch";
- **FOXO3 structure** ([16-foxo3-structure.md](16-foxo3-structure.md)): GLP-1R activation → insulin↑ → AKT → FOXO3 off—"The satiety signal shuts down the survival program";
- **Metabolic aging** ([03-metabolic-aging](../02-vascular/03-metabolic-aging.md)): Decreased GLP-1R sensitivity is part of metabolic aging—"When the satiety signal goes blunt, metabolic aging begins";
- **Nutrition/fasting** ([03-nutrition](../07-interventions/03-nutrition.md)): Feeding rhythm determines the GLP-1/insulin curve—"How you eat determines how the switches are toggled";
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): Metabolic repair → improved mitochondrial function—"Fix the engine, and the generator stabilizes too."

---

## 8. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How is GLP-1R activated? | ECD grabs GLP-1 C-terminus (calibration), N-terminus inserts into TMD (turns the lock cylinder)—two-step mechanism |
| Why is semaglutide once-weekly? | Fatty acid modification → albumin binding → week-level half-life—"Structural modification extends drug efficacy" |
| How does biased agonism arise? | Different ligands → different TMD conformations → Gs/β-arrestin bias (6° difference) |
| Why do GLP-1 drugs have "multi-organ benefits"? | GLP-1R is widely distributed (pancreas/liver/stomach/brain/heart/kidney)—"one receptor, multi-organ response" |
| How to counter aging? | Restore feeding rhythm (GLP-1R sensitivity) + drug assistance when needed—"Rhythm first, drugs as crutch" |

**Structural intuition beyond the five questions**: The GLP-1R story reveals the "ultimate question of drug design"—**"Are we 'simulating physiology' or 'hijacking physiology'?"** Semaglutide simulates GLP-1 (physiological signal) → "amplifies the correct part"; but continuous supra-physiological activation is essentially "hijacking the satiety signal"—"using a physiological key to open a supra-physiological door." The sobering structural perspective: **any receptor is not an isolated switch, but a node in a network**—behind GLP-1R activation's "multi-organ benefits" lies the possibility of "multi-organ side effects" (nausea, muscle loss, rebound after discontinuation)—"a node in a network, pull one thread and everything moves." This suggests: structural knowledge lets us "see more clearly," and also lets us "know where the boundaries are"—**"the best drug is like the best key: it opens the doors it should, and doesn't touch the doors it shouldn't."**

---

## 9. Open Questions

1. **GLP-1R intermediate state structures**: Intermediate conformations between ligand binding and Gs recruitment (time-resolved cryo-EM);
2. **β-arrestin complex structure**: Complete structure of the GLP-1R-β-arrestin complex;
3. **Molecular logic of dual/triple agonism**: How tirzepatide simultaneously activates GLP-1R and GIP receptor (chimeric peptide binding mode);
4. **GLP-1R age-related changes**: Changes in GLP-1R expression/conformation/signaling in aging;
5. **Optimization of oral small molecules**: Design of oral small molecule agonists based on 6ORV;
6. **GLP-1 and muscle**: Mechanisms of muscle loss during rapid weight loss (intersection of GLP-1R with mTOR/FOXO3)—"structural pharmacology of losing fat without losing muscle."

### 9.1 The Complete Picture of "Metabolic Anti-Aging": Network Perspective from 17 Structures

GLP-1R is Part 17 of the 10-structures series, and also the finale of the "metabolic regulation" series—now a complete "metabolic-aging structural network" can be drawn:

**Energy flow**: Complex I ([12-complex1-structure.md](12-complex1-structure.md)) produces ATP (power generation) → AMPK ([03-ampk-structure.md](03-ampk-structure.md)) senses energy (electric meter) → mTOR ([04-mtor-structure.md](04-mtor-structure.md)) determines growth (accelerator) → FOXO3 ([16-foxo3-structure.md](16-foxo3-structure.md)) determines survival (brake) → GLP-1R ([17-glp1r-structure.md](17-glp1r-structure.md)) senses satiety (fuel gauge)—**"from power generation to consumption, from eating to survival, one diagram connects it all."**

**NAD⁺ flow**: NAMPT ([10-nampt-structure.md](10-nampt-structure.md)) synthesizes (minting) → SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)) consumes (spending) → CD38/PARP1 ([08-cd38-structure.md](08-cd38-structure.md)/[09-parp1-structure.md](09-parp1-structure.md)) compete (grabbing money)—"the four-terminal closed loop of the NAD⁺ economy."

**Signal flow**: NOS/sGC ([01-nos-structures.md](01-nos-structures.md)/[02-sgc-heme.md](02-sgc-heme.md)) NO signaling (messenger) → inflammation/antioxidant switches ([14-nfkb-structure.md](14-nfkb-structure.md)/[15-nrf2-structure.md](15-nrf2-structure.md)) → cell fate ([13-p53-structure.md](13-p53-structure.md))—"from messenger to fate."

**Information flow**: TET/DNMT1 ([05-tet-dna.md](05-tet-dna.md)/[07-dnmt1-structure.md](07-dnmt1-structure.md)) epigenetic writing/erasing → SIRT1 epigenetic tuning → telomeres ([11-telomerase-structure.md](11-telomerase-structure.md)) clock—"a chain of information aging."

**Methodological insight from the "structural network"**: Reading 17 articles together, we see not 17 isolated molecules, but a **four-layer network of "metabolism-signal-epigenetics-fate"**—**"aging is not a single molecule breaking, but the network becoming imbalanced"**—anti-aging strategies are thus clear: rather than "hammering" a single target, **"restore the dynamic balance of the network"** (rhythm, moderation, multi-target)—"repair the network, not a single point." This is also the complete implementation of the knowledge base's "full-chain mechanism/systems perspective" philosophy at the molecular structure level—"from atoms to networks, every layer has evidence, every link connects."

---

## 10. Structural Data Access Guide

- **PDB entries**:
  - 6B3J: GLP-1R + biased agonist + Gs (3.3 Å cryo-EM, Liang 2018 *Nature*)—biased agonism mechanism;
  - 6ORV: GLP-1R + non-peptide agonist TT-OAD2 (3.30 Å, Zhao 2020 *Nature*)—oral small molecule agonism;
  - 6O18/6O1M, etc.: GLP-1-bound GLP-1R-Gs complex (classic active state);
  - 5VEW: GLP-1R antagonist complex;
  - 6X18, etc.: GIP receptor structure (basis for dual agonism);
  - AlphaFold: AF-P43220 (GLP-1R full-length prediction).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 11. References

1. Liang YL, Khoshouei M, Glukhova A, et al. Phase-plate cryo-EM structure of a biased agonist-bound human GLP-1 receptor-Gs complex. *Nature* 2018;555:121-125. (PDB 6B3J)
2. Zhao P, Liang YL, Belousoff MJ, et al. Activation of the GLP-1 receptor by a non-peptidic agonist. *Nature* 2020;577:432-436. (PDB 6ORV)
3. Zhang Y, Sun B, Feng D, et al. Cryo-EM structure of the activated GLP-1 receptor in complex with a G protein. *Nature* 2017;546:248-253. (First GLP-1R active-state structure)
4. Marso SP, Daniels GH, Brown-Frandsen K, et al. Liraglutide and cardiovascular outcomes in type 2 diabetes. *N Engl J Med* 2016;375:311-322. (LEADER trial, cardiovascular benefit)
5. Wilding JPH, Batterham RL, Calanna S, et al. Once-weekly semaglutide in adults with overweight or obesity. *N Engl J Med* 2021;384:989-1002. (STEP trial, semaglutide weight loss)
6. Drucker DJ. Mechanisms of action and therapeutic application of glucagon-like peptide-1. *Cell Metab* 2018;27:740-756. (GLP-1 review)
7. Wootten D, Miller LJ, Koole C, et al. Allostery and bias in G protein-coupled receptor signaling. *Cell* 2018;172:41-46. (GPCR bias review)

---

> **Structure Overview**: GLP-1R is a **Class B GPCR**—the extracellular domain (ECD) Venus flytrap-like "captures" the C-terminus of GLP-1 (affinity), and the transmembrane domain (TMD) receives the N-terminus insertion (activation)—**two-step activation: "catch first, then transmit."** After activation, TM6 swings → Gs protein α5 helix inserts → cAMP↑ → insulin↑/appetite↓/metabolic repair. **Biased agonism** (6B3J: Gs binding angle differs by 6°) provides the structural basis for "only turning on desired signals"; **non-peptide small molecules** (6ORV) make oral GLP-1 drugs a reality. **During aging, GLP-1R sensitivity↓ → metabolic aging accelerates**—anti-aging strategy: restore feeding rhythm (let GLP-1R naturally go on duty) + drug assistance when needed—"rhythm first, drugs as crutch; one receptor, whole-body benefits."
