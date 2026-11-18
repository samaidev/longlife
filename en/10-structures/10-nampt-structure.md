# Molecular Structure Deep Dive 10: NAMPT — The “Regeneration Engine” of the NAD⁺ Salvage Pathway and Its Substrate Tunnel

> **Series context**: Article 10 in 10-structures (Molecular Structure Deep Dive)—anatomy of the three-dimensional structure of NAMPT (nicotinamide phosphoribosyltransferase), and how it “recycles” nicotinamide, synthesizes NMN, and serves as the rate-limiting enzyme of the NAD⁺ salvage pathway. This provides the “regeneration-side” structural foundation for the knowledge base’s NAD⁺/SIRT1 thread ([01-foundations/04-nad-sirtuin.md](../01-foundations/04-nad-sirtuin.md)). Together with SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)), CD38 ([08-cd38-structure.md](08-cd38-structure.md)), and PARP1 ([09-parp1-structure.md](09-parp1-structure.md)), it completes the NAD⁺ economy’s loop.
> **Related articles**: SIRT1 structure: [06-sirt1-structure.md](06-sirt1-structure.md); CD38: [08-cd38-structure.md](08-cd38-structure.md); PARP1: [09-parp1-structure.md](09-parp1-structure.md); NAD⁺ network: [04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md).

---

## 0. Structural overview

**In one sentence**: NAMPT is the rate-limiting enzyme in the NAD⁺ salvage pathway—it converts nicotinamide (NAM) + PRPP into NMN (nicotinamide mononucleotide), which is then converted to NAD⁺ by NMNAT. It is the regeneration engine of the “NAD⁺ economy”: CD38/PARP1 consume NAD⁺ and release nicotinamide, and NAMPT “recycles” nicotinamide into new NAD⁺—“the water lost through the funnel is poured back in by NAMPT.”

```text
NAMPT structure: homodimer (two subunits, head to head)—each subunit contains one catalytic tunnel
                                  │
Catalytic tunnel: PRPP-binding site — phosphoribosyl-transfer reaction — nicotinamide-binding site
                                  │
Reaction: nicotinamide + PRPP ──(NAMPT)──► NMN + PPi (pyrophosphate)
                                  │
Next: NMN + ATP ──(NMNAT)──► NAD⁺ + PPi
```

**Three major structural features** (the atomic basis of its function):
1. **Type II phosphoribosyltransferase fold**: NAMPT is homologous to bacterial nicotinamide phosphoribosyltransferases—a “eukaryotic version of an ancient enzyme family.”
2. **Tunnel at the dimer interface**: the two subunits assemble head-to-head to form **one continuous substrate tunnel**; nicotinamide enters at one end and NMN exits at the other—an “assembly line through a tunnel.”
3. **Asp219-mediated substrate selectivity**: residue Asp219 determines that NAMPT recognizes nicotinamide, but not nicotinic acid or other analogs—a “molecular ruler calibration.”

**Core catalytic reaction**:

```text
Nicotinamide (NAM) + PRPP ──(NAMPT, dimer tunnel)──► NMN + pyrophosphate (PPi)
                                                               │
                                                   NMN + ATP ──(NMNAT)──► NAD⁺
```

---

## 1. Why NAMPT structure matters

NAMPT is the rate-limiting enzyme of the NAD⁺ salvage pathway (mammals rely mainly on salvage to synthesize NAD⁺; de novo synthesis is largely restricted to the liver and kidneys):

- **“Recycling” is central**: most intracellular NAD⁺ comes from the salvage pathway. CD38/PARP1/SIRT1 all consume NAD⁺ and release nicotinamide; NAMPT “rescues” the nicotinamide and converts it back into NAD⁺—the “recirculation pump of the NAD⁺ economy.”
- **Rate-limiting role**: NAMPT is the bottleneck in the salvage pathway (its Km for nicotinamide is relatively high, and its activity is regulated by nicotinamide concentration)—“the pump’s speed determines the pool’s water level.”
- **Declines with age**: NAMPT expression/activity declines with age (especially in fat, muscle, and brain) → the NAD⁺ pool shrinks → SIRT1 is starved—“aging of the regeneration side is another major contributor to NAD⁺ decline.”
- **The mystery of a protein with three identities**: NAMPT is also PBEF (pre-B-cell colony-enhancing factor) and visfatin—one protein with three identities: enzyme, cytokine, and hormone. Structurally, it has only an enzymatic active site; cytokine activity may depend on its secreted form or receptor interactions, but remains controversial. This is still unresolved and is one of the most intriguing open questions in NAMPT research.

