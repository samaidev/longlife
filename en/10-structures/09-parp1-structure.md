# Molecular Structure Deep Dive 09: PARP1 — The “Sentinel” of DNA Damage and the Reparative Consumption of NAD⁺

> **Series context**: Article 9 in 10-structures (Molecular Structure Deep Dive)—anatomy of the three-dimensional structure of PARP1 (poly[ADP-ribose] polymerase 1), and how it “senses” DNA breaks, uses NAD⁺ to synthesize poly(ADP-ribose) (PAR) chains, and, when overactivated, becomes the second major “funnel” consuming NAD⁺ during aging. This provides the “damage-side” structural foundation for the knowledge base’s NAD⁺/SIRT1 thread ([01-foundations/04-nad-sirtuin.md](../01-foundations/04-nad-sirtuin.md)) and pairs with CD38 ([08-cd38-structure.md](08-cd38-structure.md) ) to form the “two NAD⁺ funnels.”
> **Related articles**: CD38 structure: [08-cd38-structure.md](08-cd38-structure.md); SIRT1 structure: [06-sirt1-structure.md](06-sirt1-structure.md); NAD⁺ network: [04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md).

---

## 0. Structural overview

**In one sentence**: PARP1 is the cell nucleus’s “DNA damage sentinel”—it scans DNA with three zinc-finger domains and, upon detecting a single- or double-strand break, immediately uses NAD⁺ to synthesize PAR chains that summon repair proteins to the damage site. But every minute it is active consumes large amounts of NAD⁺; as DNA damage accumulates with age, its overactivation becomes an important driver of NAD⁺ decline.

```text
PARP1 domains: N-terminal Zn1 — Zn2 — Zn3 — WGR — HD (helical domain) — ART catalytic domain — C-terminal
                    │      │      │      │
             (senses DNA breaks) (auto-modification) (DNA binding) (links damage signal to catalysis)
```

**Three major structural features** (the atomic basis of its function):
1. **Three-zinc-finger module (Zn1/Zn2/Zn3)**: Zn1 and Zn3 cooperate to sense DNA breaks; Zn2 participates in auto-modification (PARylation of PARP1 itself)—a “cooperative, multi-finger damage sensor.”
2. **WGR-HD linker module**: transmits the “DNA damage signal” from the zinc fingers to the catalytic domain. HD (the helical domain) acts as an active “brake” that is released upon damage.
3. **ART catalytic domain**: uses NAD⁺ as a substrate to add ADP-ribose units one by one to acceptor proteins, forming PAR chains—an “NAD⁺ assembly line.”

**Core catalytic reaction**:

```text
NAD⁺ ──(ART catalytic domain)──► nicotinamide (released) + ADP-ribose (added to glutamate/aspartate on an acceptor protein)
        │
        └──► continuous extension: ADP-ribose-ADP-ribose-... (poly[ADP-ribose] chain, PAR)
             One NAD⁺ is consumed for each added unit
```

---

## 1. Why PARP1 structure matters

PARP1 is a double-edged sword for cell survival and death:

- **Repair function**: following a DNA single-strand break (SSB), PARP1 synthesizes PAR chains at the damage site and recruits repair factors such as XRCC1—“PAR is the damage signal light; once lit, the repair crew arrives.”
- **NAD⁺ consumption**: PARP1 consumes one NAD⁺ for every ADP-ribose unit it synthesizes (releasing nicotinamide)—**when PARP1 is activated, large quantities of NAD⁺ are “burned.”**
- **Its dual role in aging**:
  - DNA damage accumulates in aging cells → persistent PARP1 activation → excessive NAD⁺ consumption → reduced SIRT1 activity (“PARP1 and SIRT1 competing for NAD⁺” is one of the key mechanisms behind age-related NAD⁺ decline).
  - Overactivation of PARP1 also causes PAR accumulation and cellular energy depletion (NAD⁺ is a hub of energy metabolism), leading to cell death (“parthanatos,” a form of PAR-mediated cell death).
