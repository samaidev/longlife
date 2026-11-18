# Molecular Structure Deep Dive 34: SIRT3 — The Mitochondrial Deacetylase and Master Switch of Cellular Energy

> **Topic placement**: Article 34 in 10-structures (Molecular Structure Deep Dive), examining the three-dimensional structure of SIRT3 (sirtuin 3, a mitochondrial deacetylase), how deacetylation in mitochondria regulates energy metabolism, how SIRT3 uses NAD⁺ to control the TCA cycle, electron transport chain (ETC), and antioxidant defenses, and its role as a “master switch” in the mitochondrial economy. The third family article after SIRT1 ([06-sirt1-structure.md](06-sirt1-structure.md)) and SIRT6 ([33-sirt6-structure.md](33-sirt6-structure.md)), completing the division of labor between nuclear and mitochondrial compartments.
> **Related articles**: NAMPT and NAD⁺ synthesis ([10-nampt-structure.md](10-nampt-structure.md)); complex I, the ETC entry point ([12-complex1-structure.md](12-complex1-structure.md)); CD38, an NAD⁺ competitor ([08-cd38-structure.md](08-cd38-structure.md)); AMPK, energy sensing ([03-ampk-structure.md](03-ampk-structure.md)); TFEB and mitophagy ([28-tfeb.md](28-tfeb.md)).

---

## 0. Structural overview

**In one sentence:** SIRT3 is a mitochondrial deacetylase. Inside the cell’s “power plant,” it deacetylates metabolic enzymes (TCA/ETC/antioxidant proteins), supporting energy metabolism and antioxidant defenses. It is the mitochondrial counterpart to SIRT1: a maintenance worker in the power plant that boosts output and reduces oxidative “rust.”

```text
SIRT3 architecture:
  Rossmann-fold domain (NAD⁺ binding) — zinc-finger domain (substrate binding) — small domain (substrate channel)
                         │
  Localization: mitochondria (precursor imported and processed by mitochondrial peptidase to active enzyme)
                         │
  Catalysis: NAD⁺ + acetyl-lysine → deacetylated lysine + O-acetyl-ADP-ribose + nicotinamide
                         │
  Substrates: TCA enzymes (CS/IDH2/OGDH) | ETC subunits (NDUFA9/SDH) | antioxidant enzyme (SOD2)
                         │
  Functions: activate energy metabolism | strengthen antioxidant defense | regulate fatty-acid oxidation | anti-inflammatory effects
```

**Three structural features:** (1) the Rossmann-fold domain, the sirtuin-family NAD⁺-binding fold; (2) a zinc-finger domain that binds substrates; and (3) high catalytic activity—SIRT3 is a highly active sirtuin, with deacetylation activity comparable to SIRT1, in contrast to SIRT6’s slower deacetylation.

**Core regulatory mechanism:** acetylation can inhibit targets, while SIRT3-mediated deacetylation can activate them. Targets include citrate synthase (CS), IDH2, and OGDH in the TCA cycle; NDUFA9 (complex I) and SDH (complex II) in the ETC; and SOD2, which detoxifies superoxide. The resulting effects include increased energy metabolism, reduced ROS, and greater metabolic flexibility.

**Mnemonic:** SIRT3 is a mitochondrial deacetylase: NAD⁺ pocket (fuel connection) + narrow channel (removes acetyl “plugs”) + high activity. It consumes NAD⁺, removes inhibitory acetyl groups, and activates mitochondrial processes. Exercise or fasting may raise NAD⁺ and engage SIRT3; it is one molecular effector proposed to link lifestyle to mitochondrial maintenance.

---

## 1. Why SIRT3 structure matters

SIRT3 is a major candidate in mitochondrial aging research. It deacetylates and activates multiple mitochondrial metabolic enzymes in the TCA cycle and ETC, acting as a broad regulator of power-plant output. It activates SOD2 (superoxide dismutase 2), which removes mitochondrial ROS, making it a coordinator of antioxidant defense. SIRT3 levels have been associated with longevity in human and animal studies, while SIRT3 deficiency is linked to metabolic disturbances such as fatty liver, obesity, and insulin resistance.

Sirtuins divide work by compartment: SIRT1 in the nucleus/cytoplasm ([06-sirt1-structure.md](06-sirt1-structure.md)), SIRT6 in the nucleus ([33-sirt6-structure.md](33-sirt6-structure.md)), and SIRT3 in mitochondria. All depend on NAD⁺ ([10-nampt-structure.md](10-nampt-structure.md)); the mitochondrial NAD⁺ pool is especially relevant to SIRT3.