**Three key questions in structural research**:
1. How does NAMPT recognize nicotinamide rather than nicotinic acid or other substrates? (substrate selectivity)
2. How does the substrate tunnel enable “entry at one end, exit at the other”? (tunnel mechanism)
3. How does the inhibitor FK866 “jam” the tunnel? (drug design)

These questions have been addressed by structures such as 2GVG (human NAMPT + FK866, 2006) and 2H3D (mouse NAMPT + NMN, 2006).

---

## 2. Structural anatomy of NAMPT

### 2.1 Dimer and tunnel

- NAMPT is a **homodimer** (two ~55-kDa subunits); dimerization is required for activity (monomers are inactive).
- The two subunits assemble “head to head,” forming **one continuous tunnel at their interface** (~30–40 Å long).
- The tunnel wall contains conserved residues. One end is the nicotinamide-binding site and the other is the PRPP-binding site—“nicotinamide in, NMN out,” a one-way assembly line.
- **Why tunnel catalysis matters**: the tunnel “confines” substrates to the correct reaction position, making it less likely for intermediates to escape—“a closed assembly line improves efficiency and fidelity.”

### 2.2 Anatomy of the catalytic site

- **Nicotinamide subpocket**: recognizes the nicotinamide ring (aromatic-residue π-stacking + hydrogen bonds); the Asp219 carboxyl group makes a key contact with the nicotinamide amide group.
- **PRPP-binding region**: binds phosphoribosyl pyrophosphate (PRPP), positioning its phosphoribose moiety toward the nicotinamide N atom.
- **Reaction center**: N-ribosylation of nicotinamide (the nicotinamide N atom attacks C1′ of PRPP’s ribose) → NMN forms and pyrophosphate (PPi) is released.
- **Key residues**: Asp219 (substrate selectivity), His247 and others (general acid-base catalysis)—“Asp219 is the molecular ruler: only nicotinamide gets in.”

### 2.3 Inhibitor binding (FK866)

- **FK866** (a potent NAMPT inhibitor, in the nanomolar range) binds **inside the tunnel at the dimer interface**, near the nicotinamide-binding site.
- **Binding mode**: the amide portion of FK866 mimics nicotinamide, while its long-chain portion extends through the tunnel—“it occupies the nicotinamide site and blocks the tunnel.”
- **Mutational validation**: mutations of residues within the tunnel abolish FK866 inhibition—“the inhibitor and substrate compete for the same tunnel.”
- **Cancer applications**: FK866 lowers NAD⁺ and can kill tumor cells through NAD⁺ depletion—“shut down the regeneration engine to starve rapidly proliferating tumors.”

---

## 3. Catalytic mechanism: from structure to chemistry

### 3.00 The “recycling plant” assembly line: why a tunnel is necessary

The previous section described NAMPT’s tunnel structure. Here we explore why a tunnel is necessary. Imagine a recycling plant: nicotinamide is “waste,” PRPP is “new raw material,” and NMN is a “semi-finished product.” If the molecules were allowed to collide freely in solution, the reaction could still happen, but with very low efficiency and many by-products. NAMPT’s tunnel solves three problems:

**Problem one: how do the substrates “line up”?** The ring nitrogen of nicotinamide must attack C1′ of PRPP’s ribose precisely (within 2–3 Å), while nicotinamide’s amide group must be recognized by Asp219 (ensuring that only nicotinamide is recycled). In solution, the two substrates wander randomly and the probability of alignment is very low. The tunnel **forces both into the same space**: nicotinamide enters one end and is held in its subpocket; PRPP enters the other and is held in its binding region—**“clamp both ends and the reaction site naturally aligns.”** This captures the essence of enzyme catalysis: not simply speeding up a reaction, but **confining reactants together and positioning them correctly**.