- **Comparison with CD38**: CD38 is a “continuous, slow-draining funnel” (highly expressed in immune and aging cells, with ongoing consumption); PARP1 is a “burst-flow funnel” (consuming NAD⁺ intensely during DNA damage)—**one slow and one fast: two funnels.**

**Three key questions in structural research**:
1. How does PARP1 “sense” DNA breaks rather than intact DNA? (damage recognition)
2. How does DNA binding activate the catalytic domain? (conformational activation)
3. Why does PARP1 consume NAD⁺ so intensely? (the substrate logic of catalysis)

These questions were answered by structures such as 4DQY (PARP1-DNA break complex, 2012 *Science*).

---

## 2. PARP1’s multidomain architecture: a “modular sentinel”

PARP1 is 1,014 residues long and is the best-studied member of the PARP family (17 members). Its modular design separates “sensing” from “catalysis” and couples them through conformational changes:

### 2.1 Three-zinc-finger module (damage sensor)

- **Zn1** (~residues 100–200): binds at DNA double-strand breaks and recognizes the “geometry of the break” (not the sequence).
- **Zn2** (~200–300): participates in auto-modification (PARP1 adds PAR chains to itself)—a site for “self-labeling.”
- **Zn3** (~330–420): cooperates with Zn1 to bind DNA breaks and stabilizes the Zn1-DNA interface.
- **Key property**: the zinc fingers recognize the **physical shape of a DNA break** (exposed ends, unpaired bases, helical distortion), not a particular sequence—“PARP1 does not care what kind of break it is; any break triggers the alarm.”
- Zn²⁺ coordination in the zinc fingers (e.g., 3 Cys + 1 His) is redox-sensitive: oxidative stress can disrupt Zn²⁺ coordination and cause PARP1 to be inappropriately activated or inactivated—“oxidative damage can injure the sentinel itself.”

### 2.2 WGR-HD linker module (signal transmission)

- **WGR domain** (~420–530 residues): contains the conserved Trp-Gly-Arg motif and binds DNA and participates in protein-protein interactions—“passes the zinc fingers’ damage signal onward.”
- **HD domain (helical domain)** (~530–660 residues): an “inhibitory brake” on the catalytic domain. At rest, HD holds down the ART catalytic domain and prevents it from binding NAD⁺.
- **Damage activation**: DNA-break binding → collective action by Zn1/Zn3/WGR → conformational rearrangement → HD disengages from the catalytic domain → the catalytic domain becomes “looser” (with increased protein dynamics) → NAD⁺ can enter → catalysis begins.

### 2.3 ART catalytic domain (NAD⁺ assembly line)

- **ART fold**: ADP-ribosyltransferase fold (Rossmann-like), containing an NAD⁺-binding pocket.
- **Key residues**: His862, Tyr907 (human PARP1), among others, participate in NAD⁺ cleavage and ADP-ribose transfer.
- **Catalytic process**: the nicotinamide-N-ribose bond in NAD⁺ is cleaved → nicotinamide is released → ADP-ribose is transferred to the carboxyl group of an acceptor glutamate/aspartate → the chain is extended (the ADP-ribose from the next NAD⁺ is attached to the preceding unit’s 2′-OH).
- **Substrate diversity**: PARP1 acceptors include histones (H1/H2B, etc.), DNA repair proteins (XRCC1, DNA ligase III), and PARP1 itself (auto-modification)—“PAR chains are scaffolding that gathers repair proteins at the damage site.”

---

## 3. Activation: from structure to chemistry

### 3.00 Why doesn’t the “sentinel” give false alarms? The geometric code for DNA-break recognition

A capable sentinel must “sound the alarm only when warranted.” PARP1 passes intact DNA countless times every day; why is it activated only by breaks? The answer lies in “shape complementarity.”