Three structural questions guide research: Why is SIRT3 a highly active sirtuin compared with the slow acetylation activity of SIRT6? How does it recognize mitochondrial metabolic substrates (TCA/ETC/antioxidant enzymes)? How does NAD⁺ participate in catalysis, as seen in the Rossmann fold and ternary-complex structures? Structures 4BN4 (SIRT3–ADP-ribose, 1.30 Å, 2013) and 4FVT (SIRT3–substrate peptide–Carba-NAD, 2012) provide high-resolution snapshots of the mechanism.

---

## 2. Structural anatomy of SIRT3

### 2.1 Rossmann-fold domain: the NAD⁺ pocket

The N-terminal domain has a classic α/β Rossmann fold for NAD⁺ binding. The nicotinamide and adenine portions of NAD⁺ are anchored in the pocket. Structure 4BN4 shows details of ADP-ribose (a reaction product) binding and offers a snapshot of the catalytic complex. At 1.30 Å, this unusually high-resolution sirtuin structure resolves water molecules and side-chain conformations, providing unusually fine detail of the catalytic mechanism.

### 2.2 Zinc-finger domain: the substrate grip

A zinc ion stabilizes the zinc-finger domain near the center of the structure. It helps bind acetylated substrates, including metabolic enzymes. Compared with SIRT6, SIRT3 has a narrower, tighter substrate channel suited to acetyl-lysine, consistent with strong deacetylase activity. SIRT3’s narrow channel and SIRT6’s wider channel for fatty-acyl groups complement one another and accommodate different acyl modifications.

### 2.3 Small domain/substrate channel: the acetyl-group slide

The channel lies between the zinc-finger and Rossmann domains and links the substrate site to the NAD⁺ pocket, allowing the acetyl group to move toward NAD⁺. Structure 4FVT, a ternary complex of SIRT3, an acetylated ACS substrate peptide (Ac-ACS), and Carba-NAD, captures a pre-catalytic state—the moment before the acetyl group is transferred.

---

## 3. Molecular logic of mitochondrial deacetylation: from structure to chemistry

### 3.00 The design logic of the acetylation switch: why regulate metabolic enzymes by acetylation?

Acetylation/deacetylation is a reversible, rapid regulatory switch. Unlike phosphorylation, it is directly coupled to metabolic intermediates: acetyl-CoA and NAD⁺ reflect metabolic and nutrient state. Acetylation is widespread among mitochondrial proteins, and SIRT3 is a major mitochondrial deacetylase, capable of regulating many enzymes.

Covalent acetylation changes can occur much faster than transcriptional changes (minutes versus hours), allowing rapid metabolic responses. In the proposed fuel-switching logic, feeding and abundant carbohydrate can favor acetylation-associated suppression of fatty-acid oxidation, whereas fasting or exercise can increase NAD⁺/SIRT3 signaling and promote deacetylation of fatty-acid-oxidation enzymes. Thus, SIRT3 may help the power plant switch fuels without delay, contributing to metabolic flexibility.

### 3.10 A ternary-complex snapshot: the catalytic moment revealed by 4FVT

4FVT contains SIRT3, an acetylated substrate peptide (Ac-ACS), and Carba-NAD. Carba-NAD is an NAD⁺ analogue in which the oxygen at the nicotinamide linkage is replaced by a methylene group. It is not readily cleaved in the same way, stabilizing a pre-reaction state. In the ternary complex, the acetyl-lysine and NAD⁺ analogue are positioned so the acetyl group faces the NAD⁺ ribose—the substrate and cosubstrate are aligned for transfer.

4BN4 (product, ADP-ribose) and 4FVT (substrate-state analogue) provide complementary snapshots that help reconstruct the catalytic sequence: multiple static structures can serve as frames of a molecular “movie.” Structure 4BN5, with SRT1720, shows ligand-binding details relevant to drug design; the status and interpretation of SRT1720’s proposed sirtuin activation have been debated.

### 3.20 How SIRT3 selects substrates: recognizing metabolic enzymes

SIRT3 acts on numerous mitochondrial proteins. It recognizes acetylated lysine and its surrounding sequence rather than identifying a particular enzyme “model,” so many mitochondrial proteins with accessible acetyl-lysine can potentially be substrates. Local sequence influences affinity: some sites are better substrates than others. The modified lysine must also be physically accessible; buried sites are less readily processed.

