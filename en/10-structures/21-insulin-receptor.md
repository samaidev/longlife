# Molecular Structure Deep Dive 21: Insulin Receptor — The "Main Gateway" of Metabolic Signaling and the "Λ"-Shaped Receptor

> **Topic Positioning**: 10-structures (Molecular Structure Deep Dive) Part 21 — dissecting the three-dimensional structure of the insulin receptor (IR), understanding "how insulin binds the receptor extracellular domain," "how signals transduce across the cell membrane," and the "main gateway" role of insulin signaling in metabolic aging. This is the structural foundation of the knowledge base's insulin/IGF-1 signaling main thread ([07-interventions/03-nutrition.md](../07-interventions/03-nutrition.md)), and the common upstream of FOXO3 ([16-foxo3-structure.md](16-foxo3-structure.md))/GLP-1R ([17-glp1r-structure.md](17-glp1r-structure.md))/mTOR ([04-mtor-structure.md](04-mtor-structure.md)).
> **Related Articles**: FOXO3 see [16-foxo3-structure.md](16-foxo3-structure.md); GLP-1R see [17-glp1r-structure.md](17-glp1r-structure.md); mTOR see [04-mtor-structure.md](04-mtor-structure.md); metabolic aging see [03-metabolic-aging](../02-vascular/03-metabolic-aging.md); metformin see [07-metformin-ampk](../04-drugs/07-metformin-ampk.md).

---

## 0. Structure at a Glance

**In one sentence**: The insulin receptor is the cell surface's "metabolic main gateway" — insulin (the "fed" signal) binds the receptor extracellular domain → receptor dimer "deforms" → intracellular tyrosine kinases trans-phosphorylate each other for activation → initiates the PI3K-AKT pathway → promotes glucose uptake/anabolism/inhibits FOXO3 — "the 'city gate' of metabolic signaling, with FOXO3/mTOR/AMPK all inside the gate."

```text
Insulin Receptor (IR) Structure:
  α subunit (×2, extracellular): L1-CR-L2-FnIII1-FnIII2-insert domain-FnIII3
  β subunit (×2, transmembrane+intracellular): transmembrane helix + tyrosine kinase domain (TK) + C-terminus
                  │
  Dimer:  (αβ)2  →  "Λ"-shaped (inverted V) fold, two arms symmetric
                  │
  Binding:  Insulin (1 molecule) clamped between two α subunits (site 1 + site 2)
          → allosteric change → two arms close together → β subunit transmembrane signaling → TK trans-phosphorylation
```

**Three major structural features** (the atomic basis determining its function):
1. **"Λ"-shaped dimer**: Two αβ half-receptors arranged symmetrically, extracellular domain resembles an inverted V — "the left and right panels of the city gate";
2. **Insert domain**: A special domain within the α subunit, containing the α/β cleavage site + insulin binding site — "the lock of the city gate";
3. **Intracellular tyrosine kinase (TK)**: Two TK domains phosphorylate each other (trans-autophosphorylation) — "messengers inside the gate activating each other."

**Core regulatory mechanism**:

```text
Insulin binding → IR extracellular domain allosteric change (two arms close together) → β subunit TK trans-phosphorylation
    → IRS1/2 phosphorylation → PI3K → PIP3 → AKT activation
    → ①Glucose transport (GLUT4↑) ②Anabolism (mTOR↑) ③FOXO3 inhibition (shutting down survival programs)
    → Insulin resistance (signaling↓): receptor/IRS phosphatase↑, inflammation, lipid accumulation → metabolic aging
```

---

## 1. Why the Insulin Receptor Structure Matters

The insulin receptor is the "hub" of metabolic regulation:

- **"Metabolic main gateway"**: Insulin signaling is the "master switch" for whole-body metabolism (anabolism/energy storage) — "fed, store energy";
- **Insulin resistance = core of metabolic aging**: Receptor signaling↓ (resistance) → blood glucose↑/metabolic dysfunction → accelerated systemic aging — "city gate malfunction, metabolic chaos";
- **Anti-aging evidence**: Attenuated insulin/IGF-1 signaling (low insulin/IGF-1) extends lifespan in model organisms (daf-2 mutant nematodes, dwarf mice) — "turning down the main gateway extends lifespan" (related to FOXO3 activation);
- **"Longevity paradox"**: Acute insulin signaling is necessary (life maintenance); chronic hyperinsulinemia (overeating) promotes aging — "the city gate cannot stay closed, nor can it stay open all the time";
- **Dialogue with FOXO3/GLP-1R**: Insulin → AKT → FOXO3 off ([16-foxo3-structure.md](16-foxo3-structure.md)); GLP-1 promotes insulin secretion ([17-glp1r-structure.md](17-glp1r-structure.md)) — "GLP-1 is insulin's 'upstream friend,' FOXO3 is insulin's 'downstream opponent.'"

