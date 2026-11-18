# Molecular Structure Deep Dive 24: PINK1/Parkin — The "Sensor-Effector" of Mitophagy and Parkinson's Disease

> **Series Position**: 10-structures (Molecular Structure Deep Dive), Part 24 — Dissecting the three-dimensional structures of PINK1 (PTEN-induced kinase 1) and Parkin (E3 ubiquitin ligase), understanding "how cells tag damaged mitochondria," "how the phosphorylation-ubiquitination cascade initiates mitophagy," and the role of this pathway in "mitochondrial quality control" in aging and Parkinson's disease. This is the structural foundation of the knowledge base's mitophagy main thread (mitophagy section in [18-lc3-autophagy.md](18-lc3-autophagy.md)), connecting to the "leaky generator" theme of Complex I ([12-complex1-structure.md](12-complex1-structure.md)).
> **Related Entries**: LC3/autophagy see [18-lc3-autophagy.md](18-lc3-autophagy.md) (includes the mitophagy PINK1/Parkin story); Complex I see [12-complex1-structure.md](12-complex1-structure.md); Mitochondria see [04-mitochondria](../02-vascular/04-mitochondria.md); Proteasome see [20-proteasome.md](20-proteasome.md).

---

## 0. Structural Overview

**In one sentence**: PINK1 and Parkin are the "golden duo" of mitophagy — PINK1 is the "sensor" (detecting membrane potential drop at the outer mitochondrial membrane), Parkin is the "effector" (E3 ligase attaching "ubiquitin tags" to damaged mitochondria) — the "alarm and labeling machine for bad mitochondria." Their collaboration flags "damaged mitochondria" for autophagic ([18-lc3-autophagy.md](18-lc3-autophagy.md)) recycling — "the leaky generator gets tagged for scrap and hauled to the recycling station."

```text
PINK1/Parkin Pathway:
  PINK1 (Ser/Thr kinase):  N-terminal mitochondrial targeting sequence + transmembrane domain + kinase domain (contains ubiquitin-binding site)
  Parkin (E3 ligase):  UBL — RING0 — RING1 — IBR — RING2 (RBR-type E3)
                  │
  Steps:  ①Membrane potential↓ → PINK1 stabilizes on outer mitochondrial membrane
         ②PINK1 phosphorylates ubiquitin (Ser65) + phosphorylates Parkin (UBL Ser65)
         ③Phospho-ubiquitin binds Parkin → conformational opening → RBR activation
         ④Parkin ubiquitinates outer mitochondrial membrane proteins → tags damaged mitochondria
         ⑤Receptors (p62/NDP52/OPTN) → LC3 → autophagic recycling
```

**Three major structural features** (the atomic basis determining their function):
1. **PINK1 kinase domain + ubiquitin-binding site**: Uniquely "directly phosphorylates ubiquitin" (substrate-docking-independent) — "the kinase directly stamps the tag";
2. **Parkin autoinhibited conformation**: At rest, UBL presses down on RING1, activity is "locked" — "the labeling machine's safety catch";
3. **Phospho-ubiquitin (pUb) "unlocking"**: pUb binds Parkin's cryptic site → conformational opening → activation — "the phospho-tag is the key that opens the safety catch."

**Core regulatory mechanism**:

```text
Resting: Normal membrane potential → PINK1 imported into mitochondria → cleaved and degraded by PARL (low level)
      Parkin autoinhibited (UBL presses on RING1) → inactive
        │
Damage: Membrane potential↓ → PINK1 cannot be imported → stabilizes and accumulates on outer membrane
      → Phosphorylates ubiquitin (pUb) + phosphorylates Parkin
      → pUb binds Parkin cryptic site → conformational opening → E3 activation
      → Ubiquitinates outer mitochondrial membrane proteins (Miro/MFN/VDAC, etc.)
      → p62/NDP52/OPTN recognize → LC3 bridging → mitophagy
```

---

## 1. Why PINK1/Parkin Structure Matters

PINK1/Parkin is the core of mitochondrial quality control:

- **"Mitochondrial Quality Inspector"**: The PINK1/Parkin pathway clears damaged mitochondria (low membrane potential/ROS leakage) — "quality inspectors scrap defective generators";
- **Key to Parkinson's Disease (PD)**: PINK1/Parkin mutations are the most common cause of familial PD (autosomal recessive) — "quality inspector fails in their duty, dopaminergic neurons die first";
- **Anti-aging Evidence**: Mitophagy defects → accumulation of damaged mitochondria → ROS/inflammation → accelerated aging; enhancing mitophagy (exercise/fasting/Urolithin A) improves metabolic/neurological aging — "regularly scrapping bad generators ensures cells have clean electricity";
- **Dialogue with LC3** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): PINK1/Parkin is the textbook example of "selective autophagy (mitophagy)" — a perfect case of the "tagging system";
- **Dialogue with Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): Complex I damage → membrane potential↓/ROS↑ → triggers PINK1/Parkin — "leaky generators trigger quality inspection";
- **Drug Targets**: Drugs activating Parkin/mitophagy (Urolithin A, etc.) in clinical trials — "new generation of mitochondrial anti-aging drugs".

**Three Key Questions in Structural Research**:
1. How does PINK1 "sense" membrane potential (structural basis of the stabilization mechanism)?
2. How does PINK1 phosphorylate ubiquitin (atomic details of the kinase-substrate interaction)?
3. How does pUb "unlock" Parkin (mechanism of conformational opening)?

These questions have been answered in structures such as 6EQI (PINK1 + ubiquitin, 2017) and 5N2W (Parkin + pUb, 2017).

---

## 2. Structural Anatomy of PINK1/Parkin

### 2.1 PINK1—The "Sensor Kinase"

- Location: N-terminal mitochondrial targeting sequence (MTS) + transmembrane domain (TM) + kinase domain (C-terminal);
- Kinase domain: Ser/Thr kinase fold (N-lobe + C-lobe + activation loop)—the "stamping machine";
- Ubiquitin binding site: A unique surface of the kinase domain binds ubiquitin (independent of classical substrate docking)—"stamping the tag directly";
- Discovery of 6EQI: The PINK1-ubiquitin complex reveals that the ubiquitin C-terminus inserts into the kinase active site (Ser65 aligned for phosphoryl transfer)—"the tag's Ser65 is perfectly stuck in the stamping position";
- Substrate specificity: Phosphorylates ubiquitin at Ser65 (phospho-ubiquitin, pUb)—"only stamping a 'phospho-stamp' on the ubiquitin tag".

### 2.2 Parkin—The "Effector E3"

- Location: UBL (ubiquitin-like domain) — RING0 — RING1 — IBR — RING2 (RBR-type E3 ligase)—"a labeling machine made of five parts";
- Autoinhibition: In the resting state, the UBL folds over and presses against RING1 (inhibiting E2 binding)—"the safety catch is on";
- RBR catalysis: RING1 recruits E2 → ubiquitin transfers to a cysteine in RING2 (intermediate) → then transfers to the substrate—"two passes, precise labeling";
- Discovery of 5N2W: pUb binds to a cryptic site on Parkin (RING0/RING1 interface) → UBL release → conformational opening → E2 can bind—"the phospho-tag is inserted into the hidden keyhole, and the safety catch pops off";
- Substrates: Mitochondrial outer membrane proteins (Miro/MFN1/2/VDAC1, etc.)—"labeling the parts of the broken generator".

### 2.3 Phosphorylation-Ubiquitination Cascade—The "Signal Relay"

- **Step 1**: PINK1 phosphorylates "free ubiquitin" (Ser65) → produces pUb—"first, make the key";
- **Step 2**: PINK1 phosphorylates Parkin's UBL-Ser65 → promotes Parkin opening—"double-safety unlock";
- **Step 3**: pUb binds to Parkin's cryptic site → conformational opening → E3 activation—"key turns the lock";
- **Step 4**: Activated Parkin ubiquitinates mitochondrial proteins (regular ubiquitin chains, K48/K63) → recruits receptors—"labeling";
- **Step 5**: p62/NDP52/OPTN (LIR receptors) → LC3 → autophagosome engulfment—"towed away to the recycling station".

---

## 3. Molecular Logic of Mitochondrial Quality Control: From Structure to Chemistry

