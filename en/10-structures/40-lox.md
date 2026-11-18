# Molecular Structure Deep Dive 40: Lipoxygenase (ALOX15) — The “Igniter” of Lipid Peroxidation and a Fuel for Ferroptosis

> **Series placement**: Article 40 in 10-structures (Molecular Structure Deep Dives), examining the 3D structure of lipoxygenase (LOX, especially ALOX15/15-LOX) to understand how LOX oxidizes polyunsaturated fatty acids (PUFAs) into lipid hydroperoxides (LOOH), the atomic mechanism of its iron catalytic center, and its role as an “igniter” in ferroptosis, inflammation, and aging. This is the counterpart to the GPX4 article ([39-gpx4.md](39-gpx4.md)): GPX4 puts out fires; LOX starts them—completing the two-player ferroptosis story.
> **Related articles**: GPX4 ([39-gpx4.md](39-gpx4.md), ferroptosis gate/firefighter); Nrf2 ([15-nrf2-structure.md](15-nrf2-structure.md), antioxidant commander); cGAS–STING ([30-cgas-sting.md](30-cgas-sting.md), inflammatory alarm); NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md), master inflammatory switch); SIRT3 ([34-sirt3-structure.md](34-sirt3-structure.md), mitochondrial antioxidant defense).

---

## 0. Structural overview

**In one sentence:** Lipoxygenase (LOX) is an “igniter” of lipid peroxidation. It uses non-heme iron to oxidize PUFAs into lipid hydroperoxides (LOOH). LOX can fuel ferroptosis, whereas GPX4 is the “fire extinguisher”: LOX starts the fire, GPX4 puts it out, and the balance helps determine cell fate.

```text
Lipoxygenase (ALOX15) structure:
  N-terminal β-barrel (membrane binding/regulation) — catalytic domain (non-heme iron + substrate channel)
                  │
  Catalysis: Fe³⁺ + PUFA → radical → LOOH (lipid hydroperoxide) + Fe²⁺
                  │
  Substrates: arachidonic acid (AA)/linoleic acid → 15-HpETE (hydroperoxide)
                  │
  Ferroptosis: LOX-generated LOOH → iron-catalyzed Fenton chemistry → lipid-peroxidation chain → ferroptosis
```

**Three structural features** (the atomic basis of function):
1. **Non-heme iron catalytic center**: Fe³⁺/Fe²⁺ redox cycling oxidizes PUFAs—the “spark.”
2. **Long substrate channel**: accommodates long-chain PUFAs (e.g., 20-carbon arachidonic acid)—the “fuse.”
3. **N-terminal β-barrel**: membrane-binding/regulatory domain—the igniter’s mount.

**Core regulatory mechanism**:

```text
LOX “ignition–extinguishing” balance:
  LOX: PUFA + O₂ → LOOH (ignition; produces lipid hydroperoxide)
       │
  GPX4: LOOH → LOH (extinguishing; reduces the hydroperoxide)
       │
  Ferroptosis: LOX↑/GPX4↓ → LOOH accumulation → iron-catalyzed Fenton chemistry
       │              → lipid-peroxidation chain → cell death
       │
  Inflammation: LOX products (leukotrienes/HpETEs) → inflammatory mediators → chronic inflammation
```

**Take-home mnemonic:** LOX is the lipid-peroxidation igniter: iron abstracts hydrogen from PUFAs, and the long channel positions the substrate. Iron starts oxidation to LOOH; GPX4 extinguishes the resulting fire. The balance determines cell fate. LOX inhibition (e.g., zileuton where relevant), GPX4 support, and dietary omega-3 are research avenues for managing ferroptosis-related lipid oxidation.

---

## 1. Why lipoxygenase structure matters

LOX is a hub linking lipid oxidation, inflammation, and ferroptosis:

- **Igniter of lipid peroxidation**: LOX enzymatically oxidizes PUFAs to LOOH and can fuel ferroptosis. The igniter starts lipid oxidation, creating the “fire” of hydroperoxides.
- **Counterpart to GPX4**: GPX4 ([39-gpx4.md](39-gpx4.md)) extinguishes the fire by reducing LOOH; LOX starts it by producing LOOH. Their activities contribute to the balance of lipid peroxide formation and removal—an aging strategy should not be reduced to a simple ratio but may involve supporting antioxidant capacity and limiting excessive oxidation.
- **Inflammatory-mediator factory**: LOX products (leukotrienes, lipoxins, HpETEs) include inflammatory and inflammation-resolving mediators. Leukotrienes are involved in asthma and inflammation; chronic changes in lipid signaling may contribute to inflammaging.
- **Drug target**: LOX inhibitors can reduce leukotriene synthesis. Zileuton, a 5-LOX inhibitor, is approved for asthma; modulating LOX is a possible anti-inflammatory or ferroptosis-related strategy, though effects depend on LOX subtype and context.
- **Aging evidence**: LOX activity and expression can vary with age and inflammation; lipid peroxidation may increase in some settings. This makes LOX a research direction, not proof that LOX inhibition is a general anti-aging treatment.
- **Repurposing potential**: Zileuton is an approved 5-LOX inhibitor for asthma; whether it can be repurposed for ferroptosis-related disease or aging requires further evidence. An existing drug provides a starting point, not proof of efficacy for new uses.

**Three key structural questions**:
1. How does non-heme iron catalyze PUFA oxidation (the atomic iron–oxygen mechanism)?
2. How does the substrate channel position PUFA and determine regioselectivity (e.g., 15- versus 12-position)?
3. How does the N-terminal β-barrel regulate membrane association and calcium-dependent behavior?

Structures such as 1LOX (rabbit 15-LOX, 2.40 Å, 1997) and 3V99 (human 5-LOX + AA, 2.25 Å, 2012) address these questions. Together they reveal the structural logic of iron-mediated ignition and substrate positioning.

---

## 2. Structural anatomy of lipoxygenase

### 2.1 Non-heme iron catalytic center — “the spark”

- **Location**: Core of the catalytic domain.
- **Structure**: A single non-heme iron (Fe³⁺/Fe²⁺) coordinated by three histidines, a C-terminal isoleucine, and water—the iron spark held in the catalytic “furnace.”
- **Function**: Fe³⁺ abstracts hydrogen from a bis-allylic carbon of a PUFA, creating a radical; O₂ adds to the radical to form LOOH. The spark activates the fuel, oxygen is added, and a lipid hydroperoxide is produced.
- **Finding from 1LOX**: The octahedral iron-coordination geometry provides a structural basis for catalysis.
- **Precision of iron coordination**: Iron coordinates with three His nitrogens, the C-terminal Ile and water oxygens in an approximately octahedral environment, with a coordination position available for substrate/oxygen chemistry. The coordination sphere anchors the iron while enabling reaction with oxygen.
- **Iron redox cycle**: Fe²⁺ is the resting state; Fe³⁺ is the active oxidizing state for hydrogen abstraction, followed by reduction and recycling. The spark cycles between resting, ignition, and recovery.

### 2.2 Long substrate channel — “the fuse”

- **Location**: Within the catalytic domain, running from the protein surface toward the iron center.
- **Structure**: A long hydrophobic channel accommodating a ~20-carbon PUFA chain—the fuse leading to the spark.
- **Function**: The PUFA chain inserts into the channel, which positions it for regioselective hydrogen abstraction. Its orientation determines which carbon position is oxidized (e.g., 15 versus 12).
- **Finding from 3V99**: The human 5-LOX + arachidonic acid (AA) structure shows substrate binding and channel contacts. AA is positioned in the channel, helping define the site of oxidation (5-LOX products).
- **Hydrophobic lining**: Leucine, phenylalanine, and other hydrophobic residues line the channel, matching the PUFA hydrocarbon chain and stabilizing it. The smooth hydrophobic lining lets the “fuel” slide into place.
- **Channel diameter**: The channel is shaped to accommodate PUFA without allowing excessive movement, helping position the substrate accurately.