**Three key questions for structural research**:
1. How does insulin "clamp" between the dimer (atomic details of the binding site)?
2. How does the "Λ"-shaped allostery transduce signals (mechanism from extracellular to intracellular)?
3. What is the structural basis of insulin resistance (molecular reasons for weakened signaling)?

These questions were answered in structures such as 4ZXB (IR ectodomain, 2016), 3E7Y (human insulin, 1.6 Å).

---

## 2. Structural Anatomy of the Insulin Receptor

### 2.1 Extracellular Domain — The "Λ"-Shaped City Gate

- Composition: α2β2 tetramer; the extracellular portion consists of two α subunits (L1-CR-L2-FnIII1-insert domain-FnIII2-FnIII3) + two β subunit N-termini — "the left and right panels of the city gate";
- Folding: Each half-receptor forms a "Λ" shape (inverted V) — L1/L2 form the two arms of the "V," the CR domain at the apex — "the two pillars of the city gate";
- Dimerization: Two half-receptors arranged symmetrically → central "ligand-binding groove" — "the passage between the gates";
- 4ZXB findings: Multi-modal modeling of the insert domain (containing the α/β cleavage site) + glycosylation details — "seeing the decorations and seams of the city gate";
- Flexibility: The extracellular domain has significant flexibility (open/closed states) — "the city gate can open and close."

### 2.2 Insulin Binding Site — The "Lock"

- **Site 1 (classical)**: L1 domain + αCT peptide segment (α subunit C-terminus) — one face of insulin binds — "the main groove of the lock";
- **Site 2**: FnIII1 domain (the other arm of the same dimer) — insulin binds across arms — "the secondary groove of the lock";
- **"Sandwich" model**: One insulin molecule simultaneously contacts two half-receptors (site 1 on one arm, site 2 on the other) → "pulls the two arms together" — "insulin is a wedge, spreading/closing the gate gap";
- **High-affinity binding**: Two sites cooperate → high affinity (~10⁻¹¹ M) — "double latching points hold fast."

### 2.3 Transmembrane Domain and Intracellular Tyrosine Kinase — The "Messengers"

- Transmembrane helix: The β subunit transmembrane segment (~23 residues) connects extracellular/intracellular — "the passage from gate to city interior";
- Tyrosine kinase domain (TK): Intracellular catalytic domain (containing ATP binding site + activation loop) — "the messenger";
- Trans-autophosphorylation: Insulin binding → two arms close → two TK domains phosphorylate each other (activation loop Tyr1158/1162/1163, etc.) → full activation — "two messengers stamp each other's seals to take effect";
- Downstream: TK phosphorylates IRS1/2 → PI3K → AKT — "the messenger issues orders, the whole city responds."

---

## 3. The Molecular Logic of Insulin Signaling: From Structure to Chemistry

### 3.00 The Engineering Wisdom of the "Λ" Shape: Why the Insulin Receptor Is Built as an "Inverted V"

The previous section covered sandwich binding; this section delves into **why the IR extracellular domain folds into a "Λ" (inverted V) shape**. This shape is no accident—it is the geometric solution for "allosteric signal transduction":

**"Inverted V = natural 'clamp' geometry."** Two half-receptors are arranged symmetrically into a "V," with the apex (CR domain) as the hinge and the two arms (L1/FnIII) as the clamping surfaces—insulin "drops into" the opening between the arms from the top of the V → binding site 1 (one arm) + site 2 (the other arm) → "pulls the two arms together"—"the inverted V shape is naturally suited for a 'wedge-and-clamp' action."

**The mechanics of "hinge at the apex."** The CR domain (hinge) sits at the vertex of the V → the approach of the two arms is "rotation around the hinge" (lever motion) → a small extracellular displacement is transmitted through the transmembrane helix to the intracellular side and amplified—"a change in the city gate's gap is transmitted via lever into the city"—**"V-shape = the geometric basis of allosteric amplification."**

