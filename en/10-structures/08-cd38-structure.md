# Molecular Structure Deep Dive 08: CD38—The “Consumer” of NAD⁺ and Its Covalent Catalytic Mechanism

> **Topic positioning**: Article 8 in 10-structures (Molecular Structure Deep Dive). Examines the three-dimensional structure of CD38 (an NAD⁺ glycohydrolase/ADP-ribosyl cyclase) to explain how it “consumes” NAD⁺, its covalent-intermediate catalytic mechanism, and its role in the age-related decline in NAD⁺. This is the structural foundation for the “consumption side” of the knowledge base’s NAD⁺/SIRT1 thread ([01-foundations/04-nad-sirtuin.md](../01-foundations/04-nad-sirtuin.md)); CD38 and SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)) form a pair of NAD⁺ competitors.
> **Related articles**: See [06-sirt1-structure.md](06-sirt1-structure.md) for SIRT1 structure, [04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md) for the NAD⁺ network, and [03-immunity/04-immunosenescence.md](../03-immunity/04-immunosenescence.md) for immunosenescence.

---

## 0. Structural snapshot

**In one sentence**: CD38 is a “moonlighting” NAD⁺-consuming enzyme. It acts both as an NAD⁺ glycohydrolase (hydrolyzing NAD⁺ to ADPR + nicotinamide) and as an ADP-ribosyl cyclase (converting NAD⁺ to cADPR + nicotinamide). Every NAD⁺ molecule consumed releases one nicotinamide molecule. CD38 is **one of the largest “funnels” draining intracellular NAD⁺** and an important driver of the age-related decline in NAD⁺.

```text
CD38 topology: N-terminal cytoplasmic tail (short) — single transmembrane helix — extracellular catalytic domain (globular, ~258–303 residues)
                                                                          │
                                    catalytic domain: deep pocket + key catalytic residue Glu226
                                                                          │
              NAD⁺ ──► nicotinamide + ADPR (hydrolysis) OR cADPR (cyclization) + ADPR
```

**Three major structural features** (the atomic basis of function):
1. **Type II transmembrane topology**: The N-terminus is intracellular and the C-terminal catalytic domain is extracellular—an unusual orientation. Catalysis occurs at the cell surface or on extracellular vesicles.
2. **Deep catalytic pocket**: NAD⁺ binds in a deep cleft in the extracellular domain, with the nicotinamide–N-ribose bond oriented toward the catalytic residue.
3. **Glu226 covalent catalysis**: The conserved glutamate (human CD38 Glu226) nucleophilically attacks ribose C1′, forming a **covalent ADP-ribose–enzyme intermediate** (directly captured in 3DZF). This is a defining feature distinguishing the CD38 family from ordinary hydrolases.

**Core catalytic reaction**:

```text
NAD⁺ ──(Glu226 nucleophilic attack at C1′)──► covalent intermediate (ADP-ribose–O–Glu226) + nicotinamide (released)
        │
        ├──(water attack)────────────► ADPR (main hydrolysis product)
        └──(intramolecular cyclization)► cADPR (second messenger in calcium signaling)
```

---

## 1. Why CD38 structure matters

NAD⁺ is a “star molecule” in aging research: its levels decline with age (by ages 40–60 they may fall to less than half of young-adult levels), and NMN/NR supplementation has become a popular anti-aging strategy. But the **cause** of NAD⁺ decline matters more than simply “what to supplement,” and CD38 is central:

- **CD38 expression rises with age**: CD38 expression increases substantially in older tissues (adipose, liver, immune tissues), a consensus supported by multiple research groups around 2020.
- **CD38 is a major “NAD⁺ funnel”**: It is highly expressed in immune and senescent cells, and each catalytic event consumes one NAD⁺ molecule. CD38-knockout mice have substantially higher NAD⁺ levels and improved lifespan/healthspan (Chini and colleagues, 2020s).
- **CD38 competes with SIRT1**: NAD⁺ is a substrate for SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)); CD38 consumption of NAD⁺ lowers SIRT1 activity. Rising CD38 is an upstream driver of age-related decline in the NAD⁺/SIRT1 axis.
- **CD38 inhibitors are anti-aging candidates**: In animals, inhibitors such as 78c/CD38-IN-78c raise NAD⁺ and improve metabolic and aging phenotypes. The structural logic is that “closing the funnel may be more effective than pouring in more water.”

**Three key questions for structural research**:
1. How does CD38 capture and cleave NAD⁺? (Substrate recognition and catalysis)
2. How does the covalent intermediate form and break down? (Glu226 mechanism)
3. Why does one active site catalyze both hydrolysis and cyclization? (Structural basis of bifunctionality)

These questions have been addressed by structures including 3DZF (covalent-intermediate structure, 2008).

---

## 2. Structural dissection of CD38

### 2.1 Topology and membrane anchoring

- CD38 is a **type II single-pass transmembrane protein** (approximately 45-kDa monomer, with a 21-amino-acid N-terminal cytoplasmic tail, a transmembrane helix, and a 258-residue extracellular catalytic domain).
- The extracellular domain exists as a **homodimer** (a monomer is inactive or has very low activity); the dimer interface includes part of the substrate-channel interface.
- Besides its membrane-bound form, CD38 also exists in **soluble form** (released in extracellular vesicles or by proteolytic cleavage); soluble CD38 also consumes extracellular NAD⁺.
- **Transmembrane access of NAD⁺**: NAD⁺ is mainly intracellular, whereas CD38’s catalytic domain is extracellular. How CD38 consumes intracellular NAD⁺ was once a puzzle. The current view invokes an “NAD⁺ transport channel”: intracellular NAD⁺ is transported outside through a transmembrane channel in CD38 or an associated transport protein. In effect, “CD38 pulls intracellular NAD⁺ outside and consumes it.”

### 2.2 Catalytic domain: Anatomy of the deep pocket

- The extracellular catalytic domain has a **globular fold** (TIM-barrel-like/α/β structure) containing a deep, narrow **NAD⁺-binding cleft**.
- Aromatic residues (Tyr/Trp) line the cleft and form π-stacking interactions with NAD⁺’s adenine and nicotinamide rings—the substrate is clamped by an “aromatic wall.”
- A **nicotinamide subpocket** at the cleft entrance recognizes the nicotinamide ring and positions it precisely next to the catalytic residue.
- **Key catalytic residue**: Glu226 (human CD38 numbering) lies at the bottom of the cleft; its carboxylate (–COO⁻) faces C1′ of the NAD⁺ ribose—the “nucleophilic warhead” points at the glycosidic bond.

### 2.3 Dimer interface and catalytic cooperation

- Two monomers form a “head-to-head” dimer, with many hydrophobic contacts and hydrogen bonds at the interface.
- Dimerization stabilizes the conformation of the catalytic pocket; mutations disrupting the dimer interface abolish activity (biochemically validated).
- The two active sites function independently (no allosteric cooperativity), but dimerization is required for activity—two pockets, one stabilized architecture.

---

## 3. Covalent catalytic mechanism: From structure to chemistry

### 3.00 Why the “covalent intermediate” is the key to understanding CD38

Many people imagine enzyme catalysis as “position the substrate and let the reaction happen.” CD38 shows that some enzymes get directly involved. CD38 cleaves the NAD⁺ glycosidic bond not by standing aside, but by using an amino-acid side chain to **grab the substrate, form a chemical bond, and then break it down**. This is covalent catalysis. Understanding it explains why CD38 inhibitors are difficult to design and why CD38 is an efficient “NAD⁺ funnel.”