**Problem two: how do intermediates avoid “escaping”?** If reaction intermediates (such as oxonium or phosphate intermediates) escape into solution, water molecules may “steal” them (hydrolysis), producing by-products. The tunnel is a **closed channel**: the wall physically constrains intermediates, allowing them to move only toward the product end—“the assembly line is enclosed, so semi-finished products cannot fall off.” This is one reason “tunnel enzymes” can be more efficient than “open” enzymes.

**Problem three: how does the product avoid “flowing backward”?** The tunnel is **unidirectional**: nicotinamide goes in and NMN comes out. Directionality is determined by the distribution of residues lining the tunnel (the nicotinamide-binding site is at the entrance, while the exit site for NMN favors the phosphate group)—“the assembly line runs one way; semi-finished products do not flow back to be dismantled and remade.”

**The broader “tunnel principle”**: NAMPT is not the only enzyme that uses a tunnel. PARP1 ([09-parp1-structure.md](09-parp1-structure.md)) uses its NAD⁺ pocket to “clamp” its substrate; DNMT1 ([07-dnmt1-structure.md](07-dnmt1-structure.md)) uses a substrate tunnel to “measure” an acetyl group; TET ([05-tet-dna.md](05-tet-dna.md)) uses a base-flipping cavity to “lock in” 5mC. **“Confine the substrate, position it correctly, control its direction” are three broadly used strategies of enzyme catalysis.** Structural biology lets us “see” how these strategies are implemented atom by atom.

### 3.0 Atom by atom: how nicotinamide is “recycled”

Nicotinamide (NAM) is a form of vitamin B3 and a common product when CD38/PARP1/SIRT1 consume NAD⁺. NAMPT’s task is to attach phosphoribose to nicotinamide, converting it into NMN—the key step in “waste reuse.”

**Step 1: nicotinamide “enters.”** Nicotinamide enters through one end of the dimer tunnel and is “caught” by the nicotinamide subpocket: aromatic residues π-stack with its ring, and the Asp219 carboxyl group hydrogen-bonds with its amide group—**precisely positioning nicotinamide at the reaction site**. Why doesn’t NAMPT recognize nicotinic acid (a carboxyl analog of NAM)? Because Asp219’s carboxyl group complements nicotinamide’s amide group; substituting nicotinic acid’s carboxyl group would create like-charge repulsion—**“Asp219 is a molecular ruler that selects by both shape and charge.”**

**Step 2: PRPP “supplies the material.”** PRPP (phosphoribosyl pyrophosphate) enters from the other end of the tunnel, with its ribose C1′ aligned toward the nicotinamide ring nitrogen (N). PRPP’s pyrophosphate group (PPi) is the “leaving group”: its negative charge “pushes away” from the ribose, making C1′ electrophilic.

**Step 3: N-glycosylation.** The nicotinamide ring nitrogen (N) nucleophilically attacks ribose C1′ → an N-glycosidic bond forms → **NMN is generated and pyrophosphate is released**. NMN exits at the other end of the tunnel—“nicotinamide goes in; NMN comes out.”

**Step 4 (downstream): NMNAT takes over.** NMN is accepted by NMNAT (nicotinamide mononucleotide adenylyltransferase), which adds AMP (from ATP) → **NAD⁺ is generated**. The recycling loop is now closed: NAD⁺ consumed by CD38/PARP1 becomes nicotinamide, and NAMPT + NMNAT convert that nicotinamide back into NAD⁺.

**Regulatory implications of the “recirculation pump”**: NAMPT is rate-limiting (Km for nicotinamide in the ~μM range). As nicotinamide concentration rises, the pump speeds up (negative-feedback compensation), but high nicotinamide also inhibits SIRT1 (see [06-sirt1-structure.md](06-sirt1-structure.md))—**“faster recycling means more NAD⁺, but nicotinamide’s inhibitory effect also grows, requiring a finely tuned balance.”**

