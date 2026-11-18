# Molecular Structure Deep Dive 07: DNMT1—The “Writer” of DNA Methylation and Its Autoinhibition Mechanism

> **Topic positioning**: Article 7 in 10-structures (Molecular Structure Deep Dive). Examines the three-dimensional structure of DNMT1 (DNA methyltransferase 1) to understand how it “reads” hemimethylated CpGs, “writes” new methyl groups, and uses autoinhibition to ensure that it maintains rather than establishes methylation. This is the structural foundation for the knowledge base’s epigenetic-reprogramming thread ([08-frontiers/01-reprogramming/01-concept.md](../08-frontiers/01-reprogramming/01-concept.md)) and its “write–erase” pairing with TET ([05-tet-dna.md](05-tet-dna.md)).
> **Related articles**: See [05-tet-dna.md](05-tet-dna.md) for TET structure, [06-sirt1-structure.md](06-sirt1-structure.md) for SIRT1 structure, and [01-foundations/02-aging-clocks.md](../01-foundations/02-aging-clocks.md) for aging clocks.

---

## 0. Structural snapshot

**In one sentence**: DNMT1 is a maintenance DNA methyltransferase. It adds methyl groups only at **hemimethylated** CpG sites (the parental strand is methylated and the daughter strand is not), thereby copying methylation patterns after DNA replication. A sophisticated autoinhibition mechanism prevents it from methylating previously unmodified sites de novo.

```text
DNMT1 domains: N-terminal regulatory region — RFTS — CXXC — BAH1 — BAH2 — methyltransferase domain (MTase) — C-terminus
                                         │       │      │      │
                                 (replication-fork targeting) (CpG recognition) (protein interaction) (catalytic core)
```

**Three major structural features** (the atomic basis of function):
1. **CXXC zinc-finger domain**: Specifically binds **unmethylated** CpGs. It acts as a “gatekeeper,” steering DNMT1 away from sites without methyl groups.
2. **BAH1/2 domains**: Protein–protein interaction modules. A loop from BAH2 holds the catalytic domain’s target-recognition domain (TRD) in a retracted position—the “second lock” of autoinhibition.
3. **Methyltransferase domain (MTase)**: Contains the catalytic nucleophilic cysteine (human Cys1226) and uses S-adenosylmethionine (AdoMet/SAM) as the methyl donor to methylate cytosine at C5.

**Core catalytic reaction**:

```text
Hemimethylated CpG: parental strand 5mC (already methylated) ── daughter strand C (unmethylated)
                              │
  DNMT1: daughter-strand C flips out of the duplex → Cys1226 nucleophilically attacks C6 → AdoMet donates methyl → daughter-strand C becomes 5mC
                              │
  Result: both strands are methylated = the methylation pattern is “inherited” after replication
```

---

## 1. Why DNMT1 structure matters

DNA methylation (methylation of cytosine C5 in CpG dinucleotides) is one of the most important mammalian epigenetic marks. About 70–80% of CpG sites are methylated, contributing to gene silencing, imprinting, transposon repression, and X-chromosome inactivation. **Inheritance of methylation patterns depends on DNMT1 copying methylation from the parental strand to the newly synthesized daughter strand after every round of DNA replication**. If DNMT1 fails, methylation patterns are diluted and lost over generations of cell division.

**Three key questions for structural research**:
1. How does DNMT1 recognize a hemimethylated site rather than an unmethylated or fully methylated one? (Substrate selectivity)
2. How does catalysis occur—how is cytosine flipped and the methyl group transferred? (Catalytic mechanism)
3. How does autoinhibition ensure “maintenance, not establishment”? (Fidelity mechanism)

These questions are addressed by structures including 3PTA (autoinhibited state) and 4DA4 (productive catalytic state).

**Direct connections to aging**:
- With age, **global 5mC decreases** (especially in repetitive sequences and gene bodies), while **specific CpGs become hypermethylated** (in promoter regions). This “drift” in methylation patterns underlies the molecular basis of epigenetic aging clocks such as the Horvath clock.
- DNMT1 activity/expression declines with age in some cell types, and mislocalization increases. Decline of the “writer” leads to a disordered methylome.
- Balance with TET: The dynamic balance between DNMT1 (writing) and TET (erasing) determines methylation homeostasis; aging disrupts that balance (see the two-sided nature of demethylation in [05-tet-dna.md](05-tet-dna.md)).

