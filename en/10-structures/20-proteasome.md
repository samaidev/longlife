# Molecular Structure Deep Dive 20: The 20S Proteasome — The "Shredder" of Proteostasis and the Barrel-Shaped Chamber

> **Series Positioning**: 10-structures (Molecular Structure Deep Dive) Part 20 — Dissecting the three-dimensional structure of the 20S proteasome, understanding "how cells send ubiquitin-tagged proteins into a barrel-shaped chamber for shredding," "the spatial layout of three catalytic activities (chymotrypsin-like/trypsin-like/caspase-like)," and the proteasome's role in "protein quality control" during aging. This is the structural foundation of the knowledge base's proteostasis main thread ([06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md)), and together with LC3 autophagy ([18-lc3-autophagy.md](18-lc3-autophagy.md)) constitutes the "dual-channel proteostasis system."
> **Related Articles**: Proteostasis/autophagy see [06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md); LC3 autophagy see [18-lc3-autophagy.md](18-lc3-autophagy.md); Ubiquitin-proteasome system see [05-molecular-mech](../04-drugs/05-molecular-mech.md); NLRP3 see [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md); p53 see [13-p53-structure.md](13-p53-structure.md).

---

## 0. Structure Overview

**In one sentence**: The 20S proteasome is the cell's "protein shredder" — a barrel-shaped (cylindrical) protease complex that takes ubiquitin-tagged proteins in through one end of the barrel, cleaves them into small peptides in the catalytic chamber inside, and expels them from the other end — "the cell's shredding and recycling station for proteins." It divides labor with LC3 autophagy ([18-lc3-autophagy.md](18-lc3-autophagy.md)): the proteasome handles "individual proteins," while autophagy handles "bulk cargo (organelles/aggregates)" — "the shredder handles parts, the dump handles whole machines."

```text
20S Proteasome Structure:
  α ring (×7) — β ring (×7) — β ring (×7) — α ring (×7)    (4 rings × 7 subunits = 28 subunits)
   |         |          |         |
  Gating ring  Catalytic ring  Catalytic ring  Gating ring
  (regulates entry) (β1/β2/β5 activity)  (β1/β2/β5 activity)  (regulates exit)

  Structure:  αββα four-ring stack → barrel-shaped chamber (central cavity)
         α ring: gating (restricts substrate entry) + binds 19S regulatory particle
         β ring: catalytic (β1 caspase-like/β2 trypsin-like/β5 chymotrypsin-like)
```

**Three Major Structural Features** (the atomic basis determining its function):
1. **Barrel-shaped chamber (αββα)**: Four heptameric rings stacked into a barrel, with a catalytic cavity at the center — "the drum of the shredder";
2. **α-ring gating**: The N-terminal tails of the α ring close the barrel opening, regulating substrate entry — "the feed gate of the shredder";
3. **β-ring catalytic triad**: β1/β2/β5 each have their own role (three peptide bond preferences) — "three knives, three types of cuts."

**Core Regulatory Mechanism**:

```text
Ubiquitin-Proteasome System (UPS):
  E1 (activating enzyme) → E2 (conjugating enzyme) → E3 (ligase) → target protein polyubiquitinated (tagged)
      → 26S proteasome (19S+20S) recognizes ubiquitin chain → deubiquitination → substrate unfolding
      → 20S chamber degradation → small peptides (~8-10 aa) → amino acid recycling
```

---

## 1. Why the 20S Proteasome Structure Matters

The proteasome is the core executor of proteostasis:

- **"Protein quality control"**: Degrades misfolded/damaged/unneeded proteins — "the quality inspector shreds defective goods";
- **Pacemaker of "regulatory proteins"**: Degrades cyclins/transcription factors (p53, NF-κB precursor, cyclin) → controls cell cycle/signaling — "the shredder is the pacemaker of cellular rhythm";
- **Aging evidence**: Proteasome activity declines with age → misfolded protein accumulation → accelerated aging; enhancing the proteasome (exercise/certain compounds) extends lifespan in model organisms — "the shredder ages, defective goods pile up";
- **Division of labor with autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): The proteasome degrades "monomeric proteins" (soluble, require unfolding); autophagy degrades "aggregates/organelles" (bulk cargo) — "shredder vs. dump";
- **Immune connection**: The proteasome generates antigenic peptides (MHC-I presentation) — "the shredder is also the immune system's 'ingredient processing plant'";
- **Drug target**: Bortezomib/carfilzomib inhibit the proteasome to treat multiple myeloma — "cancer's 'shredder inhibitors'."