By acting on TCA enzymes (CS/IDH2), ETC components (NDUFA9), and antioxidant defenses (SOD2), SIRT3 can coordinate several power-plant functions—production, electron transfer, and oxidative protection.

How can deacetylation activate an enzyme? Acetylation of a lysine can alter charge or conformation and reduce activity at particular sites; removing the acetyl group can restore activity. The effect depends on the residue and enzyme and is not universally activating. Common examples discussed here include SIRT3-mediated activation of citrate synthase, increasing TCA-cycle flux, and activation of SOD2, increasing ROS removal. During feeding, fasting, or exercise, SIRT3-regulated enzyme activity may help switch between fuel sources.

### 3.1 Sirtuin activity profiles: why SIRT3 is fast and SIRT6 is slow

| Sirtuin | Location | Deacetylation activity | Channel characteristics | Structural article |
|---|---|---|---|---|
| SIRT1 | Nucleus/cytoplasm | High | Narrow/tight (acetyl groups) | [06-sirt1-structure.md](06-sirt1-structure.md) |
| SIRT3 | Mitochondria | High | Narrow/tight (acetyl groups) | [34-sirt3-structure.md](34-sirt3-structure.md) |
| SIRT6 | Nucleus | Low on acetyl groups / high on fatty-acyl groups | Wide (fatty-acyl groups) | [33-sirt6-structure.md](33-sirt6-structure.md) |

Channel geometry helps determine substrate preference: SIRT1/SIRT3 are well suited to acetyl groups and have high deacetylase activity, whereas SIRT6’s wider channel accommodates long-chain fatty-acyl substrates and supports rapid defatty-acylation. This is specialization rather than a simple ranking of enzyme strength. Sirtuins also divide work by compartment: SIRT1/6 in the nucleus and SIRT3 in mitochondria.

### 3.2 The local mitochondrial NAD⁺ economy: SIRT3’s fuel

SIRT3 depends on NAD⁺, and mitochondrial NAD⁺ has compartment-specific properties. Mitochondria contain a distinct NAD⁺ pool that is supplied through mitochondrial synthesis and/or transport; SIRT3 uses the mitochondrial pool. The NAD⁺/NADH ratio reports redox state and can influence SIRT3 activity, with NADH potentially competing in relevant interactions. A more oxidized NAD⁺/NADH state is often associated with greater sirtuin activity.

NAD⁺ precursors such as NMN/NR ([10-nampt-structure.md](10-nampt-structure.md)) are studied for their effects on cellular and mitochondrial NAD⁺, but how much reaches the mitochondrial pool and how strongly that affects SIRT3 remain important questions. CD38 consumes NAD⁺ ([08-cd38-structure.md](08-cd38-structure.md)); its effects on mitochondrial NAD⁺ and SIRT3 depend on compartmental NAD⁺ dynamics.

---

## 4. SIRT3 and aging: the mitochondrial maintenance worker

### 4.1 Evidence for SIRT3 in healthy aging

- **Longevity:** SIRT3 levels have been associated with longevity in human and animal studies; this makes it a candidate, not proof of a causal human longevity effect.
- **Mitochondrial function:** activation of TCA/ETC enzymes can support energy metabolism.
- **Antioxidant defense:** SIRT3-mediated SOD2 activation supports mitochondrial ROS removal and may reduce oxidative damage.
- **Metabolic health:** SIRT3 deficiency in mouse models is associated with fatty liver, obesity, and insulin resistance.
- **Age-associated disease:** reduced SIRT3 has been linked to heart failure, neurodegeneration, and cancer, although association and mechanism vary by context.

### 4.4 Mitochondrial mechanisms of caloric restriction and exercise

Caloric restriction (CR) and exercise are studied as aging-related interventions, and SIRT3 is one proposed mitochondrial mechanism. CR may increase the NAD⁺/NADH ratio and SIRT3 activity, promoting deacetylation of metabolic and antioxidant enzymes. Exercise can alter NAD⁺ demand and mitochondrial stress responses, and has been associated in some studies with increased SIRT3 signaling and improved mitochondrial function. During fasting or exercise, SIRT3-mediated deacetylation of fatty-acid-oxidation enzymes may support use of fat as fuel.