---

## 2. DNMT1’s multidomain architecture: An enzyme with multiple locks

Full-length human DNMT1 has 1,616 residues and is among the most complex mammalian methyltransferases. Multiple domains enable fine gating:

### 2.1 RFTS domain (replication-fork targeting sequence)

- **Location**: Approximately residues 350–600 at the N-terminus.
- **Function**: Targets DNMT1 to DNA replication forks through interactions with PCNA/the replication machinery—“present during replication, ready to work immediately afterward.”
- **Structural feature**: Contains a “pocket” where the UBL domain of UHRF1 can dock. UHRF1 “reads” hemimethylated CpGs and recruits DNMT1, making this a hub for reader–writer cooperation.

### 2.2 CXXC domain (CpG gatekeeper)

- **Location**: Approximately residues 600–700.
- **Structure**: A CXXC zinc finger (eight conserved Cys/His residues coordinate two Zn²⁺ ions) that recognizes **unmethylated** CpG in the DNA minor/major groove.
- **Key property**: It recognizes only unmethylated CpG; methylation causes steric interference that disrupts recognition. It steers DNMT1 toward unmethylated sites, but subsequent autoinhibition prevents methylation—“attracted to the door, but not allowed inside.”
- **Gatekeeper logic**: When CXXC binds an unmethylated CpG, the CXXC–BAH1 linker inserts between DNA and the active site, **physically blocking de novo methylation**.

### 2.3 BAH1/2 domains (interaction and autoinhibition)

- **Location**: Approximately residues 700–1100.
- **Structure**: BAH (bromo-adjacent homology) fold, a protein–protein interaction module that in other proteins can participate in chromatin recognition.
- **Autoinhibitory role**: A loop from BAH2 interacts with the MTase target-recognition domain (TRD), holding the TRD in a retracted position and preventing its insertion into the DNA major groove. It is a **brake on the active conformation**.
- The brake is released only when DNMT1 encounters hemimethylated CpG (structural rearrangement → TRD release → catalysis).

### 2.4 MTase domain (catalytic core)

- **Location**: C-terminal region, approximately residues 1100–1616.
- **Structure**: Classical AdoMet-dependent methyltransferase fold, with catalytic and target-recognition lobes.
- **Key residue**: **Catalytic cysteine Cys1226** (human), which nucleophilically attacks cytosine C6 to form a covalent intermediate.
- **Cofactor**: S-adenosylmethionine (AdoMet/SAM) binds in the cofactor pocket and donates the methyl group.

---

## 3. Autoinhibition: Why DNMT1 “maintains but does not establish” methylation

### 3.0 Atom by atom: How autoinhibition “locks” the enzyme

To understand DNMT1’s “maintenance, not establishment” rule, first consider its recognition problem. After DNA replication, the duplex contains a parental strand with its original methylation marks and a newly synthesized, initially unmethylated daughter strand. The genome now has three kinds of CpG sites: **hemimethylated** (parental strand methylated, daughter strand not), **unmethylated** (neither strand methylated), and **fully methylated** (both strands methylated). DNMT1 must act only at hemimethylated sites and never at unmethylated sites—a key that should fit only one lock.

**The challenge is that recognizing “hemimethylated” requires sensing both “methyl on the parental strand” and “no methyl on the daughter strand.”** The 3PTA structure reveals the answer: DNMT1 achieves this precise discrimination through a “double negative,” using two gates.

**First gate: A gatekeeper blocks access.** The CXXC zinc-finger domain specifically recognizes unmethylated CpGs (it does not recognize methylated CpGs because the methyl group disrupts the spatial fit of the recognition surface). When CXXC binds an unmethylated CpG, the adjacent CXXC–BAH1 linker—a stretch of peptide chain—acts like a crossbar lying between the DNA duplex and the MTase active site. **The DNA is physically pushed away by this crossbar and cannot deliver cytosine into the catalytic pocket.** This is “lock one”: CXXC attracts DNMT1 to an unmethylated site, while the linker simultaneously locks catalytic activity. The combination of “attraction + locking” prevents DNMT1 from making mistakes: it is recruited, but cannot work.

