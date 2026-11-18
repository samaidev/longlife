# Rentosertib: In-Depth Analysis of Chemical Structure, Molecular Data, and Synthesis

> Focus: A dedicated study of Rentosertib’s **structure and synthesis**—chemical structure, binding mode, structure–activity relationship (SAR), synthetic route, physicochemical properties, and preclinical/clinical pharmacokinetics (PK).  
> Target: TNIK (TRAF2- and NCK-interacting kinase) | CAS 2828567-39-9 | Molecular formula C₂₇H₃₀FN₇O | Molecular weight 487.57  
> Related documents: Overview of mechanisms in `01-rentosertib.md`; deep dive into molecular mechanisms in `05-molecular-mech.md`; NO/NAD⁺ theme in `01-foundations/03-no-basics.md`.

---

## 1. Core concept

Rentosertib is the world’s first small-molecule drug developed end-to-end with generative AI (target discovery + molecular design + clinical proof of concept). Insilico Medicine’s PandaOmics platform identified TNIK as the top candidate target from multi-omics data on idiopathic pulmonary fibrosis (IPF), after which its Chemistry42 molecular-generation platform designed a small-molecule inhibitor with a **novel bis-imidazole scaffold** (development codes INS018_055 / ISM001-055; the WHO adopted the generic name Rentosertib in 2026). The chemical structure itself embodies three design principles: anchoring at the hinge by mimicking ATP adenine, hydrophobic filling deep in the gatekeeper back pocket, and a basic, water-solubilizing tail extending toward solvent. This generative-design constraint—“two-point pharmacophore + back-pocket occupancy”—enabled nanomolar selectivity centered on TNIK (IC₅₀ = 31 nM) in a 430-kinase panel. Its relevance to anti-aging is that TNIK is a convergence kinase for the Wnt/β-catenin, TGF-β, and Hippo/YAP–TAZ pathways. Inhibiting it can systemically downregulate the senescence-associated secretory phenotype (SASP) and upregulate the NAMPT/NAD⁺ metabolic axis. In September 2026, *Nature Biotechnology* reported that plasma proteomics from the phase 2a IPF trial showed consistent biological-age reversal signals across six independent aging clocks (see `01-rentosertib.md`). Understanding the molecule’s structure is the chemical starting point for understanding “why an antifibrotic drug produces an anti-aging signal.”

## 2. Molecular data (officially confirmed)

```
Name          : Rentosertib (WHO International Nonproprietary Name)
Development codes: INS018_055 / ISM001-055 / INS018-055 (Insilico Medicine)
Commercial aliases: TNIK&MAP4K4-IN-2 (catalog aliases at MedChemExpress / Selleck)
CAS number    : 2828567-39-9
Molecular formula: C₂₇H₃₀FN₇O
Molecular weight: 487.57 g/mol
PubChem       : CID 164938183
IUPAC         : 2-[5-(4-fluorophenyl)-3-isopropylimidazol-4-yl]-N-[4-(4-methylpiperazin-1-yl)phenyl]-1H-imidazole-5-carboxamide
SMILES        : CC(C)N1C=NC(=C1C2=NC=C(N2)C(=O)NC3=CC=C(C=C3)N4CCN(CC4)C)C5=CC=C(C5)F
InChI         : InChI=1S/C27H30FN7O/c1-18(2)35-17-30-24(19-4-6-20(28)7-5-19)25(35)26-29-16-23(32-26)27(36)31-21-8-10-22(11-9-21)34-14-12-33(3)13-15-34/h4-11,16-18H,12-15H2,1-3H3,(H,29,32)(H,31,36)
Source patent : WO2022179528A1 (Insilico Medicine); synthesis and characterization details in SI-4 of the Nat Biotechnol 2024 paper
```

**Correction of development-code errors (important):** The online claim that the original code was “GLG-101 / GDC-0084” is **misinformation**. GDC-0084 is actually **paxalisib**, a PI3K inhibitor from Genentech (Roche; CAS 1382979-44-3) for glioblastoma, unrelated to Rentosertib. There is also no public evidence supporting the codes “REN-2154 / RVU-2154.” The official Rentosertib development codes are INS018_055 / ISM001-055 only. Also, **Insilico Medicine owns and develops the drug independently**; no licensing/partnership record with BMS or Ipsen has appeared in public sources (including the July 2026 HKEX announcement). Such matters remain “to be verified”; any new transaction should be confirmed through official disclosure.

**Stereochemistry:** All centers in the molecule belong to aromatic rings or planar heterocycles. It **contains no chiral carbon** and presents no stereoselective-synthesis problem—one structural reason the molecule is relatively straightforward to synthesize (unlike many kinase inhibitors with chiral piperazine/pyrrolidine side chains).

