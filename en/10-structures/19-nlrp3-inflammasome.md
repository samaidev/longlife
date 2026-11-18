# Molecular Structure Deep Dive 19: The NLRP3 Inflammasome — The "Alarm" of Inflammation and Signal Amplification via Helical Filaments

> **Series Positioning**: 10-structures (Molecular Structure Deep Dive) Part 19 — Dissecting the three-dimensional structure of the NLRP3 inflammasome, understanding "how cells sense 'danger signals' (damage/crystals/pathogens)," "how ASC polymerizes into helical filaments to amplify signals," and its role as an "alarm" in inflammaging. This is the structural foundation of the knowledge base's inflammaging main thread ([02-inflammaging](../03-immunity/02-inflammaging.md)), forming an "inflammation-autophagy" triangle together with NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md)) / LC3 autophagy ([18-lc3-autophagy.md](18-lc3-autophagy.md)).
> **Related Articles**: Inflammaging see [02-inflammaging](../03-immunity/02-inflammaging.md); NF-κB structure see [14-nfkb-structure.md](14-nfkb-structure.md); LC3/autophagy see [18-lc3-autophagy.md](18-lc3-autophagy.md); Nrf2 see [15-nrf2-structure.md](15-nrf2-structure.md); Mitochondria see [12-complex1-structure.md](12-complex1-structure.md).

---

## 0. Structure Overview

**In one sentence**: The NLRP3 inflammasome is the cell's "fire alarm" — sensing danger signals (ATP efflux, uric acid crystals, β-amyloid, pathogen products, ROS/mtDNA released by damaged mitochondria) → recruiting ASC → polymerizing into a giant "signal tower" (helical filaments) → activating caspase-1 → cleaving pro-IL-1β/pro-IL-18 → releasing mature inflammatory cytokines → triggering pyroptosis — "one alarm ignites a raging fire of inflammation."

```text
NLRP3 inflammasome assembly:
  NLRP3(sensor) --PYD--> ASC(adaptor) --CARD--> pro-caspase-1(effector)
      │                    │                    │
   Senses danger       PYD filament        CARD filament
  signals              polymerization      polymerization
  (NEK7 licensing/     (signal             (caspase-1
   K+ efflux)          amplification       activation)
                        tower)                        │
                                        Cleaves pro-IL-1β/IL-18 → mature cytokines
                                        Cleaves GSDMD → pyroptosis (membrane pore)
```

**Three key structural features** (the atomic basis determining its function):
1. **NLRP3's three-domain architecture**: PYD (recruitment) + NACHT (ATPase/oligomerization) + LRR (ligand sensing) — "sensor-processor-antenna";
2. **NEK7's "gatekeeper" role**: NEK7 binds at the LRR/NACHT junction of NLRP3, licensing activation — "gatekeeper grants passage";
3. **ASC's helical filaments**: PYD filaments (~13 subunits/turn) polymerize helically, amplifying the signal — "the spiral staircase of the signal tower."

**Core regulatory mechanism**:

```text
Resting: NLRP3 auto-inhibited (intramolecular interactions), held in inactive state
        │
Danger signals: K+ efflux/ROS/lysosomal rupture/NEK7 licensing → NLRP3 opens
        │
Assembly: NLRP3 oligomerizes → recruits ASC → PYD filaments → CARD filaments → pro-caspase-1 clusters
        │
Effector: caspase-1 auto-activates → cleaves IL-1β/IL-18/GSDMD → inflammation + pyroptosis
```

---

## 1. Why the NLRP3 Inflammasome Structure Matters

NLRP3 is a "star target" in inflammation research:

- **"Inflammation alarm"**: Senses multiple danger signals (a key sensor for sterile inflammation) — "alarms even without infection; alarms at any 'danger'";
- **Core of inflammaging**: In old age, NLRP3 is chronically activated (damage accumulation/mitochondrial ROS/crystals) → chronic IL-1β → inflammaging — "the alarm breaks down with age, ringing nonstop";
- **Disease connections**: Gout (uric acid crystals), atherosclerosis (cholesterol crystals), Alzheimer's (β-amyloid), type 2 diabetes (islet amyloid) — "the alarm misfires, and the whole body suffers";
- **Anti-aging evidence**: NLRP3 inhibition improves metabolic/neural/cardiovascular aging phenotypes in animals — "turn off the misfiring alarm, and inflammation subsides";
- **Dialogue with autophagy**: Autophagy clears danger signals (damaged mitochondria/crystals) → inhibits NLRP3 — "the garbage recycling station is the alarm's 'fire extinguisher'";
- **Drug target**: NLRP3 inhibitors (MCC950, etc.) in clinical studies — "the star target of a new generation of anti-inflammatory drugs."

