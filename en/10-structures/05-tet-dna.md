# Molecular Structure Deep Dive 05: TET Dioxygenases and DNA Demethylation—The “Eraser” of Epigenetic Reprogramming

> **Topic positioning**: Article 5 in 10-structures (Molecular Structure Deep Dive). Examines how TET proteins (TET1/2/3) “erase” DNA methylation marks. This is the atomic-level foundation for the knowledge base’s epigenetic-reprogramming thread ([08-frontiers/01-reprogramming/01-concept.md](../08-frontiers/01-reprogramming/01-concept.md)): the TET enzymes activated by OSK factors, the causal TET experiments of Lu 2020, and the molecular mechanism for turning back the aging clock all converge here.
> **Related articles**: See [08-frontiers/01-reprogramming/01-concept.md](../08-frontiers/01-reprogramming/01-concept.md) and [02-animal-evidence](../08-frontiers/01-reprogramming/02-animal-evidence.md) for epigenetic reprogramming; [01-foundations/02-aging-clocks.md](../01-foundations/02-aging-clocks.md) for aging clocks; and [02-animal-evidence](../08-frontiers/01-reprogramming/02-animal-evidence.md) for animal evidence on reprogramming.

---

## 1. Core concept: An oxidase that changes the epigenetic order

DNA methylation (5-methylcytosine, 5mC) is one of the most stable epigenetic marks in mammals and was traditionally thought to be “easy to write, hard to erase.” The discovery of TET proteins (Tahiliani et al., *Science*, 2009) changed this view: **TET dioxygenases progressively oxidize 5mC to 5-hydroxymethylcytosine (5hmC) → 5-formylcytosine (5fC) → 5-carboxylcytosine (5caC). Thymine DNA glycosylase (TDG) then excises the modified base, and base-excision repair (BER) restores unmodified cytosine.** Active demethylation thus became a reality.

**Core structural questions**:

1. **Specificity**: How does TET selectively oxidize 5mC rather than unmodified C?
2. **Multistep oxidation**: How can the same active site carry out the three successive oxidations, 5mC → 5hmC → 5fC → 5caC (adding one oxygen at each step)?
3. **CpG recognition**: Why does TET2 prefer 5mC in a CpG dinucleotide context?
4. **Cancer mutations**: Why are cancer-associated TET2 mutations concentrated in residues involved in Fe(II)/NOG chelation, DNA interaction, and zinc-finger structure?

## 2. Overall architecture: A compact catalytic domain with two zinc fingers and a double-stranded β-helix

**PDB 4NM6** (human TET2 catalytic domain + methylated DNA, 2.02 Å; Hu 2013, *Cell* 155:1545) is the landmark structure. The TET2 catalytic domain (approximately 500 amino acids at the C-terminus) has three components:

```text
┌── Cys-rich domain ──────────┐   ┌── DSBH domain (double-stranded β-helix) ──┐
│        │                    │   │    Fe(II) + NOG active center             │
│        └── zinc finger 1 ── zinc finger 2 ──┘                                │
│             (two zinc fingers “stitch” the two domains together)             │
│                    │                                                         │
│                    └── forms a compact catalytic cavity ────────────────────┘
│                                │
│                    DNA-binding surface (base flips in)
└──────────────────────────────────────────────────────────────────────────────┘
```

- **Cys-rich domain**: Contains multiple cysteines that coordinate Zn²⁺ through two zinc fingers (Zn1 and Zn2), “stabilizing DNA above the DSBH core” (original paper).
- **DSBH domain (double-stranded β-helix)**: The hallmark fold of the 2-oxoglutarate (2OG)-dependent dioxygenase superfamily. Eight β-strands form a “jelly-roll” barrel that houses Fe(II) and the cosubstrate NOG (N-oxalylglycine, a 2OG analog).
- **DNA binding**: DNA binds on the catalytic-domain surface, and **5mC flips out of double-stranded DNA into the catalytic cavity**. This is a classic mechanism used by DNA-modifying enzymes (including methyltransferases).

## 3. Catalytic cavity: Atomic dissection of the Fe(II)–2OG active center

### 3.1 Metal-center coordination (DSBH core)

The Fe(II) inside the DSBH barrel is coordinated by three conserved residues (TET2 numbering):

| Ligand residue | Atom | Role |
|---|---|---|
| **His1382** | Nε | Coordinates Fe (one of the His ligands) |
| **His1384** | Nε | Coordinates Fe |
| **Asp1386** | Carboxylate O | Coordinates Fe (bidentate) |