**The “smooth surface” of intact DNA cannot fool PARP1.** The phosphate backbone lies on the outside of the double helix, base pairs are tucked inside, and the major and minor grooves follow regular patterns. The recognition surfaces of Zn1/Zn3 are “tailor-made for the shape of a break”: they need to “see” exposed bases, free ends, and a distorted helix. The surface of intact DNA offers none of these features—like a blank key that cannot fit a lock designed for a broken key.

**The “abnormal geometry” of broken DNA triggers the alarm.** In a single-strand break, the backbone discontinuity locally loosens the double helix and bases can “flip out” of their pairs; Zn1 recognizes this “loosened bubble.” At a double-strand break, the end resembles a “split log”; Zn3 grips the end and recognizes the 5′-phosphate group. **“It recognizes shape, not sequence”**—that is why PARP1 is sensitive to breaks of many types (without preference for position or sequence), the design principle behind a “broad-spectrum sentinel.”

**The cost of a “false alarm.”** If PARP1 were inappropriately activated by non-break abnormalities (such as DNA bending or protein-binding sites), it would waste NAD⁺ and recruit repair proteins incorrectly. The structural solution is **multidomain cooperation**: Zn1, Zn3, and WGR must all **simultaneously** recognize the same break to trigger conformational collapse—“three people must confirm before the alarm sounds.” This “multi-sensor AND gate” reduces false alarms, at the cost of requiring a stronger signal to respond.

**This explains why PARP1 inhibitors work.** Drugs such as olaparib do not prevent “recognition” (by the Zn domains); they occupy the NAD⁺ pocket in the catalytic domain—“the alarm can sound, but there is no ammunition.” It also helps explain why the side effects of PARP1 inhibitors are relatively manageable: they do not affect damage recognition (the alarm still sounds); they halt the “repair assembly line” (NAD⁺→PAR), while cells can fall back on other repair pathways (such as HRR).

### 3.0 Atom by atom: how PARP1 “sniffs out” DNA breaks

Imagine a patrol officer in the nucleus “feeling” DNA—PARP1 is like that patrol officer, with its three zinc fingers (Zn1, Zn3, and WGR) acting as three hands that continually and gently touch the DNA double helix. Under normal conditions the helix surface is smooth and the bases are deeply buried. The fingers “feel” orderly major and minor grooves; no alarm is raised.

**When DNA breaks, its shape changes.** In an SSB, a phosphodiester backbone bond is broken at one point, locally relaxing the helix and exposing bases. In a DSB, both strands are broken and the ends resemble a “split log.” These **geometric abnormalities** (exposed bases, a distorted helix, free 5′-phosphate ends) are the recognition signals for Zn1 and Zn3—they act like “shape-complementary pincers,” clamping onto the break and locking in the abnormal DNA geometry.

**The “clamp” sets off a domino effect.** Once Zn1/Zn3 grip the DNA break, the WGR domain also joins in, and the three domains “huddle” at the break. This “huddle” is transmitted through internal protein linkers to the HD domain. HD originally acts like a “brake pad” pressed against the ART catalytic domain; now it is pushed away. The catalytic domain becomes more dynamic (crystallographic B factors rise and interdomain motions increase), the NAD⁺-binding pocket is “unlocked,” NAD⁺ flows in, and catalysis begins.

**The value of the 4DQY structure** is that it captured this “damage-bound state”—the compact conformation of Zn1/Zn3/WGR-CAT. It demonstrated that **PARP1 activation is not a “flipped switch” but “conformational destabilization”**: a DNA break makes the catalytic domain “softer,” allowing NAD⁺ to enter. This “dynamic activation” model, rather than the classic “allosteric switch” model, was an important structural-biology discovery in 2012.

### 3.1 The “domino” pathway of conformational activation

```text
DNA break ──► Zn1/Zn3 clamp onto break geometry ──► WGR cooperatively binds
    │
    ▼
Conformational collapse (formation of interdomain contact network) ──► HD disengages from catalytic domain ──► catalytic-domain dynamics increase
    │
    ▼
NAD⁺ enters active pocket ──► catalysis begins (nicotinamide release + PAR-chain extension)
```