### 3.1 The molecular ruler for substrate selectivity

```text
Nicotinamide (NAM): ring N + C3 amide (-CONH₂)       → recognized by NAMPT ✓
Nicotinic acid (NA): ring N + C3 carboxyl (-COOH)    → rejected (charge repulsion) ✗
NMN: nicotinamide + ribose-phosphate                    → product; does not re-enter ✗
```

- **Asp219 is key to selectivity**: mutation of Asp219 (e.g., D219A) causes NAMPT to lose specificity for nicotinamide (and accept nicotinic acid)—“replace the molecular ruler and the substrate range broadens.”
- **Biological significance**: selectivity ensures the salvage pathway recycles the correct raw material and avoids accumulation of incorrect products—“molecular-ruler calibration safeguards metabolic-pathway fidelity.”
- **Comparison with DNMT1’s “molecular ruler”** ([07-dnmt1-structure.md](07-dnmt1-structure.md)): DNMT1’s tunnel “measures” acetyl-chain length, while NAMPT’s subpocket “measures” nicotinamide’s charge—“different enzymes, same design principle.”

---

## 4. NAMPT and the “four-part loop” of the NAD⁺ economy

Together with [06-sirt1-structure.md](06-sirt1-structure.md), [08-cd38-structure.md](08-cd38-structure.md), and [09-parp1-structure.md](09-parp1-structure.md), NAMPT completes the NAD⁺ economy loop:

```text
[Regeneration side] NAMPT (rate-limiting) + NMNAT ──► NAD⁺ pool
                              ▲                         │
Nicotinamide ◄────────────────┴──────── CD38/PARP1 consumption (releases nicotinamide)
                              ▲                         │
                              └──────── SIRT1 utilization (releases nicotinamide + OAADPr)
                                         │
                              NMN/NR supplementation (exogenous precursors; bypass NAMPT)
```

- **Core of the loop**: NAMPT “recycles” nicotinamide released by the consumption side, helping maintain the pool—“a race between the pump and the funnels.”
- **Imbalance with aging**: CD38/PARP1 consumption ↑ (funnels widen) + NAMPT activity ↓ (pump slows) → pool depletion—“pressure from both ends.”
- **What NMN/NR supplementation does**: exogenous NMN/NR enters directly at the NMNAT step, bypassing NAMPT—“bypass the slowing pump and pour water directly in” (provided transporter efficiency is adequate).
- **Four intervention levers**: ① activate NAMPT (speed up the pump); ② inhibit CD38 (plug the funnel); ③ reduce DNA damage (less PARP1 activity); ④ supplement NMN/NR (add water from outside)—“the NAD⁺ economy runs well only when all four are addressed.”

### 4.01 The pump-funnel dynamic balance: why NMN works differently in different older adults

The four-part loop seems simple, but why does NMN help some people while producing only modest effects in others? A structural perspective offers several possible answers:

**Variable one: funnel size (CD38/PARP1 activity).** If CD38 is highly expressed (chronic inflammation, immunosenescence) or PARP1 is frequently activated (high DNA damage), supplemented NMN → NAD⁺ may be consumed rapidly—“the rate of pouring cannot keep up with the leak.” This helps explain why **controlling inflammation/reducing damage before supplementing NMN may work better** (“plug the funnel before pouring in water”).

**Variable two: transport efficiency (NMN entry into cells).** NMN is a charged small molecule (it has a phosphate group), and whether it can efficiently enter cells remains controversial (including whether a transporter is needed). If transport is inefficient, the “actual utilization” of oral NMN may be limited—“the water is poured into the funnel, but the pipe is narrow, so it flows in slowly.”

**Variable three: NAMPT’s own state.** If NAMPT activity remains adequate, nicotinamide supplementation (NR/NAM) may be sufficient, since NAMPT converts nicotinamide into NMN. If NAMPT has declined substantially, direct NMN supplementation may be more effective because it bypasses the rate-limiting enzyme—“if the pump is slow, bypass it; if it works well, supply it with raw material.”