### 2.3 N-terminal β-barrel — “the mount”

- **Location**: N terminus.
- **Structure**: β-barrel domain involved in membrane association and regulation—the igniter’s mounting base.
- **Function**: Membrane association brings LOX into contact with membrane PUFA; some LOXs are also regulated by calcium. The mount lets the enzyme reach membrane lipids and ignite oxidation at the membrane.

---

## 3. Molecular logic of iron-catalyzed oxidation: from structure to chemistry

### 3.0 Atom by atom: how iron “ignites” a PUFA

How does LOX oxidize a relatively stable PUFA? The answer is iron–oxygen radical chemistry—the ignition mechanism.

**Hydrogen abstraction (hydrogen-atom transfer).** An activated iron species (commonly described as Fe³⁺–OH) abstracts a hydrogen atom from a PUFA’s bis-allylic carbon—the carbon between two double bonds, whose C–H bond is especially susceptible—forming a carbon-centered radical. The spark takes hydrogen from the fuel, activating it; abstraction is the first step of ignition.

**Oxygen addition.** The carbon radical reacts with O₂ to form a peroxyl radical. This can abstract hydrogen from another PUFA, yielding LOOH and a new radical, potentially propagating a chain reaction. The fire spreads as oxygen adds and another hydrogen is taken.

**Iron recycling.** During catalysis, iron cycles between oxidation states; substrate/product chemistry and cellular reducing systems restore the active state. The iron can be reused, sustaining catalytic turnover.

**Why PUFAs?** PUFAs have bis-allylic C–H bonds that are relatively easy to abstract. LOX therefore acts preferentially on these susceptible sites—the enzyme recognizes an “easy-to-ignite” fuel.

### 3.1 Regioselectivity: why oxidation occurs at a particular position

LOX family members show regioselectivity (5-, 8-, 12-, or 15-LOX): the igniter targets a specific position.

**Channel length and depth.** Channel shape and depth determine how far a PUFA inserts and which hydrogen-abstraction site faces the iron. Differences in depth/orientation help distinguish 5-LOX from 15-LOX.

**Binding pockets in the channel.** Amino-acid pockets anchor the PUFA in a particular orientation, aligning a bis-allylic carbon with the iron. The “fuse” is held in place so a specific site faces the spark.

**Evidence from 3V99.** The human 5-LOX + AA structure (2.25 Å) shows substrate positioning associated with 5-LOX product formation. It provides structural evidence for substrate binding, though product regioselectivity also depends on enzyme chemistry and conditions.

**Physiological significance.** Different LOX products—including leukotrienes and lipoxins—have different biological actions. Oxidation at different positions can yield distinct signaling products and functions.

**5-LOX versus 15-LOX.** 5-LOX is best known for leukotriene biosynthesis and inflammatory signaling; 15-LOX produces 15-lipoxygenated products and can participate in lipoxin biosynthesis, lipid signaling, and ferroptosis-related oxidation. Their roles are context-dependent. Which isoform to inhibit depends on the therapeutic goal (e.g., 5-LOX in asthma versus particular 15-LOX pathways in lipid oxidation).

**Channel plasticity.** The S663D 5-LOX variant represented in 3V99 shows that changes associated with phosphorylation mimicry can alter product profiles, including 15-LOX-like activity. This supports a role for substrate-channel geometry in regioselectivity, while not implying that a single mutation alone explains all functional differences.

### 3.2 LOX–GPX4 tug-of-war: the balance of ferroptosis

LOX starts oxidation while GPX4 removes lipid hydroperoxides—the ferroptosis “tug-of-war.”

