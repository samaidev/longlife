# Molecular Structure Deep Dive 33: SIRT6 — The “Longevity Deacylase,” Genome Guardian, and Metabolic Tuner

> **Topic placement**: Article 33 in 10-structures (Molecular Structure Deep Dive), examining the three-dimensional structure of SIRT6 (sirtuin 6), how an NAD⁺-dependent deacylase works, why SIRT6 deacetylates slowly but de-fatty-acylates rapidly, and its multitasking roles in DNA repair, telomere maintenance, and glucose metabolism. A sister article to SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)).
> **Related articles**: NAMPT and NAD⁺ synthesis ([10-nampt-structure.md](10-nampt-structure.md)); SIRT1, a family representative ([06-sirt1-structure.md](06-sirt1-structure.md)); TERT and telomere maintenance ([11-telomerase-structure.md](11-telomerase-structure.md)); p53 and the DNA-damage response ([13-p53-structure.md](13-p53-structure.md)).

---

## 0. Structural overview

**In one sentence:** SIRT6 is an NAD⁺-dependent deacylase. It mainly deacetylates H3K9ac/H3K56ac (gene silencing and DNA repair) and also removes long-chain fatty acyl groups (regulating TNF-α secretion). It is the genome-guardian counterpart to SIRT1: it trims acetyl groups on chromatin, safeguards genome stability, and regulates glucose metabolism.

```text
SIRT6 architecture:
  Rossmann-fold domain (NAD⁺ binding) — zinc-finger domain (substrate/chromatin binding) — small domain (substrate channel)
                         │
  Catalysis: NAD⁺ + acetyl-lysine → O-acetyl-ADP-ribose + deacetylated lysine + nicotinamide
                         │
  Substrates: H3K9ac/H3K56ac (deacetylation) / long-chain fatty-acyl lysine (defatty-acylation; TNF-α)
                         │
  Functions: chromatin silencing | DNA double-strand-break repair | telomere maintenance | glucose-metabolism transcription
```

**Three structural features:** the Rossmann-fold domain is the sirtuin-family NAD⁺-binding pocket; the zinc-finger domain binds substrates/chromatin; and a substrate channel links the NAD⁺ pocket to the substrate site, allowing acyl groups to move toward NAD⁺.

**Core catalytic profile:** SIRT6 deacetylation of H3K9ac/H3K56ac is slow—about 1,000-fold slower than SIRT1 in the cited assays—whereas removal of long-chain fatty-acyl lysine is rapid and may be a major physiological function. NAD⁺ is the shared cosubstrate. Products include O-acetyl-ADP-ribose or O-fatty-acyl-ADP-ribose and nicotinamide.

**Mnemonic:** SIRT6 is an NAD⁺-dependent deacylase: Rossmann fold (NAD⁺ pocket) + zinc finger (substrate grip) + a channel that accommodates long-chain fatty acyl groups. It consumes NAD⁺, helps maintain the genome, and tunes glucose metabolism. NAD⁺ replenishment is like recharging it ([10-nampt-structure.md](10-nampt-structure.md)).

---

## 1. Why SIRT6 structure matters

SIRT6 is a prominent target in aging research. Overexpression extends lifespan in male mice (Kanfi et al., 2012). It recruits or activates DNA-repair machinery, including pathways for double-strand breaks (NHEJ/HR), and helps maintain genomic stability. It maintains silencing of telomeric chromatin, supporting telomere stability. It suppresses glycolytic genes—HIF-1α targets—and thereby regulates metabolism. Its defatty-acylation activity regulates TNF-α secretion, linking it to inflammation (revealed by 3ZG6).

SIRT6 complements SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)): SIRT1 is associated especially with metabolism and stress responses, while SIRT6 is associated with the genome and telomeres. Both are important consumers in the NAD⁺ economy. NAD⁺ availability ([10-nampt-structure.md](10-nampt-structure.md)) can influence SIRT6 activity; NAD⁺ replenishment or NAMPT activation may support it.

Three structural questions are central: Why is SIRT6 deacetylation about 1,000 times slower than SIRT1’s? Why is its defatty-acylation activity rapid (the “hidden function” revealed by 3ZG6)? How does NAD⁺ participate in catalysis through the Rossmann fold and nicotinamide channel? Structures 3K35 (the first SIRT6 structure, 2011) and 3ZG6 (defatty-acylation, 2013) illuminate these questions.