**The informational significance of the "symmetric dimer."** The two half-receptors are identical (symmetric) → insulin only needs to bind "site 1 on either arm + site 2 on the opposite arm" (no need to distinguish left from right)—"the key works either way, front or back"—this lowers the directional requirements for binding and improves signaling reliability.

**The balance of "flexibility vs. rigidity."** The IR extracellular domain has flexibility (open/closed state dynamics) → insulin binding "selects and stabilizes the closed state"—"induced fit"—**"the receptor is not a rigid city gate, but a 'spring door'—insulin pushes it into the closed position."**

**Contrast with GLP-1R**: GLP-1R ([17-glp1r-structure.md](17-glp1r-structure.md)) uses a "venus flytrap ECD + 7TM" architecture, while IR uses a "Λ-shaped dimer + single-pass transmembrane + TK"—two completely different receptor architectures, yet both employ the universal logic of "ligand-induced allostery → intracellular conformational change"—"different city gates, same mechanics."

### 3.0 Looking Atom by Atom: Why Insulin Binds in a "Sandwich"

Many people ask: when insulin binds the receptor, why isn't it "one insulin, one binding site," but rather "one insulin sandwiched between two subunits"? The answer lies in "the precision of signal amplification":

**"Sandwich = the lever of allostery."** Insulin simultaneously contacts two half-receptors → binding itself "pulls the two arms together" (allostery) → intracellular TK domains approach each other → trans-phosphorylation—**"binding is allostery, allostery is signal"**—no additional "signal transduction molecule" is needed; the binding event itself is the signal—"the wedge is inserted, the gate gap changes, and the messenger inside the city senses it."

**"Sandwich = high affinity."** The two sites bind cooperatively (site 1 + site 2) → affinity far exceeds that of a single site (~1000-fold)—"double latching points hold fast"—ensuring that physiological insulin concentrations (pM–nM) are sufficient for activation—"the city gate is extremely sensitive to the 'genuine key.'"

**"Sandwich = specificity."** Insulin/IGF-1 are highly homologous (~50% sequence similarity), yet receptor selectivity differs—subtle differences in the binding sites (key residues in the αCT peptide segment) determine "insulin vs. IGF-1" selectivity—"the teeth of the lock distinguish two similar keys."

**"The magnitude of allostery."** The conformational change induced by insulin binding is a "fine-tuning" (arms approach by ~a few angstroms) rather than a "large-scale movement"—small extracellular change → transmembrane transduction → significant intracellular activation—"a tiny shift in the gate gap causes a big change in intracellular signaling"—this is a universal design of receptor signal transduction (allosteric amplification)—"small input, large output."

### 3.1 Structural-Pathway Perspective on "Insulin Resistance"

Insulin resistance (IR signaling↓) is the core of metabolic aging—mechanisms from structure to pathway:

- **Receptor level**: Receptor expression↓/internalization↓ (chronic hyperinsulinemia) → fewer/closed gates—"chronic overload, gate under repair";
- **IRS level**: IRS1/2 serine phosphorylation (JNK/IKK inflammatory kinases) → inhibits IRS function → signal interruption—"messengers 'stamped and disabled'";
- **Phosphatases**: PTP1B dephosphorylates IR/TK → weakened signaling—"the messenger's seal is erased";
- **Lipids/Inflammation**: Lipid accumulation (DAG/ceramides) → activates PKC/JNK → inhibits IRS—"spies (inflammation) inside the city sabotage communications";
- **ER stress**: UPR activation → inhibits insulin signaling—"city logistics paralyzed."

**"The consequence chain of resistance"**: Insulin signaling↓ → glucose uptake↓ (blood glucose↑) → pancreatic β-cell compensation (insulin↑) → hyperinsulinemia → further resistance + chronic FOXO3 inhibition → vicious cycle—"gate malfunction, garrison (β cells) works overtime, the more overtime the more chaos."

### 3.20 The Multi-Organ Landscape of "Insulin Resistance": One Gate, Multiple Roads into the City

Insulin resistance is not a single-organ event—it is systemic, with different tissues having different consequences of "malfunction":

**Muscle (main glucose uptake).** Resistance → GLUT4 translocation↓ → postprandial blood glucose↑—"muscle doesn't take up glucose, blood sugar stays in the blood."

**Liver (gluconeogenesis center).** Resistance → gluconeogenesis inhibition fails → hepatic glucose output↑ (fasting blood glucose↑)—"the liver doesn't heed the 'ceasefire' order, keeps releasing sugar."