**Second gate: A brake holds the TRD.** Even with the first lock, the MTase domain has an “arm” of its own—the target-recognition domain (TRD), which would normally extend into the DNA major groove and grasp cytosine. A loop from BAH2 acts like a hand that **holds the TRD by the shoulder**, fixing it in its retracted position. If the arm cannot extend, it cannot grasp the substrate. This is “lock two.”

**How does a hemimethylated site unlock DNMT1?** The 4DA4 structure shows that when the DNA is hemimethylated, a shallow hydrophobic depression in MTase “reads” the methyl group on parental-strand 5mC (the depression is tailored to this methyl group; unmethylated C does not fit). This methyl-reading event triggers a global conformational rearrangement: the linker moves aside, the TRD is released, and the daughter-strand cytosine flips into the catalytic pocket. **“Methyl read = brake released = work begins.”** Hemimethylation is the actual “key.”

**The elegance of this design**: DNMT1 does not directly “recognize hemimethylation”—a difficult task because the daughter strand is, by definition, bare. Instead it “recognizes unmethylated CpG → locks itself” and “recognizes the methyl group → unlocks itself.” Two relatively simple recognition events combine to produce sophisticated selectivity. **“Simple recognition, combined decision-making”** is a common design principle in molecular machines (analogous to the Rheb/Rag “two-key” logic in [04-mtor-structure.md](04-mtor-structure.md)).

### 3.1 The two “locks” (revealed by the 3PTA structure)

3PTA (human DNMT1 residues 646–1600 + unmethylated CpG DNA, 3.60 Å; Song 2011, *Science*) reveals the complete autoinhibitory architecture:

**Lock 1 (CXXC–BAH1 linker)**: When CXXC binds an unmethylated CpG, the linker between CXXC and BAH1 lies **across the space between the DNA and the MTase active site**, pushing DNA away and preventing cytosine from flipping into the catalytic pocket. Even though CXXC recruits DNMT1 to the unmethylated site, the linker ensures that it “does no work once there.”

**Lock 2 (BAH2–TRD interaction)**: A loop extending from BAH2 grabs the TRD of the MTase domain and stabilizes it in a **retracted conformation**. The TRD should enter the DNA major groove to recognize cytosine, but is held immobile. This provides double protection: the substrate cannot enter (lock 1), and the recognition element cannot extend (lock 2).

### 3.2 Biological significance of autoinhibition

- **Prevents erroneous de novo methylation**: If DNMT1 acted on unmethylated sites, methylation patterns could be “contaminated” (genes silenced inappropriately and transposons repressed incorrectly).
- **Source of specificity**: DNMT1’s maintenance specificity does not come from directly “recognizing hemimethylation” (its CXXC domain actually recognizes unmethylated CpG); it comes from **being attracted to an unmethylated site and autoinhibited there, while being activated by a hemimethylated site**—dual gating.
- **Evolutionary logic**: Separating maintenance from establishment (DNMT1 maintains; DNMT3A/3B establish de novo methylation) avoids lowering fidelity by assigning two tasks to one enzyme—specialization improves fidelity.

### 3.3 Conformational changes upon activation by hemimethylated DNA (revealed by 4DA4)

4DA4 (mouse DNMT1 residues 731–1602 + hemimethylated CpG DNA, 2.60 Å; Song 2012, *Science*) captures a **productive catalytic state**:

- The parental-strand 5mC of hemimethylated CpG is recognized: its methyl group sits in a **shallow hydrophobic depression** in MTase, “reading” the presence of the methyl group.
- Unmethylated cytosine on the daughter strand **flips out of the duplex** (base flipping) into the catalytic pocket.
- The catalytic residue (mouse Cys1229, corresponding to human Cys1226) forms a covalent intermediate with cytosine C6; a half-covalent state is captured structurally.
- The duplex **distorts at the CpG** (an intercalation pocket); both strands partially flip (“double base flipping”). DNA deformation is a prerequisite for catalysis.
- Comparing 3PTA (autoinhibited, unmethylated DNA) with 4DA4 (catalytic, hemimethylated DNA) provides an atomic snapshot of the gating switch.