**Three key questions in structural research**:
1. How does the barrel-shaped chamber ensure "only what should be shredded enters" (α-ring gating)?
2. How do the three catalytic activities divide labor (substrate preferences of β1/β2/β5)?
3. How do substrates enter the chamber (the unfolding-translocation mechanism)?

These questions were answered in structures such as 1RYP (yeast 20S, 1997) and 4R3O (human 20S + carfilzomib, 2015).

---

## 2. Structural Anatomy of the 20S Proteasome

### 2.1 Barrel-Shaped Chamber (αββα Four-Ring Stack) — "The Drum of the Shredder"

- Composition: **28 subunits** (4 rings × 7 subunits) — α7β7β7α7 — "four concentric rings";
- Structure: Four heptameric rings stacked → form a central cavity (~15 Å diameter) — "the central channel of the drum";
- Chamber partitioning: α rings form the "anteroom" (substrate entry), β rings form the "catalytic chamber" (degradation occurs) — "anteroom receives, catalytic chamber works";
- Symmetry: C2 symmetry (two αββα half-barrels face to face) — "two half-barrels form one barrel";
- Foundation of 1RYP: The first proteasome crystal structure (2.4 Å) revealed the barrel-shaped fold — "seeing all the parts of the shredder."

### 2.2 α-Ring Gating — "Feed Gate"

- Location: Both ends of the barrel (α7 rings);
- Structure: N-terminal tails (~10-35 residues) of α subunits extend into the channel opening, forming a gate — "the latch";
- Function: Restricts substrate entry (prevents large proteins from freely entering) + binds 19S regulatory particle (forming 26S) — "the gate is both a latch and a doorbell";
- Gating states: Dynamic switching between open/closed (opens when 19S/substrate binds) — "gate opens and closes on demand";
- Substrate selectivity of the "gate": Small peptides/unfolded proteins can pass through; folded proteins require 19S unfolding — "the gate only lets 'loose parts' in."

### 2.3 β-Ring Catalysis — "Three Knives"

- Location: Two β7 rings (inner wall of the barrel);
- Catalytic subunits: β1 (caspase-like, cleaves after acidic residues), β2 (trypsin-like, cleaves after basic residues), β5 (chymotrypsin-like, cleaves after hydrophobic residues) — "three knives, three types of cuts";
- Catalytic mechanism: N-terminal threonine) — "threonine's hydroxyl group serves as the 'blade'";
- Products: Small peptides of ~8-10 amino acids — "cut into standard-sized 'parts'";
- Finding from 4R3O: Carfilzomib covalently binds β5's Thr1 (irreversible inhibition) — "the drug 'welds shut' the main knife."

---

## 3. Molecular Logic of Protein Degradation: From Structure to Chemistry

### 3.00 The Engineering Wisdom of the "Barrel Design": Why the Shredder Is Built as a Barrel

**Why seven subunits per ring?** The heptameric ring (7 subunits/ring) is not a random number — ① Seven is "the integer arrangement closest to circular" (7 × ~51° ≈ 360°), making the ring nearly a perfect circular channel — "a round tube is better for feeding than a square one"; ② The subunit interfaces of the heptameric ring have a "tilt" (β subunit active sites face inward) — "all 7 seats face the center"; ③ The "asymmetry" of seven (not the neat symmetry of 6/8) facilitates staggered stacking between rings — "odd-numbered arrangement, rings interlock more stably."

**Why four rings (αββα)?** ① α rings at both ends (gating + binding 19S) — "doors at the entry and exit"; ② β rings in the middle (catalytic chamber) — "knives in the center of the workshop"; ③ Two β rings face to face → the catalytic chamber is "deepened" (active sites of both β rings together form a longer degradation channel) — "the workshop is deep enough to cleave even long proteins."