**Power of covalent catalysis: speed.** Noncovalent hydrolysis (for example, an esterase passively waiting for water to attack) has limited speed. Covalent catalysis divides the reaction into two faster, more controllable steps: first form a stable enzyme–substrate adduct, then release product. Once CD38’s Glu226 grabs NAD⁺, nicotinamide is immediately displaced as an excellent leaving group and a covalent intermediate rapidly forms. **NAD⁺ cleavage is completed on a millisecond timescale.** This is why CD38 can be a major NAD⁺ funnel: not because it “wants” to consume NAD⁺, but because its catalytic mechanism is inherently efficient.

**Cost of covalent catalysis: the intermediate must be “seen.”** Covalent intermediates usually live only microseconds to milliseconds and are hard to capture by conventional crystallography. 3DZF is valuable because researchers used ara-F-ribose-5′-phosphate, a fluorinated analog, to “freeze” the intermediate: fluorine’s strong electron-withdrawing effect greatly slows its breakdown, allowing the Glu226–ribose covalent adduct to persist in the crystal. **This is a classic example of using chemistry to freeze a transient structure.**

**Implication of covalent catalysis: two inhibitor-design strategies.** Understanding the covalent mechanism suggests two approaches: (1) “take the seat” with a substrate analog occupying the NAD⁺-binding cleft (competitive inhibition, e.g., ara-F-NAD⁺); or (2) “disable the warhead” using an electrophilic compound that reacts with Glu226 (irreversible covalent inhibition). Each has trade-offs: competitive inhibitors are reversible but may require high concentrations; covalent inhibitors can be potent but carry off-target toxicity risks. **Understanding mechanism is necessary to weigh strategy.**

### 3.0a Atom by atom: How Glu226 “grabs” NAD⁺

The nicotinamide–N-ribose bond (N-glycosidic bond) of NAD⁺ is the catalytic target. It is chemically quite stable, so CD38 must forcefully break it. The structure reveals the answer: **covalent attachment first, cleavage second.**

**Step 1: Nucleophilic attack by Glu226.** In the catalytic cleft, the Glu226 side-chain carboxylate (–COO⁻) acts as a nucleophile, attacking C1′ of the NAD⁺ ribose (the carbon attached to nicotinamide). This forms a **covalent intermediate**: ADP-ribose is linked to Glu226 by an ester bond, and nicotinamide leaves as the leaving group (released as CD38’s first product of NAD⁺ consumption). The 3DZF structure (2.01 Å) uses an ara-F-ribose-5′-phosphate analog to **directly capture this covalent intermediate**—the Glu226–ribose covalent adduct is clearly visible.

**Step 2: The intermediate reaches a “fork in the road.”** The covalent intermediate has two possible fates:
- **Hydrolysis (main path)**: A water molecule attacks the intermediate → ADPR (linear ADP-ribose) is released. CD38 acts as an NAD⁺ glycohydrolase.
- **Cyclization (minor but important path)**: The ribose 2′-OH attacks intramolecularly → cADPR (cyclic ADP-ribose) is released. CD38 acts as an ADP-ribosyl cyclase.

**Why does the mechanism matter?** CD38 does not simply “chop” NAD⁺ by hydrolysis; it first grabs it covalently and then the intermediate follows one of two routes. This also explains why inhibitor design is difficult: inhibitors must compete with Glu226’s nucleophilic attack (or occupy the nicotinamide subpocket), while the intermediate lifetime is extremely short because catalysis is rapid. The trapped intermediate in 3DZF provides a crucial snapshot for inhibitor design.

### 3.1 Structural logic of bifunctionality

- **One active site, two products**: The balance between hydrolysis and cyclization depends on the availability of water at the active site. If the pocket opening faces solvent, hydrolysis is favored; if the opening is blocked, cyclization is favored.
- **Significance of cADPR signaling**: cADPR is a **second messenger in calcium signaling** (it activates ryanodine receptors → calcium release from the endoplasmic reticulum). CD38 not only consumes NAD⁺ but also produces a calcium-signaling molecule.
- **Role in immune cells**: CD38 is highly expressed on activated T cells, B cells, and NK cells. Its cADPR/ADPR products participate in immune signaling, and CD38 is also a surface marker (“CD38⁺ cells”).
- **Evolutionary perspective**: CD38-family members (CD38, BST1/CD157, SARM1) use Glu-based covalent catalysis. They share a catalytic core but differ in substrate preference; SARM1 can catastrophically consume NAD⁺ during axonal injury.