**Variable four: tissue differences.** NAD⁺ pools differ in their degree of independence across tissues (the liver has strong synthesis capacity, while brain/muscle rely more on salvage)—“whether the supplement reaches a key tissue determines its effect.”

**Structural logic of “personalized NAD⁺ support”**: the ideal approach is to measure first (NAMPT activity, CD38 levels, inflammatory state), then determine the priority combination of “repair the pump, plug the funnel, add water, or reduce damage”—“same molecule, different people, different strategies” (echoing the personalized-roadmap logic in [09-immortality/04-roadmap.md](../09-immortality/04-roadmap.md)). **Structural biology can make “individual differences” measurable through molecular indicators rather than mere intuition**—a key step in applying precision medicine to healthy aging.

---

## 5. NAMPT and aging: “pump failure” from a structural perspective

### 5.1 Mechanisms of age-related decline

- **Declining expression**: NAMPT expression declines with age in tissues such as fat, muscle, and brain (epigenetic silencing/transcriptional downregulation).
- **Circadian-clock coupling**: NAMPT expression is regulated by CLOCK/BMAL1 (the NAMPT promoter contains an E-box)—circadian disruption (common with aging) → disrupted NAMPT rhythms → weaker NAD⁺ oscillations (see [07-interventions/05-sleep-optimization.md](../07-interventions/05-sleep-optimization.md)).
- **Activity regulation**: NAMPT activity is affected by nicotinamide concentration (substrate activation/product inhibition), oxidative modifications (Cys oxidation), and other factors—“the pump’s condition worsens with aging.”

### 5.2 Consequences of “pump failure”

- **Smaller NAD⁺ pool**: inadequate recycling + ongoing consumption → NAD⁺ declines (in older tissues, levels may fall to 50% of those in youth).
- **SIRT1 is starved**: insufficient NAD⁺ → reduced SIRT1 activity → less deacetylation → metabolic/mitochondrial/inflammatory dysregulation (“aging of the regeneration side drags down the utilization side”).
- **Mitochondrial impact**: NAD⁺ is a mitochondrial redox carrier—declining NAD⁺ → impaired mitochondrial energy metabolism (“the pool runs dry and the energy supply is cut off”).
- **Vicious cycle**: SIRT1 declines → mitochondrial function ↓ → oxidative stress ↑ → oxidative damage to NAMPT → the pump slows further—a “pump failure–pool depletion–worsening damage” death spiral.

### 5.3 Anti-aging implications from a structural perspective

- **“Repair the pump” and “add water”**: NAMPT activators (such as P7C3-like compounds and some natural products) raise NAD⁺ in animals—a “repair the pump” strategy. NMN/NR supplementation is an “add water” strategy; the two may be combined.
- **Circadian rhythm**: the rhythmicity of NAMPT suggests that the timing of NAD⁺ supplementation may matter (in coordination with the body clock)—“when to supplement may matter as much as how much.”
- **Tissue specificity**: NAMPT differs substantially among tissues (brain, muscle, and fat are important)—“whole-body NMN supplementation may be less effective than targeting key tissues.”
- **Measure first**: NAMPT activity/expression can be measured in blood/tissue—“first assess the pump’s condition, then decide whether to repair it or add water.”

---

## 6. Evidence grading

| Structural claim | Evidence level | Basis |
|---|---|---|
| NAMPT is a type II phosphoribosyltransferase (dimer) | ★★★★★ Established | 2GVG/2H3D (2006) |
| The dimer interface forms a substrate tunnel | ★★★★★ Established | Crystal structures |
| Asp219 determines nicotinamide specificity | ★★★★★ Established | Mutational validation (2GVG) |
| Catalysis: NAM + PRPP → NMN + PPi | ★★★★★ Established | Biochemistry |
| FK866 binds in the tunnel and inhibits NAMPT | ★★★★★ Established | 2GVG + mutations |
| NAMPT is rate-limiting in the salvage pathway | ★★★★★ Established | Biochemistry + genetics |
| NAMPT expression declines with age | ★★★★ Strong | Studies across multiple tissues |
| NAMPT is regulated by the circadian clock (E-box) | ★★★★★ Established | Molecular biology |
| NAMPT activators raise NAD⁺ (in animals) | ★★★★ Strong | Animal studies |
| Anti-aging efficacy of NAMPT in humans | ★★ Preliminary | Early clinical evidence |