**Three key questions in structural research**:
1. How does NLRP3 maintain "standby" mode (the molecular mechanism of auto-inhibition)?
2. How does NEK7 "license" activation (the atomic details of the gatekeeper)?
3. How do ASC filaments amplify signals (the mechanism of helical polymerization)?

These questions were answered in structures such as 6NPY (NLRP3-NEK7, 2019) and 3J63 (ASC PYD filament, 2014).

---

## 2. Structural Anatomy of the NLRP3 Inflammasome

### 2.1 NLRP3's Three-Domain Architecture — "Sensor-Processor-Antenna"

- **PYD (pyrin domain, N-terminal)**: The "adaptor" that recruits ASC — PYD-PYD homotypic interaction — "the alarm's trigger button";
- **NACHT domain (central)**: ATPase activity + oligomerization (NLRP3's NACHT domain oligomerizes into a "wheel" upon activation) — "the alarm's processor";
- **LRR domain (C-terminal)**: Leucine-rich repeats, sensing ligands/regulating auto-inhibition — "the alarm's antenna";
- **Auto-inhibition**: At rest, LRR folds back to suppress NACHT/PYD → intramolecular auto-inhibition — "the alarm's safety pin is inserted";
- **Activation**: Danger signals → auto-inhibition released → NACHT oligomerization → PYD exposed → recruits ASC — "pull the safety pin, press the trigger button."

### 2.2 NEK7's "Gatekeeper" Role

- **NEK7 (NIMA-related kinase 7)**: Binds at the LRR/NACHT junction of NLRP3 — "the gatekeeper stands at the door";
- **Finding from 6NPY**: NEK7 forms extensive contacts with NLRP3's LRR domain (~1800 Å² interface) — "the gatekeeper holds the door handle";
- **"Licensing" mechanism**: NEK7 binding → stabilizes NLRP3's open conformation → licenses oligomerization — "the gatekeeper grants passage, and only then can the alarm sound";
- **Kinase activity not required**: NEK7's kinase activity is not essential for NLRP3 activation (primarily a structural role) — "the gatekeeper is not the security chief, just opens the door."

### 2.3 ASC's Helical Filaments — "Signal Tower"

- **ASC (apoptosis-associated speck-like protein)**: Contains PYD + CARD domains — "adaptor protein, can connect at both ends";
- **Assembly**: NLRP3's PYD → recruits ASC's PYD → ASC's PYD polymerizes into filaments (helical, ~13 subunits/turn) → ASC's CARD polymerizes into filaments → recruits pro-caspase-1 — "plug-in cascade, one thread strings together the entire alarm system";
- **Finding from 3J63**: Helical structure of ASC PYD filaments (near-atomic resolution) — "seeing every step of the signal tower's staircase";
- **Signal amplification**: One NLRP3 oligomer → recruits large amounts of ASC → recruits large amounts of pro-caspase-1 → massive IL-1β — "one alarm, amplified into a raging fire";
- **"Nucleation-induced polymerization"**: Fiber growth relies on "nucleation-elongation" (nucleation-polymerization) — "the first step is the seed, then it builds itself upward."

---

## 3. The "Alarm Logic" of Inflammasomes: From Structure to Chemistry

### 3.00 The Engineering Wisdom of "Helical Fibers": Why Signal Towers Are Built as Helices

Each turn of the helical fiber consists of approximately 13 subunits, tightly stacked—packing the maximum amount of ASC per unit length—making the signal tower more compact. Each subunit in the helix contacts both the preceding and following subunits (i±1 interface), enabling multivalent binding and resulting in exceptionally high fiber stability (slow dissociation)—"hand-in-hand forming a ring is stronger than a single-file chain." The growth of helical fibers occurs via terminal elongation; after nucleation, each turn provides a new binding surface, accelerating growth exponentially—"once the first step is laid, the signal tower builds itself upward."

The rate-limiting step in fiber formation is "nucleation" (a few ASC molecules first come together to form a seed, which is slow); once nucleated, "elongation" is fast—"ignition is the hardest part, but once it catches, it burns fast." This explains why inflammasome activation has a "threshold" (sufficient signal is needed for nucleation)—"if the seeds don't come together, the alarm doesn't sound; once they do, it all sounds."

The all-or-none nature of nucleation-elongation makes inflammasome activation a "threshold event"—**"the inflammasome doesn't 'gradually sound'; it's 'all silent or all sounding'"**—this explains why gout/heart attack episodes are "acute events" (crystals suddenly reach the nucleation threshold)—"the alarm has only two modes: 'silent' and 'full blast.'"

### 3.0 Why Inflammasomes Require Multi-level Amplification

If NLRP3 directly activated caspase-1, one NLRP3 could only activate one caspase-1—the signal would be too weak, and "one NLRP3 misactivation = one inflammatory cytokine," with too much noise—"a guard spots a thief and shoots directly, likely to cause collateral damage."

The multi-level amplification design:
- Level 1: NLRP3 senses danger (specificity, but few in number)—"the scout";
- Level 2: ASC fiber polymerization (amplification, one NLRP3 recruits hundreds of ASC)—"the scout blows the whistle, a company arrives";
- Level 3: pro-caspase-1 aggregation and autoactivation (amplification, each ASC recruits multiple)—"a company opens fire, firepower coverage";
- Effect: Each NLRP3 event → thousands of IL-1β—"signal amplified 3-4 orders of magnitude."

Helical fibers are good amplifiers because: ① the helical structure provides **multivalent binding** (each ASC binds the two adjacent ASC molecules, high affinity)—"hand-in-hand is stronger than a single handshake"; ② fiber growth is **autocatalytic** (elongation is fast after nucleation)—"once started, unstoppable"; ③ fibers are **supramolecular structures** (giant molecular assemblies)—"a small alarm, a whole tower."

Multi-level amplification ensures that even "one danger signal" can elicit "a sufficiently large response" (sensitivity); but multiple checkpoints such as NEK7 licensing are needed to prevent false alarms (specificity)—"the scout must report + the gatekeeper must grant passage + the signal must be strong enough—three checks before opening fire."

### 3.1 The Diversity of Danger Signals: One Alarm, Multiple Triggers

NLRP3's "peculiarity" lies in its ability to sense **multiple unrelated** danger signals—uric acid crystals, ATP, ROS, lysosomal rupture, β-amyloid, cholesterol crystals...—"one alarm connected to many sensors." Mechanistic models:

- **"Potassium efflux" model**: Various stimuli → intracellular potassium efflux → decreased potassium concentration → NLRP3 activation—"the common signal is 'potassium has fled'";
- **"Lysosomal rupture" model**: Crystals/particles → phagocytosed by lysosomes → rupture → cathepsin release → NLRP3 activation—"the garbage bag bursts, dirty stuff leaks out";
- **"ROS/mtDNA" model**: Damaged mitochondria release ROS/mtDNA → activate NLRP3—"the generator leaks electricity, the alarm sounds";
- **"NEK7 licensing" model**: NEK7 is the common "gatekeeper" (6NPY)—"regardless of the alarm, the gatekeeper must grant passage."

NLRP3 likely does not directly bind all ligands but is activated through **common downstream pathways** (potassium efflux/ROS/lysosomal rupture)—"the alarm doesn't recognize 'specific threats,' it recognizes 'common danger signals' (universal indicators of cell damage)"—this explains why NLRP3 is the core of "sterile inflammation" (not dependent on pathogen recognition)—"as long as it's an 'injury' signal, it alarms."

### 3.20 Structural Explanation for Gout and Myocardial Infarction: How Crystals Detonate the Alarm

NLRP3's "crystal sensing" is one of its most famous functions—the structural logic of gout (uric acid crystals) and atherosclerosis (cholesterol crystals):

Monosodium urate crystals (gout)/cholesterol crystals (atherosclerosis) → phagocytosed by macrophages → lysosomes cannot degrade them (crystals too hard) → lysosomal rupture → cathepsin release + potassium efflux → NLRP3 activation → massive IL-1β release—"stones that can't be swallowed burst the garbage bag."

Acute gout attacks occur because crystals suddenly appear in large quantities (blood uric acid supersaturation precipitates) → many macrophages simultaneously "swallow stones, burst bags" → NLRP3 nucleation threshold instantaneously crossed → signal tower fully assembled → IL-1β storm → joint redness, swelling, heat, pain—"the alarm goes from silent to full blast with just one stone."

Atherosclerosis is "chronic inflammation": cholesterol crystals slowly accumulate → NLRP3 repeatedly activated at low levels → chronic IL-1β → plaque inflammation → plaque instability (rupture → heart attack)—"small stones repeatedly grinding, inflammation slowly burning."

Anti-aging insights: ① Lower uric acid (control purines/medication) → reduce gout alarms; ② Control blood lipids (source of cholesterol crystals) → reduce vascular alarms; ③ Enhance lysosomes/autophagy ([18-lc3-autophagy.md](18-lc3-autophagy.md)) → timely crystal clearance/enhanced "digestive capacity"—"keep stones out of the bag, and if the bag bursts, it can mend itself."

---

## 4. NLRP3 and Aging: A Structural Perspective on "Alarm Aging"

### 4.1 Chronic NLRP3 Activation in Aging

- **Accumulation of danger signals**: Age-related damage accumulation (protein aggregates, oxidative damage, damaged mitochondria, crystals) → repeated NLRP3 activation—"the alarm rings every day";
- **Decline in autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Decreased ability to clear danger signals → NLRP3 loses its "fire extinguisher"—"the recycling station stops working, the alarm rings louder";
- **"Priming-triggering" dual signal**: NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md)) upregulates pro-IL-1β (priming signal) + NLRP3 activation (triggering signal) → chronic IL-1β—"the alarm needs 'pre-loaded ammunition' (NF-κB) + 'trigger pull' (NLRP3)";
- **Consequences**: Chronic low-grade inflammation (inflammaging) → accelerated atherosclerosis/insulin resistance/neurodegeneration/sarcopenia—"the alarm rings continuously, the whole body is overloaded."