### 3.2 CD38 versus SIRT1: Competition for NAD⁺

| Dimension | CD38 (consumer) | SIRT1 (user) |
|---|---|---|
| Reaction | NAD⁺ → nicotinamide + ADPR/cADPR | NAD⁺ + acetylated lysine → nicotinamide + OAADPr |
| Products per NAD⁺ | ADPR/cADPR (signaling/metabolism) | OAADPr (signaling) + deacetylated substrate |
| Aging trend | Expression↑ (immune/adipose tissues) | Activity↓ (NAD⁺ shortage + oxidative damage) |
| Intervention | Inhibitors (e.g., 78c) | Substrate supply (NMN/NR) + allosteric activation (STACs) |
| Structural core | Glu226 covalent intermediate | Rossmann fold + Zn²⁺ zinc finger |

**“Zero-sum competition” in NAD⁺ allocation**: The cellular NAD⁺ pool is limited; the more CD38 consumes, the less remains for SIRT1. With age, CD38↑ → NAD⁺ is “drained” → SIRT1 is starved. **Blocking CD38 is an upstream strategy for rescuing SIRT1**, potentially more fundamental than simply supplementing NMN, since supplemented NAD⁺ may also be consumed by CD38.

---

## 4. CD38 inhibitors: From structure to drugs

### 4.1 Binding modes of known inhibitors

- **Nicotinamide analogs** (e.g., ara-F-NAD⁺): Occupy the nicotinamide subpocket and competitively block NAD⁺ binding.
- **Flavonoids** (e.g., apigenin, luteolin): Bind near the pocket entrance and partially occupy the substrate channel. Affinity is low (micromolar), but these compounds occur naturally.
- **Covalent inhibitors**: Target catalytic residue Glu226 to form an irreversible adduct—potentially potent, but with toxicity risk.
- **78c (CD38-IN-78c)**: A potent, selective inhibitor (nanomolar range) that binds in an allosteric/substrate-competitive region of the active-site cleft. In animal studies, it raises NAD⁺ by 50–100%, improves glucose tolerance, and extends healthspan (Chini group, 2020s).

### 4.2 Structural challenges in inhibitor design

- **Highly conserved active site**: CD38 and BST1/CD157 have nearly identical active sites, making it difficult to inhibit CD38 selectively without affecting BST1. 78c achieves selectivity by exploiting differences in peripheral pocket residues.
- **Polar pocket**: The NAD⁺-binding cleft is rich in polar/aromatic residues. Drug-like molecules must balance polarity with permeability and oral availability.
- **Lesson from the covalent intermediate**: The ara-F intermediate structure in 3DZF suggests a “transition-state mimic” strategy—design drugs based on transition-state analogs, as in neuraminidase inhibitor oseltamivir.

---

## 5. CD38 and aging: The “funnel theory” from a structural perspective

### 5.1 Why CD38 rises with age

- **Immune-cell infiltration**: Older adipose and liver tissues have increased infiltration by CD38⁺ immune cells (macrophages, T cells)—“immunosenescence drives NAD⁺ consumption.”
- **Senescent cells (SASP)**: Senescent cells highly express CD38 as part of the SASP—“senescent cells release CD38 and consume NAD⁺ in surrounding tissues.”
- **Amplification by inflammation**: CD38-derived cADPR → calcium signaling → release of pro-inflammatory factors → further immune-cell infiltration → more CD38. This is an inflammatory vicious cycle of NAD⁺ consumption (see [02-inflammaging](../03-immunity/02-inflammaging.md)).