## 3. Structural decomposition and structure–activity relationship (SAR)

```
 isopropyl ── N─imidazole ring A ── C2─C5 ── imidazole ring B ── C(=O)NH ── para-substituted phenyl ── N-methylpiperazine
 (iPr)       │                                            (amide bond)              (solubilizing tail)
             └─ 5-(4-fluorophenyl) ── hydrophobic anchor (back-pocket filling)
```

| Structural unit | Group | Chemical role | Function and SAR logic |
|---|---|---|---|
| Imidazole A | 1-isopropyl-5-(4-fluorophenyl)imidazole | Hydrophobic aromatic core | Isopropyl points toward Asn158/Gln157; p-fluorophenyl penetrates the gatekeeper back pocket (coplanar with the Met105 C–S–C bond; S-to-ring carbon 3.8 Å), contributing van der Waals packing and selectivity |
| Imidazole B | 1H-imidazole-5-carboxamide | Hydrogen-bond donor/acceptor | Imidazole NH forms a hydrogen bond with the hinge backbone and the gatekeeper Met105 side-chain sulfur (~3.2 Å); carboxamide carbonyl oxygen forms a hydrogen bridge with hinge Cys108-NH—**an ATP adenine-mimicking anchor** |
| Amide bond | –C(=O)NH– | Linker + conformational lock | Amide NH forms an **intramolecular hydrogen bond** with the adjacent imidazole nitrogen, locking the bis-imidazole in a planar conformation and preorganizing it for the pocket (lowering the entropic cost) |
| p-Fluorophenyl | 4-F-C₆H₄ | Electronic effect + metabolic protection | Fluorine blocks the para aromatic metabolic hotspot (slowing oxidative metabolism) and modulates overall pKa and lipophilicity |
| N-methylpiperazine | 4-methylpiperazin-1-yl | Basic, water-solubilizing tail | Piperazine nitrogen is protonated at physiological pH (pKa about 7–8), contributing solubility, oral absorption, and low plasma-protein binding; it extends into solvent without interfering with pocket binding |

**Key SAR point (mapping generative constraints to drug-like properties):** The Chemistry42 generation constraints were deliberate. The pharmacophore disclosed in the paper followed a “two-point hypothesis”: (1) a hydrogen-bond acceptor forms a bond with hinge-region **Cys108-NH**; (2) a hydrophobic center penetrates the **non-conserved back pocket near gatekeeper Met105**, bounded by Met105, Leu73, Leu103, Ala52, and Val104. The engine also penalized structures that violated drug-like ranges (logP, molecular weight, hydrogen-bond donor/acceptor counts, TPSA, number of rotatable bonds, number of aromatic rings) and synthetic-accessibility thresholds. **Back-pocket occupancy is a selectivity strategy:** the hinge is highly conserved across kinases, whereas the gatekeeper back pocket varies; occupying this non-conserved pocket is key to escaping “pan-kinase inhibition” and creating a selectivity window. The bis-imidazole scaffold itself was a novel generative-model output, deliberately outside the patent space of known kinase-inhibitor scaffolds such as quinazolines, pyridopyrimidines, and indazoles.

**Why certain structural details remain “to be verified”:** The public paper (Ren et al., *Nat Biotechnol*, 2024) presents an overlay with the TNIK co-crystal structures of NCB-0846 (PDB 5D7A) and compound 9 (PDB 5AX9), along with a predicted binding-mode diagram. However, **a co-crystal structure of INS018_055 itself has not been published**. Therefore, the binding mode described above is fundamentally based on structural overlay and docking prediction (the paper calls it a “predicted binding mode”). Hydrogen-bond distances (3.2 Å and 3.8 Å) come from that model and are high-confidence inference, not crystallographic measurement—an important precision boundary when reading these data.

## 4. Binding mode in the TNIK kinase domain

### 4.1 Pocket anatomy

TNIK is a serine/threonine kinase in the GCK subfamily of the STE20 family (~161 kDa). Its catalytic domain has a canonical bilobal structure: an N-lobe (mainly β-sheets, including the P-loop) and a C-lobe (mainly α-helices, including the catalytic and activation loops), with the ATP pocket in the cleft between them. The pocket has three functional regions: the **hinge**, connecting the lobes and accommodating ATP adenine; the **hydrophobic back pocket**, defined by the gatekeeper residue (Met105 in TNIK; many other kinases have valine/leucine/threonine, whose side chains are shorter) and the phenylalanine of the DFG motif; and the **solvent region**, facing the cytoplasm.