**Adipose (storage organ).** Resistance → lipolysis inhibition fails → free fatty acids↑ → ectopic lipid accumulation (muscle/liver) → further resistance—"adipose doesn't heed the 'store it' order, leaks oil everywhere."

**Pancreatic β cells (compensators).** Long-term resistance → β-cell compensatory hypersecretion → eventual failure (β-cell apoptosis) → diabetes—"garrison works itself to death."

**Brain (feeding center).** Resistance/abnormal signaling → hypothalamic insulin signaling↓ → appetite dysregulation → obesity—"gate malfunction, central cafeteria opens randomly."

**"Multi-organ interplay" structural-systemic insight**: Insulin resistance is "systemic failure"—different tissues' "gates" malfunction simultaneously, exacerbating each other (lipid accumulation → inflammation → resistance)—**"metabolic aging is 'multiple gates on fire,' not a single-point failure"**—anti-aging requires "systemic management" (diet/exercise/sleep multi-pronged), not "fixing one organ"—"city-wide firefighting, not repairing one gate."

---

## 4. Insulin Signaling and Aging: The "Main Gate Rhythm" from a Structural Perspective

### 4.1 "Insulin-IGF-1 Signaling (IIS) and Longevity"

- **Model organism evidence**: daf-2 (nematode IR homolog) mutation → doubled lifespan (dependent on DAF-16/FOXO3); dwarf mice (GH/IGF-1 deficiency) → extended lifespan—"turning down the main gate leads to a longer life";
- **Human evidence**: IGF-1 levels correlate with longevity (complex, U-shaped); insulin sensitivity (not hyperinsulinemia) correlates with healthy aging—"the entrance needs to be 'sensitive' but not 'high-flow'";
- **Explanation of the "longevity paradox"**: The "quantity" and "sensitivity" of insulin signaling must be distinguished—"high sensitivity + low flow" (healthy) vs "low sensitivity + high flow" (resistance/overeating)—"a sensitive gate + few cars = smooth traffic; a sluggish gate + many cars = traffic jam."

### 4.10 "From Nematodes to Humans": The Complete Picture of the IIS Longevity Evidence Chain

**Nematodes (daf-2/daf-16).** daf-2 (IR homolog) mutation → doubled lifespan; and dependent on daf-16 (FOXO homolog)—"turning down the city gate + activating survival programs = longevity"—Kenyon's pioneering discovery in 1993—"the first evidence of a longevity switch was in nematodes."

**Fruit flies (InR/dFOXO).** InR mutation/downregulation → extended lifespan; dFOXO overexpression → extension—"the city gate logic also holds true in fruit flies."

**Mice (IGF-1R heterozygous/Growth hormone deficiency).** IGF-1R heterozygous knockout female mice → extended lifespan; Ames dwarf mice (GH deficiency → low IGF-1) → extended lifespan + slowed aging—"mammals also follow this rule."

**Humans (Genetic association).** FOXO3 genotype correlates with longevity ([16-foxo3-structure.md](16-foxo3-structure.md)); common characteristics of centenarians: good insulin sensitivity + tendency for low insulin/IGF-1—"the 'metabolic signature' of human longevity = sensitive city gate + low flow."

**The profound implication of "structural conservation"**: IR/FOXO3 are highly conserved from nematodes to humans—**"300 million years of evolution, the mechanics of the city gate haven't changed—indicating that the 'IIS-survival program' trade-off is a fundamental law of life."**

**"Cautious conclusion"**: IIS attenuation extends lifespan mainly through "moderate reduction in adulthood" (excessive reduction has developmental/immune costs); human intervention should "slightly reduce flow + maintain sensitivity"—"fine-tune the gate, don't dismantle it."

### 4.2 Anti-aging Strategies for the "Main Gate"

- **Caloric restriction/Fasting** ([03-nutrition](../07-interventions/03-nutrition.md)): Lower insulin → reduce "flow" → restore sensitivity—"reduce traffic flow, and the gate regains sensitivity";
- **Exercise**: Muscle contraction → AMPK activation + GLUT4 translocation (insulin-independent) → improved sensitivity—"build a 'bypass' into the city";
- **Sugar control/Mediterranean diet**: Reduce postprandial insulin spikes → protect β cells + restore sensitivity—"don't overload the city gate";
- **Metformin** ([07-metformin-ampk](../04-drugs/07-metformin-ampk.md)): AMPK activation → improved insulin sensitivity—"the drug oils the gate hinges";
- **GLP-1 drugs** ([17-glp1r-structure.md](17-glp1r-structure.md)): Promote insulin (glucose-dependent) → stable blood sugar → protect β cells—"let the guards work overtime as needed, without working them to death."