### 5.2 Evidence chain for the “block the funnel” strategy

- **CD38-knockout mice**: Higher NAD⁺, improved metabolism, greater exercise capacity, and longer lifespan (validated in multiple mouse backgrounds).
- **CD38 inhibitor 78c**: Restores NAD⁺ and SIRT1 activity in old mice and improves glucose tolerance and mitochondrial function (e.g., Chini 2022).
- **Human translation**: CD38 inhibitors have entered early clinical development, primarily in combination with cancer immunotherapy; anti-aging indications remain exploratory.
- **Synergy with NMN**: In animals, NMN supplementation plus CD38 inhibition (“add water + stop the leak”) outperforms either intervention alone—the structural logic of a two-pronged approach.

### 5.3 Anti-aging implications from a structural perspective

- **Treating symptoms versus causes**: NMN supplementation is “pouring water into a leaking funnel” (a symptomatic approach; the leak remains), while CD38 inhibition “plugs the funnel” (more causal, but excessive inhibition may impair immune function). **The ideal strategy is to partially plug the leak while continuing to replenish the pool.**
- **Challenge of tissue specificity**: CD38 has normal functions in immune signaling; systemic inhibition could impair immunity. Tissue-targeted CD38 inhibition (for example, delivery specifically to adipose tissue or liver) is a future direction.
- **Connection to SIRT1**: CD38 inhibition → NAD⁺ rises → SIRT1 activation → eNOS deacetylation → NO production. CD38 inhibition can indirectly activate the NO pathway, linking [06-sirt1-structure.md](06-sirt1-structure.md) and [01-nos-structures.md](01-nos-structures.md).

---

## 6. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| CD38 is a type II transmembrane protein with an extracellular catalytic domain | ★★★★★ Established | Topology + structure |
| Catalytic domain has a globular fold and deep NAD⁺ pocket | ★★★★★ Established | Crystal structure |
| Glu226 nucleophilic attack forms covalent intermediate | ★★★★★ Established | 3DZF (2008, *Chem Biol*) |
| Covalent intermediate → ADPR (hydrolysis)/cADPR (cyclization) | ★★★★★ Established | 3DZF + biochemistry |
| cADPR is a calcium-signaling second messenger | ★★★★★ Established | Pharmacology (ryanodine receptor) |
| CD38 expression rises with age (immune/adipose tissues) | ★★★★ Strong | Multiple groups; 2020s consensus |
| CD38-mediated NAD⁺ consumption lowers SIRT1 activity | ★★★★ Strong | Biochemistry + animal studies |
| CD38 knockout/inhibition raises NAD⁺ and improves healthspan | ★★★★ Strong (robust animal data) | Multiple models |
| Anti-aging efficacy of inhibitors such as 78c in humans | ★★ Preliminary | Early clinical/translational stage |

---

## 7. Connections to the knowledge base’s main themes

### 7.0 Three structural sides of NAD⁺ economics

Combining [06-sirt1-structure.md](06-sirt1-structure.md) (SIRT1) with [04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md), NAD⁺ economics has three sides:

```text
【Supply】 NAMPT (salvage) / NMNAT (synthesis) ──► NAD⁺ pool
                                                   │
【Consumption】 ┌─ CD38 (glycohydrolysis/cyclization; rises with age) → nicotinamide + ADPR/cADPR
               ├─ PARP (poly-ADP-ribosylation, DNA repair; rises with damage)
               └─ SIRT1/3 (deacetylation, substrate use) → nicotinamide + OAADPr
                                                   │
【Recycling】 Nicotinamide ──(NAMPT)──► NMN ──(NMNAT)──► NAD⁺ (salvage cycle)
```