---

## 4. Catalytic mechanism: From structure to chemistry

### 4.0 The “chemical ballet” of methyl transfer: Why Cys1226 is indispensable

The previous section described the “locks” and “key”; this section follows how the “key turns.” DNMT1 methylates cytosine at C5, with catalytic cysteine Cys1226 and methyl donor AdoMet as the lead players. At the atomic level:

**First, consider the position of cytosine.** Cytosine is a pyrimidine base with a hydrogen (–H) at C5. Replacing that hydrogen with methyl (–CH₃) is chemically difficult: C5 is not naturally reactive (it is not a nucleophilic site), so direct “hydrogen replacement” barely occurs under physiological conditions. **The enzyme’s solution is to activate cytosine before adding the methyl group.** Cys1226’s thiol (–SH) nucleophilically attacks C6. This attack disrupts the C5–C6 double bond, turning C5 from an “alkene carbon” into a carbanion. **The carbanion can accept the methyl group.** This is a classic Michael-addition mechanism: addition first, methylation next, elimination last.

**Next, AdoMet donates its methyl group.** AdoMet (S-adenosylmethionine) is the cell’s universal “methyl wallet.” Its sulfur bears an activated methyl group (the sulfonium ion makes the methyl strongly electron-deficient and easy for a nucleophile to take). DNMT1’s cofactor pocket positions AdoMet precisely: its methyl lies only 2–3 Å from the C5 carbanion, within reach. After transfer, AdoMet becomes SAH (S-adenosylhomocysteine). **The wallet is empty—and SAH is also a competitive inhibitor of DNMT1** (product inhibition that prevents excessive methylation).

**Finally, elimination.** After the methyl group is installed, Cys1226 withdraws from C6 (β-elimination), restoring the C5–C6 double bond and forming 5-methylcytosine (5mC). The complete cycle is carbanion formation → methylation → restoration of the double bond. Cytosine has become 5mC, and the DNA duplex is restored.

**Why does this explain the pharmacology of 5-Aza?** 5-Azacytidine (5-Aza) replaces the carbon at cytosine’s C5 with nitrogen. Michael addition proceeds as usual (Cys1226 attacks C6), but the final step is blocked: **nitrogen cannot undergo β-elimination** like carbon. The covalent intermediate becomes trapped between Cys1226 and DNA. DNMT1 is effectively “nailed” to DNA and is subsequently degraded; cellular DNMT1 is depleted, and newly replicated DNA loses methylation maintenance through passive demethylation. The chemical basis of a “suicide substrate” is making the final step of the Cys-catalyzed reaction impossible—a classic example of structural biology explaining drug mechanism.

### 4.1 Three-step catalysis (chemistry of methyl transfer)

```text
Step 1: Base flipping + nucleophilic attack
  Daughter-strand cytosine flips out of the duplex → Cys1226 thiol (–SH) is deprotonated and attacks C6
  → Cys–S–C6 covalent intermediate forms (cytosine C5–C6 double bond is “broken”)

Step 2: Methyl transfer
  Methyl group of AdoMet (SAM) → transfers to cytosine C5 → 5-methylcytosine (5mC) forms
  AdoMet becomes S-adenosylhomocysteine (SAH)

Step 3: Elimination + release
  C5 is deprotonated → Cys is eliminated from C6 (β-elimination) → C5–C6 double bond restored
  → 5mC is released from the catalytic pocket and the DNA duplex is restored
```

### 4.2 Why Cys1226 is so important

- It is the “nucleophilic switch” of the entire reaction. The Cys thiol is partly deprotonated at physiological pH (pKa about 8.3); after base flipping, the active-site environment (positively charged Arg/Lys) further lowers its pKa, ensuring nucleophilicity.
- **Mutation of Cys1226 completely inactivates the enzyme** (biochemically validated).
- This also explains how **oxidative stress/reactive oxygen species** can inhibit DNMT1: Cys is readily oxidized (–SH → –SOH/–SO₂H), losing its nucleophilicity. This is the molecular mechanism by which oxidative stress impairs maintenance methylation.
- In contrast to TET, which uses Fe(II) for oxidation (demethylation), DNMT1 uses Cys for nucleophilic catalysis (methylation)—the “writer” and “eraser” use opposite mechanisms.