### 4.2 Predicted binding mode (paper data)

```
         Hinge                         Back pocket                 Solvent region
┌──────────────────────┐   ┌─────────────────────────┐   ┌───────────────────┐
│ Cys108-NH ← carbonyl O│   │ Met105(S) ← imidazole NH│   │                   │
│       (H-bridge)       │   │          (~3.2 Å)       │   │ N-methylpiperazine│
│ backbone carbonyl ←   │   │ Leu73/Ala52/Val104/     │   │ (protonated)       │
│ imidazole NH (H-bond)  │   │ Leu103 define hydrophobic│  │ extends into solvent│
│ imidazole B ≈ ATP      │   │ walls                   │   │ contributes solubility│
│ adenine position       │   │ p-fluorophenyl inserts  │   │                   │
│                        │   │ (coplanar with C–S–C,   │   │                   │
│                        │   │ 3.8 Å)                  │   │                   │
│                        │   │ isopropyl → Asn158/Gln157│  │                   │
└──────────────────────┘   └─────────────────────────┘   └───────────────────┘
```

The points correspond to data disclosed in the paper:

1. **Two hinge hydrogen bonds:** The **carboxamide carbonyl oxygen of imidazole B forms a hydrogen bridge with Cys108-NH** (mimicking ATP adenine N1). The imidazole-ring NH also participates in the hinge-region hydrogen-bond network. This is a shared anchoring mode of TNIK inhibitors such as NCB-0846 and compound 9.
2. **Intramolecular hydrogen bond locks conformation:** An intramolecular hydrogen bond between the amide NH and adjacent imidazole nitrogen fixes the bis-imidazole in a planar conformation, reducing the entropic cost of binding. This is the key design insight of linking the three fragments “bis-imidazole + amide” into one unit.
3. **Gatekeeper hydrogen bond:** The imidazole NH is about 3.2 Å from the Met105 side-chain sulfur and may form a hydrogen bond. Co-crystal structures of NCB-0846 and compound 9 show the Met105 side chain “covering” the back-pocket entrance; neither can displace this residue. **INS018_055 is the only known TNIK inhibitor predicted to insert deeply into the back pocket**—the structural basis for its improved selectivity over related molecules.
4. **Hydrophobic back-pocket filling:** The second imidazole directs the p-fluorophenyl group into the back pocket, with its plane approximately coplanar with the C–S–C bond of Met105 (3.8 Å from sulfur to the nearest ring carbon), enabling π–sulfur interactions and tight van der Waals contacts. The isopropyl group points toward the polar edge near Asn158/Gln157, providing both hydrophobic packing and contact at the pocket base.
5. **DFG conformation:** Based on its pharmacophore (without an extended hydrophobic tail) and binding kinetics (Kd = 4.32 nM; rapid binding), the molecule is classified as a **Type I (DFG-in), ATP-competitive** inhibitor: it occupies the adenine site, does not rely on covalent modification, and binds reversibly. It has been suggested that it might also bind the DFG-out state, but no co-crystal evidence exists; this remains “to be verified.”

### 4.3 Measured binding affinity (SPR)

Surface plasmon resonance (Biacore 8K, His-tagged TNIK fragment 9–315): **Kd = 4.32 nM**, significantly stronger than the early TNIK inhibitors used as comparators (NCB-0846 and KY-05009 had higher Kd values in the same assay). Kd 4.32 nM and enzyme IC₅₀ 31 nM are in the same range, indicating consistency between binding and functional inhibition, without substantial “binds but does not inhibit” off-target binding.

## 5. Kinase selectivity (KinaseProfiler data)

The paper used Eurofins’ standard KinaseProfiler to screen **430 kinases** at a single concentration of 10 μM (mainly radiometric assays; lipid kinases and ATM/ATR/DNA-PK by HTRF), then measured IC₅₀ dose–response curves for 42 top hits:

| Measure | Value | Notes |
|---|---|---|
| TNIK IC₅₀ | **31 nM** | Most inhibited target in the panel |
| Nanomolar-range hits (<1 μM) | Mainly fibrosis-related kinases | ALK4, TGFBR1, DDR1, etc. (explicitly stated in the paper) |
| Improvement over early lead | Better than NCB-0846 | NCB-0846 had IC₅₀ <100 nM against 8 of 50 kinases; INS018_055 had significantly higher IC₅₀ against 6 of these |

