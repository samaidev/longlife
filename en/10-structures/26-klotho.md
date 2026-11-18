# Molecular Structure Deep Dive 26: Klotho—the “Longevity Protein” and Molecular Scaffold for FGF23 Signaling

> **Series context**: Article 26 in 10-structures (Molecular Structure Deep Dive): the three-dimensional structure of Klotho (α-Klotho), including how Klotho serves as the “molecular scaffold” for FGF23 signaling, how its two glycosidase-like domains (KL1/KL2) work together, and its role as a “longevity protein” in aging. This provides a structural foundation for the knowledge base’s aging-mechanism thread ([01-aging-hallmarks](../01-foundations/01-aging-hallmarks.md)). Alongside FOXO3 ([16-foxo3-structure.md]), Klotho is a “longevity factor,” and it connects with the metabolic-regulation theme of the insulin receptor ([21-insulin-receptor.md]).
> **Related articles**: Aging hallmarks: [01-aging-hallmarks](../01-foundations/01-aging-hallmarks.md); FOXO3: [16-foxo3-structure.md](16-foxo3-structure.md); insulin receptor: [21-insulin-receptor.md](21-insulin-receptor.md); metabolic aging: [03-metabolic-aging](../02-vascular/03-metabolic-aging.md); vascular calcification: [05-vascular-calcification](../02-vascular/05-vascular-calcification.md).

---

## 0. Structural overview

**In one sentence**: Klotho is a “longevity protein”—a transmembrane protein whose extracellular region comprises two glycosidase-like domains (KL1/KL2). It acts as a “molecular scaffold” (a nonenzymatic coreceptor) for FGF23 signaling and also participates in aging regulation as a soluble hormone: a “longevity sentinel” on the cell surface that bridges phosphate metabolism and aging.

```text
α-Klotho structure:
  KL1 domain (glycosidase-like, ~516 aa) — KL2 domain (glycosidase-like, ~439 aa) — transmembrane segment — short intracellular tail (9 aa)
                  │
  Membrane-bound: KL1/KL2 fold into a “horseshoe-shaped” scaffold → bind FGFR1c + FGF23 → ternary complex
                  │
  Function: ① FGF23 signaling coreceptor (phosphate-metabolism regulation) ② soluble Klotho (released by cleavage) → hormone-like effects
                  │
  Aging: Klotho expression declines with age → disrupted phosphate metabolism/vascular calcification/accelerated aging
         Klotho overexpression → longer lifespan in model organisms
```

**Three major structural features** (the atomic basis of its function):
1. **KL1/KL2 tandem glycosidase-like domains**: homologous to β-glucosidases (~20–40% sequence similarity), but their **enzymatic active sites are inactive**—“enzyme-like in shape, without enzyme activity; it serves only as a scaffold”;
2. **“Horseshoe-shaped” scaffold**: KL1/KL2 fold into an open horseshoe that captures FGF23—“the scaffold welds the three partners of the signal together”;
3. **FGF23-binding interface**: the C-terminus of FGF23 binds at the KL1/KL2 interface—“FGF23’s ‘hand’ grips the scaffold.”

**Core regulatory mechanism**:

```text
Membrane Klotho + FGFR1c → FGF23 binding (1:1:1 ternary complex) → signal activation
    → phosphate-metabolism regulation (urinary phosphate excretion ↑ / vitamin D ↓) → phosphate homeostasis
        │
Soluble Klotho (cleaved by ADAM10/17) → circulating hormone
    → suppresses aging signals (insulin/IGF-1 ↓, antioxidant activity ↑) → protects blood vessels/kidneys/brain
        │
Aging: Klotho ↓ → phosphate ↑ / vascular calcification / FGF23 resistance → accelerated aging
     Klotho ↑ (overexpression/induction) → longer lifespan (in model organisms)
```

---

## 1. Why Klotho’s structure matters

Klotho is a “star gene” in anti-aging research:

- **“Longevity protein”**: Klotho overexpression extends mouse lifespan (~20–30%); Klotho deficiency → accelerated aging (a progeria-like phenotype)—a “leading contender among longevity genes”;
- **Bridge between phosphate metabolism and aging**: Klotho is an FGF23 coreceptor and regulates phosphate excretion—“disrupted phosphate metabolism is an accelerator of aging” (vascular calcification/renal failure);
- **Anti-aging evidence**: Klotho levels decline with age; overexpression improves cognition and vascular and kidney function—“higher longevity-protein levels, slower aging”;
- **Soluble Klotho**: circulating Klotho released by cleavage acts like a hormone and promotes longevity (inhibits IGF-1 signaling/has antioxidant effects)—“the longevity protein can also work remotely”;
- **Crosstalk with FOXO3/IGF-1**: Klotho inhibits insulin/IGF-1 signaling (synergizing with FOXO3 activation)—a member of the “longevity-signaling network” (see [16-foxo3-structure.md](16-foxo3-structure.md)/[21-insulin-receptor.md](21-insulin-receptor.md));
- **Disease links**: chronic kidney disease (Klotho ↓) → vascular calcification/bone disease; diabetes/hypertension → Klotho ↓—“Klotho protects the metabolism–vasculature–kidney axis.”

**Three key questions for structural research**:
1. How does Klotho “capture” FGF23-FGFR1c (assembly of the ternary complex)?
2. Why do KL1/KL2 have an “enzyme-like shape but no enzyme activity” (evolution of their scaffold function)?
3. What structural differences distinguish membrane-bound from soluble forms (functional division of labor)?

These questions were answered by structures such as 5W21 (αKlotho-FGF23-FGFR1c, 2018).

---

## 2. Structural anatomy of Klotho

### 2.1 KL1/KL2 tandem domains—the “two arms of the scaffold”

- **Location**: extracellular region (KL1 ~516 aa + KL2 ~439 aa);
- **Structure**: two glycosidase-like domains (TIM-barrel folds, homologous to β-glucosidases)—“it looks like an enzyme, but is not one”;
- **Loss of enzymatic activity**: mutations of catalytic residues in KL1/KL2 (lost during evolution) → no glycosidase activity—“the tool changed its purpose: from ‘scissors’ to ‘scaffold’”;
- **Finding from 5W21**: KL1/KL2 fold into an “open horseshoe,” creating a central groove that accommodates FGF23—“the two arms open to embrace FGF23”;
- **Glycosylation**: KL1/KL2 contain multiple N-glycosylation sites → stabilize the structure and affect binding—“reinforcement for the scaffold.”

### 2.2 FGF23-binding interface—the “handle for the signal”

- **FGF23**: fibroblast growth factor 23 (a phosphate-regulating hormone secreted by bone)—the “remote control” for phosphate metabolism;
- **Binding**: the C-terminus of FGF23 binds the KL1/KL2 interface (a 1:1:1 ternary complex in 5W21)—“FGF23’s ‘hand’ grips the Klotho scaffold”;
- **Binding to FGFR1c**: the Klotho scaffold also contacts FGFR1c (domains D2/D3) → forms the FGF23-Klotho-FGFR1c ternary complex—“the scaffold welds the three partners of the signal together”;
- **Specificity**: Klotho selects FGFR1c (rather than other FGFRs) → tissue-specific signaling—“the scaffold fits only a particular receptor.”

### 2.3 Membrane-bound vs. soluble forms—“two modes of operation”

- **Membrane-bound**: KL1/KL2 are anchored in the membrane → local signaling (FGF23 signaling in kidney/parathyroid)—a “fixed outpost”;
- **Soluble**: ADAM10/17 cleave the extracellular domain → circulating Klotho → systemic hormone-like effects—a “mobile sentinel”;
- **Division of labor**: membrane Klotho handles FGF23/phosphate metabolism; soluble Klotho inhibits IGF-1/Wnt and promotes antioxidant activity—“the fixed outpost manages phosphate; the mobile sentinel manages longevity.”

---

## 3. Molecular logic of the “molecular scaffold”: from structure to chemistry

### 3.00 Engineering ingenuity of the “horseshoe-shaped scaffold”: why Klotho has “two arms held open”

The previous section introduced the nonenzymatic scaffold. Here we examine **how KL1/KL2 fold into a horseshoe and why this shape is suited to a scaffold**—a classic case of shape determining function:

**“The tandem arrangement of TIM barrels.”** KL1 and KL2 are each TIM-barrel (β/α-barrel) folds, characteristic of the glycosidase family. The two barrels are arranged “head to tail,” forming an “open horseshoe” (U shape)—“two cylinders joined to make a U-shaped clamp”—“the angle between the barrels determines how wide the clamp opens.”