---

## 2. Structural anatomy of SIRT6

### 2.1 Rossmann-fold domain: the NAD⁺ pocket

The N-terminal domain has a classic α/β Rossmann fold for NAD⁺ binding. The nicotinamide and adenine portions of NAD⁺ are anchored in the pocket. Structure 3K35 showed a relatively shallow/open NAD⁺ pocket, a feature relevant to substrate recognition and compatible with the enzyme’s preference for larger fatty-acyl substrates.

### 2.2 Zinc-finger domain: the substrate grip

A zinc ion stabilizes the zinc-finger domain near the center of the structure. It helps bind acetylated substrates and chromatin, including histone H3 tails. SIRT6’s zinc-finger region and substrate channel differ from SIRT1’s, helping explain their different substrate preferences.

### 2.3 Substrate channel: the acyl-group slide

The channel lies between the zinc-finger and Rossmann domains and connects the substrate-binding site to the NAD⁺ pocket. Structure 3ZG6 showed that it is relatively wide and suited to long-chain fatty-acyl groups, helping explain rapid defatty-acylation.

---

## 3. Molecular logic of sirtuin catalysis: from structure to chemistry

### 3.00 Why sirtuins consume NAD⁺: a chemical choice from HDACs to sirtuins

Class I/II HDACs use Zn²⁺ to polarize water and hydrolyze acetyl groups without consuming NAD⁺. Class III sirtuins instead use NAD⁺ as a cosubstrate, cleaving its glycosidic bond; each deacylation consumes one NAD⁺. This “cost” couples activity to metabolic state, because NAD⁺ availability reflects energy and stress conditions. Nicotinamide provides feedback inhibition, and NAD⁺ levels offer a means of regulation. Sirtuins are ancient proteins found in bacteria, and their NAD⁺-dependent chemistry is evolutionarily conserved.

The energetic price buys metabolic coupling and adjustability: the enzyme’s activity follows the “fuel supply.” NAD⁺ is also contested by other consumers. PARP uses it in DNA repair ([09-parp1-structure.md](09-parp1-structure.md)), and CD38 also consumes it ([08-cd38-structure.md](08-cd38-structure.md)); the finite NAD⁺ pool therefore allocates resources among competing processes.

### 3.10 The journey of the acetyl group: from lysine to ADP-ribose

Sirtuin deacetylation can be described in two chemical stages. First, the acetyl group on acetyl-lysine attacks the 1''-ribose carbon of NAD⁺, forming an O-acetyl-ADP-ribose intermediate and releasing nicotinamide. Hydrolysis of the intermediate yields O-acetyl-ADP-ribose (OAADPr) and restores unacetylated lysine.

Nicotinamide (NAM), a reaction product, can rebind and inhibit the enzyme by feedback. NAMPT recycles it into the NAD⁺ salvage pathway ([10-nampt-structure.md](10-nampt-structure.md)), helping relieve inhibition. The substrate channel determines which acyl groups can enter: SIRT6’s wider channel accommodates long-chain fatty acyl groups, which helps account for its rapid defatty-acylation.

### 3.20 SIRT6’s “slow deacetylation, fast defatty-acylation”: specialization, not weakness

The low deacetylase activity initially observed in 3K35—about 1,000-fold slower than SIRT1 in several assays—could be misread as evidence that SIRT6 is weak. The 3ZG6 work revealed that SIRT6 efficiently removes long-chain fatty-acyl groups, including myristoyl and palmitoyl modifications. Its substrate channel is better suited to long hydrophobic acyl groups than to acetyl-lysine, which it binds less optimally.

SIRT6 may therefore specialize in defatty-acylation, including regulation of TNF-α secretion, while deacetylation is another function. Its roles span genome regulation (H3K9/K56 deacetylation) and inflammation (fatty-acyl removal from TNF-α), with additional metabolic effects. Its “main job” cannot be inferred from the best-known activity alone; structure, biochemistry, and functional studies must be considered together. As a multifunctional enzyme, SIRT6 may offer several points of intervention—but this does not establish that indiscriminate enhancement is beneficial.