### 3.00 The Engineering Wisdom of "Phospho-Ubiquitin": Why Does PINK1 "Stamp the Tag"

The previous section discussed the two keys; this section delves into **the most unique molecular event: a kinase phosphorylating "ubiquitin" rather than a "substrate protein"**—this is extremely rare among kinases, but why?

**"Ubiquitin is a universal tag; stamping a phospho-stamp = upgrading the tag"**. Ordinary ubiquitination = "degradation/processing" tag; pUb (Ser65 phosphorylation) = "upgraded tag" (recruiting "readers" like Parkin)—"ordinary sticker vs. QR-code sticker"—the phospho-stamp allows the ubiquitin chain to "be recognized by special readers (Parkin)"—"upgrading the tag to unlock new readers".

**"Why Ser65?"** Ubiquitin's Ser65 is located near its C-terminal tail (flexible region)—PINK1's kinase active site perfectly accommodates the ubiquitin C-terminus (6EQI reveals: the ubiquitin C-terminus inserts into the active site, with Ser65 aligned to the γ-phosphate)—"Ser65's position is exactly within the kinase's reach"—"evolution chose a serine that is 'easy to reach'".

**"Benefits of phosphorylated ubiquitin as a 'messenger'"**: ① Ubiquitin is abundant in cells (can be phosphorylated in large quantities, strong signal); ② pUb is a "soluble messenger" (diffuses from the membrane to the cytoplasm); ③ pUb has "specific readers" (Parkin, etc.)—"messengers must be numerous, diffusible, and have designated recipients".

**"The unique chemistry of 'kinase-ubiquitin'"**: Most kinases phosphorylate "specific motifs of protein substrates"; PINK1 phosphorylates "a single residue of the small protein ubiquitin"—"extremely high specificity"—this is a new family of "ubiquitin kinases"—"PINK1 is the first discovered 'ubiquitin kinase'".

**"Anti-aging insights"**: pUb is the "molecular fingerprint of mitochondrial damage"—detecting pUb can assess mitochondrial quality; enhancing pUb signaling (activating PINK1) can enhance quality control—"the molecular fingerprint is both a diagnostic tool and an intervention target—killing two birds with one stone".

### 3.0 An atom-by-atom look: Why "phosphorylated ubiquitin" is a double key

One might ask: Why does PINK1 need to phosphorylate ubiquitin first, and then let pUb activate Parkin? Can't PINK1 directly phosphorylate and activate Parkin? The answer lies in the "fidelity of signal amplification":

**"pUb as an 'amplifier'"**. One PINK1 can phosphorylate many free ubiquitin molecules → producing a large amount of pUb → multiple pUbs bind to Parkin (multivalent) → stronger activation—"one alarm creates a bunch of keys"—much more amplified than "one-to-one phosphorylation of Parkin"—"quantity is signal strength".

**"pUb as a 'transmembrane messenger'"**. PINK1 generates pUb on the outer mitochondrial membrane → pUb diffuses/recruits Parkin (in the cytoplasm) → transmits the "mitochondria are broken" signal from the membrane to the cytoplasm—"pUb is a 'bad news flyer', distributed to cytoplasmic Parkin"—"alarm on the membrane, response in the cytoplasm".

**"Fidelity of double phosphorylation"**. PINK1 simultaneously phosphorylates ubiquitin (making the key) + Parkin UBL (helping to unlock) → requires "both phosphorylation stamps to be applied" for full activation → reduces false activation (noise)—"both keys must be present for the lock to open"—"dual signal = prevents false alarms".

**"Parkin's self-inhibition = default off"**. At rest, Parkin is self-inhibited (UBL suppresses RING1) → won't randomly tag things (avoiding healthy mitochondria being mistakenly scrapped)—"the tagging machine is locked by default, only opening upon receiving the 'phospho-key'"—"default off + precise opening = selectivity".

### 3.1 "The mitophagy relay race": From sensor to recycling station

The complete PINK1/Parkin → mitophagy relay (echoing the story of [18-lc3-autophagy.md](18-lc3-autophagy.md)):