**Why is the chamber ~15 Å?** The 15 Å channel only allows "unfolded peptide chains" (diameter ~5-10 Å) to pass, not folded proteins (diameter >20 Å) — "channel size = natural access control, only loose parts allowed" — this is more fundamental than "tag recognition": even without a ubiquitin tag, folded proteins cannot enter — "physical filtering + tag verification, double insurance."

**Why does the Ntn hydrolase use N-terminal threonine?** Thr1 of β subunits is exposed to the chamber interior (N-terminal nucleophile) — "the blade is mounted on the inner wall of the chamber, facing the channel" — this is the common design of the "N-terminal nucleophile hydrolase (Ntn)" family: the active site is provided by the subunit's N-terminus, covalently integrated with the barrel wall — "the knife and the wall are one piece, cannot be removed" — **"the catalytic center is fixed on the chamber wall, substrates pass through the middle, and the knife cuts from the side"** — this is the most elegant aspect of barrel-shaped proteases.

### 3.0 Why "Shredding" Must Occur Inside a Barrel

**"Barrel isolation = safety."** If the proteasome were exposed in the cytoplasm, it would randomly degrade any protein ("shredding" the cell) — "leaving knives lying around will hurt people." The barrel-shaped chamber **isolates catalytic activity inside the barrel** — only substrates that "can enter the gate" are degraded — "knives locked in the kitchen, only processing ingredients brought in."

**"Gating = precision."** α-ring gating ensures "only what should be degraded" (ubiquitinated + unfolded) enters — "the feed gate checks, only defective goods enter, good goods are exempt." This ensures the proteasome "does not cause collateral damage" — "the quality inspector is at the door, not at every workstation."

**"Chamber = controllable process."** Substrates enter from one end and exit from the other — a one-way channel, with the degradation process completed inside the chamber — "assembly line flows one way, no backflow."

### 3.1 "Ubiquitin Tags" and "Unfolding-Translocation": Two Preparation Steps Before Entry

**Step 1: Ubiquitination (tagging).** E1→E2→E3 cascade → polyubiquitin chain (K48 linkage) on target protein lysine → "to-be-shredded" tag — "tracking number (K48 chain)";
**Step 2: Unfolding (unpacking).** The AAA-ATPase (Rpt1-6) of the 19S regulatory particle recognizes the ubiquitin chain → deubiquitinating enzyme (USP14, etc.) clips the chain → ATP-driven substrate unfolding → translocation into the 20S chamber — "unpacking, stuffing into the shredder";
**Step 3: Degradation (shredding).** Three catalytic activities in the 20S chamber cleave peptide bonds → small peptides → release — "shredded into standard parts";
**"Energy cost"**: Unfolding/translocation requires ATP (19S ATPase) — "unpacking costs electricity."

**The complete chain of "selectivity"**: Ubiquitination (who to shred) → 19S recognition (confirm tag) → unfolding (prepare for barrel entry) → 20S degradation (execute shredding) — "tag-verify-unpack-shred" four-step assembly line — **"every step has a checkpoint, the mis-shred rate is extremely low."**

---

## 4. Proteasome and Aging: "Shredder Aging" from a Structural Perspective

### 4.1 Age-Related Decline of the Proteasome

- **Activity decline**: Proteasome activity decreases in aged tissues (20S/26S levels or catalytic efficiency ↓) — "shredder aging";
- **Subunit changes**: Oxidative damage/misfolding accumulation → proteasome itself gets damaged — "the shredder rusts itself";
- **Regulatory decline**: 19S regulatory particle levels/function decrease → reduced 26S assembly — "half the feed gate is broken";
- **Consequences**: Misfolded/oxidized protein accumulation → proteotoxicity (neurodegeneration/sarcopenia) → accelerated aging — "defective goods pile up on the factory floor, quality control paralyzed."

### 4.2 Anti-Aging Strategies: "Repairing the Shredder"

