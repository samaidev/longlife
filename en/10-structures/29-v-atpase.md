# Molecular Structure Deep Dive 29: V-ATPase—the “Proton-Pump Engine” and Rotary Motor for Lysosomal Acidification

> **Series context**: Article 29 in 10-structures (Molecular Structure Deep Dive): the three-dimensional structure of V-ATPase (vacuolar-type ATPase), including how cells “acidify” lysosomes, how ATP drives the proton pump, the molecular mechanism of rotary catalysis, and V-ATPase’s role as the lysosomal “engine” in anti-aging. It is the downstream execution machine in the knowledge base’s lysosome narrative ([28-tfeb.md](28-tfeb.md)): TFEB is the “lysosome factory manager,” while V-ATPase is the “proton-pump engine.”
> **Related articles**: TFEB: [28-tfeb.md](28-tfeb.md); LC3/autophagy: [18-lc3-autophagy.md](18-lc3-autophagy.md); Complex I: [12-complex1-structure.md](12-complex1-structure.md) (comparison with rotary/energy machines); mTOR: [04-mtor-structure.md](04-mtor-structure.md) (V-ATPase-mTOR interaction).

---

## 0. Structural overview

**In one sentence**: V-ATPase is the lysosome’s “proton-pump engine”—an ATP-driven pump that moves protons (H⁺) into lysosomes to maintain an acidic interior (pH ~4.5–5.0)—“the lysosome’s acidification engine: without it, lysosomes cannot ‘burn waste’ (hydrolases need an acidic environment).” It consists of two complexes: cytosolic V₁ (ATP hydrolysis, rotary motor) and membrane-embedded V₀ (proton channel, rotary pump)—“V₁ is the engine, V₀ the water pump, joined by a shaft.”

```text
V-ATPase structure:
  V₁ (cytosolic, ATP hydrolysis): A3B3 (catalytic hexamer) + C/D/E/F/G/H (accessory) + central shaft (DF)
                  │
  Connection: central shaft passes through → drives V₀ rotation
                  │
  V₀ (in membrane, proton pump): a (1) + c8-c9 ring (rotor) + e/f/d (accessory)
                  │
  Rotary catalysis: ATP hydrolysis (three A/B pairs) → central shaft rotates → c-ring rotates
                    → protons pumped into lysosome through the a/c interface
```

**Three major structural features** (the atomic basis of function):
1. **V₁ A₃B₃ catalytic hexamer**: three AB pairs; ATP hydrolysis drives rotation—“a three-cylinder engine”;
2. **Central shaft (subunits D/F)**: rotary shaft connecting V₁ to V₀—“the driveshaft from the engine to the pump”;
3. **V₀ c-ring**: membrane-embedded rotor (8–9 c subunits); protons move across the a/c interface—“the impeller of the rotary pump.”

**Core regulatory mechanism**:

```text
ATP + H2O → ADP + Pi (V1 A/B pairs, three active sites cycle in turn)
    → central shaft rotates (120°/step) → c-ring rotates
    → protons pumped from cytosol into lysosomal lumen through the a/c interface
    → lysosomal acidification (pH 4.5–5.0) → hydrolase activation → degradation
        │
Regulation: reversible V1-V0 dissociation (glucose starvation) → pump switched off (energy saving)
            mTORC1 interacts with V-ATPase (at lysosomal surface) → nutrient sensing
```

---

## 1. Why V-ATPase’s structure matters

V-ATPase is the “engine” of lysosomal function:

- **“Lysosomal acidification engine”**: V-ATPase maintains an acidic lysosomal environment (the optimal pH for hydrolases)—“without acidification, lysosomes are just props” (the lysosome step in [28-tfeb.md](28-tfeb.md));
- **“The final step of autophagy-lysosome function”**: after an autophagosome fuses with a lysosome, V-ATPase must acidify it so its contents can be degraded—“whether waste gets burned depends on the engine” ([18-lc3-autophagy.md](18-lc3-autophagy.md));
- **Anti-aging evidence**: V-ATPase function declines with age → inadequate lysosomal acidification → reduced degradation → waste accumulation (the “lysosomal aging” in [28-tfeb.md](28-tfeb.md))—“when the engine ages, the recycling center shuts down”;
- **Crosstalk with TFEB** ([28-tfeb.md](28-tfeb.md)): V-ATPase subunits are TFEB target genes—“the manager orders new engines”; V-ATPase also contributes to mTORC1 activation at the lysosomal surface (negative feedback)—“the engine also participates in nutrient sensing”;
- **Crosstalk with mTOR** ([04-mtor-structure.md](04-mtor-structure.md)): mTORC1 is activated at the lysosomal surface by V-ATPase/Rag (amino-acid sensing)—“the lysosome is a nutrient-signaling center, and V-ATPase supplies its power”;
- **Drug target**: V-ATPase inhibitors (e.g., bafilomycin) are research tools/anticancer agents (inhibit acidification)—“the engine’s brake.”

**Three key questions for structural research**:
1. How does ATP hydrolysis drive rotation (mechanism of rotary catalysis)?
2. How are protons transported through the a/c interface (the pump’s molecular pathway)?
3. How are V₁ and V₀ assembled and dissociated (regulatory mechanism)?

These questions have been addressed by structures such as 6WM3 (complete human V-ATPase, 2020).

---

## 2. Structural anatomy of V-ATPase

### 2.1 V₁ A₃B₃ catalytic hexamer—the “three-cylinder engine”

- **Location**: cytosolic side;
- **Structure**: three A subunits and three B subunits alternate in a ring (hexamer)—“the cylinders of a three-cylinder engine”;
- **Catalytic sites**: ATP binding/hydrolysis occurs at A/B interfaces (catalytic residues on A subunits)—“the three cylinders take turns doing work”;
- **Rotary catalysis**: ATP hydrolysis → central shaft rotates 120° per step (three sites cycle)—“the three cylinders fire in turn, rotating the shaft”;
- **Finding from 6WM3**: structures captured in three rotary states (states 1/2/3) reveal intermediates of the rotation cycle—“three strokes of the engine captured in snapshots.”

### 2.2 Central shaft (DF)—“the driveshaft”

- **Location**: center of V₁, passing through the A₃B₃ ring;
- **Structure**: D/F subunits form a helical shaft → connect the V₁ catalytic ring with the V₀ c-ring—“the driveshaft from engine to pump”;
- **Rotation**: ATP hydrolysis drives rotation of the central shaft → turns the c-ring—“when the shaft turns, the impeller turns”;
- **Comparison with F-ATPase**: V-ATPase is structurally homologous to F-ATPase (mitochondrial ATP synthase; rotary catalysis)—“members of the same rotary-motor family” (see the energy machine in [12-complex1-structure.md](12-complex1-structure.md));
- **“Reverse operation”**: F-ATPase uses the proton gradient to synthesize ATP; V-ATPase uses ATP to pump protons—“same motor, forward or reverse.”

### 2.3 V₀ c-ring—the “rotary pump”

- **Location**: within the membrane;
- **Structure**: c subunits (8–9) form a membrane-embedded ring (c8-c9 ring)—“the pump’s impeller”;
- **Proton pathway**: two “half-channels” at the interface between membrane-embedded subunit a and the c-ring → protons enter/leave the c-ring through the a/c interface—“protons enter through the inlet in a and rotate out with the c-ring”;
- **Rotary-pump mechanism**: c-ring rotation → glutamate (Glu) in each c subunit binds/releases a proton → protons move from the cytosol into the lumen—“each turn of the impeller carries a proton across the membrane”;
- **Finding from 6WLW**: lipids/glycosylation in the V₀ region → stabilize the c-ring and form a luminal glycan coat—“lubrication and corrosion protection for the pump.”

---

## 3. Molecular logic of rotary catalysis: from structure to chemistry

### 3.00 Engineering logic of the “rotary motor”: why V-ATPase is a “molecular electric motor”

The previous section described the rotary pump. Here we examine **the design details that make V-ATPase a “molecular motor”**—a pinnacle of biological nanomachinery:

**“The firing order of the three-cylinder engine.”** The three catalytic sites in A₃B₃ “cycle through different states” during rotation (one binds ATP, one hydrolyzes it, one releases ADP/Pi). The three states captured in 6WM3 correspond to “three strokes of the three cylinders”—“the cylinders fire in turn, keeping the shaft in continuous rotation”—**“rotary catalysis means three sites hand off the work, so energy conversion does not stop.”**

**“Mechanics of a 120° step.”** One ATP hydrolysis event → ~120° shaft rotation (one step) → three steps per revolution → the c-ring rotates with it—“each ATP buys 120° of rotation”—“the chemical-to-rotation gear ratio is fixed (1 ATP = 120°).”

**“The c-ring’s number of ‘teeth’ and proton count.”** The c-ring has 8–9 c subunits → pumps 8–9 protons per revolution (each c-subunit Glu carries one proton)—“8–9 protons per turn; the gear’s tooth count determines the pumping capacity”—“the gear’s tooth count determines the number of protons pumped.”

**“Half-channel design at the a/c interface.”** Subunit a provides two “half-channels” (a cytosolic inlet + luminal outlet) → protons are handed off at the a/c interface: a cytosolic proton enters a half-channel → binds c-ring Glu → rotates halfway with the c-ring → reaches the luminal half-channel → is released—“the proton rides the impeller halfway, from inlet to outlet”—“half-channels + rotation = a one-way pump.”

**“Comparison with ATP synthase (F₁F₀).”** V-ATPase and mitochondrial ATP synthase (F-ATPase) are “nearly isomorphic” (A₃B₃ ≈ F₁, c-ring ≈ c₈–₁₅), but operate in **opposite directions** (F uses the proton gradient to synthesize ATP; V uses ATP to pump protons)—“the same motor generates power in one direction and pumps in the other: a two-mode motor of the nanoworld”—**“evolution built a two-mode rotary motor that can work in either direction”** (see the energy machine in [12-complex1-structure.md](12-complex1-structure.md)).

### 3.0 Atom by atom: why V-ATPase uses rotation to pump protons

A common question is: why use “rotation” rather than “opening and closing” (channel gating) to pump protons? The answer is efficiency and continuity:

**“Rotation enables continuous pumping.”** A rotary motor can run continuously (pumping a proton with each step) → high, sustained pumping rate—“a rotary pump is faster than a reciprocating pump.” Lysosomes need continuous acidification (hydrolase activity consumes the pH gradient) → they need a “continuous pump”—“the engine must run continuously, not intermittently.”

**“Rotation lets three sites take turns, increasing efficiency.”** The three catalytic sites in A₃B₃ “take turns working” (one hydrolyzes ATP, one binds ATP, one releases ADP) → continuous energy utilization—“the cylinders fire in turn; there is no idle stroke”—“rotary catalysis enables continuous energy use.”

**“Rotation enables direct, efficient mechanical coupling.”** Chemical energy from ATP hydrolysis → directly converted into rotational mechanical energy (without an intermediate carrier) → low energy loss—“chemical energy becomes rotation directly, without an intermediate ‘spring.’”

**“Coordination between rotation and the proton pathway.”** The c-ring rotates while subunit a remains fixed → half-channels at the a/c interface enable proton handoff (with each step, one Glu moves from the cytosolic to the luminal side)—“the impeller and stator work together; one step, one proton”—“rotation + half-channels = a continuous one-way pump.”

**“Comparison with Complex I.”** Complex I ([12-complex1-structure.md](12-complex1-structure.md)) uses redox energy to pump protons (without rotation); V-ATPase uses ATP hydrolysis and rotation—“two energy sources (redox vs. ATP), two pumping methods (conformational change vs. rotation)”—“the cell has several proton-pumping strategies.”

### 3.1 Reversible V₁/V₀ dissociation: the engine’s “shutdown and restart”

A distinctive regulatory feature of V-ATPase is reversible dissociation of V₁ from V₀—the “engine can shut down”:

**“Dissociation (shutdown).”** Glucose starvation/energy deficiency → V₁ dissociates from V₀ (into the cytosol) → pump activity stops → ATP is conserved—“out of fuel, shut down to save it.” Dissociation of V₁ also exposes V₀ and may regulate membrane permeability (a non-pumping role)—“even when the engine is off, it may still serve as a ‘gate.’”

**“Reassembly (restart).”** Glucose returns → V₁ rebinds V₀ → pumping resumes → lysosomes acidify again—“refuel and restart.” Assembly is regulated by signals (glycosylation/protein interactions)—“restart requires a ‘key.’”

**“Physiological significance of disassembly/reassembly.”** ① energy saving (turn off the pump when energy is scarce); ② regulation of lysosomal pH (pH changes affect degradation/signaling); ③ participation in organelle fusion (membrane functions after V₀ dissociation)—“shutting down the engine saves fuel and also changes the state of the whole vehicle.”

**“Age-related dysregulation of disassembly/reassembly.”** In older organisms, V-ATPase assembly and pump activity decline → insufficient lysosomal acidification → reduced degradation—“the engine stays off for too long and the recycling center shuts down”—“repairing the engine means restoring assembly and supplying energy.”

### 3.20 V-ATPase and mTOR: the engine also acts as a “nutrient sensor”

V-ATPase’s “second job” is to contribute to mTORC1 activation at the lysosomal surface—“the engine moonlights as a nutrient alarm”:

**“The lysosome is a nutrient-sensing center.”** Amino acids reach the lysosomal lumen → V-ATPase senses the luminal amino-acid concentration → activates the Ragulator-Rag complex → recruits mTORC1 to the lysosomal surface → activates it—“the lysosome is a nutrient-signaling center, and V-ATPase is its sensor” ([04-mtor-structure.md](04-mtor-structure.md)).

**“V-ATPase as a sensor (model).”** Subunit a/V₁ subunits of V-ATPase interact with Ragulator → changes in luminal amino-acid concentration → changes in V-ATPase conformation/pumping state → signal passed to Rag → mTORC1—“the engine’s rpm reflects the amount of fuel (amino acids)”—“the pump’s operating state is a nutrient readout.”

**“The engine’s dual identity.”** ① pumps protons (acidifies lysosomes); ② senses nutrients (activates mTORC1)—“one machine, two functions”—“the engine works (pumps) and sends information (senses).”

**“Connection to aging.”** Reduced lysosomal V-ATPase function → ① insufficient acidification (reduced degradation); ② abnormal nutrient sensing (abnormal mTORC1 signaling) → metabolic dysfunction—“when the engine breaks, it can neither burn waste nor report nutrient status”—“repair the engine and solve both problems.”

**“Anti-aging implications.”** Maintaining healthy V-ATPase function → ① normal lysosomal degradation; ② normal mTORC1 nutrient sensing—“a healthy engine keeps both the recycling center and nutrient center working”—**“V-ATPase is a hub in the lysosome-nutrient-autophagy triangle; structural research reveals that one machine has multiple responsibilities.”**

---

## 4. V-ATPase and aging: a structural view of the “aging engine”

### 4.1 V-ATPase declines with age

- **Expression/assembly ↓**: expression of V-ATPase subunits or V₁/V₀ assembly declines in aged tissues—“engine parts age, and assembly becomes less efficient”;
- **Acidification capacity ↓**: lysosomal pH rises (inadequate acidification) → hydrolase activity ↓ → degradation capacity ↓—“the engine has too little power to burn waste”;
- **Vicious cycle with TFEB** ([28-tfeb.md](28-tfeb.md)): V-ATPase ↓ → lysosomal acidification ↓ → autophagy-lysosome degradation ↓ → waste accumulates → cellular damage → TFEB activity also ↓ → V-ATPase declines further—“engine breaks → recycling center shuts down → manager fails → engine deteriorates further”;
- **Consequence**: accumulation of waste/damaged organelles → accelerated aging (neurodegeneration/sarcopenia/metabolic dysfunction)—“the recycling center shuts down and waste fills the cell.”