### 4.3 AdoMet (SAM), the “methyl wallet”

- AdoMet is the main cellular methyl donor and is central to the methyl cycle, linked to folate and methionine metabolism.
- DNMT1’s cofactor pocket precisely positions AdoMet so that the methyl group points toward C5 (2–3 Å away).
- After methylation, AdoMet becomes SAH, a competitive inhibitor of DNMTs (product inhibition). A functioning methyl cycle supports methylation (see the folate/B12 discussion in [07-interventions/04-supplements.md](../07-interventions/04-supplements.md)).

---

## 5. DNMT1 and aging: Slowing the clock from a structural perspective

### 5.1 Three patterns of methylation drift

Structural interpretations of age-related DNA methylation changes:

- **Global 5mC loss**: Methylation of repetitive sequences (LINE-1, Alu) declines with age → risk of transposon derepression → genomic instability. Structural explanation: lower DNMT1 activity + oxidative damage (including oxidation of Cys1226) + accumulated replication errors → writing cannot keep up with dilution.
- **Hypermethylation of promoter CpG islands**: Promoters of particular genes (tumor suppressors, developmental genes) gain aberrant methylation → gene silencing. This does not fit DNMT1’s maintenance role and is more suggestive of de novo activity or TET dysregulation—“writing where it should not.”
- **Clock sites**: Horvath and others identified specific CpGs whose methylation levels correlate strongly with age (epigenetic clocks). Predictable drift at these sites is a molecular timer of aging.

### 5.2 DNMT1 and epigenetic reprogramming

- Reprogramming (OSK/OSKM) requires **large-scale demethylation** (led by TET) plus reconstruction of methylation patterns (de novo DNMT3A/3B + maintenance DNMT1)—“erase clean, then rewrite.”
- Some rejuvenating effects of partial reprogramming (ER-100, etc.) result from resetting methylation patterns; DNMT1’s role is to maintain the newly written pattern.
- Structurally, DNMT1 must be “correctly activated” (release autoinhibition at hemimethylated sites) and “correctly restrained” (not interfere with TET-mediated erasure). **Balance between writing and erasing is essential for safe reprogramming** (see the four layers of defense in [01-concept](../08-frontiers/01-reprogramming/01-concept.md)).

### 5.3 Structural mechanism of 5-azacytidine (5-Aza)-class drugs

- 5-Azacytidine and decitabine (5-aza-2′-deoxycytidine) are nucleoside analogs that, after incorporation into DNA, **trap DNMT1**:
  - The C5 position of azacytosine contains nitrogen (N), not carbon (C). After nucleophilic attack by Cys1226, **β-elimination cannot occur**; the covalent intermediate is trapped, irreversibly locking DNMT1 onto DNA.
  - DNMT1 is depleted through degradation, and DNA methylation passively declines through replication dilution.
- Clinical use: myelodysplastic syndromes (MDS)/acute myeloid leukemia (AML)—“disable the methylation writer with a suicide substrate to awaken silenced tumor-suppressor genes.”
- Anti-aging perspective: low-dose 5-Aza improves aging phenotypes in animals through partial demethylation, but **global demethylation carries substantial risk** (transposon activation). “How much and where to erase” is the core problem (see the dual nature of TET in [05-tet-dna.md](05-tet-dna.md)).

---

## 6. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| DNMT1 is a maintenance methyltransferase (hemimethylated substrate) | ★★★★★ Established | Biochemistry + genetics |
| CXXC recognizes unmethylated CpG | ★★★★★ Established | 3PTA + biochemistry |
| CXXC–BAH1 linker blocks de novo methylation (lock 1) | ★★★★★ Established | 3PTA (2011, *Science*) |
| BAH2 loop holds the TRD (lock 2) | ★★★★★ Established | 3PTA |
| Activation by hemimethylation: 5mC binds shallow pocket + cytosine flips | ★★★★★ Established | 4DA4 (2012, *Science*) |
| Cys1226 nucleophilic catalysis (covalent intermediate) | ★★★★★ Established | 4DA4 + biochemistry |
| Double base flipping/DNA distortion | ★★★★ Strong | 4DA4 |
| Oxidative damage to Cys → DNMT1 inactivation | ★★★★ Strong | Biochemistry (structural inference) |
| 5-Aza traps DNMT1 (suicide substrate) | ★★★★★ Established | Pharmacology + structure |
| Age-related methylation drift (global decrease/specific increase) | ★★★★★ Established | Large-scale methylome studies |