These three residues (the HxD motif, His-His-Asp) form the **triangular coordination face** for Fe(II). The remaining coordination positions are occupied by the **C1 carboxylate and C2 keto group of 2OG** (bidentate coordination) and a **water molecule**, forming the classic octahedral coordination sphere of “three His/Asp residues + 2OG + water” (the facial triad plus equatorial ligands).

### 3.2 Catalytic cycle: A relay of three oxidations

```text
Fe(II) + 2OG + O₂ ──► Fe(IV)=O (ferryl intermediate) + succinate + CO₂
                            │
                            ▼
    5mC + Fe(IV)=O ──► 5hmC + Fe(II) (first hydroxylation)
                            │
                            ▼
    5hmC + Fe(IV)=O ──► 5fC + Fe(II) (second oxidation)
                            │
                            ▼
    5fC + Fe(IV)=O ──► 5caC + Fe(II) (third oxidation)
```

- In each cycle, oxidative decarboxylation of 2OG (→ succinate + CO₂) generates a highly reactive **Fe(IV)=O (ferryl) intermediate**.
- Ferryl abstracts hydrogen from the substrate’s methyl/methylene/formyl group; hydroxyl rebound then yields the oxygenated product.
- **Stepwise oxidation of 5mC → 5hmC → 5fC → 5caC**: The active-site cavity is designed so that oxidized derivatives of 5mC (5hmC/5fC) can remain in place and undergo further oxidation. As the original paper notes, “the methyl group of 5mC is not involved in TET2–DNA contacts, allowing the catalytic pocket to accommodate 5mC derivatives for further oxidation.”
- Finally, TDG excises 5caC → BER repairs the site → unmodified C. **Complete demethylation is accomplished in two stages: oxidation + excision.**

### 3.2a “One loading, three shots”: The structural code for multistep oxidation

TET’s unusual catalytic feature is that **a single active site carries out three successive oxidations** (5mC → 5hmC → 5fC → 5caC), adding one oxygen to the product of the previous reaction each time. How is this achieved structurally? Three design features are indispensable:

**Feature 1: The substrate “does not run away.”** After 5mC is oxidized to 5hmC, the product remains held by the residue network in the catalytic cavity. The hydroxymethyl group of 5hmC is close in size to the methyl group of 5mC, and the binding mode is nearly unchanged; the product does not dissociate or move. Because the methyl group of 5mC does not contact TET2–DNA, oxidation leaves the contact pattern largely unchanged and the product remains in place. **Product retention is a prerequisite for multistep catalysis**—if every product dissociated, the enzyme would only catalyze one oxidation at a time.

**Feature 2: Reuse of Fe(IV)=O.** Each catalytic cycle consumes one molecule of 2OG to generate one Fe(IV)=O; three oxidations therefore require three molecules of 2OG (three cycles). The 2OG-binding site in the active cavity is reloaded after each cycle (2OG is replenished from the cytoplasm), while Fe undergoes redox cycling between reactions (Fe²⁺ → Fe(IV)=O → Fe²⁺). **The enzyme remains; the cosubstrate is renewed.**

**Feature 3: Increasing chemical oxidation state.** 5mC → 5hmC is hydroxylation (C–H → C–OH); 5hmC → 5fC is dehydrogenative oxidation (C–OH → C=O, an aldehyde); and 5fC → 5caC is aldehyde oxidation (C=O → COOH, a carboxylic acid). The reactions become progressively more demanding chemically (aldehyde oxidation requires stronger oxidizing conditions), but the Fe(IV)=O hydrogen-abstraction-and-rebound mechanism works for all three. **Structurally, the cavity permits both the hydroxymethyl group of 5hmC and the aldehyde of 5fC**, allowing the three oxidations to proceed consecutively in the same cavity.

**Why oxidation stops at 5caC**: The carboxyl group of 5caC is negatively charged and is electrostatically repelled by the negatively charged, Asp/Glu-rich active-site environment. It also cannot undergo further hydrogen abstraction because there is no available C–H bond. **The chemical endpoint is determined by the substrate structure.** TDG then enters: it specifically recognizes 5fC/5caC (not 5mC/5hmC) and cleaves the glycosidic bond, leaving an abasic (AP) site that BER repairs to C. The division of labor is clear: “TET oxidizes to the endpoint; TDG excises.”