- **Exercise**: Exercise enhances proteasome activity (adaptation of the ubiquitin-proteasome system) — "use it or lose it; the more you use the shredder, the sharper it gets";
- **Caloric restriction**: CR enhances proteasome activity — "moderate hunger, stricter quality control";
- **Small-molecule activators**: Certain compounds (e.g., oleuropein) enhance the proteasome — "oiling the shredder";
- **Reducing burden**: Reduce production of misfolded proteins (glucose control/antioxidants) → shredder doesn't have to work overtime — "fewer defective goods, shredder doesn't get tired";
- **The "moderation" principle**: Excessive proteasome activation may accelerate degradation of normal proteins (e.g., muscle proteins) — "the shredder can't be too aggressive, or it'll damage good parts."

### 4.20 The Marvelous Mechanism of "Partial Degradation": The Shredder Can Also Be a "Processing Plant"

One of the most "counterintuitive" functions of the proteasome is **"partial degradation" (limited processing)** — not completely chopping up a protein, but "snipping off a segment." The most famous example is NF-κB precursor p105→p50 ([14-nfkb-structure.md](14-nfkb-structure.md)):

**"Limited processing of p105→p50."** After p105 (NF-κB precursor) is ubiquitinated, the proteasome does not fully degrade it, but degrades the C-terminal half, retaining the N-terminal p50 (containing the RHD domain) → p50 forms an NF-κB dimer with p65 — "the shredder 'snips half,' keeping the useful front portion."

**Structural mechanism of "limited processing" (model)**: The C-terminus of p105 contains a "glycine-rich region" (GRR) → prevents complete proteasomal degradation ("jamming" translocation) → only the C-terminus is degraded, the N-terminus is retained — "a 'baffle' gets stuck during feeding, so it only grinds up to the baffle."

**Other examples of "limited processing"**: SREBP (lipid metabolism transcription factor), Cubitus interruptus (Hedgehog signaling) — "snip a segment, activate a transcription factor" — "the shredder moonlights as a 'protein processing plant.'"

**Anti-aging/pharmacological significance of "limited processing"**: ① Understanding the "processing dependence" of NF-κB activation → regulating p105 processing can regulate inflammation; ② Part of the mechanism of proteasome inhibitors (bortezomib) in treating myeloma = blocking NF-κB processing — "jam the trimming, cancer cells 'go deaf' (NF-κB signaling cut off)" — "the proteasome is not just a garbage dump, but also a signaling processing plant — its 'trimming' function is a goldmine for drug targets."

### 4.3 "Dual Pathways": Proteasome vs. Autophagy

| Dimension | Proteasome (20S/26S) | Autophagy (LC3 pathway) |
|---|---|---|
| Substrate | Monomeric proteins (soluble) | Aggregates/organelles/bulk cargo |
| Tag | Ubiquitin (K48 chains) | LC3-LIR receptors |
| Structure | Barrel-shaped chamber | Double-membrane vesicle |
| Energy | ATP (19S unfolding) | ATP (membrane formation/fusion) |
| Product | Small peptides (8-10 aa) | Amino acids/small molecules |
| Aging trend | Activity ↓ | Activity ↓ |

**Coordination of "dual pathways"**: Soluble misfolded proteins → proteasome; aggregation-prone proteins/organelles → autophagy — **"the shredder handles loose parts, the dump handles large items"** — the two work synergistically to maintain proteostasis. **Anti-aging insight**: Both pathways need repair — "both the shredder (proteasome) and the dump (autophagy) must be functional for the cell to stay clean."

### 4.30 "Age-Related Proteotoxicity": The Consequence Chain of Shredder Failure

**Step 1: Defective goods accumulate.** Proteasome activity↓ → slower degradation of misfolded/oxidized proteins → more "defective goods" in the cytoplasm — "quality inspector efficiency drops, defective goods hit the shelves."

**Step 2: Aggregation and toxicity.** Defective proteins tend to aggregate (hydrophobic surfaces exposed) → form aggregates/oligomeric toxins (prefibrillar oligomers) → interfere with membranes/organelles/signaling — "defective goods pile together, blocking the production line."