The same catalytic logic can be summarized this way: unlike zinc-dependent HDACs, sirtuins use NAD⁺ as a chemical cosubstrate. The acyl group is transferred to the ADP-ribose portion, nicotinamide is released, and NAM can feed back on the enzyme until recycled through NAMPT. SIRT6’s relatively low acetyl-lysine activity is consistent with a channel better suited to long-chain fatty-acyl substrates.

### 3.1 Discovery of defatty-acylation: the 3ZG6 finding

The 2013 3ZG6 structure and accompanying work established SIRT6’s ability to remove long-chain fatty-acyl modifications from lysine, extending its role beyond deacetylation. Protein lysines can be modified with fatty acids such as myristate or palmitate; SIRT6 removes these groups efficiently. Defatty-acylation of TNF-α regulates its secretion and thus provides a link to inflammatory control.

The structure revealed a hydrophobic channel that can accommodate long fatty-acyl chains. In contrast to SIRT1’s strong deacetylase activity in metabolic regulation, SIRT6 has a distinct profile: efficient defatty-acylation and slower deacetylation linked to genome regulation. These differences illustrate how family members divide labor by compartment and substrate specificity. SIRT6 adds a defatty-acylation dimension to the sirtuin family’s acylation-regulatory repertoire.

---

## 4. SIRT6 and aging: the genome guardian in structural perspective

### 4.1 Evidence for SIRT6 in aging

- **Lifespan:** SIRT6 overexpression extends lifespan in male mice (Kanfi et al., 2012, *Nature*). Loss-of-function models show genomic instability and premature-aging-like features, providing complementary evidence.
- **DNA repair:** SIRT6 deficiency impairs repair, destabilizes the genome, and causes premature-aging phenotypes.
- **Telomeres:** SIRT6 maintains telomeric silencing and chromatin stability, complementing telomere extension by TERT ([11-telomerase-structure.md](11-telomerase-structure.md)).
- **Metabolism:** SIRT6 knockout causes severe glucose and metabolic dysregulation and can be lethal in mice, indicating an essential role.
- **Inflammation:** Defatty-acylation of TNF-α provides an inflammatory-control function and intersects with NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md)).

### 4.4 Molecular details of SIRT6 in DNA repair: a coordinator of double-strand-break repair

When a DNA double-strand break (DSB) occurs, SIRT6 is recruited to the chromatin at the break. It deacetylates H3K9ac/H3K56ac and alters the local chromatin state. It then recruits or activates repair proteins, including DNA-PK and non-homologous end-joining (NHEJ) factors, helping initiate repair. At telomeres, SIRT6 maintains H3K9 deacetylation and heterochromatic silencing, helping prevent telomere–telomere fusion. This complements, rather than replaces, telomere extension by TERT.

SIRT6 deficiency lowers DSB repair, allowing mutations and genomic instability to accumulate and producing premature-aging phenotypes (as reported by Mostoslavsky et al., 2006). The genome guardian’s failure leaves the genome increasingly damaged.

### 4.5 SIRT6 and glucose metabolism: the HIF-1α brake

SIRT6 deacetylates H3K9ac at promoters of HIF-1α target genes, including glycolytic genes, repressing their transcription and restraining glycolysis. In SIRT6-knockout mice, glycolytic genes rise as HIF-1α regulation is disrupted; glucose uptake and metabolism become abnormal, with severe and sometimes lethal consequences. SIRT6 is therefore a stabilizer of glucose metabolism.

Excessive glycolysis is associated with aging-related metabolic dysregulation and cancer (including the Warburg effect), although the implications depend on tissue and context. SIRT6’s metabolic role intersects with AMPK, an energy sensor ([03-ampk-structure.md](03-ampk-structure.md)), and mTOR, which promotes biosynthesis ([04-mtor-structure.md](04-mtor-structure.md)): SIRT6 regulates glucose, AMPK senses energy, and mTOR regulates growth. Healthy aging involves balance among these pathways.

### 4.2 SIRT6 and SIRT1: division of labor in the sirtuin network

| Family member | Major functions | Structural article |
|---|---|---|
| SIRT1 | Metabolism/stress responses (deacetylation) | [06-sirt1-structure.md](06-sirt1-structure.md) |
| SIRT6 | Genome/telomeres/glucose metabolism (deacetylation and defatty-acylation) | [33-sirt6-structure.md](33-sirt6-structure.md) |
| SIRT3 | Mitochondrial metabolism | Not listed |
| SIRT7 | Ribosomes/chromatin | Not listed |