- **Rate of ignition**: LOX catalyzes PUFA oxidation and contributes to enzymatic production of lipid hydroperoxides.
- **Extinguishing capacity**: GPX4 ([39-gpx4.md](39-gpx4.md)) uses GSH to reduce LOOH. Its capacity depends in part on GSH availability.
- **What balance means**: If lipid peroxide production exceeds clearance, LOOH can accumulate and contribute to iron-catalyzed radical propagation and ferroptosis. This is not captured by a universal LOX/GPX4 ratio; the broader system includes iron, antioxidant pathways, and substrate availability.
- **Aging research**: Potential strategies under investigation include supporting GPX4/GSH defenses and limiting excessive LOX-mediated oxidation. The goal is not indiscriminate suppression but restoration of physiological balance.

### 3.30 Evolution of the LOX catalytic domain: conserved iron from plants to humans

Iron-mediated catalysis is broadly conserved across the LOX family, from plants to humans—the inherited spark.

- **Wide distribution**: LOXs occur in plants (e.g., legumes) and animals (mammalian 5/12/15-LOXs); the iron-based catalytic core is conserved.
- **Domain evolution**: Mammalian LOXs have an N-terminal β-barrel involved in membrane binding/regulation, whereas plant LOXs generally lack the same domain architecture. This supports additional membrane-related regulation in animals.
- **Divergence in regioselectivity**: 5-, 12-, and 15-LOXs diversified from common ancestors, with channel differences contributing to distinct products and functions—different igniters produce different lipid signals.
- **Evolutionary implication**: LOX is an ancient, conserved enzyme family. Lipid oxidation and antioxidant defenses represent a fundamental biological tension; healthy regulation requires balance rather than extremes.

### 3.40 Substrate selection: why LOX “recognizes” PUFAs

LOX preferentially oxidizes PUFAs rather than saturated fatty acids—it selects its fuel.

**Vulnerability of the bis-allylic carbon.** PUFAs contain methylene groups between double bonds with relatively weak C–H bonds, making hydrogen abstraction easier. LOX targets these susceptible positions.

**Saturated fats are less susceptible to this chemistry.** Saturated fatty acids lack double bonds and bis-allylic carbons, so they do not offer the same preferred LOX substrate sites.

**PUFA content of membrane lipids.** Membrane phospholipids can contain PUFAs, including in phosphatidylcholine and cardiolipin. Their oxidation can damage membranes, a key feature of ferroptosis.

**Aging implication:** Dietary PUFA intake should not be framed simply as “less is better.” PUFAs are essential fatty acids with important physiological functions. The relevant goal is balanced nutrition and control of oxidative stress—not indiscriminate removal of essential fats.

---

## 4. Lipoxygenase and aging: “the igniter out of control” from a structural perspective

### 4.1 Evidence on LOX in aging and disease

- **Age/inflammation changes**: LOX activity and inflammatory signaling can change with age or disease; lipid peroxidation may increase in some contexts. These changes do not establish a universal age-related rise in LOX.
- **Ferroptosis**: LOX can contribute to ferroptosis-related lipid oxidation, and LOX inhibition can reduce this contribution in some models, including contexts relevant to neurodegeneration or ischemia.
- **Inflammation**: LOX products such as leukotrienes and HpETEs can act as inflammatory mediators; leukotriene pathways are involved in asthma and other inflammatory conditions. Chronic dysregulation may contribute to inflammaging.
- **Cancer**: LOX isoforms can have pro- or anti-tumor effects depending on isoform, tissue, and context; their roles are complex.
- **Neurodegeneration**: Increased LOX-related lipid oxidation has been studied in relation to neuronal injury and neurodegenerative disease, but causal and therapeutic roles remain under investigation.

### 4.2 Two major players in lipid oxidation: structural contrast between LOX and GPX4

| Enzyme | Role | Catalytic center | Structure article |
|---|---|---|---|
| LOX | Ignition (produces LOOH) | Non-heme iron | [40-lox.md](40-lox.md) |
| GPX4 | Extinguishing (reduces LOOH) | Selenocysteine (Sec) | [39-gpx4.md](39-gpx4.md) |