---

## 7. Connections to the knowledge base’s main themes

### 7.0 The DNMT1–TET “write–erase” pair: Yin and yang of epigenetic homeostasis

The knowledge base’s epigenetic thread has two major effector enzymes: DNMT1 (this article, writer) and TET (eraser; [05-tet-dna.md](05-tet-dna.md)). Structurally, they are a complementary pair:

| Dimension | DNMT1 (write) | TET (erase) |
|---|---|---|
| Reaction | Cytosine C5 methylation (adds methyl) | 5mC oxidation (first step of demethylation) |
| Catalysis | Cys1226 nucleophile (covalent intermediate) | Fe(II)–2OG oxidation (ferryl intermediate) |
| Cofactor | AdoMet (SAM) donates methyl | 2OG + O₂ |
| Substrate | Hemimethylated CpG (maintenance) | Any accessible 5mC (oxidation) |
| Structural core | Multidomain autoinhibitory gating | DSBH fold + base flipping |
| Aging trend | Activity↓ (global 5mC↓) | Partly increased/dysregulated |
| Intervention | 5-Aza inhibition (reactivate genes) | TET activation (reprogramming) |

**Structural essence of homeostasis**: Methylation level = DNMT1 writing rate − TET erasure rate − replication dilution rate. Aging disrupts all three (writing declines, erasure is dysregulated, dilution continues), and the methylome drifts. The “hand” of the epigenetic clock reflects their net effect. **Interventions (5-Aza, TET activation, reprogramming) all ultimately rebalance writing and erasing**. Structural studies provide atomic-level grounds for where and how to adjust that balance—**write–erase balance is the yin and yang of epigenetic homeostasis and the prerequisite for reversible epigenetic age.**

### 7.1 Dialogue with the main articles

- **TET structure** ([05-tet-dna.md](05-tet-dna.md)): The other half of the write–erase pair; read together, the two articles provide the complete structural picture of the DNA methylation cycle.
- **Epigenetic reprogramming** ([01-concept](../08-frontiers/01-reprogramming/01-concept.md)): Reprogramming = large-scale erasure (TET) + pattern reconstruction (de novo DNMT3 family + maintenance DNMT1)—the structural logic of “erase, then rewrite.”
- **Aging clocks** ([02-aging-clocks](../01-foundations/02-aging-clocks.md)): The Horvath clock measures age-related drift in methylation at specific CpGs; drift in the DNMT1/TET balance is the clock’s molecular mechanism.
- **NAD⁺/SIRT1** ([04-nad-sirtuin](../01-foundations/04-nad-sirtuin.md)): SIRT1 regulates DNMT1 activity by deacetylating and stabilizing it. An indirect chain is “NAD⁺ decline → SIRT1 decline → DNMT1 instability → methylation drift.”
- **Molecular-structure topic**: Together with SIRT1 (deacetylation), TET (demethylation), and NOS (NO signaling), DNMT1 forms part of the structural foundation linking epigenetics, metabolism, and signaling.

---

## 8. Five structure–aging questions

| Question | Structural answer |
|---|---|
| Why does DNMT1 maintain but not establish methylation? | Dual autoinhibition: the CXXC gatekeeper (lock 1) + BAH2 holding the TRD (lock 2); an unmethylated site attracts DNMT1 but does not grant access. |
| How does hemimethylation activate catalysis? | Parental-strand 5mC enters a shallow hydrophobic pocket (methyl is read), while daughter-strand C flips into the catalytic pocket (flipping is the activation signal). |
| How is the methyl group added? | Cys1226 attacks C6 → AdoMet donates methyl to C5 → β-elimination restores the double bond (three steps). |
| Why does oxidative stress impair methylation? | Catalytic Cys and Zn²⁺-coordinating Cys are oxidative targets → loss of nucleophilicity and structural integrity. |
| How does 5-Aza disable DNMT1? | Azacytosine has N rather than C at C5 and cannot undergo β-elimination → covalent intermediate is trapped → DNMT1 is degraded and depleted. |