- **“Destabilization is activation”**: rather than stabilizing an active conformation, the inhibitory conformation is “broken apart”—in contrast with CD38’s “stable catalysis” (CD38 is a constitutively active enzyme, while PARP1 has its brake on at rest and releases it upon damage).
- **Negative feedback from auto-modification**: after catalysis starts, PARP1 adds PAR chains to itself (auto-modification). The strongly negatively charged PAR chains repel PARP1 from DNA electrostatically, stopping catalysis—“once repair is done, it withdraws; once it withdraws, it stops.”
- **“Burst” NAD⁺ consumption**: upon DNA damage, PARP1 rapidly synthesizes PAR at the damage site (consuming hundreds of NAD⁺ molecules per minute)—an amplification effect of “one lesion, tens of thousands of NAD⁺ consumed.”

### 3.2 The signaling function of PAR chains

- **PAR is a “damage signal light”**: PAR chains are covalently attached to acceptor proteins, forming strongly negatively charged “polymeric tags.” Repair proteins (XRCC1, LIG3, PNK) recognize these tags through PAR-binding domains and “assemble” at the damage site.
- **PAR lifetime**: PARG (poly[ADP-ribose] glycohydrolase) rapidly degrades PAR chains (half-life on the order of minutes)—the “signal light” switches on and off quickly, preserving signal reversibility.
- **PAR and cell death**: PARP1 overactivation (severe DNA damage) → extensive PAR accumulation → release of AIF from mitochondria → cell death (parthanatos)—“excessive repair turns into a death signal.”
- **The “NAD⁺ cost” of PAR**: every ADP-ribose unit costs one NAD⁺. During intense PARP1 activation, NAD⁺ can be exhausted within minutes—“the repair bill is paid in NAD⁺.”

---

## 4. PARP1 inhibitors: from structure to drugs

### 4.1 Inhibitor binding modes

- **NAD⁺-competitive inhibitors**: olaparib, niraparib, rucaparib, and others occupy the NAD⁺-binding pocket (the nicotinamide subpocket), competitively blocking substrate binding.
- **Structural basis**: inhibitors mimic the nicotinamide portion of NAD⁺ (including an amide group), “passing for the real thing” in the nicotinamide subpocket, while an extension occupies part of the ribose/phosphate region—“occupying the seat without doing the work.”
- **Selectivity**: PARP1/2 inhibitors are highly selective for PARP1/2 (differences in active sites), with lower selectivity for PARP3 and other family members—“target the main funnel without touching the side funnels.”

### 4.2 The “synthetic lethality” logic of clinical use

- **BRCA1/2-deficient tumors**: BRCA1/2 are key proteins in homologous recombination repair (HRR); mutations impair HRR, leaving tumors dependent on PARP1-mediated base-excision repair (BER) for survival.
- **Synthetic lethality**: PARP1 inhibition + BRCA deficiency = two repair barriers → DNA damage accumulates → tumor-cell death (normal cells retain HRR)—“use structure-guided targeting against cells with a specific defect.”
- **Clinical status**: olaparib and other drugs are approved for BRCA-mutant ovarian, breast, pancreatic, and other cancers—“PARP inhibitors are a paradigm of precision cancer medicine.”

### 4.3 PARP modulation from an anti-aging perspective

- **The debate over “moderate inhibition”**: in animals, PARP1 inhibition (or knockdown) raises NAD⁺ and improves metabolism/mitochondrial function in some studies—“reducing NAD⁺ consumption may help.”
- **But complete inhibition is harmful**: PARP1 is required for DNA repair; long-term complete inhibition increases mutation/cancer risk—“repairing is problematic, and not repairing is problematic too.”
- **Ideal strategy**: reduce DNA damage (antioxidants, lifestyle) → PARP1 is naturally activated less often → less NAD⁺ is consumed—“treat the root cause rather than plugging the funnel.” This contrasts with the CD38 article’s “plug the funnel” strategy: for PARP1, the goal should be to “reduce the trigger,” not inhibit the enzyme itself.