### 3.3 Substrate recognition: Why only 5mC is oxidized

- The methyl group of 5mC **points toward Fe(II)** (“5mC inserts into the catalytic pocket with its methyl group oriented toward the catalytic Fe(II),” as stated in the original paper).
- Unmodified C lacks the methyl group and cannot “reach” the ferryl intermediate (the distance is wrong). Selectivity comes from **precise substrate positioning within the cavity**.
- Multiple residues lock the 5mC base in place through hydrogen bonds and van der Waals interactions, ensuring that its methyl points toward the catalytic center.
- **CpG preference**: TET2 recognizes the CpG dinucleotide context. The G adjacent to 5mC makes specific contacts with the protein, providing CpG-context recognition. This structurally echoes the fact that most 5mC in the genome occurs at CpG sites.

### 3.3a From “methyl orientation” to “selective oxidation”: One key for one lock

TET’s substrate selectivity seems simple (“it oxidizes only 5mC”), but the structural mechanism behind it is sophisticated:

**Geometry of “methyl orientation.”** Crystal structures show the 5mC methyl group (–CH₃ at C5 of the pyrimidine ring) pointing directly toward the Fe(II) catalytic center. This means that for catalysis to occur, the target of ferryl oxygen—the methyl C–H bond—must lie precisely within hydrogen-abstraction distance (about 2.5–3 Å). At C5, unmodified cytosine (C) has a hydrogen atom (–H). Although hydrogen is small, it lacks the carbon atom that “reaches toward the catalytic center,” and ferryl cannot abstract it effectively: both the C–H bond energy and spatial positioning are unsuitable. **“Methyl is the right handle; hydrogen is the wrong handle.”** TET distinguishes 5mC from C through geometry, rather than simply chemical identity.

**Revisiting “product retention.”** After oxidation of 5mC to 5hmC, C5 bears a hydroxymethyl group (–CH₂OH), slightly larger than methyl but still accommodated by the active cavity. The hydroxymethyl also points toward the Fe center and can be oxidized again (dehydrogenated to an aldehyde). **At each step there is a handle, and the handle remains after oxidation**—the geometric basis for multistep catalysis.

**“Context locking” in CpG recognition.** TET2 recognizes not only 5mC itself but also its CpG dinucleotide context. The guanine (G) at the 3′ side of 5mC makes hydrogen-bonding and base-stacking contacts with TET2 residues—“watch the G to lock onto the C.” **The biological significance of this context preference** is that most genomic 5mC occurs at CpG sites (in gene promoters and gene bodies). TET2’s CpG preference lets it target methylation hotspots rather than erase methylation randomly.

**Why 5hmC is a “way station,” not an endpoint**: 5hmC can be further oxidized by TET (→5fC→5caC, along the demethylation pathway), or it can function as an independent epigenetic mark read by its own binding proteins. “5hmC is both an intermediate in demethylation and an independent signal,” so TET oxidation products have dual functions (see the discussion of 5hmC as an aging biomarker in [01-foundations/02-aging-clocks.md](../01-foundations/02-aging-clocks.md)).

## 4. A “structural map” of cancer mutations

TET2 is frequently mutated in myeloid malignancies (about 10–20%). Mapping mutation sites onto the structure reveals their functional effects:

| Mutation type | Structural location | Functional consequence |
|---|---|---|
| Mutations in Fe(II)/NOG-chelating residues | DSBH active center | Loss of metal/cosubstrate binding → enzyme inactivation |
| Mutations in DNA-interacting residues | DNA-binding surface | Inability to bind/flip substrate → inactivation |
| Mutations in zinc-finger residues | Zn1/Zn2 | Disrupted zinc coordination → abnormal catalytic-domain folding |
| Nonsense/frameshift mutations | Any location | Truncated protein → dominant-negative effects |

**“Mutation map = structure–function map”**: TET2 mutation sites in cancer-genome datasets (including TCGA) map almost entirely to four functional regions: Fe coordination, 2OG binding, DNA interaction, or zinc fingers. This is a classic example of “structure-guided precision medicine” (see the AI drug-design discussion in [08-frontiers/04-ai-drugs/01-ai-discovery.md](../08-frontiers/04-ai-drugs/01-ai-discovery.md)).

## 5. TET and aging: Turning back the clock from a structural perspective

### 5.1 TET is the “eraser” of epigenetic reprogramming