**Iron versus selenium:** LOX uses iron to oxidize PUFAs and initiate lipid oxidation; GPX4 uses Sec to reduce lipid hydroperoxides. Their chemistries point in opposing directions—one oxidizing, one reducing.

**Shared substrate/product:** LOOH is a product of LOX-mediated oxidation and a substrate for GPX4. The same molecule lies at the interface of production and removal; the balance of formation and clearance matters.

**Structural contrast:** LOX has a long channel for positioning PUFAs and an iron center; GPX4 has an open, relatively flat active surface and a Sec center. Their architectures suit different tasks.

**Long channel versus flat surface:** LOX must orient a long PUFA precisely, favoring a deep channel; GPX4 must access diverse lipid hydroperoxides, favoring a more open surface. Structure reflects function.

**Complementary chemistry:** LOX catalyzes oxidation using iron; GPX4 catalyzes peroxide reduction using selenium. One helps produce lipid hydroperoxides; the other removes them.

### 4.4 LOX and dietary lipids: the dual aspects of omega-3/6

LOX substrates derive from dietary and cellular lipids, and omega-3/omega-6 pathways can produce different signals.

**Omega-6 and inflammatory signaling.** Omega-6 fatty acids such as linoleic acid and arachidonic acid can be converted into LOX products, including leukotrienes that promote inflammatory signaling. The outcome depends on pathway and context; omega-6 fats are not inherently harmful.

**Omega-3 and pro-resolving signaling.** EPA/DHA can give rise to lipid mediators, including resolvins and related pro-resolving mediators, through enzymatic pathways that can involve LOX. These may support resolution of inflammation and tissue repair.

**Dietary balance.** Modern diets can have a higher omega-6/omega-3 ratio than some traditional diets, but the ideal ratio and clinical effects depend on the overall dietary pattern. The key is an adequate, balanced intake rather than treating one class as universally inflammatory and the other as universally protective.

**Aging implication:** Dietary lipid composition can influence substrate availability and mediator profiles. A balanced dietary pattern, potentially including omega-3 sources, may support healthy inflammatory regulation; it is not a stand-alone substitute for medical care. LOX modulation and diet are complementary research areas.

**Overall aging implication:** The balance between lipid peroxide generation (including LOX) and removal (including GPX4) is relevant to ferroptosis. Healthy regulation involves both limiting excessive oxidation and maintaining adequate antioxidant capacity.

### 4.3 LOX and inflammaging: leukotrienes as inflammatory alarms

LOX products include inflammatory mediators and other lipid signals—the igniter’s alarm signals.

**Leukotriene synthesis.** 5-LOX acts on arachidonic acid in the leukotriene pathway, yielding mediators such as LTB₄ and cysteinyl leukotrienes (LTC₄, etc.) that influence chemotaxis, vascular tone, and inflammation. The igniter can trigger an inflammatory alarm.

**HpETE signaling.** 12/15-LOX products such as HpETEs/HETEs can act as lipid signals, including in metabolic regulation (for example, some lipid ligands can affect PPAR pathways). Oxidized lipids can be both damaging products and signals.

**Dialogue with NF-κB/cGAS–STING.** LOX products can influence inflammatory pathways such as NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md)); cellular damage may release DNA and activate cGAS–STING ([30-cgas-sting.md](30-cgas-sting.md)). Lipid signaling, damage, and inflammatory alarms can amplify one another, though the relationships depend on context.

**Additional evidence for the ferroptosis tug-of-war:** GPX4 inhibition by RSL3 can induce ferroptosis, while inhibition of particular LOX pathways can partially protect in some models. This supports a role for LOX in certain ferroptosis settings, but does not make all ferroptosis LOX-dependent.