**Step 3: Chaperone system overload.** Aggregates consume molecular chaperones (Hsp70, etc.) → insufficient chaperones → more proteins fail to fold → vicious cycle — "rescue teams are bogged down by defective goods, new proteins have no one to help them fold."

**Step 4: Cell damage.** Proteotoxicity → mitochondrial damage (ROS↑, [12-complex1-structure.md](12-complex1-structure.md)), inflammation (NLRP3, [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)), apoptosis — "defective goods trigger system-wide failure."

**Step 5: Tissue aging.** Neurodegeneration (AD/PD protein aggregation), sarcopenia (muscle protein mass↓), heart (misfolded protein accumulation) — "proteotoxicity = the histological hallmark of aging."

**"Prevention-Clearance" dual strategy**: ① Prevention (reduce defective goods: antioxidants/glucose control/temperature control); ② Clearance (enhance degradation: exercise/CR/activators) — "produce fewer defective goods + clear them frequently" — **"proteotoxicity cannot be solved by 'fixing one enzyme'; it requires maintenance of the 'entire quality control system.'"**

---

## 5. Evidence Grading

| Structural Fact | Evidence Level | Basis |
|---|---|---|
| 20S is αββα four-ring barrel structure | ★★★★★ Definitive | 1RYP (1997 Nature) |
| 28 subunits (4×7) | ★★★★★ Definitive | 1RYP |
| α-ring N-terminal tail gating | ★★★★★ Definitive | Multiple structures |
| β1/β2/β5 three catalytic activities | ★★★★★ Definitive | Biochemistry + structure |
| N-terminal Thr1 catalysis (Ntn hydrolase) | ★★★★★ Definitive | 1RYP etc. |
| Carfilzomib covalent binding to β5 Thr1 | ★★★★★ Definitive | 4R3O (2015 Structure) |
| Proteasome activity declines with age | ★★★★ Strong | Multi-tissue studies |
| Exercise/CR enhances proteasome | ★★★★ Strong | Animal studies |

---

## 6. Connections to Knowledge Base Main Threads

### 6.0 The Structural Family of "Proteostasis": Proteasome–Autophagy–UPR

| Molecule | Role | Structure Article | Aging Trend |
|---|---|---|---|
| 20S Proteasome | Monomeric protein shredder | [20-proteasome.md](20-proteasome.md) | Activity ↓ |
| LC3/Autophagy | Bulk cargo recycling station | [18-lc3-autophagy.md](18-lc3-autophagy.md) | Activity ↓ |
| (UPR not listed) | ER stress response | — | Dysregulated |

**Three pillars of "proteostasis"**: ① Synthesis (ribosome/mTOR); ② Folding (chaperones/UPR); ③ Degradation (proteasome + autophagy) — **"the balance of synthesis-folding-degradation determines proteome health."** In aging: degradation pathways↓ (proteasome/autophagy) + dysregulated synthesis (mTOR) → misfolded protein accumulation — "both the production line and the recycling station have problems, defective goods pile up."

**Anti-aging intervention from a proteostasis perspective**: ① Reduce misfolded proteins (antioxidants/glucose control); ② Enhance degradation (exercise/CR/activators); ③ Maintain folding (chaperone induction, heat shock response) — "produce fewer defective goods + fix the shredder + fix the folding machine" — a three-pronged approach.

### 6.00 "Heat Shock Response": The "Emergency Generator" of Proteostasis

**"What is HSR"**: Heat/stress → heat shock factor (HSF1) activation → upregulates molecular chaperones (Hsp70/Hsp90/small Hsp) — "during stress, the cell launches a 'folding rescue team.'"