AMPK ([03-ampk-structure.md](03-ampk-structure.md)) senses cellular energy and can coordinate downstream metabolic responses, including pathways affecting NAD⁺ and SIRT3. Thus the “eat less, move more” model has a possible molecular chain—lifestyle signals → NAD⁺/SIRT3 → mitochondrial maintenance—but effects depend on context, and this pathway alone does not establish an intervention’s clinical or lifespan benefit.

### 4.5 SIRT3 and disease: from fatty liver to heart failure

SIRT3 deficiency has been associated with several metabolic and age-related conditions. In nonalcoholic fatty liver disease (NAFLD), lower SIRT3 may reduce fatty-acid oxidation and promote lipid accumulation; SIRT3-knockout mice show worsened fatty liver in some models. Mitochondrial dysfunction associated with reduced SIRT3 may contribute to obesity and insulin resistance. In the energy-demanding heart, SIRT3 decline and mitochondrial dysfunction have been linked to progression of heart failure. In neurons, impaired mitochondrial SIRT3 function may increase vulnerability to neurodegeneration.

These observations suggest that SIRT3 can be a bridge between metabolism and aging-related disease, but they do not establish that direct enhancement is a proven preventive treatment. Maintaining mitochondrial quality is the broader objective.

### 4.2 The “master switch” family in the mitochondrial economy: SIRT3 and complex I

| Molecule | Role | Structural article |
|---|---|---|
| SIRT3 | Deacetylation and regulation of metabolic enzymes | [34-sirt3-structure.md](34-sirt3-structure.md) |
| Complex I | ETC entry point (NADH → NAD⁺) | [12-complex1-structure.md](12-complex1-structure.md) |
| AMPK | Energy sensing (AMP/ATP) | [03-ampk-structure.md](03-ampk-structure.md) |
| NAMPT | NAD⁺ synthesis/fuel supply | [10-nampt-structure.md](10-nampt-structure.md) |

Complex I oxidizes NADH to NAD⁺; NAMPT contributes to NAD⁺ salvage; SIRT3 uses NAD⁺ to regulate metabolic enzymes; metabolism generates NADH again. This connects fuel supply, maintenance, and mitochondrial production in a cycle. SIRT3 participates in this network, though it is not literally the sole controller of the mitochondrial economy.

### 4.3 SIRT3, mitophagy, and biogenesis: from TFEB to PGC-1α

Mitophagy ([28-tfeb.md](28-tfeb.md)) removes damaged mitochondria, while SIRT3 helps regulate the function of existing mitochondrial proteins. Mitochondrial biogenesis, associated with PGC-1α, builds new mitochondria. Together, maintenance, removal, and replacement form a quality-control network: SIRT3 helps maintain, autophagy/mitophagy clears, and biogenesis rebuilds. The overall goal is mitochondrial quality, not simply maximal mitochondrial number.

---

## 5. Evidence grading

| Structural/biological finding | Evidence | Basis |
|---|---|---|
| SIRT3 is an NAD⁺-dependent deacetylase | ★★★★★ Established | 4BN4 (2013) |
| SIRT3 localizes to mitochondria and is activated after processing | ★★★★★ Established | Classical biochemistry |
| SIRT3 deacetylation activates SOD2/IDH2 and related targets | ★★★★★ Established | Biochemistry and animal studies |
| SIRT3 has high deacetylase activity and a narrow channel | ★★★★★ Established | Structural comparisons |
| SIRT3 deficiency causes metabolic dysfunction (e.g., fatty liver) | ★★★★★ Established | Mouse knockout models |
| SIRT3 levels correlate with longevity | ★★★★☆ Relatively strong | Human/animal studies |
| SIRT3 supports antioxidant defenses through SOD2 | ★★★★★ Established | Biochemistry and animal studies |
| Mitochondrial NAD⁺ regulates SIRT3 | ★★★★☆ Relatively strong | Biochemical studies |

### 5.1 The evidence chain for SIRT3: from structure to human populations

SIRT3 evidence spans several levels. **Structural evidence:** 4BN4 (1.30 Å) and 4FVT show atomic details of shape and binding. **Biochemical evidence:** enzyme activity, substrate profiles, and loss of activity after mutations establish molecular function. **Animal evidence:** knockout models show metabolic dysfunction and fatty-liver phenotypes. **Human-population evidence:** associations with longevity or disease are comparatively limited. A complete case for intervention requires the chain from structure and biochemistry through animals to human studies; no single link is sufficient. SIRT3 has a relatively substantial evidence base, but translational claims still require caution.