**Physiological functions of LOX:** LOX is not simply harmful. Its products participate in normal physiology, including development, barrier biology, and inflammation resolution. Complete or chronic inhibition may have adverse effects; modulation should be selective and context-dependent.

---

## 5. Evidence grading

| Structural fact | Evidence level | Basis |
|---|---|---|
| LOX non-heme iron catalytic center | ★★★★★ Established | 1LOX (1997, *NSB*) |
| Long substrate channel accommodates PUFAs | ★★★★★ Established | 1LOX/3V99 |
| Iron coordination (3 His + C-terminal Ile + water) | ★★★★★ Established | 1LOX |
| Substrate complex (5-LOX + AA) | ★★★★★ Established | 3V99 (2012, *FASEB J*) |
| LOX oxidizes PUFAs to LOOH | ★★★★★ Established | Classical biochemistry |
| LOX contributes to ferroptosis in some settings | ★★★★☆ Strong | Multiple studies |
| LOX products such as leukotrienes mediate inflammation | ★★★★★ Established | Classical pharmacology |
| LOX inhibitor zileuton approved | ★★★★★ Established | FDA approval for asthma |

### 5.1 Supplement: pharmacological validation of LOX

LOX has pharmacological validation, including an approved drug—but new applications require separate evidence.

**Approval of zileuton.** Zileuton, a 5-LOX inhibitor, was approved by the FDA for asthma in 1996, demonstrating that the leukotriene pathway can be pharmacologically targeted in humans.

**Repurposing direction.** Zileuton’s potential in ferroptosis-related disease or aging has been explored in preclinical contexts; efficacy and safety for those indications remain to be established in humans. Known approval in asthma does not establish benefit for aging.

**Lesson from the drug evidence:** LOX is a druggable pathway, and an approved agent can support new research. Repurposing may be efficient, but the new indication still requires rigorous testing.

---

## 6. Connections to the knowledge-base themes

### 6.0 Lipid-oxidation family: opposing LOX and GPX4 structures

```text
Ignition: LOX (40, iron-catalyzed, PUFA → LOOH)
Extinguishing: GPX4 (39, Sec-catalyzed, LOOH → LOH)
Command: Nrf2 (15, transcription of GPX4 and other defenses)
Inflammation: NF-κB (14) | cGAS–STING (30)
```

**The complete lipid-oxidation balance:** LOX ([40-lox.md](40-lox.md)) promotes formation → GPX4 ([39-gpx4.md](39-gpx4.md)) reduces lipid peroxides → Nrf2 ([15-nrf2-structure.md](15-nrf2-structure.md)) coordinates antioxidant gene expression → inflammatory pathways ([14-nfkb-structure.md](14-nfkb-structure.md)/[30-cgas-sting.md](30-cgas-sting.md)) respond to signals and damage. Ignition, removal, command, inflammation: four linked components. Healthy aging research asks how to limit excessive oxidation, support antioxidant defenses, and regulate inflammation across the pathway.

### 5.1 Maturity of LOX evidence: from 1993 to 2017

LOX research has accumulated structural and functional evidence over decades:

- **1993: early LOX structures**: Soybean/rabbit LOX structures revealed the iron center and established an early structural foundation.
- **1997: mammalian 15-LOX structure (1LOX)**: Rabbit 15-LOX at about 2.4 Å clarified the catalytic domain and substrate channel.
- **2012: 5-LOX + AA (3V99)**: The human 5-LOX substrate complex provided structural information on substrate binding and regioselectivity.
- **2017: PEBP1–15-LOX–ferroptosis (Nature)**: Work on the PEBP1/15-LOX complex connected lipoxygenase-mediated lipid peroxidation to ferroptosis mechanisms.

**Lesson from the evidence:** LOX has substantial structural and functional evidence, from early structures to ferroptosis-related mechanisms. Its biology is sufficiently grounded for targeted research, while precise causal roles remain context-specific.

### 6.1 Further links to the main series: lipid oxidation–ferroptosis network