---

## 7. Connections to the knowledge base’s central themes

### 7.0 Four-part overview of the “NAD⁺ economy”: pump, funnels, user, and external supply

The four structural foundations of the NAD⁺ economy are now in place:

| Role | Protein | PDB anchor | Article | Aging trend |
|---|---|---|---|---|
| Regeneration pump | NAMPT (+NMNAT) | 2GVG/2H3D | [10-NAMPT](10-nampt-structure.md) | Pump slows ↓ |
| Continuous funnel | CD38 | 3DZF | [08-CD38](08-cd38-structure.md) | Funnel widens ↑ |
| Burst funnel | PARP1 | 4DQY | [09-PARP1](09-parp1-structure.md) | Damage triggers ↑ |
| User | SIRT1 | 4I5I/4ZZJ | [06-SIRT1](06-sirt1-structure.md) | Starved ↓ |
| Exogenous precursors | NMN/NR | — | [04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md) | Supplementation strategy |

**“Balance among the four ends” is the essence of NAD⁺ homeostasis**: fast pump, small funnels, little damage, and a well-fed user = health; slow pump, large funnels, extensive damage, and a starved user = aging. **Every anti-aging intervention—NMN, CD38 inhibitors, NAMPT activators, antioxidants—adjusts one of these four variables.** Structural insight upgrades NAD⁺-related healthy aging from “supplement one molecule” to “regulate a system.”

### 7.1 Dialogue with the core articles

- **NAD⁺/SIRT1 network** ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md)): this article fills in the “regeneration side”—NAMPT is rate-limiting in the salvage pathway, completing the loop with SIRT1 (utilization) and CD38/PARP1 (consumption).
- **SIRT1 structure** ([06-sirt1-structure.md](06-sirt1-structure.md)): NAMPT’s synthesis of NMN → NAD⁺ is upstream in SIRT1’s “food chain”—“if the pump stops, SIRT1 goes hungry.”
- **CD38 structure** ([08-cd38-structure.md](08-cd38-structure.md)): nicotinamide released by CD38 is recycled by NAMPT—“the pump retrieves the water that leaks through the funnel.” Their combined activity determines the NAD⁺ pool.
- **PARP1 structure** ([09-parp1-structure.md](09-parp1-structure.md)): PARP1 consumes NAD⁺ in bursts during damage, beyond NAMPT’s ability to keep up—“a race between a flood and a pump.”
- **Sleep** ([07-interventions/05-sleep-optimization.md](../07-interventions/05-sleep-optimization.md)): NAMPT is regulated by the circadian clock—“sleep well, and the pump works well.”
- **Supplements** ([07-interventions/04-supplements.md](../07-interventions/04-supplements.md)): NMN/NR supplementation bypasses NAMPT by providing NMN directly—the “bypass the slow pump and add water” strategy and its limitations.

### 7.2 Why the “four-part loop” is the ultimate framework for understanding NAD⁺ and healthy aging

One common misconception in the NAD⁺ healthy-aging field is that “NMN supplementation is all you need.” A structural perspective decisively challenges this: **NAD⁺ is not a stagnant pool, but a dynamic pool with inflows and outflows.**

**The pool’s four valves**: inlet (synthesis by NAMPT + NMNAT), outlet one (ongoing consumption by CD38), outlet two (damage-induced consumption by PARP1), and the user (consumption/signaling by SIRT1). **Any single intervention changes only one valve; if all the others remain unchanged, the effect on the pool level is limited.** NMN supplementation increases the inflow, but CD38/PARP1 outflow continues, limiting the net increase.