- **Imbalance with age**: CD38/PARP consumption↑ + NAMPT activity↓ → NAD⁺ pool shrinks → SIRT1 is “starved.”
- **Structural intervention points**: (1) block CD38 (inhibitors); (2) reduce PARP demand (less DNA damage); (3) supply precursors (NMN/NR); and (4) activate NAMPT (for example, indirectly through NMN).
- **“Repair all three sides” strategy**: More comprehensive than supplementation alone—expand supply, conserve through reduced consumption, and improve recycling.

### 7.01 Structural evidence grading of three intervention points: From atoms to strategy

The previous section outlined three sides of NAD⁺ economics. Here each is assigned a structural-evidence level to guide strategy:

**Supply (expand): NMN/NR supplementation.** Structural basis: NAMPT/NMNAT are key enzymes in NAD⁺ synthesis with crystal structures; supplying NMN/NR increases substrate availability and can raise NAD⁺ synthesis. **Evidence: ★★★★** (robust animal evidence; human Phase I/II studies ongoing). A caveat from a structural perspective: NAD⁺ synthesis involves more than one “pipe,” and whether NMN efficiently enters cells (requiring specific transporters) remains debated—supplying raw material does not guarantee an open pipeline.

**Consumption (conserve): CD38 inhibition.** Structural basis: 3DZF reveals CD38 covalent catalysis and pocket architecture, and inhibitors such as 78c have defined binding modes. **Evidence: ★★★★ in animals / ★★ in humans**: strong animal results (NAD⁺ restoration and healthspan improvement), but human RCT evidence is lacking. Structural challenge: the CD38 active site is highly conserved, making selective inhibition (without affecting BST1/SARM1) difficult—block the large funnel, not the small ones.

**Recycling (improve): NAMPT activation.** Structural basis: NAMPT has crystal structures, including a substrate-bound form, with defined active/allosteric sites. **Evidence: ★★★**: NAMPT activators (such as P7C3-like compounds) work in neuroprotection animal models, but specificity and toxicity need optimization. Structural approach: NAMPT’s allosteric pockets, such as the substrate-induced dimerization interface, are potential targets—make the salvage enzyme work harder.

**Structural logic of a three-part combination**: Why might “expand supply + conserve + improve recycling” outperform a single intervention? NAD⁺ economics is a **negative-feedback system**: NMN supply can be offset by CD38 consumption (the funnel remains); CD38 inhibition alone may restore little NAD⁺ if NAMPT activity is insufficient. Addressing all three sides can raise the total pool. **A system-level problem needs a system-level solution**—the central structural lesson for NAD⁺-based anti-aging strategies (a molecular implementation of the combination approach discussed in [09-immortality/02-breakthrough-candidates.md](../09-immortality/02-breakthrough-candidates.md)).

### 7.1 Dialogue with the main articles

- **NAD⁺/SIRT1 network** ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md)): This article fills in the consumption side. CD38 is an upstream driver of NAD⁺ decline, completing the picture alongside the supply side (NAMPT/NMNAT) and the utilization side (SIRT1).
- **SIRT1 structure** ([06-sirt1-structure.md](06-sirt1-structure.md)): The NAD⁺-competition counterpart. CD38 consumes NAD⁺ → SIRT1 loses substrate. Read together, the articles provide the structural picture of NAD⁺ allocation.
- **Immunosenescence** ([04-immunosenescence](../03-immunity/04-immunosenescence.md)): Infiltration by CD38⁺ immune cells contributes to NAD⁺ consumption in older tissues—immune aging can undermine metabolic anti-aging.
- **Inflammaging** ([02-inflammaging](../03-immunity/02-inflammaging.md)): The CD38–cADPR–calcium–inflammation vicious cycle.
- **Supplements** ([07-interventions/04-supplements.md](../07-interventions/04-supplements.md)): Limitation of NMN/NR supplementation while the funnel remains open—supplemented NAD⁺ may still be consumed by CD38.
- **Molecular-structure topic**: Alongside SIRT1 (NAD⁺ use) and NOS (NO signaling), CD38 forms part of the structural foundation of the NAD⁺–NO metabolic network. **CD38 inhibition → NAD⁺↑ → SIRT1 activation → eNOS deacetylation → NO production** links this article to the NO thread and SIRT1 article in a single anti-aging structural narrative.