### 4.3 The Dialogue Between "Insulin Signaling" and Other Switches

| Downstream | Effect of Insulin | Structure Chapter |
|---|---|---|
| AKT-FOXO3 | Inhibition (phosphorylation-mediated cytoplasmic retention) | [16-foxo3-structure.md](16-foxo3-structure.md) |
| mTOR | Activation (anabolism) | [04-mtor-structure.md](04-mtor-structure.md) |
| AMPK | Antagonism (insulin inhibits AMPK) | [03-ampk-structure.md](03-ampk-structure.md) |
| GLUT4 | Promotes translocation (glucose uptake) | — |
| Glycogen/Lipid synthesis | Promotes (energy storage) | — |

**The regulatory significance of the "Main Gate"**: Almost all metabolic switches are "downstream" or "adjacent" to insulin signaling—**"controlling insulin signaling controls half the metabolic network"**—this explains why "sugar control/reducing insulin" is the cornerstone of metabolic anti-aging—"the city gate is the master valve; when the valve is stable, the whole city is stable."

---

## 5. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| IR is an α2β2 dimer ("Λ" shape) | ★★★★★ Solid | 4ZXB etc. |
| Insulin binding site 1 (L1+αCT) | ★★★★★ Solid | 3E7Y-related complexes |
| Insulin cross-arm binding (site 2) | ★★★★★ Solid | 4ZXB etc. |
| Insulin allosteric activation (arms brought together) | ★★★★★ Solid | Structure + dynamics |
| TK trans-autophosphorylation | ★★★★★ Solid | Biochemistry + structure |
| daf-2/IIS and longevity (C. elegans) | ★★★★★ Solid | Classical genetics |
| Insulin resistance increases with age | ★★★★★ Solid | Epidemiology |
| CR/exercise improves insulin sensitivity | ★★★★★ Solid | Clinical studies |

---

## 6. Connection to the Knowledge Base Main Thread

### 6.0 Structural Overview of "Metabolic Signaling": From Insulin to Aging

**"Signaling backbone"**:
```
Insulin → IR (this article 21) → PI3K-AKT → [mTOR(04) synthesis | FOXO3(16) survival | AMPK(03) antagonism]
GLP-1 → GLP-1R(17) → Insulin↑ (back to start)
Energy → AMPK(03) → [Autophagy(18) | FOXO3(16)]
Nutrients → mTORC1(04) → [Synthesis | Autophagy↓]
```

**"Anti-aging logic of the backbone"**: ① Reduce insulin "traffic" (CR/sugar control) → FOXO3 gets a window + mTOR gets intermittent breaks — "city gate traffic reduced, internal switches balanced"; ② Improve sensitivity (exercise/metformin) → effective signaling with less insulin — "gate is sensitive, fewer carts still enter the city"; ③ GLP-1 (drug) → insulin on demand — "garrison works overtime as needed".

### 6.00 The Circadian Rhythm of "Insulin Signaling": The City Gate Also Has Working Hours

**"Circadian fluctuation of insulin sensitivity".** Early morning (dawn phenomenon) → lower insulin sensitivity; daytime activity → higher sensitivity; nighttime → sensitivity recovery/changes — "city gate wide open by day, half-closed at night."

**"Feeding rhythm and the insulin curve".** Each meal → insulin peak; between meals → decline; fasting → trough — "city gate 'opens-closes' with meals" — the higher the feeding frequency, the more frequently the gate "opens and closes," and the more fatigued the signaling system becomes — "frequent opening and closing wears the hinges fast."

**"Metabolic cost of circadian disruption".** Late nights/shift work → insulin sensitivity↓ + appetite hormone disruption → accelerated metabolic aging — "city gate schedule disrupted, the whole city falls into chaos."

**"Structure-rhythm" anti-aging insights**: ① **Intermittent fasting** ([03-nutrition](../07-interventions/03-nutrition.md)) → gives insulin signaling a "trough period" (gate rests) → restores sensitivity — "let the city gate have off-duty time"; ② **Regular schedule** → maintains the rhythm of insulin sensitivity — "city gate opens and closes on time"; ③ **Morning light/exercise** → calibrates the biological clock → metabolic rhythm synchronization — "city gate runs on schedule" — **"The 'rhythm dimension' of anti-aging: insulin signaling needs 'intermittency,' not 'always-on'"**.