**"Relay 1: Sensing"**. Membrane potential ↓ (Complex I damage/ROS) → PINK1 stabilizes on the outer membrane—"generator leaks electricity, alarm is installed" (echoing [12-complex1-structure.md](12-complex1-structure.md));

**"Relay 2: Tagging"**. PINK1 → pUb + Parkin activation → ubiquitination of mitochondrial proteins—"tagging machine works, bad generator is tagged 'to be processed'";

**"Relay 3: Bridging"**. Ubiquitination → receptors (p62/NDP52/OPTN, containing LIR) → bridge to LC3 (autophagosome membrane)—"courier sticks the tag onto the recycling truck";

**"Relay 4: Recycling"**. Autophagosome engulfs bad mitochondria → lysosomal degradation—"dragged to the recycling station for shredding";

**"Relay 5: Renewal"**. Mitochondrial biogenesis (PGC-1α, etc.) → new generators—"dismantle the old, install the new".

**"The Anti-Aging Significance of the Relay"**: Aging in any link of the entire relay (PINK1 expression↓/Parkin activity↓/receptor↓/autophagy↓) → damaged mitochondria accumulate → ROS/inflammation → accelerated aging — "if the baton is dropped, the broken generators pile up" — **"Mitochondrial quality control = the health of the entire relay"**.

---

## 4. PINK1/Parkin and Aging: "Quality Inspector Aging" from a Structural Perspective

### 4.1 Mitophagy Declines with Age

- **PINK1/Parkin expression/activity↓**: Mitophagy-related genes↓ in aged tissues — "not enough quality inspectors";
- **Widespread membrane potential decline**: Aged mitochondrial membrane potential↓ → chronic PINK1 stabilization → pathway "saturation/depletion" — "too many alarms, the labeling machine can't keep up";
- **Downstream autophagy↓** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Lysosomal aging → even if labeled, recycling fails — "labeled but the recycling station won't take it";
- **Consequences**: Damaged mitochondria accumulate → ROS leakage↑ ([12-complex1-structure.md](12-complex1-structure.md)) + inflammation (NLRP3, [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)) → accelerated aging — "broken generators pile up, leaking electricity and smoking".

### 4.2 Anti-Aging Strategies: "Fixing the Quality Inspector"

- **Exercise**: Exercise-induced mitophagy (AMPK/energy stress) — "training the quality inspector";
- **Fasting/Caloric restriction** ([03-nutrition](../07-interventions/03-nutrition.md)): AMPK activation → mitophagy — "a little hunger gets the quality inspector on duty";
- **Urolithin A**: Pomegranate metabolite, induces mitophagy (clinical studies) — "pharmacologically activating the quality inspector";
- **NAD⁺ precursors** ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md)): SIRT1/3 → mitochondrial function + autophagy — "fixing the NAD⁺ economy, the quality inspector has power";
- **The "moderation" principle**: Excessive mitophagy (prolonged fasting) → insufficient mitochondrial quantity (energy crisis) — "the quality inspector shouldn't be too diligent, scrapping good generators too" — "moderate scrapping, balanced renewal".

### 4.3 "The Structural Story of Parkinson's Disease": The Cost of Quality Inspector Failure

PINK1/Parkin mutations → molecular chain leading to PD:

**"Why do dopamine neurons die first?"** ①Dopamine neurons have extremely high energy demands (abundant mitochondria); ②PD-related protein (α-synuclein) aggregation → mitochondrial stress; ③PINK1/Parkin mutations → mitophagy defects → bad mitochondria accumulate → ATP↓/ROS↑ → neuronal death — "energy factory collapse + toxin accumulation, high-energy-consuming neurons crash first".

**"Familial vs. sporadic PD"**: PINK1/Parkin mutations (familial, ~10%); sporadic PD commonly involves mitochondrial dysfunction (no mutation, but pathway impaired) — "inherited quality inspector absence vs. acquired quality inspector aging, converging on the same endpoint".

**"From structure to therapy"**: ①Enhance Parkin activity (activators) → restore mitophagy — "fix the labeling machine"; ②Enhance downstream autophagy (rapamycin/fasting) → bypass Parkin defects — "bypass the broken labeling machine, directly strengthen the recycling station"; ③Target α-synuclein → reduce mitochondrial stress — "fewer accidents, the quality inspector isn't overwhelmed" — "multi-pronged approach, protecting dopamine neurons — this is the map structural biology gives to PD therapy".