**Interpretation:** (1) TNIK IC₅₀ of 31 nM and SPR Kd of 4.32 nM cross-validate TNIK as the main target. (2) Ancillary activity is not random off-target activity; it is **concentrated in fibrosis-related kinases upstream or downstream of the TGF-β axis** (ALK4/TGFBR1 are TGF-β receptor family members). In the context of IPF, this may contribute synergistically to antifibrotic effects, explaining the robustness of FVC improvement across the three dose groups over 12 weeks. (3) The supplier-catalog alias “TNIK&MAP4K4-IN-2” indicates substantial inhibition of MAP4K4 (an upstream kinase in the Hippo pathway), but **its exact IC₅₀ has not been disclosed in the main paper (to be verified)**. Ancillary MAP4K4 inhibition is a double-edged sword: in theory it weakens LATS1/2-mediated suppression of YAP/TAZ and could raise YAP activity, while YAP itself is profibrotic (see the controversy in Section 7 of document 01).

## 6. Synthesis-route analysis

⚠️ **Status of process disclosure:** The official synthesis process has not been published in full. Patent WO2022179528A1 and paper supplementary information SI-4 provide definitions and characterization (the compound was supplied by WuXi AppTec). The following is a retrosynthetic analysis based on medicinal-chemistry logic (consistent with the patent scaffold), a high-confidence inference rather than a reproduction of the official process.

### 6.1 Retrosynthetic disconnections

```
Target molecule C₂₇H₃₀FN₇O
  ├─ Disconnection 1 (amide bond; priority): imidazole B carboxylic acid + 4-(4-methylpiperazin-1-yl)aniline
  │      → HATU/EDCI amide coupling (mild, high-yielding, no stereochemical control required)
  └─ Disconnection 2 (C–C bond): imidazole A C2 boronate × imidazole B C5 bromide
         → Suzuki–Miyaura coupling (Pd-catalyzed; regioselectivity is key)
```

### 6.2 Plausible route (six-step logic)

**Step 1: Build imidazole A (1-isopropyl-5-(4-fluorophenyl)imidazole)**
- Method A: Radziszewski multicomponent condensation (4-fluorobenzaldehyde + isopropylamine + glyoxal/ammonium salt)—one-pot construction, but regiochemistry (1,4- vs 1,5-substitution) must be controlled.
- Method B (more controllable): α-bromination of 4-fluoroacetophenone → cyclization with formamide/ammonium acetate → N-alkylation (2-iodopropane/K₂CO₃ or Mitsunobu reaction with isopropanol). N1 alkylation is well-defined and avoids multisubstituted isomers.

**Step 2: Build imidazole B (ethyl 5-bromo-1H-imidazole-4-carboxylate)**
- Commercially available ethyl imidazole-4-carboxylate can be brominated with NBS (preferentially at C5). The imidazole NH should first be shielded with an SEM/Ts protecting group to prevent interference from NH and N-arylation side reactions during coupling.

**Step 3: Suzuki–Miyaura coupling (A C2 × B C5)**
- Selective lithiation of imidazole A at C2 (n-BuLi, −78 °C, THF) → trapping with isopropyl pinacol boronate (iPrO-Bpin).
- Coupling conditions: Pd(dppf)Cl₂ catalyst, K₂CO₃ base, mixed DMF/H₂O solvent, 80–100 °C. **Challenge:** Imidazole has three potential coupling positions (2/4/5); regioselectivity depends on protecting-group strategy and the preselected halogenation position.

**Step 4: Ester hydrolysis:** Mild hydrolysis with LiOH/THF/H₂O gives the imidazole B carboxylic acid.

**Step 5: Amidation:** Activate the carboxylic acid with HATU/DIPEA or EDCI/HOBt and couple with 4-(4-methylpiperazin-1-yl)aniline to form the target amide bond.

**Step 6: Purification and confirmation:** Silica-gel chromatography (DCM/MeOH gradient) or reverse-phase HPLC to clinical-grade purity (≥99%); confirm by ¹H NMR / ¹³C NMR / HRMS (calculated [M+H]⁺ 488.2453).

### 6.3 Synthetic challenges

1. **Regioselectivity of the bis-imidazole C–C coupling:** Imidazole positions 2/4/5 differ substantially in electrophilic/metalation reactivity; protecting groups and temperature must both be controlled.
2. **Interference from imidazole B 1H:** An unprotected NH can quench the Pd catalyst and trigger N-arylation; SEM/Ts protection and deprotection add two steps.
3. **C2 lithiation selectivity:** Lithiation of imidazole A at C2 must avoid competition at C4/C5; −78 °C and steric direction are both essential.
4. **Scale-up crystallization:** Clinical-grade purity (99.9%+) and crystal-form consistency (affecting dissolution of the oral formulation) are scale-up bottlenecks.
5. **No chiral centers:** No stereochemical control is needed; overall process complexity is concentrated in heterocycle coupling rather than chiral synthesis, a relative advantage.