### 6.1 Main Thread Article Dialogue

- **FOXO3 structure** ([16-foxo3-structure.md](16-foxo3-structure.md)): Insulin → AKT → FOXO3 off — "main entrance shuts down survival programs";
- **GLP-1R structure** ([17-glp1r-structure.md](17-glp1r-structure.md)): GLP-1 → Insulin↑ → IR — "upstream friend";
- **mTOR structure** ([04-mtor-structure.md](04-mtor-structure.md)): Insulin → mTOR activation — "main entrance turns on the growth switch";
- **AMPK structure** ([03-ampk-structure.md](03-ampk-structure.md)): AMPK antagonizes insulin signaling — "two master switches in opposite directions";
- **Metabolic aging** ([03-metabolic-aging](../02-vascular/03-metabolic-aging.md)): Insulin resistance = core of metabolic aging — "main entrance malfunction";
- **Metformin** ([07-metformin-ampk](../04-drugs/07-metformin-ampk.md)): Improves sensitivity — "repairing the city gate";
- **Nutrition/Fasting** ([03-nutrition](../07-interventions/03-nutrition.md)): Feeding rhythm → insulin curve — "how you eat determines gate traffic."

---

## 7. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How does insulin activate the receptor? | Clamped between two half-receptors (site 1+2) → arms close → TK trans-phosphorylation |
| Why the "sandwich" design? | Binding = allostery (signal) + high affinity + specificity — "wedge + double latch" |
| Structural basis of insulin resistance? | Receptor↓/IRS phosphorylation inhibition/PTP1B/inflammation — "gate + messengers both fail" |
| Why does IIS attenuation extend lifespan? | FOXO3 activation + mTOR inhibition — "main gate turned down, survival programs on duty" |
| How to counter aging? | CR/exercise/metformin reduce flow + improve sensitivity — "sensitive gate, fewer cars" |

**Structural intuition beyond the five questions**: The insulin receptor story reveals the "universal grammar" of receptor signal transduction—**"the ligand does not enter the cell; it only 'knocks'—the signal is conducted by the receptor's own conformational change."** Insulin does not enter the cell (binding the extracellular domain is sufficient); the signal relies entirely on IR's "deformation" (arms close → TK trans-phosphorylation) to reach the intracellular side—"the key doesn't enter the door, the door opens itself"—this is the common logic of all membrane receptors (GPCR/receptor tyrosine kinases/cytokine receptors)—"the cell's 'city gate' philosophy: knock from outside, open from inside, the key never enters the courtyard." The evolutionary significance of this design: **the signal is "amplified" inside the cell (one binding event → kinase cascade → thousands of downstream molecules), while the ligand itself carries no "amplification capacity"**—"the gate-opening motion is small, the city's response is large"—**"the receptor is an 'amplifier,' the ligand is merely a 'switch'—understanding this explains why 'few but precise signals' (low insulin) can maintain health, while 'many and chaotic' (high insulin resistance)instead disrupts the system"**.

---

## 8. Open Questions

1. **Full-length IR structure**: Complete structure of extracellular + transmembrane + intracellular TK (continuous mechanism of signal transduction);
2. **Dynamics of insulin binding**: Real-time process of binding/allostery (single-molecule/time-resolved);
3. **IR/IGF-1R hybrid receptors**: Structure and signaling properties of hybrid receptors;
4. **Molecular details of insulin resistance**: Structural basis of IRS phosphorylation inhibition;
5. **"Selective activation" drugs**: Can "metabolic-biased" insulin analogs be designed;
6. **"Tissue specificity"**: Signaling differences of IR in different tissues (liver/muscle/adipose/brain).

### 8.1 "The Final Chapter of Receptor Signaling": Methodological Summary of 21 Structure Articles

The insulin receptor is Part 21 of the 10-structures series—the finale of the "metabolic signaling" series. At this point, the series has covered the complete chain from "signal entry" to "execution machinery":

**Signaling layer**: IR ([21](21-insulin-receptor.md) city gate) → GLP-1R ([17](17-glp1r-structure.md) satiety) → NO signaling ([01](01-nos-structures.md)/[02](02-sgc-heme.md) messenger);