**“A U shape is naturally suited for gripping.”** The opening of the U accommodates FGF23 (a “long, slender” growth factor of ~170 aa). The C-terminus of FGF23 extends into the U-shaped groove and contacts both KL1 and KL2 at the same time—“the clamp grips FGF23 around its ‘waist’”—“the two walls of the U are ideally positioned to hold FGF23.”

**“Three contact surfaces.”** 5W21 shows that FGF23 contacts Klotho at: ① the hydrophobic surface of KL1 with the FGF23 C-terminus; ② the polar surface of KL2 with the middle of FGF23; and ③ FGFR1c D2/D3 with the FGF23 N-terminus—“three-way contact makes the grip firm”—“not a single point, but a broad surface of contact.”

**“Adjustable opening and closing.”** The Klotho scaffold may undergo conformational dynamics (the width of the U-shaped opening may vary), regulating FGF23 binding and release—“the clamp can fine-tune its tightness”—“the scaffold is not rigid; it is a spring clamp.”

**“Connection to FGFR dimerization.”** The FGF23-Klotho-FGFR1c ternary complex further dimerizes (two ternary complexes face one another) → intracellular FGFR kinases phosphorylate each other → signaling—“two clamps pair up to trigger the signal”—“the scaffold not only holds the three partners together, but also promotes activation by dimerization.”

### 3.0 Atom by atom: why Klotho is a “nonenzymatic scaffold”

A common question is: if Klotho is a “glycosidase-like” protein, why does it have no enzymatic activity? The answer reveals a deep principle of molecular evolution:

**“Evolution from enzyme to scaffold.”** Klotho’s ancestor may have been a glycosidase. Catalytic residues mutated during evolution (and activity was lost), while the “binding surface” was retained, turning it into a “pure scaffold”—“scissors became a clamp: cutting was lost, gripping remained”—an example of molecular exaptation (functional repurposing)—“evolution wastes nothing: unused functions are discarded, useful ones are retained.”

**“Why is ‘enzyme-shaped but inactive’ better?”** ① A scaffold does not need catalysis (only binding), so losing enzyme activity “sheds a burden” (avoiding inappropriate substrate cleavage)—“the scaffold need not do the work; it can focus on holding things together”; ② an enzyme-like fold provides a “stable binding surface” (the hydrophobic surface of the TIM barrel), naturally suited to scaffolding—“the ‘handle’ of an old tool becomes the ‘grip’ of a new one”; ③ the two KL1/KL2 domains provide a “large binding surface” that can hold FGF23 and FGFR1c simultaneously—“two domains mean two grips, welding three partners together.”

**“The scaffold’s welding function.”** FGF23 alone binds FGFR1c weakly (low affinity); Klotho bridges them, stabilizing the ternary complex and enabling signaling—“without the scaffold, FGF23 cannot reach FGFR1c”—**“Klotho is the matchmaker for FGF23 signaling: it brings the two parties together”**—the matchmaker’s value is that, without it, the two parties (FGF23/FGFR1c) would not see one another.

**“Scaffold specificity.”** The “shape” of the Klotho scaffold means it pairs specifically with FGFR1c + FGF23 (not other FGF/FGFR combinations)—“the matchmaker brings together only a particular pair”—“scaffold shape determines selectivity.”

### 3.1 The “FGF23-Klotho phosphate-metabolism axis”: from structure to physiology

The central function of FGF23-Klotho signaling is regulation of phosphate metabolism:

**“The physiology of phosphate.”** Phosphate is essential for life (ATP/DNA/membranes), but excess phosphate → vascular calcification/renal injury/accelerated aging—“phosphate is a double-edged sword: too little is harmful, but too much accelerates aging.”

**“How FGF23-Klotho controls phosphate.”** ① FGF23 (secreted by bone) binds renal Klotho-FGFR1c → inhibits the sodium-phosphate cotransporter NPT2a → urinary phosphate excretion ↑—“the kidneys excrete more phosphate”; ② inhibits synthesis of 1,25-dihydroxyvitamin D → intestinal phosphate absorption ↓—“the gut absorbs less phosphate”; ③ result: blood phosphate ↓ → protects blood vessels/kidneys—“phosphate control = prevention of calcification = protection against aging.”