**“Coordinated valves” are the essence of systems thinking**: the ideal approach increases inflow, reduces outflow, and improves utilization efficiency at the same time—NMN supplementation (inflow) + CD38 inhibition (close outlet one) + reduced DNA damage (close outlet two) + regular circadian rhythms (preserve NAMPT rhythms) = a substantial rise in pool level (NAD⁺) and adequate substrate for SIRT1.

**The layered value of structural knowledge**: one structure article tells us how an enzyme works; reading four together shows us how the system runs. **From articles 06 to 10 (SIRT1 → DNMT1 → CD38 → PARP1 → NAMPT), the 10-structures series builds not just portraits of ten molecules, but a structural map of a core aging-related metabolic network.** This map is the scientific basis for “personalized NAD⁺ healthy-aging strategies” (measure valve status first, then choose intervention combinations).

---

## 8. Five structural questions about aging

| Question | Structural answer |
|---|---|
| Why is NAMPT rate-limiting? | It is a bottleneck in the salvage pathway (high Km; regulated by nicotinamide)—“the pump’s speed determines the water level.” |
| How does NAMPT recognize only nicotinamide? | Asp219 is a molecular ruler, selecting by both charge and shape. |
| How does FK866 inhibit NAMPT? | It enters the dimer tunnel, occupying the nicotinamide site and blocking the tunnel—“take the seat and block the road.” |
| Why can NAD⁺ not be replenished as well during aging? | The pump (NAMPT) slows while the funnels (CD38/PARP1) widen—pressure from both ends. |
| Why can NMN supplementation work? | It bypasses NAMPT and enters directly at NMNAT—“bypass the slow pump and add water from outside” (transporter-dependent). |

**Structural intuition beyond these five questions**: NAMPT also illustrates the “flexible design” of metabolic pathways—when one route (salvage) slows, cells have other options (exogenous NMN, de novo synthesis, or an NR bypass). **Redundancy among metabolic pathways is a “spare tire” for coping with aging.** This also explains why NMN/NR supplementation may be “useful but limited”: it can bypass NAMPT, but not CD38-mediated consumption or transporter bottlenecks. **“Understand redundancy to make good use of it.”** Structural biology reveals the interfaces of each backup route (transporters, enzymes, feedback), helping supplementation strategies move from “blind trial” toward precision. **The closing question of this series: the endpoint of molecular-structure research is to help everyone “see” the otherwise invisible valves and pipes in the body.**

---

## 9. Open questions

1. **NAMPT’s cytokine function**: how does secreted NAMPT (eNAMPT) function extracellularly as PBEF/visfatin (receptor?)—the molecular mechanism behind “enzyme activity vs. hormone.”
2. **NAMPT post-translational modifications**: effects of phosphorylation/oxidative modifications on activity and dimerization (not fully resolved structurally).
3. **Inter-tissue “NAD⁺ communication”**: does eNAMPT in the hypothalamus-adipose axis truly contribute to whole-body NAD⁺ regulation (Imai’s hypothesis)?
4. **Specificity of NAMPT activators**: how do compounds such as P7C3 avoid off-target effects on other phosphoribosyltransferases?
5. **Quantifying circadian coupling**: the relationship between NAMPT rhythm amplitude and NAD⁺ oscillation (and how much it weakens with age).
6. **The NMN-transporter controversy**: does NMN truly require a transporter (Slc12a8?) to enter cells—the structural/biochemical evidence for whether the “water pipe” is open.

### 9.1 From “molecular structure” to “systems medicine”: methodological lessons from NAMPT

Article 10 on NAMPT closes the “four-piece NAD⁺ economy” set (SIRT1/CD38/PARP1/NAMPT). Looking back across these four articles, a clear methodology emerges: **how can structural biology help us move from “one molecule” to “one system”?**

**Step one: characterize the “personality” of each molecule.** PDB structures show what each enzyme looks like (fold), how it works (catalytic mechanism), and how it is regulated (allostery, autoinhibition, product feedback)—the Zn²⁺ zinc finger of SIRT1, the Glu226 covalent intermediate of CD38, PARP1’s three-zinc-finger sensor, and NAMPT’s tunnel assembly line.