### 4.2 Anti-Aging Strategies: "Turning Off the Alarm"

- **NLRP3 inhibitors**: MCC950 (selectively inhibits NLRP3 assembly) in preclinical/early clinical—"directly turn off the alarm";
- **IL-1β blockade**: Canakinumab (anti-IL-1β antibody)—CANTOS trial showed cardiovascular benefit—"silence the alarm's sound";
- **Lifestyle**: Exercise (promotes autophagy, reduces danger signals), diet (reduces uric acid/cholesterol crystals), sleep—"reduce things that trigger the alarm";
- **Autophagy enhancement** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Clear danger signals → inhibit NLRP3—"fix the fire extinguisher, and the alarm naturally rings less";
- **"Moderation" principle**: NLRP3 has protective functions (anti-infection/repair)—complete inhibition carries immunological risk—"the alarm cannot be dismantled, only repaired."

### 4.3 The Balance of "Alarm vs. Fire Extinguisher"

The inflammasome and autophagy are a "yin-yang pair":
- Autophagy: Clears danger signals (extinguishes fire) → inhibits NLRP3—"fire extinguisher";
- NLRP3: Senses danger signals (alarms) → promotes inflammation/pyroptosis—"alarm";
- Balance: In health, the two are balanced (danger signals cleared by autophagy, alarm occasionally sounds); in aging, autophagy↓ → alarm↑ → vicious cycle—"the fire extinguisher runs out of water, the alarm keeps ringing."