**“The vicious cycle of phosphate metabolism when Klotho is low.”** Chronic kidney disease → Klotho ↓ → FGF23 resistance → blood phosphate ↑ → vascular calcification → worsening kidney damage → further Klotho ↓—“phosphate cannot be excreted, calcification worsens, the kidneys deteriorate, and the vicious cycle continues.”

**“The phosphate-aging hypothesis.”** Higher blood phosphate (even within the normal range) is associated with aging/cardiovascular disease—“phosphate control is an important part of anti-aging”—Klotho is the hub connecting “phosphate control and protection from aging”—“Klotho is the gatekeeper of phosphate metabolism; guard phosphate, and you guard blood vessels and kidneys.”

### 3.20 Klotho’s many facets: from FGF23 coreceptor to systemic protection

Klotho’s functions extend far beyond being an “FGF23 coreceptor”—the “longevity protein” has multiple effects:

**“Phosphate control/calcification axis.”** FGF23-Klotho → phosphate excretion → prevents vascular calcification ([05-vascular-calcification](../02-vascular/05-vascular-calcification.md))—“guard phosphate, guard blood vessels.”

**“Reconsidering phosphate’s double-edged sword.”** Phosphate is essential (ATP/DNA/membranes), but “phosphate excess” is commonplace in modern diets (phosphate additives in processed foods)—“too much phosphate accelerates calcification.” Klotho is the body’s defense against “phosphate excess”—“the phosphate load of modern diets makes Klotho’s gatekeeping more important.” Controlling phosphate (eating fewer processed foods) may be one of the “most underestimated dietary anti-aging strategies”—“less phosphate means less burden on Klotho; fewer processed foods mean less work for the longevity sentinel.”

**“IGF-1 inhibition.”** Soluble Klotho inhibits insulin/IGF-1 signaling (by receptor binding/downregulation) → mimics the longevity effects of reduced IIS (see [21-insulin-receptor.md](21-insulin-receptor.md)/[16-foxo3-structure.md](16-foxo3-structure.md))—“the longevity protein suppresses growth signals and switches on survival programs; this is one of Klotho’s core longevity mechanisms.”

**“Antioxidant activity.”** Soluble Klotho upregulates antioxidant enzymes (e.g., SOD2) → lowers oxidative stress—“the longevity protein is also an antioxidant” (see [15-nrf2-structure.md](15-nrf2-structure.md)).

**“Wnt inhibition.”** Klotho inhibits Wnt signaling → maintains stem cells/prevents fibrosis—“the longevity protein protects stem cells” (see [07-stem-cell-exhaustion](../01-foundations/07-stem-cell-exhaustion.md)).

**“Ion-channel regulation.”** Klotho regulates TRPV5/TRPV6 (calcium channels) → calcium metabolism—“the longevity protein also manages calcium.”

**“Structural basis of its multiple roles.”** The surfaces of soluble Klotho’s KL1/KL2 domains may contain multiple “binding sites” (different partners use different surfaces)—“one scaffold, multiple attachment points”—“the many facets of the longevity protein arise from one scaffold serving multiple purposes.”

**“Scaffold attachment points and anti-aging interventions.”** If KL1/KL2 surfaces contain an “IGF-1 inhibition site” and an “antioxidant site” (hypothetically), modulators could be designed to “selectively enhance specific functions”—“strengthen IGF inhibition without strengthening phosphate control”—“selectively exploit the scaffold’s versatility.” This depends on precise mapping between structure and function—“we must know what each attachment point does before we can intervene precisely.”

**“Klotho’s crosstalk with insulin signaling.”** Klotho inhibits IGF-1 signaling ([21-insulin-receptor.md]) and directly engages the “main entry point of metabolism”—“the longevity protein puts the brakes on metabolism’s main gateway.” Reduced IIS → FOXO3 activation ([16-foxo3-structure.md]) → survival program—“Klotho is an upstream brake on the IIS pathway.” Understanding Klotho’s scaffold structure helps us understand “how to apply the IIS brake gently”—“structural knowledge offers targets for gently suppressing IIS.”

**“Anti-aging implications.”** Klotho provides “multi-target protection” (phosphate/IGF-1/oxidation/Wnt/calcium), so boosting Klotho is like “combating aging through multiple pathways”—“one protein, multiple lines of defense.” This helps explain why Klotho is a research hotspot—“pleiotropy means efficacy: one stands guard against many.”