The knowledge base’s reprogramming thread (OSK → TET → demethylation → clock reversal) can be understood at the structural level:

```text
OSK factors ──► activate pluripotency network ──► upregulate TET1/2/3
                                                     │
                                                     ▼
                         TET oxidizes 5mC → 5hmC → 5fC → 5caC (three reactions in the catalytic cavity)
                                                     │
                                                     ▼
                         TDG excision + BER repair → unmodified C (demethylation complete)
                                                     │
                                                     ▼
                         Aging-associated methylation sites are “erased” → epigenetic clock reset
```

- **TET knockdown experiment of Lu 2020** ([02-animal-evidence](../08-frontiers/01-reprogramming/02-animal-evidence.md)): Removing TET1/2 eliminated OSK’s regenerative effects—causal evidence that “reprogramming = TET-mediated demethylation.”
- **Structural significance**: The design of TET’s active cavity (which accommodates 5mC derivatives for successive oxidation) enables efficient “complete-chain demethylation,” providing the molecular throughput needed for clock reversal.
- **TET and aging**: TET expression and activity change with age (declining in some tissues), as do 5hmC levels. Some “epigenetic drift” results from an imbalance between TET and methyltransferases.

### 5.1a The molecular scale of “clock reversal”: How TET acts on hundreds of sites

Epigenetic clocks such as the Horvath clock monitor 353 CpG sites, while reprogramming resets the methylation states of these sites and potentially the entire genome. How does TET accomplish this large-scale task? It helps to establish a sense of scale:

**Estimating the workload.** The human genome contains about 28 million CpG sites, of which roughly 70% are methylated. TET-mediated demethylation during reprogramming does not need to “erase everything”; it needs to reset only the differentially methylated sites associated with aging (thousands to tens of thousands). Even so, this entails thousands of catalytic events per second—**TET enzymes in a single cell must work at high speed**, which depends on three conditions: (1) increased TET expression (transcriptional activation by OSK); (2) abundant substrate (5mC; about 70% of genomic CpGs are methylated); and (3) adequate 2OG/Fe²⁺ supply from mitochondrial metabolism, linking to the “mitochondria–epigenome axis.”

**The appearance and reality of “site selectivity.”** Clock sites such as the 353 Horvath CpGs are merely “probes”; TET itself is not specific to clock sites and oxidizes all accessible 5mC. **Clock reversal is the result of clock sites being reset along with a genome-wide wave of demethylation.** This also explains the “dose–safety” issue in reprogramming: excessive TET activation can erase methylation that should remain (for example, at imprinted genes and transposon-silencing sites), causing genomic instability. “TET activity must be moderate” is a core constraint on the safety of epigenetic reprogramming (see the four layers of defense in Section 3.5 of [01-concept](../08-frontiers/01-reprogramming/01-concept.md)).

**Structural meaning of “partial reprogramming”**: Transient or cyclical OSK expression → transient TET activation → one “round” of demethylation (erasing aging-associated sites) → withdrawal of the factors and decline in TET. **Pulsed TET activation achieves “partial erasure”**—resetting the clock without losing control of the whole genome. This is the molecular essence of “partial reprogramming”: not “partially activating TET,” but “activating TET transiently.”

### 5.2 Structural implications for chemical reprogramming

One ideal goal of small-molecule chemical reprogramming (Guan 2022; Section 3.4 of [01-concept](../08-frontiers/01-reprogramming/01-concept.md)) is to “activate endogenous TET or mimic its activity.” At the structural level, possible strategies include:

- Increase TET expression (epigenetic drugs, such as HDAC inhibitors that upregulate TET transcription).
- Stabilize TET protein (for example, by inhibiting its degradation through deubiquitination).
- Directly activate catalysis (2OG analogs or Fe supply—since 2OG is a cosubstrate, supplementation could theoretically increase TET activity. This is the structural logic behind “α-KG supplementation for anti-aging”; see the α-KG discussion in [02-mitotherapeutics](../08-frontiers/05-mitochondria/02-mitotherapeutics.md)).

## 6. Evidence grading