---

## 5. PARP1 and aging: the “repair-consumption tradeoff” from a structural perspective

### 5.1 The PARP1 dilemma in aging

- **DNA damage accumulates with age**: oxidative damage, replication errors, and telomere shortening → more breaks → increased frequency/intensity of PARP1 activation.
- **The “repair tax” on NAD⁺**: every damage-repair event incurs an “NAD⁺ tax” (PAR synthesis consumes NAD⁺)—more damage, a heavier tax, and less NAD⁺.
- **“Starving” SIRT1**: PARP1 takes NAD⁺ away → SIRT1 lacks substrate → deacetylation declines → mitochondria, metabolism, and inflammation all become dysregulated (“the NAD⁺ tug-of-war between PARP1 and SIRT1”).
- **Vicious cycle**: SIRT1 declines → mitochondrial function ↓ → oxidative stress ↑ → more DNA damage → more PARP1 activity → less NAD⁺—a “damage-consumption-damage” death spiral.

### 5.2 A bird’s-eye view of the “NAD⁺ economy”: three funnels working together

Together with [08-cd38-structure.md](08-cd38-structure.md), this article presents two major consumption-side funnels and one user of NAD⁺:

```text
                   ┌─ CD38 (continuous funnel; immune/aging cells; increases with age)
NAD⁺ pool ──consumption───┼─ PARP1 (burst funnel; activated by DNA damage; damage increases with age)
                   └─ SIRT1 (user; deacetylation; activity declines with age)
         │
         Regeneration side: NAMPT (salvage) ←─ nicotinamide (released by both funnels)
```

- **Combined consumption by CD38 and PARP1**: CD38 drains NAD⁺ in a steady trickle, while PARP1 causes a “flash flood” during damage. Together they rapidly deplete the NAD⁺ pool in older adults.
- **“Recycling” nicotinamide**: both funnels release nicotinamide, which NAMPT salvages to regenerate NAD⁺. But NAMPT activity declines with age, lowering “recycling efficiency.”
- **Layered interventions**: use inhibitors for CD38 (plug the funnel), reduce damage to limit PARP1 triggering, and supply substrate to SIRT1 (feed the user)—“three-pronged, each with its own role.”

### 5.3 Anti-aging implications from a structural perspective

- **“Sustaining less damage” is better than “doing more repair”**: reduce DNA damage (antioxidants, sleep, avoiding radiation/toxins) → less PARP1 activation → preserve NAD⁺—the structural logic of prevention.
- **PARP inhibitors as a “double-edged sword”**: there is no clinical evidence for anti-aging doses of PARP inhibitors, and the cancer risk of long-term inhibition cannot be ignored—“not currently an anti-aging option.”
- **Potential synergy with NMN**: NMN supplementation (supply raw materials) + damage reduction (fewer triggers)—“opening the supply line + reducing the outflow” is logically better than either strategy alone.
- **Measure first**: PAR levels/PARP activity can be measured in blood/tissue—“first find out how leaky your funnel is, then decide what to replenish.”

---

## 6. Evidence grading

| Structural claim | Evidence level | Basis |
|---|---|---|
| PARP1 is a multidomain module (Zn1-3/WGR/HD/ART) | ★★★★★ Established | Crystal structures |
| Zn1/Zn3 recognize DNA-break geometry (not sequence) | ★★★★★ Established | 4DQY (2012 *Science*) |
| DNA binding → conformational collapse → catalytic-domain destabilization and activation | ★★★★★ Established | 4DQY |
| HD domain acts as a catalytic “brake” (released upon damage) | ★★★★★ Established | 4DQY + biochemistry |
| Catalysis = NAD⁺ cleavage + ADP-ribose-chain extension | ★★★★★ Established | Biochemistry + structure |
| PAR chains recruit repair proteins (e.g., XRCC1) | ★★★★★ Established | Biochemistry |
| Auto-modification → negative-feedback release from DNA | ★★★★★ Established | Biochemistry |
| PARP1 overactivation consumes NAD⁺ and lowers SIRT1 | ★★★★ Strong | Biochemistry + animal studies |
| PARP1 inhibition raises NAD⁺ (in animals) | ★★★★ Strong | Animal studies (limited human evidence) |
| PARP inhibitors treat cancer (BRCA deficiency) | ★★★★★ Established | Clinically approved |