**Regulatory layer**: AMPK ([03](03-ampk-structure.md) energy) → mTOR ([04](04-mtor-structure.md) growth) → FOXO3 ([16](16-foxo3-structure.md) survival);

**Execution layer**: Autophagy ([18](18-lc3-autophagy.md) recycling station) → Proteasome ([20](20-proteasome.md) shredder) → Complex I ([12](12-complex1-structure.md) generator);

**Information layer**: Epigenetics ([05](05-tet-dna.md)/[06](06-sirt1-structure.md)/[07](07-dnmt1-structure.md)) → Telomeres ([11](11-telomerase-structure.md) clock) → Cell fate ([13](13-p53-structure.md));

**Defense layer**: NF-κB ([14](14-nfkb-structure.md)) → Nrf2 ([15](15-nrf2-structure.md)) → NLRP3 ([19](19-nlrp3-inflammasome.md));

**NAD⁺ economy**: NAMPT ([10](10-nampt-structure.md))/SIRT1 ([06](06-sirt1-structure.md))/CD38 ([08](08-cd38-structure.md))/PARP1 ([09](09-parp1-structure.md)).

**"Core conclusion of reading all 21 articles together"**: Aging is not "one molecule breaking," but **"network imbalance across five layers: signaling-regulation-execution-information-defense"**—each structure article reveals "how one molecule works," while reading them together reveals "how the network operates"—**"from atoms to networks, from mechanisms to strategies—this is the complete map of the 10-structures series, and the ultimate realization of the knowledge base's 'full-chain mechanism' philosophy."**

---

## 9. Structural Data Acquisition Guide

- **PDB entries**:
  - 3E7Y: Human insulin (1.60 Å) — ligand structure;
  - 4ZXB: Human IR ectodomain (3.30 Å, Croll 2016 *Structure*) — "Λ"-shaped fold;
  - 2DTG: IR ectodomain (3.8 Å, McKern 2006 *Nature*) — first IR ectodomain structure;
  - 3W11/3W12: IR-TK domain + ligand complexes;
  - 4XSS, etc.: IGF-1R structures;
  - 1IRK: IR-TK domain (classic, Hubbard 1994);
  - AlphaFold: AF-P06213 (predicted full-length IR).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (Authentic Literature)

1. Croll TI, Smith BJ, Margetts MB, et al. Higher-resolution structure of the human insulin receptor ectodomain: multi-modal inclusion of the insert domain. *Structure* 2016;24:469-476. (PDB 4ZXB)
2. McKern NM, Lawrence MC, Streltsov VA, et al. Structure of the insulin receptor ectodomain reveals a folded-over conformation. *Nature* 2006;443:218-221. (PDB 2DTG)
3. Hubbard SR, Wei L, Ellis L, Hendrickson WA. Crystal structure of the tyrosine kinase domain of the human insulin receptor. *Nature* 1994;372:746-754. (PDB 1IRK)
4. Kenyon C, Chang J, Gensch E, Rudner A, Tabtiang R. A C. elegans mutant that lives twice as long as wild type. *Nature* 1993;366:461-464. (daf-2 longevity discovery)
5. De Meyts P. The insulin receptor: structure, function and signaling. *Am J Med* 2000;108:1-9. (IR review)
6. Samuel VT, Shulman GI. Mechanisms for insulin resistance: common threads and missing links. *Cell* 2012;148:852-871. (Insulin resistance mechanisms)
7. Fontana L, Partridge L, Longo VD. Extending healthy life span--from yeast to humans. *Science* 2010;328:321-326. (IIS and lifespan review)

---

> **Structure at a Glance**: The insulin receptor is the cell's **"metabolic main gateway"** — an α2β2 tetramer forming a **"Λ" shape** (revealed by 4ZXB); insulin is "clamped" between two half-receptors (site 1 + site 2) → arms close → TK trans-autophosphorylation → PI3K-AKT → glucose uptake/anabolism/FOXO3 inhibition. **Insulin resistance (signaling↓) → core of metabolic aging**; **IIS attenuation (daf-2 mutation) extends lifespan (FOXO3 activation)** — the "longevity paradox" explained: need "high sensitivity + low flow" (sensitive gate, fewer cars). **Anti-aging strategies**: CR/sugar control to reduce flow + exercise/metformin to improve sensitivity — "repair the city gate, let metabolic signaling flow smoothly without overload."