---

## 4. Klotho and aging: a structural view of the “aging longevity sentinel”

### 4.1 Klotho declines with age

- **Reduced expression**: Klotho expression in kidney/brain/blood vessels declines with age—“the longevity sentinels are being lost”;
- **Decline of soluble form**: circulating Klotho declines with age (kidney injury/epigenetic silencing)—“fewer mobile sentinels”;
- **Consequences**: phosphate ↑/FGF23 resistance/vascular calcification/oxidation ↑/IGF-1 signaling ↑ → accelerated aging—“once the sentinels fail, phosphate and calcification advance unchecked.”

### 4.2 Anti-aging strategies to “repair the sentinels”

- **Induce Klotho**: exercise (acute exercise ↑ circulating Klotho)/vitamin D regulation/some drugs—“recruit sentinels”;
- **Supplement Klotho**: recombinant Klotho (improves cognition/vascular function in animal studies)—“airdrop sentinels”;
- **Control dietary phosphate**: low-phosphate diet/phosphate binders → reduce FGF23 pressure → protect Klotho—“keep the sentinels from working overtime”;
- **Protect the kidneys**: control blood pressure/glucose → protect kidneys → preserve Klotho expression—“protect the sentinels’ home base (the kidneys)”;
- **“Moderation” principle**: Klotho overexpression may carry risks (excessive FGF23 signaling → hypophosphatemia/osteomalacia)—“there must not be too many sentinels, or too little phosphate.”

### 4.3 The “longevity-gene network”: Klotho-FOXO3-IGF-1

Klotho is one member of a “longevity-gene network”:

| Longevity factor | Mechanism | Structure article |
|---|---|---|
| Klotho | Inhibits IGF-1/controls phosphate/antioxidant activity | [26-klotho.md](26-klotho.md) |
| FOXO3 | Transcription of survival programs | [16-foxo3-structure.md](16-foxo3-structure.md) |
| Insulin receptor (low signaling) | Reduced IIS | [21-insulin-receptor.md](21-insulin-receptor.md) |
| SIRT1 | NAD⁺-dependent deacetylation | [06-sirt1-structure.md](06-sirt1-structure.md) |

**“Network synergy.”** Klotho inhibits IGF-1 → AKT ↓ → FOXO3 activation ([16-foxo3-structure.md]) → survival program; Klotho’s antioxidant effects protect SIRT1 (preserve NAD⁺)—“longevity factors reinforce one another, forming a longevity network”—“an individual’s longevity is supported by the network.”

---

## 5. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| The αKlotho extracellular region contains KL1/KL2 tandem domains | ★★★★★ Established | 5W21 and others |
| KL1/KL2 are glycosidase-like but enzymatically inactive | ★★★★★ Established | Sequence + structure |
| Klotho-FGF23-FGFR1c ternary complex | ★★★★★ Established | 5W21 (2018, *Nature*) |
| Klotho is a molecular scaffold for FGF23 signaling | ★★★★★ Established | 5W21 |
| Klotho overexpression extends mouse lifespan | ★★★★★ Established | Classic study by Kuro-o, 1997 |
| Klotho deficiency accelerates aging | ★★★★★ Established | Mouse models |
| Circulating Klotho declines with age/kidney disease | ★★★★★ Established | Clinical studies |
| Acute exercise raises circulating Klotho | ★★★★ Strong | Human studies |

---

## 6. Connections to the knowledge-base narrative

### 6.0 Structural overview of “longevity factors”: the longevity network across 26 articles

The “longevity factor” family in the 10-structures series now has four members, forming a “longevity network”:

**“How the longevity network works”**:
- Klotho ([26](26-klotho.md)): inhibits IGF-1 + controls phosphate + antioxidant activity—the “upstream sentinel”;
- Insulin receptor ([21](21-insulin-receptor.md)): entry point for IIS signaling—the “downstream target of inhibition”;
- FOXO3 ([16](16-foxo3-structure.md)): transcription of survival programs—the “executor”;
- SIRT1 ([06](06-sirt1-structure.md)): NAD⁺-dependent modification—the “coordinator.”

**“Network logic.”** Klotho ↑ → IGF-1 signaling ↓ → FOXO3 activation + phosphate control/antioxidant effects → longevity—“an upstream factor (Klotho) activates downstream longevity programs by inhibiting IIS”—**“Longevity is not a single gene, but a network—and Klotho is an important node in it.”**