### 6.4 Practical advice (research use)

- **Prefer purchasing:** Commercial material with ≥99% purity is available from suppliers such as MCE (HY-160623) and Selleck (E1944), at a cost in the low-thousands of yuan. In-house synthesis requires a complex multistep heterocyclic route (n-BuLi, Pd catalysts, toxic/flammable reagents such as DMF); total cost greatly exceeds purchasing.
- The research opportunity lies in **scaffold hopping**: using the bis-imidazole–amide–arylamine core while systematically varying (a) the gatekeeper back-pocket group (p-fluorophenyl → other small aryl/heteroaryl groups), (b) the solvent tail (N-methylpiperazine → morpholine/carbamoylpiperidine to tune pKa and metabolism), and (c) the hinge anchor (carboxamide → amide bioisostere). This would explore the boundaries of SAR for TNIK back-pocket selectivity, a chemical space where “human intuition” can complement AI-generated chemistry.

## 7. Physicochemical properties and drug-likeness

| Property | Data | Source/notes |
|---|---|---|
| Molecular weight | 487.57 g/mol | Official; at the edge of Lipinski’s 500 limit |
| Solubility | DMSO/ethanol ≥100 mg/mL; insoluble in water | Supplier data; free-base form |
| Estimated logP | About 3–4 | Specific value not given in paper; estimated from structure (exact value to be verified) |
| Kinetic solubility | Early lead <2 μM → markedly improved after optimization | Disclosed in paper: initial screening lead had poor solubility; INS018_055 was ADMET-optimized |
| Metabolic stability | Early lead: high clearance in human/mouse liver microsomes → addressed by optimization | Disclosed in paper; core motivation for lead optimization |
| CYP inhibition | Early lead IC₅₀ <10 μM → addressed by optimization | Disclosed; final compound CYP profile not public (to be verified) |
| hERG | No public data | To be verified |
| Oral absorption | Tmax 1.0–1.5 h (fasted) | Measured in phase 1 |
| Elimination half-life | 7.4–11.9 h | Measured in phase 1 (supports BID dosing) |

**Drug-likeness narrative:** The paper describes a textbook “AI generation → ADMET repair” feedback loop. The first Chemistry42-generated lead had nanomolar binding but **high clearance in human/mouse liver microsomes, CYP inhibition IC₅₀ <10 μM, and kinetic solubility <2 μM**—three fatal liabilities. Subsequent lead optimization aimed at improving ADMET and produced INS018_055. Thus, the final bis-imidazole scaffold was not an instant hit from one generation; it was the outcome of multiple “generate–screen–repair” cycles. This is the essential difference between generative-AI drug discovery and classical medicinal chemistry: the generator proposes diverse structures, while wet-lab experiments and ADMET predictions eliminate failures.

## 8. Preclinical PK/PD and in vivo efficacy

### 8.1 Enzyme activity, cell activity, and cytotoxicity (in vitro)

| Assay | IC₅₀/CC₅₀ | Notes |
|---|---|---|
| TNIK enzyme activity (KinaseProfiler) | 31 nM | Main target |
| SPR binding Kd | 4.32 nM | High affinity |
| MRC-5 cell α-SMA (TGF-β-induced FMT) | 27.14 nM | Functional antifibrotic readout |
| Primary lung fibroblasts from IPF patients, α-SMA | 50 / 79 / 63 nM (three donors) | **IPF cells more sensitive than healthy-donor cells (79/200/320 nM)** |
| IPF bronchial-epithelial EMT (FN1) | 250 / 320 / 400 nM | Nintedanib comparator: 1,600 / 6,300 / 7,900 nM—**6–20-fold advantage** |
| MRC-5 cytotoxicity CC₅₀ | 84.3 μM | Therapeutic window >3,000-fold |
| HK-2 renal epithelial CC₅₀ | 37.37 μM | About 300 times the α-SMA IC₅₀ (0.104 μM) |

Key finding: **Inhibition potency was systematically higher in cells derived from IPF patients than in healthy-donor cells** (fibroblasts 50–79 vs. 79–320 nM), suggesting greater TNIK dependence in the IPF microenvironment (high TGF-β burden). This is functional evidence of “lesion selectivity” and may explain the possibility of efficacy and safety at clinical doses.

### 8.2 In vivo efficacy (multiorgan fibrosis models)