**Step two: establish the network of relationships among molecules.** Structures describe not only individual molecules but also how they “interact”: NAMPT’s product (NMN) is a source of substrate for SIRT1; CD38’s product (nicotinamide) is NAMPT’s raw material; and PARP1 consumption races against NAMPT regeneration. **“Every molecule’s active site is an interface for conversation with other molecules.”**

**Step three: move from the “network” to “system-level intervention.”** Once the four ends of the NAD⁺ economy are understood, healthy-aging interventions are no longer blind attempts to “supplement one molecule,” but rational designs for “regulating a system”—choosing combinations to repair the pump, plug the funnels, add water, and reduce damage according to the individual’s pump/funnel/user status. **“Structural knowledge moves healthy aging from empiricism toward systems engineering.”** This is the enduring value of the entire 10-structures series, from [01-NOS](01-nos-structures.md) to [10-NAMPT](10-nampt-structure.md).

---

## 10. Guide to obtaining structural data

- **PDB entries**:
  - 2GVG: human NAMPT + FK866 (2.20 Å, Khan 2006 *Nat Struct Mol Biol*)—inhibitor binding and substrate selectivity.
  - 2GVJ/2GVL: human NAMPT variants/different ligands (same study series).
  - 2H3B/2H3D: mouse NAMPT ± NMN (2.10 Å, Wang 2006 *Nat Struct Mol Biol*)—product-bound state.
  - Later structures: high-resolution human NAMPT structures (e.g., 4NST).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX, AlphaFold prediction (AF-P43490).

---

## 11. References (published sources)

1. Khan JA, Tao X, Tong L. Molecular basis for the inhibition of human NMPRTase, a novel target for anticancer agents. *Nat Struct Mol Biol* 2006;13:582-588. (PDB 2GVG)
2. Wang T, Zhang X, Bheda P, et al. Structure of Nampt/PBEF/visfatin, a mammalian NAD⁺ biosynthetic enzyme. *Nat Struct Mol Biol* 2006;13:661-662. (PDB 2H3D)
3. Revollo JR, Grimm AA, Imai S. The NAD⁺ biosynthesis pathway mediated by nicotinamide phosphoribosyltransferase regulates Sir2 activity in mammalian cells. *J Biol Chem* 2004;279:50754-50763. (NAMPT regulation of SIRT1)
4. Yoshino J, Mills KF, Yoon MJ, Imai S. Nicotinamide mononucleotide, a key NAD⁺ intermediate, treats the pathophysiology of diet- and age-induced diabetes in mice. *Cell Metab* 2011;14:528-536. (NMN in animals)
5. Imai S. “Clocks” in the NAD⁺ world: NAD⁺ as an oscillating system. *Nat Rev Mol Cell Biol* 2016;17:421-433. (NAD⁺ rhythms)
6. Covarrubias AJ, Perrone R, Grozio A, Verdin E. NAD⁺ metabolism and its roles in cellular processes during ageing. *Nat Rev Mol Cell Biol* 2021;22:119-141. (NAD⁺ metabolism review)
7. Grozio A, Sociali G, Sturla L, et al. CD73 protein as a source of extracellular precursors for sustained NAD⁺ biosynthesis in FK866-treated tumor cells. *J Biol Chem* 2013;288:25938-25949. (Compensatory pathways during NAMPT inhibition)

---

> **Structural summary**: NAMPT = homodimer + substrate tunnel at the interface (nicotinamide in, NMN out) + Asp219 molecular ruler (recognizes nicotinamide only). **It is the rate-limiting pump of the NAD⁺ salvage pathway**—CD38/PARP1/SIRT1 consume NAD⁺ and release nicotinamide; NAMPT recycles nicotinamide into NMN → NAD⁺. **With aging, the pump slows (NAMPT ↓) while the funnels widen (CD38 ↑/PARP1 damage ↑) → the pool is depleted → SIRT1 is starved.** The “four-part loop” (pump/funnels/user/external supply) is a systems-level way to understand NAD⁺ and healthy aging.