| Structural finding | Evidence level | Basis |
|---|---|---|
| TET2–DNA crystal structure (5mC flips into cavity) | ★★★★★ Established | PDB 4NM6, 2.02 Å |
| Fe(II) coordination by the HxD motif | ★★★★★ Established | Crystal structure + mutagenesis |
| Bidentate coordination of Fe by 2OG (NOG cocrystal) | ★★★★★ Established | Crystal structure |
| 5mC methyl group points toward Fe(II) | ★★★★★ Established | Directly visible in crystal structure |
| Active cavity accommodates 5mC derivatives (multistep oxidation) | ★★★★ Strong | Structure + biochemistry |
| CpG-recognition mechanism | ★★★★ Strong | Structure + preference assays |
| Cancer mutations cluster at functional residues | ★★★★★ Established | TCGA mutations + structural mapping |
| TET-mediated demethylation in reprogramming (Lu 2020) | ★★★★ Strong | Knockdown experiment + structural interpretation |

**Methodological loop of “structural genomics”**: Analysis of cancer mutations in TET2 illustrates a downstream application of structural biology: genomic sequencing identifies mutations (TCGA/ICGC) → structural mapping identifies their functional impact (Section 4) → functional experiments validate it (enzyme activity/protein stability) → prognosis and targeted strategies are informed. **The sequence-to-structure-to-function loop** is a standard paradigm of modern genomic medicine and underlies the integration of “AI + structure + omics” discussed in [08-frontiers/04-ai-drugs/01-ai-discovery.md](../08-frontiers/04-ai-drugs/01-ai-discovery.md). The same approach can interpret aging-associated epigenetic mutations, such as DNMT3A/TET2 mutations in clonal hematopoiesis of indeterminate potential (CHIP; see [04-immunosenescence](../03-immunity/04-immunosenescence.md)): “structure explains mutations; mutations guide intervention.”

## 7. Connections to the knowledge base’s main themes

- **Epigenetic reprogramming** (Section 3.2 of [01-concept](../08-frontiers/01-reprogramming/01-concept.md)): The structural basis of active TET demethylation is explained atom by atom—base flipping, Fe(IV)=O oxidation, and a three-step relay.
- **Aging clocks** ([01-foundations/02-aging-clocks.md](../01-foundations/02-aging-clocks.md)): TET-mediated demethylation is the molecular executor of clock reversal; erasure of 5mC at clock sites turns the clock back.
- **α-KG and mitochondria** ([02-mitotherapeutics](../08-frontiers/05-mitochondria/02-mitotherapeutics.md)): α-KG (=2OG) is a cosubstrate for TET and other demethylases. Mitochondrial metabolism directly supplies “fuel” for epigenetic reprogramming—the structural connection point of the “mitochondria–epigenome axis.”
- **NO and epigenetic crosstalk** (Section 7.1 of [01-foundations/03-no-basics.md](../01-foundations/03-no-basics.md)): NO can S-nitrosylate DNMT/TET and affect methylation. The two-way dialogue between NO and epigenetic machinery structurally involves the accessibility of cysteine residues to modification.

## 8. Open questions

1. **Full-length TET in the chromatin environment**: The complete structure of TET on a nucleosome, including its N-terminal regulatory domains, has not been resolved. The dynamics of how TET searches chromatin for 5mC are unknown.
2. **Intermediate states in multistep oxidation**: Transition-state structures from 5mC → 5hmC and 5hmC → 5fC have not been captured; time-resolved crystallography is being explored.
3. **Structural differences among TET1/2/3**: The functional significance of the CXXC domain in TET1 (which binds CpG) compared with TET2 (which lacks CXXC, with the IDAX protein serving as a substitute) remains to be determined.
4. **Readers of 5hmC**: The structures of proteins that recognize 5hmC as an independent epigenetic mark remain to be characterized. 5hmC is not only an intermediate product, but also a functional mark.
5. **Pharmacological TET activation**: Can small molecules enhance TET activity for anti-aging demethylation without causing harmful genome-wide demethylation?

## 8.1 Active demethylation in structural perspective

TET-mediated demethylation is not an isolated event. Its structural mechanism runs through the full epigenetic cycle of “writing, reading, and erasing”:

- **Writing (DNMT)**: DNA methyltransferases (DNMT3A/3B establish methylation; DNMT1 maintains it) “write” 5mC into DNA. DNMTs and TET share a base-flipping mechanism (the substrate flips out of the duplex and enters the active cavity), but act in opposite directions (DNMT adds methyl; TET oxidizes it). **“Flip in—modify—flip back” is a general structural strategy for DNA-modifying enzymes.**
- **Reading (MBD/MeCP2)**: Methyl-CpG-binding proteins (MeCP2, MBD1–4) recognize 5mC through a methyl-binding domain (MBD). TET’s oxidation product 5hmC is not recognized by MBD (“5hmC disables the gene-silencing mark”); this explains from the reader’s perspective why oxidation is the first step of erasure.
- **Erasing (TET + TDG + BER)**: TET carries out three oxidations → TDG recognizes and excises 5fC/5caC → BER restores C. This “oxidation–excision–repair” trio forms the complete demethylation machinery (He 2011, *Science*).
- **Contrast with passive demethylation**: When DNMT1 fails to maintain methylation during replication (for example, in proliferating cells), 5mC is diluted by cell division. This passive demethylation is independent of TET-mediated active oxidation; both pathways cooperate during reprogramming.

## 8.2 The “dose and timing” problem for TET in reprogramming and aging

- **TET expression timing during reprogramming**: TET1/2 expression rises during iPSC reprogramming as part of the pluripotency network, with OSK activating TET transcription. But excessive or premature TET activation may cause genome-wide demethylation and genomic instability. “Moderate activation + site selectivity” is key to safe reprogramming.
- **TET and the “site selectivity” of aging clocks**: Aging clocks (Horvath and others) monitor only hundreds of CpG sites. If TET-mediated demethylation could reset just these “clock sites” without disturbing the rest of the genome, it might allow “selective epigenetic rejuvenation.” In practice, TET cannot achieve site specificity, which is an engineering challenge for chemical reprogramming.
- **5hmC as an aging biomarker**: The genomic distribution of 5hmC changes with age (and declines in some tissues). A 5hmC profile can provide a complementary readout of “epigenetic aging” and report downstream TET activity, complementing DNAmAge in [02-aging-clocks](../01-foundations/02-aging-clocks.md).
- **TET and tumor suppression**: TET2 is a tumor-suppressor gene in myeloid malignancies. “TET protects epigenetic homeostasis = cancer prevention”; some anticancer potential of partial reprogramming may result from TET-mediated epigenetic resetting that clears precancerous epigenetic abnormalities.

### 8.3 The dual nature of demethylation from a structural perspective

TET-mediated demethylation is an “eraser” of age-associated methylation in anti-aging, but a double-edged sword in cancer. Understanding its structural basis helps define the safety boundary:

- **Beneficial side (anti-aging/reprogramming)**: TET oxidizes 5mC → erases age-associated methylation → resets clocks and rejuvenates gene expression. Clock reversal and rejuvenation effects, including optic-nerve regeneration in Lu 2020 and lifespan extension in Macip 2024, depend on the TET pathway. **Moderate demethylation = epigenetic resetting.**
- **Harmful side (cancer)**: Excessive TET activation or abnormal expression → widespread genomic demethylation → transposon activation (release of LINE-1 repression → genomic instability), activation of oncogenes through demethylation, and loss of imprinting. **Genome-wide demethylation can be genomic catastrophe.** This explains the apparent paradox in which TET can be tumor suppressive (TET2 loss → myeloid malignancy) but potentially tumor-promoting when overactivated.
- **Structural essence of the “dose window”**: Catalytic activity (Fe(II)/2OG supply) and expression level (transcriptional regulation) jointly determine the extent of demethylation. **Moderate TET activity = epigenetic rejuvenation; excessive TET activity = genomic catastrophe.** This is a core constraint on the safety of epigenetic reprogramming and echoes the logic of the “monitoring layer” among the four defenses in Section 3.5 of [01-concept](../08-frontiers/01-reprogramming/01-concept.md): track demethylation in real time to prevent crossing the boundary.

**Implication for an “immortality drug”**: For epigenetic reprogramming to become a safe route to an “immortality drug breakthrough,” it must solve the problem of site-selective TET activation. Ideally, it would “erase only aging-associated sites, not transposon or imprinting sites,” but TET itself lacks site specificity and oxidizes all accessible 5mC. **Engineering directions**: (1) target TET to specific genomic regions by fusing it to a DNA-binding domain; (2) use pulsed activation for one transient round of erasure; and (3) combine it with transposon-silencing mechanisms (H3K9me3/SIRT6). These structural constraints annotate the engineering bottleneck behind the 31/40 score for epigenetic reprogramming in [09-immortality/02-breakthrough-candidates](../09-immortality/02-breakthrough-candidates.md).

## 9. References (authentic literature)