---

## 7. Connections to the knowledge base’s central themes

### 7.0 The philosophy of “repair-consumption”: why the body pays with NAD⁺

PARP1’s structure reveals a profound biological tradeoff: **the cell uses the “energy currency” NAD⁺ to pay the “repair bill.”** Why not another molecule? The structural perspective offers an answer:

**NAD⁺ is a “ready-made warehouse of ADP-ribose.”** ADP-ribose units need a stable carrier. The nicotinamide-N-ribose bond in NAD⁺ happens to be a “ready-made break point”: when cleaved, the released ADP-ribose can be attached directly to a protein, while nicotinamide can be recycled to resynthesize NAD⁺ through the salvage pathway. **“Breaking down the ribose in NAD⁺ is cheaper than synthesizing ADP-ribose from scratch.”** Evolution selected NAD⁺ as an “use-and-break” carrier of ADP-ribose.

**The cost of this tradeoff** is that repair activity directly consumes the energy currency: more damage means less NAD⁺. **“Repair and metabolism are a zero-sum game.”** PARP1 directly links DNA damage to NAD⁺ metabolism—this is the central structural logic for understanding why NAD⁺ declines with age.

### 7.00 The dual identity of the “energy currency”: NAD⁺ is both fuel and building material

Taking this further, why does NAD⁺ “wear several hats”? Structural biology gives a thought-provoking answer: **NAD⁺’s two roles—as a redox carrier (fuel) and an ADP-ribose donor (building material)—are determined by the same molecular structure.**

**Look at NAD⁺’s chemical structure.** NAD⁺ = nicotinamide-ribose-pyrophosphate-ribose-adenine. The nicotinamide ring is the “working end” for redox reactions (accepting/donating hydrogen), while the nicotinamide-N-ribose bond is the “demolition point” for ADP-ribosyltransferases. **The same molecule has one end for energy metabolism and another for signaling/repair**—evolution’s “two-for-one deal.”

**This creates a sharp competition.** When a cell needs substantial energy (glycolysis/mitochondria need NAD⁺ as a redox carrier) and also faces DNA damage (PARP1 needs NAD⁺ as repair material), both compete for the NAD⁺ pool. **With aging, mitochondrial dysfunction (greater need for NAD⁺ to help) + accumulating DNA damage (greater PARP1 demand for repair) = pressure from both sides, until the pool runs dry.** SIRT1, a third consumer, is caught in the middle and is the first to “starve.”

**The lesson of the “two-for-one deal.”** Since NAD⁺ is a scarce resource, the essence of anti-aging strategies is to **“lighten the load on NAD⁺”**: ① reduce damage (less PARP1 activity); ② reduce continuous consumption (inhibit CD38); ③ increase supply (supplement NMN/NR); ④ improve regeneration efficiency (NAMPT activity). **Only by acting on all four fronts can the same NAD⁺ serve well as fuel, building material, and signaling substrate.** This is the structural foundation of “NAD⁺ economy” thinking (echoing the three-part picture in [08-cd38-structure.md](08-cd38-structure.md), with this article adding burst consumption on the “damage side”).

### 7.1 Dialogue with the core articles