### 4.2 Anti-aging strategies to “repair the engine”

- **Energy supply**: NAD⁺ economy ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md))/mitochondrial health ([12-complex1-structure.md](12-complex1-structure.md)) → adequate ATP → fuel for V-ATPase—“the engine needs fuel (ATP)”;
- **TFEB activation** ([28-tfeb.md](28-tfeb.md)): fasting/exercise → TFEB enters the nucleus → V-ATPase-subunit genes ↑ → build new engines—“the manager orders replacement engines”;
- **Reduce lysosomal burden**: glucose control/antioxidant measures → less waste → lysosomes avoid overload → V-ATPase avoids fatigue—“burn less waste, and the engine tires less”;
- **Exercise**: enhances lysosomal function (TFEB + energy) → supports engine health—“use it or lose it: the engine works better with use”;
- **“Moderation” principle**: excessive V-ATPase inhibition (e.g., bafilomycin) → lysosomal failure; abnormal overactivation → may affect pH in other organelles—“the engine should run normally, not overheat.”

### 4.3 The complete lysosome-autophagy chain: TFEB-V-ATPase-LC3

| Step | Molecule | Structure article | Function |
|---|---|---|---|
| Initiation | ULK1 | [27-ulk1.md](27-ulk1.md) | Autophagosome nucleation |
| Labeling | LC3 | [18-lc3-autophagy.md](18-lc3-autophagy.md) | Autophagosome labeling |
| Expansion | TFEB | [28-tfeb.md](28-tfeb.md) | Lysosomal genes ↑ |
| Acidification | V-ATPase | [29-v-atpase.md](29-v-atpase.md) | Lysosomal acidification |
| Degradation | Hydrolases | (acid-dependent) | Degradation of contents |

**“Logic of the chain.”** ULK1 initiates → LC3 labels → TFEB expands capacity (including V-ATPase) → V-ATPase acidifies → hydrolases degrade—“initiation-labeling-expansion-acidification-degradation,” a five-link loop—**“V-ATPase is the engine at the final step: without acidification, all the earlier steps are for nothing”**—“the recycling center may be built, but without power (acidification), it still cannot burn waste.”

---

## 5. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| V-ATPase consists of V₁ (cytosolic) + V₀ (membrane) | ★★★★★ Established | 6WM3 and others |
| V₁ A₃B₃ hexamer catalyzes ATP hydrolysis | ★★★★★ Established | 6WM3 (2020, *Mol Cell*) |
| Central shaft (DF) connects V₁/V₀ | ★★★★★ Established | 6WM3 |
| V₀ c-ring rotates to pump protons | ★★★★★ Established | 6WM3/6WLW |
| Rotary catalysis (three states captured) | ★★★★★ Established | 6WM3 |
| Reversible V₁/V₀ dissociation (starvation) | ★★★★★ Established | Classic biochemistry |
| Lysosomal acidification depends on V-ATPase | ★★★★★ Established | Physiology |
| V-ATPase function declines with age | ★★★★ Strong | Multiple studies |

---

## 6. Connections to the knowledge-base narrative

### 6.0 Structural overview of the “energy-machine family”: the rotary motor across 29 articles

The energy-machine family in the 10-structures series now has three members:

| Machine | Function | Structure article | Energy source |
|---|---|---|---|
| Complex I | Respiratory-chain proton pump | [12-complex1-structure.md](12-complex1-structure.md) | Redox (nonrotary) |
| ATP synthase (F-ATPase) | ATP synthesis | (related) | Proton gradient (rotation) |
| V-ATPase | Lysosomal acidification | [29-v-atpase.md](29-v-atpase.md) | ATP (rotation) |

**“Rotary-motor family.”** V-ATPase and F-ATPase share the design of “rotary catalysis” (A₃B₃/F₁ homologs; c-rings/V₀ homologous)—“one ancestral motor: one makes ATP, the other pumps protons”—**“evolution copied a rotary motor and adapted it to different uses”** (echoing the “protein reassignment” theme in [26-klotho.md](26-klotho.md)).