### 4.30 The Structural Story of "Pyroptosis": The Alarm's Ultimate "Mutual Destruction"

The inflammasome's ultimate effect is **pyroptosis**—a form of "inflammatory cell death." Its structural logic is "the warrior cuts off his own arm":

**Step 1: Caspase-1 cleaves GSDMD.** Activated caspase-1 cleaves the linker of gasdermin D (GSDMD) → releases the N-terminal pore-forming domain—"pulling the pin on the 'bomb'."

**Step 2: GSDMD-NT punches holes.** GSDMD-NT oligomerizes → forms ~10-20 nm pores on the cell membrane (ring-shaped oligomers)—"blasting holes in the cell wall."

**Step 3: Content release.** Membrane pores → IL-1β/IL-18 release (inflammatory cytokines exit) + cell swelling/rupture (pyroptosis)—"the alarm rings to the end, scattering inflammatory cytokines, sacrificing itself."

Pyroptosis has a dual nature:
- Protective: During infection, pyroptosis "sacrifices the local area, alerts the whole body" (clears infection foci, recruits immunity)—"when the fortress is breached, blow up the armory so the enemy can't use it";
- Pathological: Chronic activation damages tissues (arterial plaques, neurons)—"the alarm misfires, and the building is blown up."

Anti-aging significance: Inhibiting NLRP3/caspase-1 → reducing pyroptosis → protecting tissues (especially vascular/neural)—"don't let the alarm blow up the building"—but anti-infective pyroptosis capacity must be retained—"the alarm must be able to sound, but not misfire or sound excessively."