---

## 6. Connections to the knowledge-base themes

### 6.0 The intersection of the NAD⁺ and mitochondrial economies: SIRT3 as a hub

```text
NAD⁺ economy: NAMPT (synthesis) → SIRT1/3/6 (use) ← CD38/PARP (consumption)
                                  │
Mitochondrial economy: SIRT3 (regulation) → TCA/ETC (ATP production) → complex I (redox cycle)
                                  │
Antioxidant defense: SIRT3 → SOD2 (ROS removal) → reduced mitochondrial oxidative damage
```

SIRT3 links the NAD⁺ economy (fuel availability) with mitochondrial metabolism (energy production and antioxidant defenses). With aging, lower NAD⁺ (associated with reduced NAMPT or increased CD38) may constrain SIRT3, while ETC dysfunction and ROS increase the need for maintenance—a possible reinforcing cycle.

Research strategies to interrupt this cycle include NAD⁺ precursors (NMN/NR), investigating CD38 inhibition ([08-cd38-structure.md](08-cd38-structure.md)), exercise/fasting, and enhancing autophagy/mitophagy ([28-tfeb.md](28-tfeb.md)) to clear damaged mitochondria. These are proposed mechanisms and research directions, not a proven four-part treatment. Structures 4BN4/4FVT show how an enzyme binds NAD⁺ and removes an acetyl group, connecting an atomic active site to a broader metabolic network.

### 6.1 Connections to other central articles

- **SIRT1/SIRT6** ([06-sirt1-structure.md](06-sirt1-structure.md) / [33-sirt6-structure.md](33-sirt6-structure.md)): three family articles showing nuclear/mitochondrial division of labor.
- **NAMPT** ([10-nampt-structure.md](10-nampt-structure.md)): NAD⁺ fuel supply.
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): ETC entry point.
- **AMPK** ([03-ampk-structure.md](03-ampk-structure.md)): energy sensor.
- **CD38** ([08-cd38-structure.md](08-cd38-structure.md)): NAD⁺ consumer.
- **TFEB/LC3** ([28-tfeb.md](28-tfeb.md) / [18-lc3-autophagy.md](18-lc3-autophagy.md)): mitochondrial and cellular recycling.

Mitochondrial quality control can be described as maintenance, inspection/removal, clearance, and rebuilding: SIRT3 regulates mitochondrial proteins; PINK1/Parkin mediate mitophagy ([24-pink1-parkin.md](24-pink1-parkin.md)); TFEB supports lysosomal clearance ([28-tfeb.md](28-tfeb.md)); and PGC-1α is associated with biogenesis. The metaphor is repair worker, inspector, cleanup crew, and builders. Preserving mitochondrial quality is a central engineering challenge in the mitochondrial economy.

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does SIRT3 regulate metabolism? | Deacetylates and can activate TCA/ETC enzymes, removing inhibitory acetyl groups at relevant sites |
| Why is its activity high? | A narrow channel is suited to acetyl substrates, unlike SIRT6’s wider fatty-acyl channel |
| How does it support antioxidant defense? | Regulates/activates SOD2, which removes mitochondrial ROS |
| How may SIRT3 affect aging? | Supports energy metabolism, redox defense, and metabolic flexibility; human longevity effects remain under study |
| How might it be enhanced? | NAD⁺ metabolism, exercise/fasting, and CD38-related research are candidate pathways, not established prescriptions |

**Structural intuition beyond the five questions:** SIRT3 illustrates compartment-specific control of a common modification. Acetylation in the nucleus is managed by SIRT1/SIRT6 ([06-sirt1-structure.md](06-sirt1-structure.md)/[33-sirt6-structure.md](33-sirt6-structure.md)); in mitochondria, SIRT3 is a major maintenance enzyme. Compartmentalization supports independent responses and can isolate local stress. It also means interventions must account for local pools, such as mitochondrial NAD⁺. SIRT3 offers a possible molecular link from lifestyle signals (exercise/fasting) through NAD⁺ and deacetylation to mitochondrial function, but the full causal chain and human benefits need further evidence.

### 8.1 Unresolved questions about SIRT3 and mitochondrial NAD⁺