Sirtuins also divide labor by compartment: SIRT1 in the nucleus/cytoplasm, SIRT6 in the nucleus/chromatin, and SIRT3 in mitochondria. NAD⁺ is their common fuel ([10-nampt-structure.md](10-nampt-structure.md)); raising NAD⁺ can affect multiple family members, not SIRT6 alone.

### 4.3 The NAD⁺ economy’s endpoint: from NAMPT to SIRT6

NAMPT synthesizes NAD⁺ through the salvage pathway ([10-nampt-structure.md](10-nampt-structure.md)); sirtuins consume NAD⁺ during deacylation and release NAM, which can be recycled by NAMPT. In this cycle, NAMPT makes NAD⁺, sirtuins consume it, and NAM is reclaimed ([01-foundations/04-nad-sirtuin.md](../01-foundations/04-nad-sirtuin.md)). NAD⁺ declines with age in association with reduced NAMPT and increased CD38 ([08-cd38-structure.md](08-cd38-structure.md)); lower NAD⁺ may reduce SIRT6 activity and genome maintenance. NMN/NR supplementation is often described as “recharging” SIRT6, but downstream effects and clinical benefits require evidence beyond the biochemical pathway.

---

## 5. Evidence grading

| Structural/biological finding | Evidence | Basis |
|---|---|---|
| SIRT6 is an NAD⁺-dependent deacetylase | ★★★★★ Established | 3K35 (2011, JBC) |
| SIRT6 deacetylation is low (~1,000-fold slower) | ★★★★★ Established | 3K35 biochemistry/structure |
| SIRT6 defatty-acylates long-chain substrates, including TNF-α | ★★★★★ Established | 3ZG6 (2013, *Nature*) |
| Substrate channel accommodates long-chain fatty-acyl groups | ★★★★★ Established | 3ZG6 |
| SIRT6 overexpression extends lifespan in male mice | ★★★★★ Established | Kanfi et al., 2012, *Nature* |
| SIRT6 deficiency impairs DNA repair and causes premature aging | ★★★★★ Established | Animal models |
| SIRT6 maintains telomeric silencing | ★★★★★ Established | Cell/animal studies |
| SIRT6 knockout causes metabolic dysfunction/lethality | ★★★★★ Established | Mouse knockout |

### 5.1 Evidence strength: structural versus functional levels

SIRT6 evidence forms a hierarchy. **Structural evidence** (3K35/3ZG6 atomic coordinates, reported resolutions around 2.0–2.2 Å) shows molecular shape and binding. **Biochemical evidence** (deacetylation/defatty-acylation assays and inactive catalytic mutants) establishes enzymatic function; structural and biochemical evidence together are especially strong. **Cellular and animal evidence** (lifespan extension with overexpression, premature aging after knockout) addresses organism-level relevance, though causal chains can include indirect effects. **Human-population evidence** linking SIRT6 with human longevity or disease remains limited. Grading evidence prevents overinterpretation: structure is not itself proof of organismal benefit, and molecular function is not automatically an anti-aging intervention.

---

## 6. Connections to the knowledge-base themes

### 6.0 Structural overview of the NAD⁺ economy: NAMPT → SIRT1 → SIRT6

| Molecule | Role | Structural article |
|---|---|---|
| NAMPT | NAD⁺ synthesis (salvage pathway) | [10-nampt-structure.md](10-nampt-structure.md) |
| SIRT1 | NAD⁺ consumption (deacetylation; metabolism/stress) | [06-sirt1-structure.md](06-sirt1-structure.md) |
| SIRT6 | NAD⁺ consumption (deacylation; genome/telomeres) | [33-sirt6-structure.md](33-sirt6-structure.md) |
| CD38 | NAD⁺ consumption (competitive, inflammation-related) | [08-cd38-structure.md](08-cd38-structure.md) |
| PARP1 | NAD⁺ consumption (DNA repair) | [09-parp1-structure.md](09-parp1-structure.md) |