---

## 5. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| NLRP3 three domains (PYD/NACHT/LRR) | ★★★★★ Definitive | Sequence + structure |
| NEK7 binds NLRP3 LRR/NACHT interface | ★★★★★ Definitive | 6NPY (2019 Nature) |
| NEK7 kinase activity not required | ★★★★★ Definitive | Mutations + structure |
| ASC PYD fibrillar helical polymerization | ★★★★★ Definitive | 3J63 (2014 Cell) |
| Nucleation-induced polymerization mechanism | ★★★★★ Definitive | 3J63 |
| Potassium efflux/ROS activate NLRP3 | ★★★★★ Definitive | Multiple studies |
| NLRP3 inhibition improves aging phenotypes | ★★★★ Strong | Animal studies |
| Canakinumab cardiovascular benefit | ★★★★★ Definitive | CANTOS trial |

---

## 6. Connections to Knowledge Base Main Threads

### 6.0 The "Inflammation Triangle": Structural Dialogue between NF-κB–NLRP3–Autophagy

The inflammation-immunity family in the 10-structures series now has three members:

| Molecule | Role | Structure Article | Aging Trend |
|---|---|---|---|
| NF-κB | Inflammation "master switch" (transcription) | [14-nfkb-structure.md](14-nfkb-structure.md) | Activity ↑ |
| NLRP3 | Inflammation "alarm" (assembly) | [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md) | Activity ↑ |
| LC3/Autophagy | Inflammation "fire extinguisher" (clearance) | [18-lc3-autophagy.md](18-lc3-autophagy.md) | Activity ↓ |

**Operation of the "Inflammation Triangle"**:
- **Priming**: NF-κB upregulates pro-IL-1β/NLRP3 (pre-loading ammunition)—"the master switch orders loading";
- **Triggering**: NLRP3 senses danger signals → assembles → cleaves IL-1β—"the alarm pulls the trigger";
- **Extinguishing**: Autophagy clears danger signals → inhibits NLRP3—"the fire extinguisher cools things down";
- **Vicious cycle**: Aging NF-κB↑ (more ammunition) + NLRP3↑ (sensitive trigger) + Autophagy↓ (empty extinguisher) → chronic inflammation—"three interlocking rings of inflammaging."

**Strategies to "break the triangle"**: ① Anti-NF-κB (fix the master switch); ② Inhibit NLRP3 (tune the alarm); ③ Activate autophagy (fix the fire extinguisher)—"a three-pronged approach is needed to break the inflammation-aging cycle."

### 6.00 The "Priming–Triggering" Two-Signal Model: Why Inflammation Requires "Two Keys"

The cooperation between NF-κB and NLRP3 reveals an important immunological design—**the "priming–triggering" two-signal model**:

**Signal 1: Priming (NF-κB).** NF-κB transcriptionally upregulates pro-IL-1β, pro-IL-18, and NLRP3 itself—"pre-loading ammunition." The inflammasome "cannot fire without ammunition"—NF-κB is the "arsenal."

**Signal 2: Triggering (NLRP3 assembly).** Danger signals → NLRP3 oligomerization → cleavage of pro-IL-1β → mature IL-1β release—"pulling the trigger." Ammunition only (signal 1) without a trigger (signal 2) → no firing; trigger only without ammunition → firing blanks—"both keys must be present for the lock to open."