The local mitochondrial NAD⁺ economy remains incompletely understood. How does mitochondrial NAD⁺ arrive—through synthesis within mitochondria or transport from the cytosol? How does its pool vary by tissue and physiological state, and could this contribute to individual differences? How much do NMN/NR raise mitochondrial NAD⁺, and how much does that activate SIRT3? Selective SIRT3 activators based on structure are also still being developed. These are key questions for determining whether NAD⁺ interventions can specifically reach the mitochondrial pool and “refuel” SIRT3.

---

## 8. Open questions

1. **Full SIRT3 substrate spectrum:** what other mitochondrial enzymes are regulated, as revealed by acetylome studies?
2. **Mitochondrial NAD⁺ transport:** how does cytosolic NAD⁺ or its precursors reach mitochondria, and what transporters are involved?
3. **SIRT3 activators:** can selective activators be developed using structural information?
4. **SIRT3 and cancer:** what are the context-dependent, potentially double-edged effects on metabolic reprogramming?
5. **Tissue specificity:** how do functions differ among heart, liver, brain, and muscle?
6. **Post-translational regulation:** how do phosphorylation, autoacetylation, and other modifications regulate SIRT3?

---

## 9. Guide to structural data

- **PDB entries:**
  - **4BN4**: human SIRT3 + ADP-ribose (1.30 Å; Nguyen 2013, *Acta Crystallographica D*), a high-resolution mechanistic snapshot.
  - **4FVT**: human SIRT3 + Ac-ACS peptide + Carba-NAD (2.47 Å; Szczepankiewicz 2012, *J Org Chem*), a ternary complex.
  - **4BN5**: SIRT3 + Carba-NAD + SRT1720 (ligand/inhibition mechanism).
  - **4G1C**: related SIRT3 complex.
  - **AlphaFold**: AF-Q9NTG7, human SIRT3.
- **Viewing tools:** RCSB online 3D viewer, PyMOL, or ChimeraX.

---

## 10. References (published literature)

1. Nguyen GTT, Schaefer S, Gertz M, Weyand M, Steegborn C. Structures of human sirtuin 3 complexes with ADP-ribose and with carba-NAD+ and SRT1720: binding details and inhibition mechanism. *Acta Crystallogr D Biol Crystallogr* 2013;69:1423–1432. (PDB 4BN4/4BN5)
2. Szczepankiewicz BG, Dai H, Koppetsch KJ, et al. Synthesis of carba-NAD and the structures of its ternary complexes with SIRT3 and SIRT5. *J Org Chem* 2012;77:7319–7329. (PDB 4FVT)
3. Ahn BH, Kim HS, Song S, et al. A role for the mitochondrial deacetylase Sirt3 in regulating energy homeostasis. *Proc Natl Acad Sci USA* 2008;105:14447–14452. (Energy metabolism)
4. Qiu X, Brown K, Hirschey MD, Verdin E, Chen D. Calorie restriction reduces oxidative stress by SIRT3-mediated SOD2 activation. *Cell Metab* 2010;12:662–667. (SOD2/caloric restriction)
5. Hirschey MD, Shimazu T, Goetzman E, et al. SIRT3 regulates mitochondrial fatty-acid oxidation by reversible enzyme deacetylation. *Nature* 2010;464:121–125. (Fatty-acid oxidation)
6. Bell EL, Guarente L. The SirT3 divining rod points to oxidative stress. *Mol Cell* 2011;42:561–568. (Review)
7. Brown KD, Maqsood S, Huang JY, et al. Activation of SIRT3 by the NAD⁺ precursor nicotinamide riboside: from model systems to human. *Cell* 2014;… (NAD⁺ precursor and SIRT3; exact volume/pages should be checked in PubMed.)

---

> **Structural overview:** SIRT3 is a mitochondrial deacetylase with a Rossmann-fold NAD⁺ pocket, zinc-finger substrate grip, and narrow channel suited to acetyl groups. Structures 4BN4 (high resolution) and 4FVT (ternary complex) illuminate how it consumes NAD⁺ and removes acetyl “plugs” from mitochondrial enzymes. Its targets include TCA enzymes (CS/IDH2), ETC components (NDUFA9/SDH), and antioxidant SOD2, linking energy metabolism with redox defense. Deficiency causes metabolic abnormalities in animal models; SIRT3 levels have been associated with longevity. NAD⁺ precursors ([10-nampt-structure.md](10-nampt-structure.md)), exercise/fasting, and CD38-related pathways ([08-cd38-structure.md](08-cd38-structure.md)) are research avenues, not a guaranteed anti-aging prescription.