NAMPT supplies NAD⁺; sirtuins, PARP, and CD38 consume it. Aging may combine reduced supply (lower NAMPT) with increased consumption (higher CD38/PARP), depleting NAD⁺ and reducing sirtuin activity. NMN/NR are proposed to increase supply, while CD38 inhibition is proposed to conserve it. NAD⁺ fuels both sirtuins (acylation regulation) and PARP (DNA repair), linking epigenetic regulation and genome maintenance. Animal studies report metabolic or mitochondrial effects of NAD⁺ precursors, but these findings should not be equated automatically with established human anti-aging benefit.

Age-related CD38 increases in immune cells can consume NAD⁺ and compete with sirtuins. Quercetin-like compounds and drugs have been investigated as CD38 inhibitors; their effects and practical use require careful evidence evaluation. A proposed SIRT6-support framework combines exercise or caloric restriction/intermittent fasting, NAD⁺ precursors, and limiting NAD⁺ consumption—but these are research hypotheses and not a proven prescription to maximize SIRT6.

### 6.1 Connections to other central articles

- **SIRT1** ([06-sirt1-structure.md](06-sirt1-structure.md)): sister enzyme, associated with metabolism versus genome maintenance.
- **NAMPT** ([10-nampt-structure.md](10-nampt-structure.md)): NAD⁺ fuel supply.
- **CD38** ([08-cd38-structure.md](08-cd38-structure.md)): a competing NAD⁺ consumer.
- **PARP1** ([09-parp1-structure.md](09-parp1-structure.md)): DNA repair also consumes NAD⁺.
- **TERT** ([11-telomerase-structure.md](11-telomerase-structure.md)): another component of telomere maintenance.
- **p53** ([13-p53-structure.md](13-p53-structure.md)): decision-making after DNA damage.

The genome-maintenance network includes TERT-mediated telomere extension, SIRT6-mediated telomeric silencing and DSB repair, PARP-mediated single-strand-break repair, and p53-mediated damage responses. These are complementary functions, not interchangeable ones. Aging-related genome maintenance involves telomeres, DNA repair, and chromatin regulation together.

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does SIRT6 deacetylate? | NAD⁺-dependent transfer of the acetyl group to NAD⁺’s ribose, with nicotinamide release |
| Why is deacetylation slow? | The channel/pocket favors long-chain fatty-acyl substrates; acetyl-lysine is not its preferred “main course” |
| How does defatty-acylation work? | A wide hydrophobic channel accommodates long chains, enabling efficient catalysis (including TNF-α regulation) |
| How may SIRT6 affect aging? | DNA repair, telomere maintenance, glucose metabolism, and inflammation regulation |
| How might it be supported? | NAD⁺ metabolism, CD38-related pathways, exercise, and caloric restriction are research avenues—not guaranteed interventions |

**Structural intuition beyond the five questions:** enzyme activity must always be considered with respect to substrate. SIRT6 is slow on acetyl substrates but fast on fatty-acyl substrates; a seemingly “weak” enzyme may instead be specialized for a different substrate. Molecular structure, biochemistry, and function together identify its physiological role. SIRT6 also illustrates how NAD⁺ can translate metabolic state into genome maintenance: NAD⁺ is the fuel, SIRT6 the enzyme, and genome stability a possible outcome.

---

## 8. Open questions

1. **Full SIRT6 substrate spectrum:** what targets exist beyond H3K9/K56 and TNF-α?
2. **Physiological meaning of defatty-acylation:** how extensive and important is long-chain fatty-acylation regulation?
3. **SIRT6 activators:** can compounds selectively activate it on a structural basis?
4. **Molecular details at telomeres:** how exactly does SIRT6 maintain telomeric chromatin?
5. **SIRT6 and cancer:** genome stability may have context-dependent, potentially double-edged effects.
6. **Post-translational regulation:** how do phosphorylation and other modifications tune SIRT6 activity?

### 8.2 History of sirtuin research: from “silencing information regulator” to longevity hub