- **NAD⁺/SIRT1 network** ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md)): this article fills in the “damage side”—PARP1 is the second-largest NAD⁺ consumption funnel, completing the picture with CD38 (immune side), NAMPT (regeneration side), and SIRT1 (utilization side).
- **CD38 structure** ([08-cd38-structure.md](08-cd38-structure.md)): compares the two funnels—CD38 is a steady trickle, PARP1 a burst flood; their intervention strategies differ (plug vs. reduce triggering).
- **SIRT1 structure** ([06-sirt1-structure.md](06-sirt1-structure.md)): the NAD⁺ tug-of-war between PARP1 and SIRT1—the molecular-level expression of “repair first or longevity first.”
- **Mitochondria** ([02-vascular/04-mitochondria.md](../02-vascular/04-mitochondria.md)): PARP1 overactivation → NAD⁺ depletion → mitochondrial energy dysfunction—“nuclear repair drags down mitochondrial metabolism.”
- **Aging clocks** ([01-foundations/02-aging-clocks.md](../01-foundations/02-aging-clocks.md)): accumulating DNA damage is one hallmark of aging, and PARP1 couples “damage and metabolism.”
- **Molecular structure series**: read alongside CD38 and SIRT1 for the complete structural foundation of the “NAD⁺ economy.”

---

## 8. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does PARP1 know DNA is broken? | Zn1/Zn3 recognize break geometry by shape complementarity (exposed bases/helical distortion). |
| How does DNA binding activate catalysis? | Conformational collapse → HD brake released → catalytic domain destabilized → NAD⁺ enters. |
| Why does PARP1 consume NAD⁺ so intensely? | Each added ADP-ribose unit consumes one NAD⁺, and synthesis is rapid during damage. |
| Why does PARP1 burden NAD⁺ during aging? | DNA damage accumulates with age → persistent PARP1 activation → heavier NAD⁺ repair tax. |
| Can PARP1 inhibition slow aging? | Some animal evidence supports it, but complete inhibition impairs repair—“reduce triggering” is better than “block the enzyme.” |

---

## 9. Open questions

1. **High-resolution structure of full-length PARP1**: a complete full-length snapshot of the dynamics between Zn domains and catalytic domain throughout damage binding is lacking.
2. **Quantifying “destabilization-driven activation”**: the precise relationship between increased catalytic-domain dynamics and catalytic rate.
3. **Structure of PAR-chain branching**: how is PAR-chain branching (10–15% branching) recognized/degraded by PARG?
4. **Tissue specificity**: differences in damage-response thresholds for PARP1 across tissues (brain, liver, immune system).
5. **PAR modulation at anti-aging doses**: is there a dose window in which mild PARP1 inhibition raises NAD⁺ without impairing repair?
6. **Real-time balance between PARP1 and SIRT1**: how is NAD⁺ allocated between them during damage repair (dynamic measurements at single-cell resolution)?

### 9.1 Putting the “reduce triggering” strategy into practice: lessons from structure for daily life

If the CD38 article ([08-cd38-structure.md](08-cd38-structure.md)) suggests “plug the funnel,” this article suggests **“don’t let the funnel start working”**—reducing DNA damage reduces PARP1’s consumption of NAD⁺. How can structural knowledge translate into practical advice?

**Antioxidants are the first line of defense against triggering.** Reactive oxygen species (ROS) are a major source of DNA damage (oxidative base lesions such as 8-oxoG and oxidative strand breaks). Structurally, the damage geometry caused by ROS attacks on DNA (base modifications and strand breaks) is exactly the signal recognized by PARP1—**“less damage geometry means less PARP1 triggering.”** Lifestyle measures include a balanced, antioxidant-rich diet, avoiding oxidative stressors (smoking, excessive sun exposure, pollution), and moderate exercise (exercise-induced oxidative stress is adaptive and protective in the short term).

**Sleep is a “repair window.”** DNA repair activity increases during deep sleep (according to multiple studies), and PARP1 carries out repair during sleep—**“concentrate repair at night and disturb it less during the day.”** Sleep deprivation = accumulated repair debt = PARP1 working overtime during the day and consuming NAD⁺.