### 4.30 "The Mitophagy Paradox": Balance Between Clearance and Retention

Mitophagy is not "the more the better" — cells must balance "clearing bad mitochondria" with "retaining sufficient mitochondria":

**"The cost of insufficient clearance"**. Bad mitochondria accumulate (membrane potential↓/ROS↑) → energy crisis + oxidative damage + inflammation (NLRP3) — "keeping leaky generators drags down the entire power plant".

**"The Cost of Excessive Clearance"**. Excessive mitophagy (prolonged starvation/pathological activation) → insufficient mitochondrial quantity → energy supply crisis (especially in high-energy-consuming tissues: heart/brain/muscle) — "scrapping perfectly good generators, causing a citywide blackout".

**"Balanced Regulation"**. The balance between mitophagy and mitochondrial biogenesis (PGC-1α) → renewal cycle — "scrap one, build one" — exercise simultaneously activates both (autophagy + biogenesis) → optimal renewal — "exercise is the best 'mitochondrial renewal' strategy".

**"Structural-Physiological Implications"**: The "threshold design" of the PINK1/Parkin pathway (triggered by membrane potential threshold) → natural balance (only those "bad enough" are cleared) — "quality control standards are built into the membrane potential threshold" — during aging, threshold/sensitivity changes → balance disruption — "quality control standards go awry, leading to either missed inspections or false kills".

**"Anti-aging Prescription"**: ① Exercise (dual activation of autophagy + biogenesis) → optimal renewal; ② Moderate fasting → gentle clearance; ③ Avoid prolonged starvation/extreme dieting → prevent excessive clearance — "the renewal cycle needs 'balance', not 'extremes'" — **"Mitochondrial anti-aging = keeping the 'clearance-renewal' cycle running healthily, not desperately clearing"**.

---

## 5. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| PINK1 kinase domain directly phosphorylates ubiquitin Ser65 | ★★★★★ Hard evidence | 6EQI (2017 Nature) |
| Parkin is an RBR-type E3 (UBL-RING0-RING1-IBR-RING2) | ★★★★★ Hard evidence | Multiple structures |
| Parkin auto-inhibition (UBL presses on RING1) | ★★★★★ Hard evidence | 5N2W, etc. |
| pUb binding to a cryptic site unlocks Parkin | ★★★★★ Hard evidence | 5N2W (2017 NSMB) |
| PINK1 membrane potential-dependent stabilization mechanism | ★★★★★ Hard evidence | Biochemistry + Cells |
| PINK1/Parkin mutations cause familial PD | ★★★★★ Hard evidence | Genetics |
| Mitophagy declines with age | ★★★★ Strong | Multiple studies |
| Exercise/fasting/Urolithin A induces mitophagy | ★★★★ Strong | Animal + early clinical |

---

## 6. Connection to Knowledge Base Mainline

### 6.0 Structural Overview of the "Mitochondrial Economy": Generator-Quality Control-Renewal

The 10-structures mitochondrial family now has three members:

| Stage | Molecule | Structure Chapter | Aging Trend |
|---|---|---|---|
| Power generation | Complex I | [12-complex1-structure.md](12-complex1-structure.md) | Efficiency↓/ROS↑ |
| Quality control | PINK1/Parkin | [24-pink1-parkin.md](24-pink1-parkin.md) | Activity↓ |
| Renewal | Mitophagy + Biogenesis | [18-lc3-autophagy.md](18-lc3-autophagy.md) | Renewal↓ |

**The Cycle of the "Mitochondrial Economy"**: Complex I generates power (producing ROS byproducts) → PINK1/Parkin quality control (scrapping leaky ones) → mitophagy recycling + biogenesis renewal (replacing with new ones) — the cycle of "power generation - quality control - renewal" — during aging: power generation efficiency↓ + quality control↓ + renewal↓ → accumulation of bad mitochondria → ROS/inflammation → accelerated aging — "aging generators with no one replacing them, power gets dirtier and dirtier".