### 6.00 Klotho’s clinical prospects: from discovery to translation

Klotho’s translational path from “gene discovery” to “clinical prospects”:

**“Discovery (1997).”** Kuro-o et al. found that Klotho-mutant mice “looked aged”—“the accidental discovery of a longevity gene” (the klotho gene was named after the Greek Fate who spins the thread of life)—“named for the Fate, and aptly so.”

**“Life extension (2005).”** Kurosu et al.: Klotho overexpression extended mouse lifespan (~20–30%)—“conclusive evidence that the longevity protein can extend life.”

**“Mechanism (2006–2018).”** FGF23 coreceptor mechanism (2006) → ternary-complex structure (2018, 5W21)—“from phenotype to molecule, from mechanism to structure.”

**“Clinical biomarker.”** Circulating Klotho as a biomarker for aging/kidney disease/cardiovascular disease (low Klotho = higher risk)—“measure blood Klotho to assess aging.”

**“Therapeutic prospects.”** ① recombinant Klotho (improves cognition/vascular/kidney outcomes in animals); ② Klotho inducers (exercise/drugs); ③ gene therapy (Klotho delivery)—“from supplementation to induction, and from induction to genes.”

**“Cautious outlook.”** Klotho overexpression carries risks (hypophosphatemia/osteomalacia); the balance between “phosphate control” and “phosphate deficiency” must be maintained—“even a longevity protein must be used in moderation: there must not be too many sentinels, or too little phosphate”—“the golden rule for Klotho-based anti-aging: maintain physiological Klotho levels rather than raising them without limit.”

### 6.1 Conversations with the main narrative

- **Aging hallmarks** ([01-aging-hallmarks](../01-foundations/01-aging-hallmarks.md)): Klotho sits at the intersection of several hallmarks (phosphate metabolism/calcification/metabolism)—“the longevity protein connects multiple hallmarks of aging”;
- **FOXO3** ([16-foxo3-structure.md](16-foxo3-structure.md)): Klotho inhibits IGF-1 → FOXO3 activation—“the upstream sentinel starts the survival program”;
- **Insulin receptor** ([21-insulin-receptor.md](21-insulin-receptor.md)): a member of the IIS network—“two nodes in the longevity network”;
- **SIRT1** ([06-sirt1-structure.md](06-sirt1-structure.md)): antioxidant protection preserves NAD⁺—“longevity factors protect one another”;
- **Vascular calcification** ([05-vascular-calcification](../02-vascular/05-vascular-calcification.md)): Klotho controls phosphate → prevents calcification—“the gatekeeper protects blood vessels”;
- **Metabolic aging** ([03-metabolic-aging](../02-vascular/03-metabolic-aging.md)): Klotho and metabolic dysfunction—“the metabolism-phosphate-aging axis.”

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does Klotho work? | The KL1/KL2 horseshoe-shaped scaffold captures FGF23-FGFR1c → signal activation (5W21) |
| Why does it have an “enzyme-like shape but no enzyme activity”? | Catalytic residues were lost during evolution while the binding surface was retained—“scissors became a clamp” |
| How does it control phosphate? | FGF23-Klotho → renal phosphate excretion ↑/intestinal absorption ↓ → blood phosphate ↓ → prevents calcification |
| Why does Klotho decline with age? | Expression in kidney/brain ↓ + soluble form ↓—“the sentinels are being lost” |
| How can it combat aging? | Exercise/phosphate control/kidney protection to induce Klotho + supplementation—“recruit and airdrop sentinels” |

**Structural intuition beyond the five questions**: Klotho’s story reveals the “second life” of protein function—**“Evolution often repurposes old tools—Klotho’s change from ‘enzyme’ to ‘scaffold’ is a molecular career change.”** This phenomenon recurs throughout the 10-structures series: LC3 is a “relative” of ubiquitin (ubiquitin-like, but used differently); the ATP motor of Hsp70 is homologous to myosin ([23-hsp70.md](23-hsp70.md)); and PINK1 is a “ubiquitin kinase” ([24-pink1-parkin.md](24-pink1-parkin.md))—“protein reassignment is commonplace in evolution.” **Anti-aging implications**: ① Understanding “repurposing” helps us see why a protein has its particular roles (historical baggage creates functional diversity)—“know its past to understand its present”; ② drug design can exploit “old pockets with new uses” (although Klotho’s enzyme pocket is inactive, it may serve as a drug-binding site)—“an old pocket, a new drug target”—**“Molecular evolution tells us that a protein’s ‘history’ is its ‘functional map’”**—the most distinctive perspective offered by this article’s structural knowledge.