---

## 9. Open questions

1. **Structure of full-length DNMT1**: The dynamic relationship between RFTS and MTase domains (replication-fork recruitment → positioning → activation) lacks a full-length structural snapshot.
2. **Complete picture of UHRF1 cooperation**: The structure and dynamics of the UHRF1 (hemimethylated-DNA reader) + DNMT1 (writer) complex are not fully resolved.
3. **Kinetics of releasing autoinhibition**: The conformational path from autoinhibited to catalytic state, including intermediate states, has not been directly observed.
4. **Tissue/cell-type differences**: Differences in DNMT1 expression and activity regulation between tissues (stem cells versus terminally differentiated cells) remain to be mapped.
5. **Reversibility of epigenetic clocks**: Whether and how methylation drift at clock CpGs can be reversed by modulating DNMT1/TET remains open—can epigenetic age be reset by rebalancing writing and erasing?
6. **Boundary between de novo and maintenance activity**: Can DNMT1 “cross the line” and perform de novo methylation under certain conditions (such as UHRF1 overexpression or DNA damage)? This is important for understanding aberrant methylation.

---

## 10. Guide to structural data

- **PDB entries**:
  - 3PTA: Human DNMT1 (646–1600) + unmethylated CpG DNA (3.60 Å; Song 2011, *Science*)—autoinhibited state.
  - 4DA4: Mouse DNMT1 (731–1602) + hemimethylated CpG DNA (2.60 Å; Song 2012, *Science*)—catalytic state.
  - 3PT6/3PT9: DNMT1 variants/different DNA complexes (same research group).
  - Other DNMTs: DNMT3A (e.g., 2QRV), a de novo methyltransferase without DNMT1’s autoinhibition—the structural contrast of the “establisher.”
  - DNMT3A–DNMT3L–DNA complex (e.g., 4U7P).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX, AlphaFold full-length prediction (AF-P26358).

---

## 11. References (authentic literature)

1. Song J, Rechkoblit O, Bestor TH, Patel DJ. Structure of DNMT1-DNA complex reveals a role for autoinhibition in maintenance DNA methylation. *Science* 2011;331:1036–1040. (PDB 3PTA)
2. Song J, Teplova M, Ishibe-Murakami S, Patel DJ. Structure-based mechanistic insights into DNMT1-mediated maintenance DNA methylation. *Science* 2012;335:709–712. (PDB 4DA4)
3. Bestor TH. The DNA methyltransferases of mammals. *Hum Mol Genet* 2000;9:2395–2402. (DNMT family review)
4. Okano M, Bell DW, Haber DA, Li E. DNA methyltransferases Dnmt3a and Dnmt3b are essential for de novo methylation and mammalian development. *Cell* 1999;99:247–257. (De novo methylation)
5. Horvath S. DNA methylation age of human tissues and cell types. *Genome Biol* 2013;14:R115. (Epigenetic clock)
6. Issa JP, Kantarjian HM. Targeting DNA methylation. *Clin Cancer Res* 2009;15:3938–3946. (Clinical 5-Aza)
7. Esteve PO, Chin HG, Benner J, et al. Regulation of DNMT1 stability through SIRT1-mediated deacetylation. *Nat Struct Mol Biol* 2011;18:42–48. (SIRT1–DNMT1 connection)

---

> **Structural snapshot**: DNMT1 = CXXC (unmethylated-CpG gatekeeper) + BAH1/2 (interactions + autoinhibition) + MTase (Cys1226 catalysis + AdoMet methyl donor). **Dual-lock autoinhibition** (linker blocks DNA + TRD is held back) ensures maintenance at hemimethylated sites without de novo methylation. **Hemimethylation activates** (shallow pocket reads 5mC + daughter cytosine flips) to open catalysis. **5-Aza suicide substrate** (C5 nitrogen cannot be eliminated) disables the writer. Together with TET’s erasing activity, DNMT1 forms the molecular engine of epigenetic homeostasis and aging clocks.