1. Tahiliani M, Koh KP, Shen Y, et al. Conversion of 5-methylcytosine to 5-hydroxymethylcytosine in mammalian DNA by MLL partner TET1. *Science* 2009;324:930–935. (Discovery of TET)
2. Hu L, Li Z, Cheng J, et al. Crystal structure of TET2-DNA complex: insight into TET-mediated 5mC oxidation. *Cell* 2013;155:1545–1555. (PDB 4NM6)
3. Ito S, Shen L, Dai Q, et al. Tet proteins can convert 5-methylcytosine to 5-formylcytosine and 5-carboxylcytosine. *Science* 2011;333:1300–1303. (Multistep oxidation)
4. He YF, Li BZ, Li Z, et al. Tet-mediated formation of 5-carboxylcytosine and its excision by TDG in mammalian DNA. *Science* 2011;333:1303–1307. (TDG excision)
5. Hashimoto H, Pais JE, Zhang X, et al. Structure of a Naegleria Tet-like dioxygenase in complex with 5-methylcytosine DNA. *Nature* 2014;506:391–395. (Tet-like enzyme structure)
6. Wu X, Zhang Y. TET-mediated active DNA demethylation: mechanism, function and beyond. *Nat Rev Genet* 2017;18:517–534. (TET review)
7. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. *Nature* 2020;588:124–129. (Causal TET experiment)

## 10. Methodology and tools for TET structural research

- **Shared features of the 2OG-dependent dioxygenase family**: TET belongs to the AlkB family of 2OG-dependent dioxygenases, together with the DNA-repair enzyme AlkB and histone demethylases such as JMJD. They share the “Fe(II)–His–His–Asp + 2OG” catalytic core. TET is distinctive because its substrate is DNA-bound 5mC (rather than RNA or histones) and it can carry out successive oxidations. Research on “one active center, multiple reactions” depends on detecting intermediate products (5hmC/5fC/5caC) by quantitative LC-MS/MS.
- **Structural chemistry of detecting 5mC derivatives**: Quantifying 5hmC/5fC/5caC in DNA requires specific antibodies or chemical labeling. For example, the aldehyde group of 5fC can be labeled with hydroxylamine derivatives. “Chemically selective labeling” is an important tool for studying TET activity and monitoring demethylation during reprogramming.
- **Structural modeling and AlphaFold**: The TET catalytic domain and DSBH fold are highly conserved, and AlphaFold2 predictions agree well with crystal structures. “AI structure prediction + crystallographic validation” has accelerated structural research on the TET family, including full-length TET1/3.
- **Mutation–phenotype association analysis**: TCGA TET2 mutations plus structural mapping (Section 4) provide a standard structural-genomics workflow—from cancer genomics to structural interpretation (see [08-frontiers/04-ai-drugs/01-ai-discovery.md](../08-frontiers/04-ai-drugs/01-ai-discovery.md)).

## 11. Summary in five structure–function questions

| Question | Structural answer |
|---|---|
| How does TET selectively oxidize 5mC? | 5mC flips into the cavity with its methyl pointed at Fe(IV)=O; unmodified C cannot reach the catalytic center. |
| How are three oxidations carried out? | The active cavity accommodates 5mC derivatives (5hmC/5fC), which undergo repeated oxidation in the same Fe(IV)=O cycle. |
| How is CpG recognized? | TET2 makes specific contacts with G in the CpG dinucleotide, creating a CpG-context preference. |
| How is demethylation completed? | TET oxidation → TDG excises 5fC/5caC → BER repairs the site to C (“oxidation–excision–repair”). |
| Why do cancer mutations cluster at functional residues? | Mutations in Fe/NOG chelation, DNA interaction, and zinc fingers inactivate the enzyme (“mutation map = functional-region map”). |

**In one sentence**: TET2 is a demethylation eraser in which two zinc fingers stitch together a DSBH iron center. It flips 5mC into the path of Fe(IV)=O for three successive oxidations, after which TDG/BER completes the erasure. Understanding its structure explains both the molecular execution of epigenetic reprogramming (clock reversal) and the functional consequences of cancer mutations.

> **Structural snapshot**: TET2 = Cys-rich domain (zinc-finger stitching) + DSBH domain (Fe–His–His–Asp + 2OG active center). 5mC flips into the cavity, with its methyl pointing toward Fe(IV)=O, and undergoes three oxidations (5mC→5hmC→5fC→5caC); TDG + BER complete demethylation. Cancer mutations map to structural functional regions.