### 8.1 Klotho and model organisms: the evidence chain for a longevity protein

Evidence for Klotho’s longevity effects spans model organisms:

**“Mice.”** Klotho overexpression → longer lifespan (~20–30%) + improved cognition/vascular function; Klotho deficiency → progeria-like phenotype (stunted growth/vascular calcification/infertility/early death)—“the evidence is clear in both directions.”

**“Rats.”** Klotho overexpression → kidney protection/antifibrotic effects—“rats benefit too.”

**“Worms/flies.”** Klotho-related pathways (phosphate metabolism/IGF-1) affect lifespan—“evidence of conservation”—“from worms to mammals, the longevity logic of phosphate control and IGF inhibition is consistent.”

**“Human associations.”** Klotho genotype (the KL-VS variant) has been associated with human lifespan/cognition in some studies; circulating Klotho is associated with healthy aging—“human evidence is accumulating.”

**“Structural implications of the evidence chain.”** The “conservation” of Klotho from rodents to humans suggests its core functions (phosphate control/IGF inhibition) are “evolutionarily conserved longevity mechanisms”—“the longevity logic of phosphate control, growth suppression, and antioxidant protection is written in our genes”—“Klotho is not a novelty; it embodies an ancient principle.”

**“Klotho and anti-aging pharmacology.”** An overview of current Klotho-related interventions:

**“Direct supplementation”**: recombinant Klotho protein (animal studies: improves cognition/vascular/kidney outcomes)—“airdrop sentinels”—challenge: protein-drug half-life/route of administration—“sentinels are difficult to manufacture and transport.”

**“Induce expression”**: exercise (acute increase in circulating Klotho)/PPARγ agonists/some natural products → endogenous Klotho ↑—“let the body recruit its own sentinels”—safer and more physiological—“sentinels recruited locally fit better.”

**“Gene therapy”**: AAV-Klotho delivery (preclinical)—“replace the sentinels”—long-term effects remain to be validated—“a long-range plan for the sentinels.”

**“Epigenetic regulation”**: methylation of the Klotho promoter (increased in kidney disease) → demethylating drugs may restore expression—“remove the seal from the sentinels” (see [07-dnmt1-structure.md](07-dnmt1-structure.md))—“epigenetic unlocking restores Klotho.”

**“Combination strategy”**: Klotho induction + phosphate-controlled diet + kidney protection → multiple interventions—“recruit sentinels + reduce their burden + protect their home base”—“Klotho-based anti-aging is not a single drug but a system to maintain.”

**“The reality of clinical translation.”** Most Klotho-related interventions remain preclinical or at an early stage; human evidence (biomarkers/genotypes) is accumulating—“the journey from laboratory to clinic must proceed steadily”—“the future of the longevity protein is promising, but progress must be gradual, not rushed.”

---

## 8. Open questions

1. **Full-length membrane-anchored structure of Klotho**: the complete conformation of extracellular region + transmembrane segment + intracellular tail;
2. **Targets of soluble Klotho**: direct receptors/binding partners of circulating Klotho (beyond the FGF23 axis);
3. **KL1/KL2 conformational dynamics**: relationship between scaffold “opening and closing” and FGF23-binding kinetics;
4. **Tissue specificity**: differences in Klotho signaling among tissues (kidney/brain/blood vessels/parathyroid);
5. **Klotho inducers**: drugs/lifestyle measures that can safely raise Klotho;
6. **Klotho and neurodegeneration**: mechanisms by which Klotho affects cognition/neuroprotection.

### 8.2 Klotho and cognition: the “brain guardian” role of the longevity protein

Klotho’s neuroprotective effects have become a focus of recent research—“the longevity protein also protects the brain”:

**“Klotho and cognition.”** In animals, Klotho overexpression → improved cognition (increased hippocampal synaptic plasticity); Klotho deficiency → cognitive deficits—“the longevity protein is also a ‘memory protein.’”