### 6.00 The complete picture of lysosome-autophagy: closing the “recycling system” across 29 articles

V-ATPase is article 29 in the 10-structures series—the finale of the lysosome-autophagy sequence. The complete cellular “recycling system” now comes into view:

**“Recycling-system initiation”**: AMPK/mTOR (sensing) → ULK1 ([27](27-ulk1.md), initiation) → autophagosome nucleation;

**“Recycling-system execution”**: LC3 ([18](18-lc3-autophagy.md), labeling) → autophagosome formation;

**“Recycling-system expansion”**: TFEB ([28](28-tfeb.md), lysosomal genes) → new lysosomes/enzymes;

**“Recycling-system power”**: V-ATPase ([29](29-v-atpase.md), acidification) → hydrolase activation;

**“Recycling-system quality control”**: PINK1/Parkin ([24](24-pink1-parkin.md), mitochondria) → selective clearance.

**“Reading the recycling-system narrative across 29 articles.”** Cellular recycling is not the work of “one protein” but a complete system of sensing, initiation, execution, expansion, power, and quality control—**“anti-aging means maintaining every link in the recycling system: sensitive initiation (ULK1), efficient execution (LC3), timely expansion (TFEB), adequate power (V-ATPase/NAD⁺), and precise quality control (PINK1/Parkin).”** Keep the recycling system running comprehensively and regularly so cells can keep cleaning house—this is the fullest account of cellular recycling in the structural knowledge across 29 articles.

### 6.1 Conversations with the main narrative

- **TFEB** ([28-tfeb.md](28-tfeb.md)): the manager orders V-ATPase production—“the order for the lysosome’s engine”;
- **LC3/autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): autophagic degradation depends on acidification—“the last step depends on the engine”;
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): comparison of energy machines—“two approaches to proton pumping”;
- **mTOR** ([04-mtor-structure.md](04-mtor-structure.md)): mTOR activation at the lysosomal surface (V-ATPase-Rag)—“the engine also handles nutrient sensing”;
- **NAD⁺/SIRT1** ([06-sirt1-structure.md](06-sirt1-structure.md)): energy metabolism supports ATP → fuels the engine—“the NAD⁺ economy supplies power”;
- **Klotho** ([26-klotho.md](26-klotho.md)): Klotho’s anti-aging effects are related to lysosomal health—“the longevity protein protects the engine”;
- **ULK1** ([27-ulk1.md](27-ulk1.md)): the “first mover” in autophagy initiation—“start button + terminal engine.”

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does V-ATPase acidify lysosomes? | ATP hydrolysis → central shaft rotates → c-ring rotates → protons pumped in through the a/c interface |
| Why use rotation? | Continuous pumping + three sites taking turns + efficient mechanical coupling—“rotary pumping beats reciprocating pumping” |
| How is it regulated? | Reversible V₁/V₀ dissociation (shutdown during starvation) + reassembly (restart) |
| Why does it decline with age? | Expression/assembly ↓ + inadequate acidification + vicious cycle with TFEB—“the engine ages” |
| How can aging be countered? | Energy supply (NAD⁺/mitochondria) + TFEB activation + reducing burden—“fuel it + replace it + reduce the load” |

**“Structural intuition beyond the five questions.”** V-ATPase’s story reveals the energy-function economics of nanomachines—**“the cell uses molecular motors to turn chemical energy into mechanical energy with precision of 1 ATP = 120° rotation.”** V-ATPase is a pinnacle of biological nanoengineering: a three-cylinder engine (A₃B₃), driveshaft (DF), rotary impeller (c-ring), and half-channel pump (a/c interface)—“the cell is a molecular factory, and V-ATPase is its precision machine tool.” **Anti-aging implications**: ① nanomachine health depends on energy supply (ATP) and maintenance (assembly/replacement)—“the engine needs fuel and servicing”; ② aging = nanomachines wear down (V-ATPase assembly ↓/acidification ↓) → recycling-system failure—“the precision machine rusts, and the factory stops”; ③ anti-aging = maintenance of nanomachines (energy + replacement parts + reduced load)—“maintain the machine tool so the factory can keep running”—**“From V-ATPase’s molecular motor to the cellular factory, structural knowledge shows that aging is wear and tear in nanomachines, and anti-aging is nano-maintenance.”**