**Structural significance of "two signals"**: ① **Prevents false alarms**: a single signal is insufficient (avoids low-level NF-κB triggering inflammation)—"one safety is not enough, install two"; ② **Regulatable**: the two signals can be independently regulated (NF-κB and NLRP3 are influenced by different factors)—"arsenal and trigger managed separately"; ③ **Pathological window**: chronic inflammation = signal 1 chronically on (NF-κB↑) + signal 2 frequently triggered (abundant danger signals)—"the arsenal works around the clock, the trigger is pulled every day."

**Anti-aging implications**: Interventions can target either signal—"shut down the arsenal" (anti-NF-κB, e.g., anti-inflammatory lifestyle) or "lock the trigger" (inhibit NLRP3, e.g., MCC950)—but **"a two-pronged approach is more effective"** (simultaneously shutting down the arsenal + locking the trigger)—"both safeties engaged, and the alarm truly goes quiet."

### 6.1 Main Thread Article Dialogue

- **Inflammaging** ([02-inflammaging](../03-immunity/02-inflammaging.md)): This article is its structural foundation—"from concept to atom";
- **NF-κB Structure** ([14-nfkb-structure.md](14-nfkb-structure.md)): Priming signal (pro-IL-1β)—"coordination between the master switch and the alarm";
- **LC3/Autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Fire extinguisher vs. alarm—"the yin-yang of autophagy-inflammation";
- **Nrf2 Structure** ([15-nrf2-structure.md](15-nrf2-structure.md)): Antioxidant defense inhibits NLRP3 (reduces ROS)—"the fire department helps cool the alarm";
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): Damaged mitochondria release ROS/mtDNA to activate NLRP3—"leaking generators trigger the alarm";
- **Macrophage Polarization** ([03-macrophage-polar](../03-immunity/03-macrophage-polar.md)): M1 macrophages highly express NLRP3—"the ammunition depot of pro-inflammatory macrophages."

---

## 7. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How does NLRP3 maintain standby? | LRR folds back for auto-inhibition—"safety pin inserted" |
| How do danger signals activate? | K+ efflux/ROS/lysosomal rupture + NEK7 licensing → auto-inhibition released → oligomerization |
| How is the signal amplified? | ASC PYD/CARD helical filament cascade polymerization—"signal tower amplifies a thousandfold" |
| Why is NLRP3 chronically activated in aging? | Danger signals↑ + autophagy↓ + NF-κB ammunition↑—"alarm misfires with no one to fix it" |
| How to resist aging? | NLRP3 inhibition + autophagy enhancement + reduce danger signals—"fix the alarm, fix the fire extinguisher, prevent fires" |