- **GPX4** ([39-gpx4.md](39-gpx4.md)): opposing partner—ignition versus extinguishing.
- **Nrf2** ([15-nrf2-structure.md](15-nrf2-structure.md)): antioxidant commander—coordinates defenses.
- **NF-κB** ([14-nfkb-structure.md](14-nfkb-structure.md)): master inflammatory switch—the alarm.
- **cGAS–STING** ([30-cgas-sting.md](30-cgas-sting.md)): DNA-damage alarm.
- **SIRT3** ([34-sirt3-structure.md](34-sirt3-structure.md)): mitochondrial antioxidant defense.
- **mTOR** ([04-mtor-structure.md](04-mtor-structure.md)): upstream signaling regulator.

**Network view:** LOX ([40-lox.md](40-lox.md)) contributes to lipid oxidation; GPX4 ([39-gpx4.md](39-gpx4.md)) removes peroxides; Nrf2 ([15-nrf2-structure.md](15-nrf2-structure.md)) coordinates defenses; p53 ([13-p53-structure.md](13-p53-structure.md)) influences cell fate; NF-κB ([14-nfkb-structure.md](14-nfkb-structure.md))/cGAS–STING ([30-cgas-sting.md](30-cgas-sting.md)) participate in inflammatory responses. Together they form a network of lipid oxidation, antioxidant control, cell fate, and inflammation. Interventions should consider multiple links and context rather than assume a single “anti-aging prescription.”

**Supplementary mnemonic:** LOX uses iron to start oxidation; GPX4 uses selenium-containing Sec to reduce lipid peroxides. Articles 39 (GPX4) and 40 (LOX) are opposing sides of the ferroptosis story. The central idea is bidirectional management of lipid oxidation—limit excessive ignition while preserving sufficient antioxidant defense.

---

## 7. Five structural questions about aging

| Question | Structural answer |
|---|---|
| How does LOX oxidize PUFAs? | Iron-mediated hydrogen abstraction → radical → O₂ addition → LOOH. |
| Why is oxidation regioselective? | Channel geometry and substrate anchoring orient a particular carbon toward the iron. |
| How can LOX contribute to ferroptosis? | It can produce lipid hydroperoxides that participate in iron-catalyzed lipid oxidation. |
| How might this relate to aging? | Study LOX modulation alongside GPX4/GSH defense and inflammatory regulation. |
| How can it be modulated? | Selective, context-appropriate LOX inhibition and antioxidant-pathway support are research avenues. |

**Structural intuition beyond the five questions:** Lipid oxidation can arise through both enzymatic and non-enzymatic routes. LOX is a regulated enzymatic source and therefore a potential intervention point, unlike uncontrolled radical chemistry alone. Aging implications: (1) enzymatic lipid oxidation can be pharmacologically studied (zileuton is approved for asthma, but its anti-aging value is unproven); (2) the LOX–GPX4 system involves both peroxide formation and removal; and (3) LOX products have signaling roles as well as potential damage, so complete suppression may be undesirable. Balance and context remain central.

### 8.1 Unsolved mysteries of LOX and ferroptosis-related aging

Several questions remain open—the igniter’s blind spots:

- **Quantifying LOX contribution**: What proportion of lipid oxidation in ferroptosis is enzymatic (LOX) versus non-enzymatic (e.g., iron/ROS)? Not yet settled.
- **Isoform division of labor**: What are the respective roles of 5/12/15-LOX in ferroptosis and inflammation? The division is incompletely understood.
- **Inhibitor selectivity**: Existing LOX inhibitors such as zileuton differ in isoform specificity and potential adverse effects; improved selectivity is needed.
- **Evidence for repurposing**: Human evidence for zileuton in ferroptosis-related disease or aging is lacking and requires study.
- **Aging implication**: LOX is a potentially modifiable pathway, with an existing drug as a research starting point—not a validated anti-aging treatment. Repurposing requires evidence in the intended indication.