In the 1990s, yeast Sir2 (an ancestor of SIRT1) was identified as a silencing information regulator; rDNA silencing and lifespan effects opened the sirtuin–longevity field. In the 2000s, the seven mammalian sirtuins (SIRT1–7) were characterized and found to have differentiated roles in metabolism, genome biology, and mitochondria. In the 2010s, the first SIRT6 structure (3K35, 2011) and the defatty-acylation discovery (3ZG6, 2013) transformed the “low activity” puzzle into a broader view of a deacylase. Research on sirtuins was then integrated with NAD⁺ metabolism (NAMPT/CD38) into an NAD⁺-economy framework ([01-foundations/04-nad-sirtuin.md](../01-foundations/04-nad-sirtuin.md)): sirtuins are consumers in a metabolic system, not isolated enzymes.

### 8.3 SIRT6’s unresolved challenges: the distance from structure to clinic

Several gaps remain between laboratory findings and clinical use. Selective SIRT6 activators are still being sought; its full range of deacylation substrates remains uncertain; and the dose-response relationship is not resolved. Too little SIRT6 may impair genome maintenance, but excessive activity could also have unwanted consequences. Functions differ among tissues (liver, brain, muscle), so systemic activation may not have uniform effects. Combinations with NAD⁺ support, exercise, or caloric restriction are systems-level hypotheses, not proof that SIRT6 is a universal anti-aging target.

---

## 9. Guide to structural data

- **PDB entries:**
  - **3K35**: human SIRT6 crystal structure (2.0 Å; Pan 2011, *JBC*), the first structure.
  - **3ZG6**: SIRT6 with long-chain fatty-acyl substrate (2.2 Å; Jiang 2013, *Nature*), illustrating defatty-acylation.
  - **3PKI/3PKJ**: SIRT6 complexes with ADP-ribose/O-acetyl-ADP-ribose analogues.
  - **5MF6** and related entries: SIRT6 with substrate peptide.
  - **AlphaFold**: AF-Q8N6T7, human SIRT6.
- **Viewing tools:** RCSB online 3D viewer, PyMOL, or ChimeraX.

---

## 10. References (published literature)

1. Pan PW, Feldman JL, Devries MK, Dong A, Edwards AM, Denu JM. Structure and biochemical functions of SIRT6. *J Biol Chem* 2011;286:14575–14587. (PDB 3K35)
2. Jiang H, Khan S, Wang Y, et al. SIRT6 regulates TNF-alpha secretion through hydrolysis of long-chain fatty acyl lysine. *Nature* 2013;496:110–113. (PDB 3ZG6)
3. Kanfi Y, Naiman S, Amir G, et al. The sirtuin SIRT6 regulates lifespan in male mice. *Nature* 2012;483:218–221. (Lifespan evidence)
4. Mostoslavsky R, Chua KF, Lombard DB, et al. Genomic instability and aging-like phenotype in the absence of mammalian SIRT6. *Cell* 2006;124:315–329. (SIRT6-deficiency phenotype)
5. Michishita E, McCord RA, Berber E, et al. SIRT6 is a histone H3 lysine 9 deacetylase that modulates telomeric chromatin. *Nature* 2008;452:492–496. (Telomeres/histones)
6. Zhong L, D’Urso A, Toiber D, et al. The histone deacetylase Sirt6 regulates glucose homeostasis via Hif1alpha. *Cell* 2010;140:280–293. (Glucose metabolism)
7. Tasselli L, Zheng W, Chua KF. SIRT6: Novel mechanisms and links to aging and disease. *Trends Endocrinol Metab* 2017;28:168–185. (Review)

---

> **Structural overview:** SIRT6 is an NAD⁺-dependent deacylase, with a Rossmann-fold NAD⁺ pocket, zinc-finger substrate grip, and substrate channel (first structure 3K35). It consumes NAD⁺ to remove acetyl and fatty-acyl groups. Deacetylation is slow (~1,000-fold lower than SIRT1 in cited assays), but the channel favors long-chain fatty-acyl groups, which SIRT6 removes efficiently (3ZG6; including regulation of TNF-α secretion): specialization, not weakness. Its functions include DNA repair, telomere maintenance, glucose-metabolism regulation, and inflammation control. Overexpression extended lifespan in male mice (Kanfi 2012), while deficiency caused genomic instability and premature-aging-like phenotypes. NAD⁺ metabolism (NMN/NR precursors and NAMPT; [10-nampt-structure.md](10-nampt-structure.md)) and CD38 ([08-cd38-structure.md](08-cd38-structure.md)) are related research areas, but do not by themselves establish a human anti-aging intervention.