---

## 8. Five structure–aging questions

| Question | Structural answer |
|---|---|
| Why does CD38 consume NAD⁺ so rapidly? | High expression + rapid covalent catalysis (Glu226) + active dimer architecture. |
| How can CD38 both hydrolyze and cyclize? | The same covalent intermediate yields ADPR after water attack or cADPR after intramolecular attack. |
| Why is CD38 implicated in age-related NAD⁺ decline? | CD38 expression rises with age (immune infiltration + senescent cells), enlarging the NAD⁺ drain. |
| Why can CD38 inhibition rescue SIRT1? | NAD⁺ is no longer drained; SIRT1 substrate availability recovers and deacetylation resumes. |
| Why is NMN supplementation limited? | Supplemented NAD⁺ may still be consumed by high CD38—“the funnel is still leaking.” |

**Structural intuition beyond these five questions**: CD38 teaches another lesson: **a molecule’s fate is determined by its neighbors**. NAD⁺ itself has no preference for which enzyme consumes it; the relative presence of CD38 (consumer), SIRT1 (user), PARP (repair enzyme), and NAMPT (recycler) determines its fate. Aging disrupts this “molecular community” and shrinks the NAD⁺ pool. **Structural biology makes these neighborhood relations visible**: active-site shape, substrate preference, and competition are all accessible to analysis, and intervention at any one enzyme affects NAD⁺ allocation overall. That is why the value of “Molecular Structure Deep Dive” is not merely to inspect details, but to see the whole system.

---

## 9. Open questions

1. **Transmembrane mechanism for “pulling” NAD⁺**: Structural details of how intracellular NAD⁺ reaches the extracellular catalytic domain (channel/transport protein) are not fully resolved.
2. **Tissue-specific inhibition**: How can CD38 be inhibited in tissues such as adipose tissue/liver without harming normal CD38 function in immune cells?
3. **Role of soluble CD38**: The contribution of extracellular-vesicle-released soluble CD38 to systemic NAD⁺ consumption is unknown.
4. **Long-term effects of cADPR signaling**: What are the effects of lower cADPR on calcium signaling and neural function during chronic CD38 inhibition?
5. **Coordination between CD38 and SARM1**: How do these two NAD⁺-consuming enzymes divide labor across tissues and stress conditions?
6. **Validation of CD38 inhibition in humans**: RCTs for anti-aging indications are lacking; current development is mainly for combination cancer therapy.

### 9.1 Boundaries of the “funnel theory”: CD38 is not the only answer

This article emphasizes CD38 as a major NAD⁺ funnel, but a structural perspective requires caution: CD38 is not the only consumer in NAD⁺ economics.

**PARP family (poly-ADP-ribose polymerases).** PARP1 is activated by DNA damage and consumes large amounts of NAD⁺ to synthesize poly-ADP-ribose chains (dozens to hundreds of NAD⁺ molecules may be used per repair event). With aging, DNA damage accumulates → PARP1 remains activated → NAD⁺ is “burned.” Structurally, the PARP1 catalytic domain (ART fold) differs entirely from CD38 (it lacks Glu-based covalent catalysis and instead relies on His/Tyr catalysis). Two funnels, two mechanisms, one consequence.

**SARM1 (sterile alpha and TIR motif-containing protein 1).** During axonal injury, SARM1 is activated; its TIR domain rapidly consumes NAD⁺ as an NAD⁺-cleaving enzyme, contributing to axonal degeneration. Its active site has only recently been characterized. SARM1 belongs to the broader ADP-ribosyltransferase-fold superfamily that includes CD38, but its mechanistic details differ. It is an NAD⁺ self-destruction switch during neural injury.