**Structural intuition beyond the five questions**: The NLRP3 inflammasome story reveals the "philosophy" of the immune system—**"immunity is not 'detect everything,' but 'detect damage'"**. NLRP3 does not directly recognize pathogens but recognizes "universal signals of cell injury" (potassium efflux/ROS/content leakage)—"the immune system's primitive alarm is 'injured,' not 'who did it'." The evolutionary wisdom of this design: pathogens are infinitely diverse (impossible to pre-recognize all), but "damage" is universal—"don't recognize the enemy's face, recognize the wound." This explains why sterile inflammation (gout/atherosclerosis/Alzheimer's) shares the same alarm as infectious inflammation—"regardless of who struck, a wound is a wound." **Anti-aging insight**: Reduce "damage" (metabolic disorders/oxidative stress/crystals) → the alarm naturally rings less—"the fundamental treatment is to suffer fewer injuries, not to keep silencing the alarm."

---

## 8. Open Questions

1. **Full-length NLRP3 auto-inhibited conformation**: Complete structure of resting-state NLRP3 (how LRR suppresses NACHT);
2. **NLRP3 oligomer structure**: Atomic structure of the NACHT wheel (oligomer) after activation;
3. **Filament dynamics**: Dynamic process of ASC filament assembly/disassembly;
4. **Precise mechanism of "common danger signals"**: How potassium efflux "opens" NLRP3 (conformational change details);
5. **Structural basis of NLRP3 inhibitors**: How MCC950 etc. bind NLRP3 (binding site/allosteric);
6. **Inflammasome and pyroptosis**: Membrane structural details of GSDMD pore formation.

### 8.1 Drug Development for the "Alarm": From MCC950 to Next Generation

**MCC950 (classic inhibitor)**: Selectively inhibits NLRP3 activation (not AIM2/NLRC4)—mechanism: binds NLRP3's NACHT domain → prevents ATP hydrolysis/oligomerization—"jamming the processor's gears." However, MCC950's target binding mode remains controversial—"the lock cylinder hasn't been fully seen yet."

**"Inhibiting assembly" vs. "inhibiting effect"**: ① Inhibiting NLRP3 assembly (MCC950 class, intercepting before "nucleation")—"don't let the signal tower start construction"; ② Inhibiting downstream effects (IL-1β antibody canakinumab)—"silence the alarm's sound"—the former is more upstream and comprehensive (also inhibits pyroptosis), the latter is safer (preserves some immunity)—"intercepting the alarm vs. covering ears."

**New direction of "allosteric sites"**: NLRP3's auto-inhibited conformation (LRR pressing on NACHT) provides a drug opportunity to "lock auto-inhibition"—**"put the safety pin back in"** (stabilize auto-inhibition rather than block assembly)—"fix the lock rather than smash it."

**Challenge of "selectivity"**: NLRP3 has protective functions (anti-infection)—ideal drugs "inhibit chronic activation, preserve acute protection"—"the alarm must be able to sound, but not misfire"—this requires understanding the structural regulation of "activation threshold"—"adjust sensitivity, don't dismantle the alarm."

---

## 9. Structural Data Acquisition Guide

- **PDB Entries**:
  - 6NPY: NLRP3-NEK7 complex (3.80 Å cryo-EM, Sharif 2019 *Nature*)—NEK7 licensing mechanism;
  - 3J63: ASC PYD filament (~4 Å cryo-EM, Lu 2014 *Cell*)—helical polymerization;
  - 5H8M/5H8O etc.: NLRP3-related NACHT domain structures;
  - 6X86/6X87 etc.: NLRP3 with inhibitor complexes;
  - 2KN6 etc.: ASC PYD monomer;
  - AlphaFold: AF-Q96P20 (NLRP3 full-length prediction).
- **Viewing Tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (Real Literature)

1. Sharif H, Wang L, Wang WL, et al. Structural mechanism for NEK7-licensed activation of NLRP3 inflammasome. *Nature* 2019;570:338-343. (PDB 6NPY)
2. Lu A, Magupalli VG, Ruan J, et al. Unified polymerization mechanism for the assembly of ASC-dependent inflammasomes. *Cell* 2014;156:1193-1206. (PDB 3J63)
3. Martinon F, Burns K, Tschopp J. The inflammasome: a molecular platform triggering activation of inflammatory caspases and processing of proIL-beta. *Mol Cell* 2002;10:417-426. (Inflammasome discovery)
4. He Y, Zeng MY, Yang D, Motro B, Núñez G. NEK7 is an essential mediator of NLRP3 activation downstream of potassium efflux. *Nature* 2016;530:354-357. (NEK7 discovery)
5. Ridker PM, Everett BM, Thuren T, et al. Antiinflammatory therapy with canakinumab for atherosclerotic disease. *N Engl J Med* 2017;377:1119-1131. (CANTOS trial)
6. Coll RC, Robertson AA, Chae JJ, et al. A small-molecule inhibitor of the NLRP3 inflammasome for the treatment of inflammatory diseases. *Nat Med* 2015;21:248-255. (MCC950)
7. Latz E, Xiao TS, Stutz A. Activation and regulation of the inflammasomes. *Nat Rev Immunol* 2013;13:397-411. (Inflammasome review)

---

> **Structural Overview**: The NLRP3 inflammasome is the cell's **"fire alarm"**—NLRP3 (PYD/NACHT/LRR three domains) senses danger signals (K+ efflux/ROS/lysosomal rupture), NEK7 "gatekeeper" licenses activation → recruits ASC → **PYD/CARD helical filament cascade polymerization** (3J63: signal tower amplifies a thousandfold) → activates caspase-1 → cleaves IL-1β/IL-18/GSDMD → inflammation + pyroptosis. **In aging: danger signals↑ + autophagy↓ (empty fire extinguisher) + NF-κB↑ (abundant ammunition) → alarm chronically misfires (inflammaging)**—anti-aging strategy: NLRP3 inhibition (MCC950) + autophagy enhancement (fasting/exercise) + reduce danger signals—"fix the alarm, fix the fire extinguisher, prevent fires."