### 6.00 "Mitochondria-Nucleus Signaling": The Quality Inspector's "Reporting Mechanism"

The PINK1/Parkin pathway is not only a "clearance machine" but also participates in "mitochondria-to-nucleus signaling" — "the quality inspector reports to the central office":

**"Mitochondrial Unfolded Protein Response (UPRmt)"**. Mitochondrial stress → transcription factors such as ATF5/CHOP enter the nucleus → upregulate mitochondrial chaperones/proteases (LonP1/ClpP) — "problems inside the mitochondria, requesting a 'rescue team' from the nucleus" — UPRmt activity decreases with age → mitochondrial proteostasis↓ — "reporting channel aging".

**"Signaling role of pUb"**. In addition to activating Parkin, pUb may also participate in signal transduction (recruiting specific readers) → affecting transcription — "phospho-tags are not just 'clearance orders', but also 'situation reports'".

**"Bidirectional dialogue between the nucleus and mitochondria"**. Nucleus-encoded mitochondrial proteins (~99%) → mitochondria; mitochondrial stress signals (UPRmt/ROS/pUb) → nucleus — "bidirectional communication between the headquarters (nucleus) and the power plant (mitochondria)" — dialogue imbalance during aging (nuclear commands↓ + mitochondrial alarms↑) — "headquarters and power plant lose contact, power plant operates while sick".

**"Anti-aging implications"**: ① Maintain mitochondria-nucleus dialogue (moderate stress induces UPRmt, hormesis) → mitochondrial proteostasis — "keep the reporting channel open"; ② NAD⁺ (SIRT1/3) promotes mitochondrial biogenesis (PGC-1α) → normal nuclear commands — "clear headquarters commands"; ③ Exercise activates PGC-1α → synchronized nucleus-mitochondria renewal — "headquarters and power plant renew synchronously" — **"Mitochondrial anti-aging is not just about 'clearance', but also 'dialogue' — quality inspectors (PINK1/Parkin) must be able to do the work, and also be able to report"**.

### 6.1 Main Thread Chapter Dialogue

- **LC3/Autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): The execution arm of mitophagy — "tagged and dragged to the recycling station";
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): Source of damage — "leaking generator triggers quality inspection";
- **Mitochondria** ([04-mitochondria](../02-vascular/04-mitochondria.md)): Main thread of mitochondrial biology — "comprehensive picture of the power plant";
- **NLRP3** ([19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)): Bad mitochondria release mtDNA/ROS → inflammation — "leaking generator ignites the alarm";
- **NAD⁺/SIRT1** ([06-sirt1-structure.md](06-sirt1-structure.md)): SIRT3 regulates mitochondrial proteins — "internal modification of mitochondria";
- **AMPK** ([03-ampk-structure.md](03-ampk-structure.md)): Energy stress → mitophagy — "energy switch turns on quality inspection";
- **FOXO3** ([16-foxo3-structure.md](16-foxo3-structure.md)): Transcriptional regulation of autophagy genes — "longevity switch manages quality inspector staffing".

---

## 7. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How does PINK1 sense damaged mitochondria? | Membrane potential↓ → PINK1 cannot be imported for degradation → stabilized on the outer membrane—"alarm installed" |
| How does PINK1 tag? | Phosphorylates ubiquitin Ser65 (pUb) + phosphorylates Parkin—"making the key + unlocking" |
| How does pUb activate Parkin? | Binds to cryptic site → UBL release → RBR opening → E3 activation—"key turns the deadbolt" |
| Why does mitophagy decline with age? | PINK1/Parkin↓ + downstream autophagy↓—"aging inspector + blocked recycling station" |
| How to counter aging? | Exercise/fasting/Urolithin A/NAD⁺ moderate activation—"repair the inspector + unblock the recycling station" |