**NAMPT as the “bottleneck.”** Regardless of how active the consumers are, NAD⁺ regeneration depends on NAMPT, the rate-limiting enzyme of the salvage pathway. NAMPT activity declines with age and is associated with circadian disruption and lower SIRT1 activity. NAD⁺ can therefore decline even if CD38 remains unchanged—the funnel’s size is one issue; the tap’s flow is another.

**The “multiple funnels, multiple bottlenecks” picture** means that CD38 inhibition is important but not a universal solution. **An ideal NAD⁺ anti-aging strategy should combine interventions as needed**: people with substantial DNA damage may benefit more from PARP modulation or reducing damage with antioxidants; those at high risk of neurodegeneration may focus on SARM1; and general NAD⁺ decline may be addressed with CD38 inhibition plus NMN supplementation. **Structural knowledge stratifies strategies rather than imposing a one-size-fits-all approach**—consistent with the personalized-roadmap logic in [09-immortality/04-roadmap.md](../09-immortality/04-roadmap.md).

---

## 10. Guide to structural data

- **PDB entries**:
  - 3DZF: Human CD38 extracellular domain + covalent-intermediate analog ara-F-ribose-5′-phosphate (2.01 Å; Liu 2008, *Chem Biol*)—evidence for covalent catalysis.
  - 3DZG/3DZH/3DZI/3DZJ/3DZK: Same series (different intermediates/substrate analogs).
  - 1YH3 and related entries: Early crystal structures of the human CD38 extracellular domain.
  - Other family members: BST1/CD157 (CD38 homolog) and SARM1 (axonal NAD⁺ enzyme; e.g., 6CKL).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX, AlphaFold prediction (AF-Q10588).

---

## 11. References (authentic literature)

1. Liu Q, Kriksunov IA, Jiang H, et al. Covalent and noncovalent intermediates of an NAD utilizing enzyme, human CD38. *Chem Biol* 2008;15:1068–1078. (PDB 3DZF)
2. Lee HC. Structure and enzymatic functions of human CD38. *Mol Med* 2006;12:317–323. (CD38 structural and functional review)
3. Chini EN, Chini CCS, Kato Y, et al. CD38 ectoenzyme and NAD⁺ metabolism in aging and disease. *Nat Metab* 2020;2:1090–1097. (CD38, aging, and NAD⁺)
4. Tarragó MG, Chini CCS, Kanamori KS, et al. A potent and specific CD38 inhibitor ameliorates age-related metabolic dysfunction by reversing tissue NAD⁺ decline. *Cell Metab* 2018;27:1081–1095. (78c inhibitor)
5. Covarrubias AJ, Perrone R, Grozio A, Verdin E. NAD⁺ metabolism and its roles in cellular processes during ageing. *Nat Rev Mol Cell Biol* 2021;22:119–141. (NAD⁺ metabolism review)
6. Aksoy P, White TA, Thompson M, Chini EN. Regulation of intracellular levels of NAD: a novel role for CD38. *Biochem Biophys Res Commun* 2006;345:1386–1392. (CD38 regulation of intracellular NAD⁺)
7. Yoshino J, Baur JA, Imai SI. NAD⁺ intermediates: the biology and therapeutic potential of NMN and NR. *Cell Metab* 2018;27:513–528. (NMN/NR review)

---

> **Structural snapshot**: CD38 = type II transmembrane topology (extracellular catalytic domain) + deep NAD⁺ pocket + **Glu226 covalent catalysis** (intermediate directly captured in 3DZF). Every NAD⁺ consumed releases nicotinamide (+ ADPR/cADPR), making CD38 one of the largest drains in NAD⁺ economics. **With age, CD38↑ → NAD⁺ is drained → SIRT1 is starved.** Blocking the funnel (CD38 inhibition) is an upstream strategy for rescuing the NAD⁺/SIRT1 axis, complementary to NMN supplementation (“adding water”).