### 8.1 V-ATPase and neurodegeneration: a brain whose recycling center has lost power

V-ATPase in neurodegeneration—the “power-outage crisis” in the brain’s recycling center:

**“High lysosomal workload in neurons.”** Neurons are long-lived and highly metabolically active → lysosomes work continuously → V-ATPase operates under heavy load—“neuronal engines run at high speed for years.”

**“Insufficient acidification and aggregation.”** V-ATPase function ↓ → lysosomal pH rises → hydrolase activity ↓ → aggregates (α-synuclein/Aβ/Tau) are not cleared → neurodegeneration—“the recycling center loses power and waste piles up” (see the neurodegeneration section in [28-tfeb.md](28-tfeb.md)).

**“Evidence for acidification defects in AD/PD.”** Lysosomal acidification is inadequate (pH rises) in AD brain tissue; α-synuclein aggregation associated with PD is linked to lysosomal dysfunction—“the patients’ recycling center is experiencing a power outage.”

**“Neuroprotection by boosting V-ATPase.”** Increasing V-ATPase expression/activity (in animals) → restores lysosomal acidification → clears aggregates → neuroprotection—“restore power and the recycling center goes back to work.”

**“Therapeutic challenges.”** Brain delivery + side effects of global enhancement (effects on pH in other organelles)—“power must be supplied precisely; do not flip the wrong switch”—“the future of V-ATPase therapies for neurodegeneration lies in precise, lysosome-targeted enhancement.”

**“A prescription for anti-aging and brain protection.”** Metabolic energy health (NAD⁺/mitochondria to fuel the engine) + TFEB activation (replace the engine) + exercise (use it or lose it) → keep brain lysosomes “powered”—“keep neuronal recycling centers powered, so the brain can stay clean and renewed”—a practical guide to brain-protective anti-aging based on V-ATPase structural knowledge.

---

## 8. Open questions

1. **Complete rotary cycle of V-ATPase**: transitions among the three states (time-resolved cryo-EM);
2. **Precise proton-transport pathway**: atomic details of the proton channel at the a/c interface (water molecules/residues);
3. **Molecular mechanism of V₁/V₀ dissociation and assembly**: how signals trigger dissociation (glycosylation/phosphorylation);
4. **V-ATPase-mTOR interaction**: precise structure of nutrient sensing at the lysosomal surface;
5. **Tissue specificity**: V-ATPase regulation in different lysosomes (neurons/macrophages);
6. **V-ATPase drugs**: compounds for selective modulation (enhance lysosomal acidification vs. inhibit tumors).

### 8.2 V-ATPase and cancer: the engine’s “two-sided nature”

V-ATPase in cancer—the “recycling-center engine commandeered by cancer cells”:

**“Cancer cells depend on V-ATPase.”** Rapid proliferation/acidic metabolism (lactate produced by the Warburg effect) → dependence on V-ATPase-mediated acid export and lysosomal support for invasion → V-ATPase activity ↑ (in many cancers)—“cancer cells recruit the engine to export acid and support degradation.”

**“Tumor-promoting mechanisms of V-ATPase.”** ① extracellular acidification (V-ATPase exports protons at the plasma membrane) → acidic tumor microenvironment → invasion/immune escape; ② lysosomal acidification → autophagic energy supply; ③ export of drugs/metabolic waste → drug resistance—“the engine helps cancer cells export acid, supply energy, and resist drugs.”

**“V-ATPase inhibitors for cancer.”** Bafilomycin and related compounds → inhibit V-ATPase → normalize tumor-microenvironment pH + block autophagy → anticancer effects (preclinical)—“shut down cancer cells’ acid-export pump.” But selectivity is poor (normal cells are also affected)—“the engine’s brake is too powerful and harms bystanders.”