**Structural intuition beyond the five questions**: The story of PINK1/Parkin reveals the "division of labor wisdom of a dual-protein system"—**"separating sensor and effector is a universal design for complex systems"**. The sensor (PINK1) is responsible for "sensing the environment" (membrane potential), and the effector (Parkin) is responsible for "executing the action" (tagging)—the benefits of separating the two: ① Each can evolve/be regulated independently (PINK1 expression and Parkin activity can be regulated separately)—"the sensor and effector can be upgraded separately"; ② Signal amplification (PINK1 sensing → pUb amplification → Parkin execution)—"small sensing end, large execution end"; ③ Fault isolation (PINK1 broken ≠ Parkin necessarily broken, and vice versa)—"if one fails, the other can still partially work". This "sensing-execution separation" design appears repeatedly in biological systems (GPCR's receptor-G protein, NLRP3's sensor-effector)—**"the reliability of complex systems comes from division of labor and redundancy"**. **Anti-aging implications**: To maintain mitochondrial quality control, one must "look at both ends" (PINK1 sensing + Parkin execution + downstream recycling)—"sensor, effector, and recycling station, none can be missing".

### 8.1 "The Future of Mitophagy": From Basic Structure to Clinic

Clinical translation prospects of the PINK1/Parkin pathway—"from structure to pharmacy":

**"Urolithin A (UA)"**: Pomegranate/nut metabolite → induces mitophagy (mechanism partly via PINK1/Parkin, partly non-canonical) → clinical studies show improved muscle function (in the elderly)—"the first 'mitophagy drug' to enter the clinic".

**"Parkin activators"**: Small molecules directly activate Parkin (stabilize open conformation) → preclinical—"directly repairing the tagging machine".

**"PINK1 stabilizers"**: Enhance PINK1 stability/activity → enhance sensing—"repairing the sensor".

**"Gene therapy"**: PINK1/Parkin gene delivery (AAV) → potential treatment for familial PD—"replacing with a new inspector".

**"Relationship with lifestyle"**: Endogenous mitophagy induced by exercise/fasting complements medication—"lifestyle is the foundation, drugs are the enhancement"—"first practice internal skills (lifestyle), then use external force (drugs)".

**"Cautious outlook"**: Mitophagy enhancement needs to be "moderate" (clearance-renewal balance); clinical trials require long-term verification of safety (risk of over-clearance)—"new drugs must pass the 'balance' test"—"the golden age of mitochondrial anti-aging has arrived, but we must proceed steadily".

---

## 8. Open Questions

1. **Membrane-anchored structure of PINK1**: The full conformation of PINK1 on the outer membrane (including TM);
2. **Catalytic cycle of Parkin**: Intermediate states of ubiquitin transfer (RING2-thioester);
3. **Spatial organization of pUb signaling**: pUb microdomains on the mitochondrial surface (signal amplification);
4. **Division of labor among mitophagy receptors**: Specific roles of p62 vs NDP52 vs OPTN in mitophagy;
5. **"Non-canonical" mitophagy**: PINK1/Parkin-independent pathways (directly mediated by receptors);
6. **Early intervention in PD**: Validation of mitophagy enhancers in PD preclinical/clinical settings.

### 8.2 The Grand Picture of "Mitochondria-Aging": Overview of "Energy-Quality Control" across 24 Articles

PINK1/Parkin is the 24th article in the 10-structures series—the finale of the "Mitochondria" series. At this point, the complete chain of "energy-quality control" emerges:

**Energy flow**: Complex I ([12](12-complex1-structure.md)) generates power → NAD⁺ economy ([06](06-sirt1-structure.md)/[08](08-cd38-structure.md)/[09](09-parp1-structure.md)/[10](10-nampt-structure.md)) supplies energy → AMPK ([03](03-ampk-structure.md)) senses energy;

**Quality control**: PINK1/Parkin ([24](24-pink1-parkin.md)) inspects quality → mitophagy ([18](18-lc3-autophagy.md)) recycles → biogenesis and renewal (PGC-1α);

**Global regulation**: mTOR ([04](04-mtor-structure.md))/FOXO3 ([16](16-foxo3-structure.md))/GLP-1R ([17](17-glp1r-structure.md))/IR ([21](21-insulin-receptor.md))—the "metabolic decision committee";

**Consequences of damage**: ROS → Nrf2 ([15](15-nrf2-structure.md)) antioxidant → NLRP3 ([19](19-nlrp3-inflammasome.md)) inflammation → p53 ([13](13-p53-structure.md)) fate decision.