**“KL-VS genotype and human cognition.”** Human heterozygous KL-VS variants (which moderately increase Klotho) → better cognitive performance in some studies—“genotype influences the brain.”

**“Candidate mechanisms.”** ① Klotho inhibits oxidation/inflammation → neuroprotection; ② Klotho regulates myelin/synaptic proteins (FGF signaling); ③ Klotho interacts with NMDAR signaling—“multiple pathways protect the brain.”

**“Klotho’s perspective on cognitive aging.”** Klotho ↓ → accelerated cognitive decline; maintaining Klotho → cognitive protection—“protect the longevity protein, protect memory.”

**“A prescription for anti-aging and brain protection.”** Exercise (raises Klotho + promotes neuroplasticity) + phosphate control (protects blood vessels → protects brain) + cognitive training—“a three-in-one approach combining exercise, metabolism, and cognition—with Klotho as the link.”

**“The bridge between structure and cognition.”** Understanding the Klotho scaffold structure (KL1/KL2 surfaces) → designing “neuroprotective” Klotho modulators (selectively enhancing Klotho function in the brain)—“structural knowledge provides a target map for protecting the aging brain”—“from a molecular scaffold to cognitive protection, Klotho’s story continues.”

---

## 9. Guide to obtaining structural data

- **PDB entries**:
  - 5W21: αKlotho-FGF23-FGFR1c ternary complex (3.00 Å, Chen 2018, *Nature*)—scaffold mechanism;
  - 5W22/5W23: variants of Klotho-related complexes;
  - 3P91 and others: β-Klotho-related structures (coreceptor for FGF19/21 signaling);
  - 6V3F and others: extended Klotho-FGF23 complexes;
  - AlphaFold: AF-Q9UDR5 (full-length human αKlotho prediction).
- **Visualization tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (published literature)

1. Chen G, Liu Y, Goetz R, et al. alpha-Klotho is a non-enzymatic molecular scaffold for FGF23 hormone signalling. *Nature* 2018;553:461-466. (PDB 5W21)
2. Kuro-o M, Matsumura Y, Aizawa H, et al. Mutation of the mouse klotho gene leads to a syndrome resembling ageing. *Nature* 1997;390:45-51. (Discovery of Klotho)
3. Kurosu H, Yamamoto M, Clark JD, et al. Suppression of aging in mice by the hormone Klotho. *Science* 2005;309:1829-1833. (Klotho and lifespan extension)
4. Hu MC, Shi M, Zhang J, et al. Klotho: a novel phosphaturic substance acting as an autocrine enzyme in the renal proximal tubule. *FASEB J* 2010;24:3438-3450. (Klotho and phosphate metabolism)
5. Urakawa I, Yamazaki Y, Shimada T, et al. Klotho converts canonical FGF receptor into a specific receptor for FGF23. *Nature* 2006;444:770-774. (Klotho-FGF23 mechanism)
6. Xu Y, Sun Z. Molecular basis of Klotho: from gene to function in aging. *Endocr Rev* 2015;36:174-193. (Review of Klotho)
7. Dalton GD, Xie J, Anantharaman A, et al. Exercise acutely increases circulating Klotho in healthy adults. *J Clin Endocrinol Metab* 2016;101:2487-2494. (Exercise and Klotho)

---

> **Structural overview**: Klotho is a **“longevity protein”**—its extracellular KL1/KL2 tandem glycosidase-like domains fold into a **“horseshoe-shaped scaffold”** that captures FGF23-FGFR1c to form a ternary complex (revealed by 5W21; a “nonenzymatic molecular scaffold”)—**“the matchmaker that brings FGF23 and FGFR1c together.”** Its functions: ① the membrane-bound form regulates phosphate metabolism (excretion of phosphate/prevention of calcification); ② the soluble form inhibits IGF-1 and promotes antioxidant activity—**“phosphate control protects blood vessels; IGF inhibition supports longevity.”** **With aging, Klotho ↓ → phosphate ↑/calcification/IGF-1 ↑ → accelerated aging**; **Klotho overexpression extends lifespan in mice**. **Anti-aging strategies**: exercise-induced expression/phosphate-controlled diet/kidney protection + potential supplementation—“protect the longevity sentinel, and protect the defenses linking phosphate, metabolism, blood vessels, and kidneys.”