**“Balancing anti-aging and anticancer effects.”** Maintain V-ATPase (anti-aging) vs. inhibit V-ATPase (anticancer)—a contradiction! The proposed solution is **subtype/tissue selectivity** (target specific subtypes highly expressed in cancer cells rather than normal lysosomes)—“apply a precise brake to stop only the cancer-cell engine”—“structural knowledge (subunit differences) points toward selective design.”

**“Value of structural knowledge.”** Understanding V-ATPase subunit assembly (ATP6AP1 hub, 6WM3) → design “assembly inhibitors” that selectively disrupt the high-demand assembly process in cancer cells—“know how the engine is assembled before taking it apart precisely”—“V-ATPase is a shared anticancer and anti-aging target; selectivity is key. This is the answer structural research offers to its dual nature and the medical application of molecular-motor knowledge.”

---

## 9. Guide to obtaining structural data

- **PDB entries**:
  - 6WM3: complete human V-ATPase structure (2.9 Å cryo-EM, Wang 2020, *Mol Cell*)—three rotary states;
  - 6WLW: human V-ATPase V₀ region (state 1)—lipids/glycosylation;
  - 6WM2/6WM4: other states from the same study;
  - 5VKX and others: yeast V-ATPase-related (note: 5VKX itself is an artificial copper protein; verify before use);
  - 3J9V and others: yeast V-ATPase (classic cryo-EM);
  - AlphaFold: AF-P38606 (human ATP6V1A and other subunits).
- **Visualization tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (published literature)

1. Wang L, Wu D, Robinson CV, Wu H, Fu TM. Structures of a complete human V-ATPase reveal mechanisms of its assembly. *Mol Cell* 2020;80:501-511. (PDB 6WM3/6WLW)
2. Zhao J, Benlekbir S, Rubinstein JL. Electron cryomicroscopy observation of rotational states in a eukaryotic V-ATPase. *Nature* 2015;521:241-245. (V-ATPase rotational states)
3. Mazhab-Jafari MT, Rohou A, Schmidt C, et al. Atomic model for the membrane-embedded V(o) motor of a eukaryotic V-ATPase. *Nature* 2016;539:118-122. (V₀ atomic model)
4. Forgac M. Vacuolar ATPases: rotary proton pumps in physiology and pathophysiology. *Nat Rev Mol Cell Biol* 2007;8:917-929. (V-ATPase review)
5. Cotter K, Stransky L, McGuire C, Forgac M. Recent insights into the structure, regulation, and function of the V-ATPases. *Trends Biochem Sci* 2015;40:611-622. (V-ATPase regulation)
6. Zoncu R, Bar-Peled L, Efeyan A, Wang S, Sancak Y, Sabatini DM. mTORC1 senses lysosomal amino acids through an inside-out mechanism that requires the vacuolar H(+)-ATPase. *Science* 2011;334:678-683. (V-ATPase-mTOR)
7. Colacurcio DJ, Nixon RA. Disorders of lysosomal acidification-the emerging role of v-ATPase in aging and neurodegenerative disease. *Ageing Res Rev* 2016;32:75-88. (V-ATPase, aging, and neurodegeneration)

---

> **Structural overview**: V-ATPase is the lysosomal **“proton-pump engine”**—V₁ (cytosolic A₃B₃ catalytic hexamer, a three-cylinder engine) + V₀ (membrane-embedded c-ring, rotary pump) are connected by a central shaft (complete structure and three rotary states revealed by 6WM3)—**“ATP hydrolysis → shaft rotation → c-ring rotation → proton pumping → lysosomal acidification.”** Rotary catalysis is a shared design in the F-ATPase family. **Reversible V₁/V₀ dissociation (shutdown during starvation)** provides energy-saving regulation. **With aging, V-ATPase function ↓ → inadequate acidification → autophagy-lysosome degradation ↓ → waste accumulation**. **Anti-aging strategies**: NAD⁺/mitochondrial energy supply (fuel) + TFEB activation (replace the engine) + reduce the load—“fuel it, replace it, and reduce the load so the lysosomal engine stays healthy and the recycling center can keep burning waste.”