- **Mouse bleomycin-induced pulmonary fibrosis** (C57BL/6, n=10/group): oral 3 / 10 / 30 mg/kg BID reduced fibrotic area by **>50% (3 mg/kg) and >75% (10/30 mg/kg)** versus vehicle. Lung function (Penh) improved significantly, comparable to nintedanib 60 mg/kg QD; modified Ashcroft scores and α-SMA and collagen I staining also declined.
- **Combination with pirfenidone:** Subtherapeutic INS018_055 (3 mg/kg BID) + pirfenidone (60 mg/kg BID) was significantly better than either agent alone. 10 mg/kg + 200 mg/kg (maximum therapeutic pirfenidone dose) achieved **complete prevention of symptoms**, supporting clinical combination therapy.
- **LPS-induced acute lung injury:** A single dose significantly reduced BALF lymphocyte counts and IL-1β/IL-6/IL-7/TNF-α, while restoring anti-inflammatory IL-4; anti-inflammatory effects were stronger than those of dexamethasone.
- **Inhaled administration** (rat bleomycin model): Nebulized 0.1–6 mg/mL improved FVC, airway resistance, and lung compliance; the **lung-to-plasma drug concentration ratio was about 50-fold**—validating a “lung-targeted, low-systemic-exposure” strategy. In April 2026, the CDE accepted an IND for an inhaled formulation.
- **Mouse UUO renal fibrosis:** 3/10/30 mg/kg BID significantly reduced hydroxyproline, Sirius Red area, and collagen I scores.
- **Skin fibrosis** (bleomycin skin model): Topical 0.05% / 0.15% / 0.45% significantly reduced collagen and hydroxyproline.

## 9. Clinical PK and dose selection (why 30 mg BID)

### 9.1 Phase 1 PK data (healthy volunteers)

- **Phase 0 microdose** (Australia, ACTRN12621001541897): 100 μg IV was well tolerated; first-in-human data.
- **New Zealand phase 1** (NCT05154240, 78 participants): SAD (10/30/60/90/120 mg): fasted Tmax 1.00–1.53 h, **elimination half-life t₁/₂ = 7.42–9.74 h**, and Cmax/AUC approximately dose-proportional. After a meal, Tmax at 90 mg was delayed to 3.00 h and Cmax fell to 169 ng/mL (270 ng/mL fasted)—**a high-fat meal slows absorption and modestly reduces exposure**.
- **MAD** (30/60/120 mg QD × 7 days): t₁/₂ = 9.36–11.9 h; **no accumulation** (Day 7/Day 1 Cmax ratio 0.739–0.905; AUC ratio 0.996–1.05).
- **China phase 1** (CTR20221542): SAD 30/60/120 mg + MAD 30/60/90 mg BID × 7 days; PK was consistent with the New Zealand population, and BID dosing also showed no substantial accumulation.
- **Safety:** Adverse events were mild (positive fecal occult blood, headache, phlebitis) and resolved spontaneously. Flu-like events coincided with the COVID-19 epidemic and were judged unrelated to the drug. Overall conclusion: “safe and well tolerated in healthy volunteers, with good oral bioavailability and dose-proportional PK.”

### 9.2 Half-life of 7.4–11.9 h and rationale for 30 mg BID

A t₁/₂ of about 8–12 h supports BID dosing (roughly 1.5–2 half-life intervals, with an acceptable steady-state peak-to-trough ratio). By contrast, 60 mg QD produces a higher peak and lower trough with greater exposure fluctuation. Phase 2a (GENESIS-IPF, NCT05938920) therefore compared **30 mg QD / 30 mg BID / 60 mg QD**. The 30 mg BID schedule uses the **same daily dose (60 mg/day) to achieve a steadier exposure curve**. In the exploratory anti-aging proteomics, 30 mg BID had the most stable clock-reversal signal (9 significant comparisons out of 54; 142 uniquely changed protein trajectories), suggesting that “steady exposure” may be better than a high peak-to-trough ratio. Mechanistically, this may relate to the time-integrated dose of TNIK inhibition rather than instantaneous peak concentration (to be verified). Phase 2a efficacy data: mean FVC increased by **98.4 mL (95% CI 10.9–185.9)** in the 60 mg QD group, versus a 20.3 mL decline with placebo; improvement was more marked in the subgroup not receiving background standard antifibrotics (nintedanib/pirfenidone).

### 9.3 Phase 3 and formulation expansion

Global phase 3 began in July 2026 (Insilico Medicine HKEX announcement 03696). The primary endpoint is the **annual rate of FVC decline over 52 weeks**; secondary endpoints include time to first disease progression, change in DLCO, and quality-of-life scales. In April 2026, an inhaled formulation received a CDE IND authorization—advancing on two tracks: “oral systemic + inhaled lung-targeted.”