### 5.1 Maturity of LOX evidence: from 1993 to 2017

---

## 8. Open questions

1. **Complete LOX substrate spectrum**: identify additional lipid substrates beyond PUFAs.
2. **LOX’s quantitative contribution to ferroptosis**: determine enzymatic versus non-enzymatic oxidation contributions.
3. **New applications for LOX inhibitors**: test anti-ferroptosis/aging hypotheses, including zileuton repurposing.
4. **Tissue specificity**: define tissue functions of 5/12/15-LOX isoforms.
5. **LOX and cancer**: determine when individual isoforms promote or suppress tumors.
6. **Post-translational regulation**: establish how phosphorylation and membrane translocation regulate LOX.

---

## 9. Guide to structural data

- **PDB entries**:
  - 1LOX: rabbit 15-lipoxygenase (2.40 Å, Gillmor 1997, *Nat Struct Biol*)—early mammalian LOX structure.
  - 3V99: human 5-LOX (S663D) + arachidonic acid (2.25 Å, Gilbert 2012, *FASEB J*)—substrate complex.
  - 2P0M: rabbit 15-LOX, re-refined reference structure.
  - 3V92/3V98: human 5-LOX variants.
  - 6N2W and others: human 15-LOX-related structures.
  - AlphaFold: AF-P16050 (human ALOX15).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (published literature)

1. Gillmor SA, Villasenor A, Fletterick R, Sigal E, Browner MF. The structure of mammalian 15-lipoxygenase reveals similarity to the lipases and the determinants of substrate specificity. *Nat Struct Biol* 1997;4:1003–1009. (PDB 1LOX)
2. Gilbert NC, Rui Z, Neau DB, et al. Conversion of human 5-lipoxygenase to a 15-lipoxygenase by a point mutation to mimic phosphorylation at Serine-663. *FASEB J* 2012;26:3222–3229. (PDB 3V99)
3. Boyington JC, Gaffney BJ, Amzel LM. The three-dimensional structure of an arachidonic acid 15-lipoxygenase. *Science* 1993;260:1482–1486. (Early LOX structure)
4. Seiler A, Schneider M, Forster H, et al. Glutathione peroxidase 4 senses and translates oxidative stress into 12/15-lipoxygenase dependent- and AIF-mediated cell death. *Cell Metab* 2008;8:237–248. (GPX4–12/15-LOX)
5. Wenzel SE, Tyurina YY, Zhao J, et al. PEBP1 wardens ferroptosis by enabling lipoxygenase-generated lipid peroxidation. *Nature* 2017;547:693–697. (15-LOX–PEBP1–ferroptosis)
6. Kuhn H, Banthiya S, van Leyen K. Mammalian lipoxygenases and their biological relevance. *Biochim Biophys Acta* 2015;1851:308–330. (Review)
7. Ivanov I, Kuhn H, Heydeck D. Structural and functional biology of arachidonic acid 15-lipoxygenase-1. *Biochim Biophys Acta* 2015;1851:333–345. (15-LOX review)

---

> **Structural recap**: Lipoxygenase (LOX) is an **igniter of lipid peroxidation**: a non-heme iron catalytic center (3 His + C-terminal Ile + water; 1LOX at 2.4 Å), long PUFA substrate channel (3V99 shows human 5-LOX + AA), and N-terminal β-barrel for membrane association. **Iron-mediated hydrogen abstraction → radical formation → O₂ addition → LOOH** starts lipid oxidation. LOX and GPX4 ([39-gpx4.md](39-gpx4.md), Sec-mediated reduction) form opposing parts of the ferroptosis network: LOX contributes to peroxide formation, GPX4 to removal. LOX products such as leukotrienes also signal in inflammation. Zileuton is approved for asthma; potential use against ferroptosis or aging remains unproven. **Research focuses on selective pathway modulation, antioxidant capacity, and balanced lipid oxidation—not indiscriminate LOX suppression.**