**"Structural logic of HSR"**: HSF1 is a transcription factor (in the same "stress transcription factor" family as FOXO3/p53); chaperones are "folding machines" (Hsp70's ATPase cycle drives folding) — "the rescue team is dispatched by the 'commander-in-chief (HSF1)' and executed by 'folding machines (chaperones).'"

**"HSR and anti-aging"**: ① Mild stress (exercise/heat exposure/fasting) induces HSR → enhances proteostasis (hormesis) — "small stimulus, big adaptation"; ② HSF1 activity declines with age → sluggish stress response — "emergency generator aging"; ③ Enhancing HSR (heat exposure/exercise/certain compounds) extends lifespan in model organisms — "fix the emergency generator."

**Coordination of the "three pillars"**: HSR (folding rescue) → reduce misfolded proteins; proteasome (monomeric shredding) → degrade soluble defective goods; autophagy (bulk recycling) → clear aggregates/organelles — **"rescue-shred-recycle, three lines of defense, jointly maintaining proteostasis"** — "the cell's quality control is a 'three-dimensional defense,' not a single point."

### 6.1 Main Thread Article Dialogue

- **Proteostasis/Autophagy** ([06-proteostasis-autophagy](../01-foundations/06-proteostasis-autophagy.md)): This article and the LC3 article are its structural foundation — "structural diagram of the dual pathways";
- **LC3/Autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): Shredder vs. dump — "division of labor in the dual pathways";
- **p53 Structure** ([13-p53-structure.md](13-p53-structure.md)): p53 is the star substrate of proteasomal degradation (MDM2 ubiquitination) — "the fate judge is also managed by the shredder";
- **NF-κB Structure** ([14-nfkb-structure.md](14-nfkb-structure.md)): p105→p50 requires proteasomal processing (partial degradation) — "the processing plant of the inflammation switch";
- **NLRP3** ([19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)): Ubiquitination regulates NLRP3 degradation — "the alarm is also managed by the shredder";
- **mTOR Structure** ([04-mtor-structure.md](04-mtor-structure.md)): mTOR regulates protein synthesis — "the growth switch manages production, the shredder manages destruction";
- **Rapamycin** ([06-mtor-rapamycin](../04-drugs/06-mtor-rapamycin.md)): mTOR inhibition → autophagy↑ — "release the gas pedal, the dump opens."

---

## 7. Structure-Aging "Five Questions" Summary

| Question | Structural Answer |
|---|---|
| How does the proteasome only shred "what should be shredded"? | Ubiquitin tag + 19S recognition + α-ring gating — "tag + verify + gate-keep" |
| How do the three catalytic activities divide labor? | β1 (after acidic)/β2 (after basic)/β5 (after hydrophobic) — "three knives, three types of cuts" |
| How do substrates enter the barrel? | 19S ATPase unfolds → translocates into chamber — "unpack, stuff into shredder" |
| Why does the proteasome decline with age? | Activity↓/subunit damage/19S reduction — "shredder aging and rusting" |
| How to resist aging? | Exercise/CR/activators enhance proteasome + reduce misfolded proteins — "fix the shredder + produce fewer defective goods" |

**Structural intuition beyond the five questions**: The proteasome story reveals a universal design principle of "molecular machines" — **"dangerous functions must be isolated within safe structures."** Proteases (enzymes that can cut proteins) are "dangerous goods" for the cell — if exposed, they would shred everything. Evolution's answer: **lock proteases inside a barrel**, using gating to restrict entry — "dangerous tools locked in a dedicated room." This principle recurs: **lysosomes** (hydrolases locked in membranes), **autophagosomes** (degradation occurs in enclosed vesicles), **mitochondria** (ROS generation isolated in the inner membrane) — "wherever there are dangerous functions, there are isolating structures." **Anti-aging insight**: In aging, "isolating structures" degrade (lysosomal leakage/proteasome efficiency↓/mitochondrial damage) → "dangerous goods leak" → cell damage — "part of anti-aging is maintaining the walls of these 'dangerous goods warehouses'" — **"cell safety depends on how well 'dangerous functions' are isolated."**

---

## 8. Open Questions

1. **26S holoenzyme structure**: Conformational dynamics of the complete 19S+20S 26S (substrate translocation intermediates);
2. **Gating dynamics**: Real-time regulation of α-ring gate opening/closing (single-molecule studies);
3. **Immunoproteasome**: Structure and function of interferon-induced immune subunits (β1i/β2i/β5i);
4. **Proteasome activators**: Binding sites/mechanisms of small-molecule activators;
5. **"Partial degradation" mechanism**: How "limited processing" such as p105→p50 is achieved;
6. **Proteasome and neurodegeneration**: Precise mechanisms of proteasome dysfunction in AD/PD.