## 10. Comparison with other TNIK inhibitors

| Compound | Structural type | TNIK activity | Binding mode | Status |
|---|---|---|---|---|
| **Rentosertib** | Bis-imidazole–amide–arylamine (AI-generated) | IC₅₀ 31 nM / Kd 4.32 nM | Two hinge hydrogen bonds + **deep back-pocket insertion** (predicted) | Phase 3 (IPF) |
| **NCB-0846** | Tricyclic heteroaromatic (Chugai) | Nanomolar (literature; exact IC₅₀ to be verified) | Hinge binding; **cannot displace Met105**; shallow back-pocket occupancy | Preclinical (colorectal cancer) |
| **Compound 9** | Aminopyridine–benzonitrile | Nanomolar (literature) | Two hinge hydrogen bonds + nitrile contacts Phe172 through water molecule | Preclinical |
| **KY-05009** | Arylamide | Nanomolar (literature) | Inhibits TGF-β-induced EMT (A549) | Preclinical |
| **ON-108600** | Structure not detailed | Not public | — | Preclinical (to be verified) |

Direct comparison in the paper: NCB-0846 had IC₅₀ <100 nM against 8 kinases in a 50-kinase panel (narrow selectivity window); INS018_055 had significantly higher IC₅₀ against six of these kinases. **The selectivity advantage was attributed to the difference in back-pocket occupancy.** SPR measurements in the same assay also showed a better Kd for INS018_055 (4.32 nM) than for NCB-0846/KY-05009. The lesson is that the direction of TNIK-inhibitor iteration is from first-generation shallow hinge binding toward second-generation deep back-pocket occupancy, to combine potency with selectivity.

## 11. Connections to NO, NAD⁺, and longevity networks (the knowledge base’s distinctive perspective)

The structural interface with anti-aging is that **TNIK’s catalytic pocket connects to transcriptional hubs for metabolism and immunity**. ATP-competitive inhibition by Rentosertib → reduced Wnt/β-catenin output (interrupted TCF4 phosphorylation) + reduced TGF-β/Smad output + ancillary MAP4K4/Hippo modulation → a five-layer downstream proteomic cascade (see Section 5 of document 01): all seven SASP proteins (EREG/ESM1/IGFBP4/ITGA2/MMP10/MMP13/SPP1) down; RTK–PI3K/RAS–ERK/IGF growth axes braked; **NAMPT up → expanded NAD⁺ pool → Sirt1 activation**; SOD2/ALDH1A1/glutathione antioxidant responses up; macrophages shift from M1 to M2 polarization.

Four points of intersection with the NO theme (see `05-molecular-mech.md`):

| Node | Rentosertib side | NO-pathway side | Point of convergence |
|---|---|---|---|
| Macrophage polarization | M1→M2 transcriptional reprogramming | iNOS drives M1; eNOS is associated with M2 | Convergence on the same immune-phenotype switch |
| NAD⁺/Sirt1 | NAMPT↑→NAD⁺↑→Sirt1↑ | NO↔Sirt1 positive-feedback loop | Shared NAD⁺ metabolic pool |
| TGF-β fibrosis | TNIK inhibition→Wnt/Smad output↓ | NO/cGMP–PKG inhibits TGF-β | Different routes, same suppression of fibrosis |
| Redox homeostasis | SOD2↑, glutathione metabolism↑ | NO regulates mitochondrial ROS (CCO brake valve) | Jointly maintaining redox balance and protecting eNOS coupling |

An interesting chemical detail: protonation of the basic nitrogen in the N-methylpiperazine tail gives the molecule a positive charge, which could favor accumulation in acidic phagocytic/lysosomal compartments such as lung macrophages. This might partly explain its marked effects on immune-cell phenotype, not just lung parenchymal cells (mechanistic speculation; to be verified).

## 12. Evidence grading