**“Selective avoidance” of radiation and toxins.** Ionizing radiation and chemical toxins directly cause DNA breaks (strong triggers). The structural logic is **“don’t create breaks that can be avoided”**—use medical imaging (CT) when indicated, avoid unnecessary radiation exposure, and stay away from occupational toxins.

**The “exercise effect” of moderate damage.** A complete absence of damage is unrealistic (and moderate stressors such as exercise can be beneficial). The key is **“balance between damage and repair”**: keep the repair system supplied with sufficient NAD⁺ ammunition rather than allowing damage to remain chronically excessive. **“Structural knowledge turns ‘avoid triggering’ from a slogan into an actionable principle.”** This is the structural footnote to lifestyle interventions in [09-immortality/04-roadmap.md](../09-immortality/04-roadmap.md).

---

## 10. Guide to obtaining structural data

- **PDB entries**:
  - 4DQY: human PARP1 (Zn1+Zn3+WGR-CAT) + DNA double-strand break (3.25 Å, Langelier 2012 *Science*)—activated-state structure.
  - 1UK0/1UK1: human PARP1 catalytic domain + inhibitors (e.g., 3-aminobenzamide).
  - 4DQV and others: complexes of PARP1 with different DNA substrates.
  - 5DS3 and others: full-length/domain-combination PARP1 structures (later studies).
  - Other family members: PARP2 (e.g., 4TVJ), PARG (e.g., 4DJS)—structural comparisons with the “degrader.”
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX, AlphaFold prediction (AF-P09874).

---

## 11. References (published sources)

1. Langelier MF, Planck JL, Roy S, Pascal JM. Structural basis for DNA damage-dependent poly(ADP-ribosyl)ation by human PARP-1. *Science* 2012;336:728-732. (PDB 4DQY)
2. Langelier MF, Pascal JM. PARP-1 mechanism: from DNA damage to NAD⁺ consumption. *Curr Opin Struct Biol* 2013;23:134-143. (PARP1 mechanism review)
3. Lord CJ, Ashworth A. PARP inhibitors: synthetic lethality in the clinic. *Science* 2017;355:1152-1158. (Clinical PARP inhibitors)
4. Mouchiroud L, Houtkooper RH, Moullan N, et al. The NAD⁺/sirtuin pathway modulates longevity through activation of mitochondrial UPR and FOXO signaling. *Cell* 2013;154:430-441. (NAD⁺/SIRT1 and lifespan)
5. Bai P, Cantó C, Oudart H, et al. PARP-1 inhibition increases mitochondrial metabolism through SIRT1 activation. *Cell Metab* 2011;13:461-468. (PARP1 inhibition → SIRT1 activation)
6. Covarrubias AJ, Perrone R, Grozio A, Verdin E. NAD⁺ metabolism and its roles in cellular processes during ageing. *Nat Rev Mol Cell Biol* 2021;22:119-141. (NAD⁺ metabolism review)
7. Wang Y, Kim NS, Haines JF, et al. Poly(ADP-ribose) (PAR) binding to apoptosis-inducing factor is critical for PAR polymerase-1-dependent cell death (parthanatos). *Sci Signal* 2011;4:ra20. (Parthanatos)

---

> **Structural summary**: PARP1 = three zinc fingers (Zn1/Zn3 sense breaks) + WGR (transmission) + HD (brake) + ART catalytic domain (NAD⁺ assembly line). **“Destabilization is activation”**—DNA breaks make the catalytic domain more flexible, allowing NAD⁺ to flow in; each added ADP-ribose unit consumes one NAD⁺. **With aging, damage accumulates → PARP1 is persistently activated → the NAD⁺ repair tax increases → SIRT1 is starved.** Together with CD38, PARP1 forms the “two funnels.” The anti-aging strategy is to “reduce triggering” (less damage), not “block the enzyme” (preserve repair).