### 8.1 "Immunoproteasome": The Shredder Moonlights as an "Antigen Processing Plant"

**"Interferon-induced subunit replacement"**: IFN-γ induces β1i/β2i/β5i to replace β1/β2/β5 → immunoproteasome — "the shredder is swapped for an 'immune special edition.'"

**"Changed cleavage preferences"**: Immune subunit cleavage preferences → produce more "hydrophobic C-terminal" peptides → better suited for MHC-I binding (MHC-I prefers hydrophobic C-termini) — "cutting dishes the immune system loves to eat."

**"Antigen presentation"**: Immunoproteasome degrades viral/tumor proteins → peptides → MHC-I presentation → CD8 T cell recognition — "the shredder 'chops and photographs' the enemy, letting the immune system issue a wanted poster."

**"Anti-aging significance"**: ① In immune aging, immunoproteasome function↓ → antigen presentation↓ → immune surveillance↓ (tumor/infection risk↑) — "wanted posters can't be sent out"; ② Enhancing immunoproteasome (exercise/IFN mimics) may enhance immune surveillance — "fix the 'antigen processing plant'" — "proteostasis and immune surveillance are connected through a single 'barrel.'"

---

## 9. Structural Data Acquisition Guide

- **PDB Entries**:
  - 1RYP: Yeast 20S proteasome (2.4 Å, Groll 1997 *Nature*) — barrel structure foundation;
  - 4R3O: Human constitutive 20S + carfilzomib (2.60 Å, Harshbarger 2015 *Structure*) — drug binding;
  - 4R67: Human constitutive 20S (unbound, 2.9 Å);
  - 5GJR/5GJQ etc.: Human 26S holoenzyme (cryo-EM);
  - 3UNE etc.: Yeast 26S;
  - AlphaFold: AF-P28072 (human β5 subunit).
- **Viewing Tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (Real Literature)

1. Groll M, Ditzel L, Löwe J, et al. Structure of 20S proteasome from yeast at 2.4 A resolution. *Nature* 1997;386:463-471. (PDB 1RYP)
2. Harshbarger W, Miller C, Diedrich C, Sacchettini J. Crystal structure of the human 20S proteasome in complex with carfilzomib. *Structure* 2015;23:418-424. (PDB 4R3O)
3. Löwe J, Stock D, Jap B, Zwickl P, Baumeister W, Huber R. Crystal structure of the 20S proteasome from the archaeon T. acidophilum at 3.4 A resolution. *Science* 1995;268:533-539. (Archaeal 20S first structure)
4. Hershko A, Ciechanover A. The ubiquitin system. *Annu Rev Biochem* 1998;67:425-479. (Ubiquitin system classic review)
5. Vilchez D, Saez I, Dillin A. The role of protein clearance mechanisms in organismal ageing and age-related diseases. *Nat Commun* 2014;5:5659. (Protein clearance and aging)
6. Tomko RJ Jr, Hochstrasser M. Molecular architecture and assembly of the eukaryotic proteasome. *Annu Rev Biochem* 2013;82:415-445. (Proteasome assembly)
7. Kisselev AF, Goldberg AL. Proteasome inhibitors: from research tools to drug candidates. *Chem Biol* 2001;8:739-758. (Proteasome inhibitor review)

---

> **Structural Overview**: The 20S proteasome is the cell's **"protein shredder"** — 28 subunits (α7β7β7α7) stacked into a **barrel-shaped chamber** (1RYP foundation); α-ring gates the feed, β-ring three knives (β1 acidic/β2 basic/β5 hydrophobic, N-terminal Thr1 catalysis) shred; **ubiquitin tag (E1-E2-E3) → 19S recognition and unfolding → 20S degradation**. **In aging, proteasome activity↓ → misfolded protein accumulation accelerates aging** — anti-aging strategy: exercise/CR/activators enhance proteasome + reduce misfolded proteins — "fix the shredder, produce fewer defective goods, keep the cell clean."