| Phenomenon | Evidence level | Key source |
|---|---|---|
| Bis-imidazole scaffold, formula, CAS, patent | ★★★★★ Officially confirmed | WHO INN, PubChem, WO2022179528A1 |
| Binding mode (hinge/back pocket/solvent regions) | ★★★★ Predicted model + co-crystal overlay | *Nat Biotechnol* 2024 (predicted binding mode, not a co-crystal of this drug) |
| Kd = 4.32 nM, TNIK IC₅₀ = 31 nM, 430-kinase selectivity | ★★★★★ Measured by SPR + KinaseProfiler | *Nat Biotechnol* 2024 |
| Early-lead ADMET liabilities and optimization | ★★★★★ Disclosed in paper | *Nat Biotechnol* 2024 (SI-3) |
| Cellular/animal antifibrotic activity (multiple organs) | ★★★★ In vitro + multiple animal models | *Nat Biotechnol* 2024 |
| Phase 1 PK (t₁/₂, no accumulation, food effect) | ★★★★★ 78 participants | NCT05154240 + CTR20221542 |
| Phase 2a FVC improvement (98.4 mL vs. −20.3 mL) | ★★★ Randomized controlled study, n=71 (secondary endpoint) | *Nat Med* 2025 |
| Biological-age reversal across six clocks | ★★★ Exploratory endpoint, n=42 | *Nat Biotechnol*, 2026-09 |
| Exact MAP4K4 IC₅₀, final CYP profile, hERG | ☆ Not public | To be verified |
| BMS/Ipsen licensing; codes such as REN-2154 | ☆ No evidence (GDC-0084 is a confusion) | Corrected above |

## 13. Open questions and controversies

1. **No co-crystal structure:** A co-crystal structure of INS018_055 bound to TNIK has not been published; “deep back-pocket insertion” is a prediction. A co-crystal would decisively establish whether Met105 is displaced (determining whether it has some Type II characteristics).
2. **Net effect of ancillary MAP4K4 inhibition:** In theory, inhibiting MAP4K4 weakens LATS-mediated suppression of YAP/TAZ → YAP may rise → profibrotic effects, opposing the antifibrotic direction of TNIK inhibition. However, scTenifoldKnk simulation suggests TNIK inhibition mainly activates Hippo signaling and downregulates YAP–TAZ (paper data). Experiments are needed to resolve this tension.
3. **The “black box” of synthesis:** Scale-up processes (crystal form, salt form, green chemistry) are not disclosed beyond the patent and SI-4—a barrier as well as an opportunity for generic/improvement research.
4. **Exposure–response relationship for 30 mg BID:** Why is BID better than QD at the same daily dose? Is it the peak-to-trough ratio or the time-integrated total exposure? Existing PK/PD models do not explain the mechanism.
5. **Causal chain from structure to aging clocks:** Between “pocket binding” and “reversal across six clocks” lie transcriptional reprogramming, immune polarization, and the metabolic axis. These mediating steps have not been directly established; the “molecular black box” between chemical structure and clinical phenotype is the field’s largest open question.

## 14. References

1. Ren F, et al. A small-molecule TNIK inhibitor targets fibrosis in preclinical and clinical models. *Nat Biotechnol*. 2024. DOI: 10.1038/s41587-024-02143-0. (Structure, binding mode, KinaseProfiler, ADMET optimization, efficacy in multiple models, phase 0/I PK.)
2. Xu J (led by the Xu Zuojun team), et al. A generative AI-discovered TNIK inhibitor for IPF: a randomized phase 2a trial (GENESIS-IPF, NCT05938920). *Nat Med*. 2025. DOI: 10.1038/s41591-025-03743-2. (Phase 2a: 71 participants, 30 mg QD/BID, 60 mg QD, FVC 98.4 mL vs. −20.3 mL.)
3. Zhavoronkov A, Galkin F, et al. Integration of proteomic aging clocks in a phase 2a clinical trial. *Nat Biotechnol*. 2026-09-07. DOI: 10.1038/s41586-026-03286-y (see rentosertib-report materials). (42 participants, six clocks, 326 vs. 2 proteins, r=−0.30.)
4. Masuda M, et al. TNIK inhibition abrogates colorectal cancer stemness. *Nat Chem Biol*. 2016;12:898–905. (NCB-0846 co-crystal PDB 5D7A; TNIK inhibition and colorectal-cancer stemness.)
5. Mahmoudi T, et al. The kinase TNIK is an essential activator of Wnt target genes. *EMBO J*. 2009;28:3329–3340. (Dual kinase + scaffold roles of TNIK.)
6. Insilico Medicine. Patent WO2022179528A1 (INS018_055 structure); HKEX announcement 03696 (July 2026, phase 3 start); press release on CDE IND clearance for inhaled formulation (2026-04-29).
7. Supplier information: MedChemExpress HY-160623 / Selleck E1944 (alias TNIK&MAP4K4-IN-2, solubility, storage conditions).
8. Correction source: GDC-0084 (paxalisib, CAS 1382979-44-3) is a Genentech PI3K inhibitor and unrelated to Rentosertib (verified in TargetMol/public databases).

---

*This is a drug-focused article in the LongLife longevity-research knowledge base. Structure and binding-mode data follow the 2024 Nat Biotechnol paper; items marked “to be verified” lack public confirmation and should be updated against original sources.*