**"Reading the 'energy mainline' of the 24 articles together"**: From "power generation" (Complex I) to "quality inspection" (PINK1/Parkin) to "recycling and renewal" (autophagy + biogenesis), and then to "global metabolic regulation" (mTOR/AMPK/IR/GLP-1R)—**"Mitochondrial health = the triangular balance of energy flow + quality control + global regulation"**—the "energy prescription" for anti-aging: exercise (renewal + quality inspection + AMPK) + moderate fasting (autophagy + NAD⁺) + metabolic health (insulin sensitivity)—"keep the power plant running healthily: stable power generation, diligent quality inspection, rapid renewal, and flexible regulation—this is the complete prescription for mitochondrial anti-aging".

---

## 9. Structural Data Acquisition Guide

- **PDB entries**:
  - 6EQI: PINK1 + ubiquitin (3.10 Å, Schubert 2017 *Nature*)—phosphorylation mechanism;
  - 5N2W: Parkin + pUb (2.68 Å, Kumar 2017 *NSMB*)—cryptic site unlocking;
  - 5N38: Parkin-related (Kumar 2017);
  - 5C1Z/5C23, etc.: Parkin auto-inhibited conformation;
  - 6O1E, etc.: PINK1 and substrate complex (extended);
  - 2JPT, etc.: Ubiquitin (classic);
  - AlphaFold: AF-Q9BXM7 (PINK1), AF-O60260 (Parkin).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (Real Literature)

1. Schubert AF, Gladkova C, Pardon E, et al. Structure of PINK1 in complex with its substrate ubiquitin. *Nature* 2017;552:51-56. (PDB 6EQI)
2. Kumar A, Chaugule VK, Condos TEC, et al. Parkin-phosphoubiquitin complex reveals cryptic ubiquitin-binding site required for RBR ligase activity. *Nat Struct Mol Biol* 2017;24:475-483. (PDB 5N2W)
3. Riley BE, Lougheed JC, Callaway K, et al. Structure and function of Parkin E3 ubiquitin ligase reveals aspects of RING and HECT ligases. *Nat Commun* 2013;4:1982. (Parkin structure)
4. Kane LA, Lazarou M, Fogel AI, et al. PINK1 phosphorylates ubiquitin to activate Parkin E3 ligase activity. *J Cell Biol* 2014;205:143-153. (Discovery of PINK1 phosphorylating ubiquitin)
5. Lazarou M, Sliter DA, Kane LA, et al. The ubiquitin kinase PINK1 recruits autophagy receptors to induce mitophagy. *Nature* 2015;524:309-314. (Mitophagy receptors)
6. Pickrell AM, Youle RJ. The roles of PINK1, parkin, and mitochondrial fidelity in Parkinson's disease. *Neuron* 2015;85:257-273. (PD and mitochondrial quality control)
7. Ryu D, Mouchiroud L, Andreux PA, et al. Urolithin A induces mitophagy and prolongs lifespan in C. elegans and increases muscle function in rodents. *Nat Med* 2016;22:879-888. (Urolithin A and mitophagy)

---

> **Structural Overview**: PINK1/Parkin acts as the **"sensor-effector" of mitophagy** — PINK1 (kinase) senses membrane potential ↓ and stabilizes on the outer membrane → **phosphorylates ubiquitin Ser65 (pUb)** (6EQI reveals the direct phosphorylation mechanism) → **pUb binds to Parkin's cryptic site → unlocks auto-inhibition → RBR-E3 activation** (5N2W reveals) → ubiquitinates mitochondrial proteins → receptor bridging → LC3 autophagic recycling. The **"dual-phosphorylation checkpoint" (pUb + Parkin-UBL) ensures selectivity (prevents false positives)**. **During aging, mitophagy ↓ → accumulation of damaged mitochondria → ROS/inflammation → accelerated aging**; **PINK1/Parkin mutations → familial PD** (quality control failure, dopaminergic neurons die first). **Anti-aging strategies**: exercise/fasting/Urolithin A/NAD⁺ moderately activate mitophagy — "repairing the quality inspector, clearing the recycling station, replacing with a new generator — the complete cycle of the mitochondrial economy".
