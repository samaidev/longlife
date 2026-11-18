# PBM molecular mechanism: NO switch of mitochondrial CCO

> Topic: Light-Brain Rejuvenation · Article 1 / 5 articles in total
> Positioning: The molecular mechanism of photobiomodulation (PBM)—how red light/near-infrared light regulates mitochondria and NO
> Related articles: For an overview of the NO pathway, see 01-foundations/03-no-basics.md; for mitochondria and anti-aging, see 02-vascular/04-mitochondria.md; for spectrum engineering, see this topic 02-light-spectrum.md; for deep targeting, see 04-fus.md

## Core concepts

Photobiomodulation (PBM, formerly known as Low-Level Laser Therapy, LLLT) refers to the use of low-power red light (600–700nm) and near-infrared light (NIR, 760–1100nm) to irradiate tissues without causing thermal damage, by activating mitochondrial photoreceptors - Cytochrome c Oxidase (CCO, respiratory chain complex) IV)** - to enhance cellular energy metabolism, change signaling pathways, reduce inflammation and promote repair. Its core molecular switch is **nitric oxide (NO) photodissociation**: NO reversibly binds to the binuclear copper-heme center of CCO at physiological concentrations and inhibits respiration, while red light/near-infrared photons are enough to interrupt the NO-metal coordination bond and make the "inhibited respiratory chain" work again - this is the upstream starting point of PBM's anti-aging logic. Different from chemical drugs, PBM is a physical energy intervention that does not introduce exogenous molecules, has a clear target of action (mitochondria), and has a safety record of more than 50 years. It is a rare "device" candidate in aging intervention. This article focuses on the entire chain of molecular mechanisms, providing a mechanism base for subsequent spectrum engineering, hypothalamic targeting and experimental design.

## 1. Concept and history of PBM: from laser accidents to space medicine

### 1.1 Source: Mester’s accidental discovery in 1967

The historical starting point of photobiomodulation is the "failed experiment" of Hungarian surgeon **Endre Mester**. In 1967, Mester tried to use a low-power ruby ​​laser (Ruby Laser, 694nm) to "heat" tumors on a mouse subcutaneous transplant tumor model. It was found that the laser did not burn the tumor as expected, but instead promoted wound healing and hair growth - an unexpected surprise contrary to the hypothesis. This discovery was published in 1968 (Mester E, et al. *Laser Rev* 1968;1:3-11, specific volume to be verified) and is considered the founding event of modern phototherapy (photobiomodulation). For decades afterward, the field became known as "low-level laser therapy (LLLT)."

### 1.2 NASA and space medicine: Why does NASA care about light?

In the 1990s, **NASA** collaborated with scientist Harry Whelan and others to study cellular energy metabolism in the space environment. The microgravity, radiation and closed environment of space can damage astronauts' mitochondrial function and wound healing ability. Research funded by NASA found that** near-infrared light (near 670nm) can significantly improve mitochondrial respiration and ATP synthesis** of cultured cells and accelerate wound healing. This "space medicine" background drove two key efforts: ① Establishing a mechanistic hypothesis of how light is absorbed by mitochondria and converted into energy; ② Promoting LED arrays to replace lasers as a safer, lower-cost PBM light source (LEDs can cover a large area without the risk of coherent light point damage). In the 2000s, the application of PBM gradually expanded from wound healing to pain, inflammation, and neuroprotection. In the 2010s, it entered the fields of transcranial photobiomodulation (tPBM) and brain/cognition, becoming the source of the topic "Light-Brain-Reverse Aging".

### 1.3 Terminology evolution: LLLT → PBM

After the 2010s, the academic community tends to replace "low-intensity laser therapy" with "photobiomodulation (PBM)" because: ① low intensity is not a necessary condition, LED is equally effective; ② the word "laser" implies that coherence is necessary (actual incoherent light is also effective); ③PBM emphasizes "biomodulation" rather than "treatment", which is closer to its dose-dependent biphasic nature. Related terms include "photobiomodulation therapy (PBM Therapy)".

## 2. Tissue penetration of light: optical window and photon journey

The physical premise of PBM is that **photons must reach the mitochondria**. The journey of light through biological tissue is governed by three main processes: **absorption**, **scattering** and **reflection**.

### 2.1 Therapeutic Optical Window

Biological tissues exhibit strong wavelength-dependent attenuation of light, and there is a "therapeutic optical window" (approximately **600–1100nm**):

| Wavelength segment | Main absorber | Penetration depth characteristics |
|---|---|---|
| Visible blue-green (<500nm) | Strong absorption of hemoglobin and melanin | Very light (millimeter level) |
| Red light (600–700nm) | Hemoglobin absorption decreases, but scattering is still strong | 0.5–2cm |
| Near-infrared NIR-I (700–900nm) | Low water absorption, low hemoglobin, **"window"** | 2–5cm (optimal) |
| Near-infrared NIR-II (900–1100nm) | Water absorption rising | 1–3cm (window edge) |

Key point: **Near-infrared light near 810nm is the best penetration window**, which not only avoids the strong absorption band of hemoglobin/water, but also retains sufficient scattering penetration. This is also the physical reason why the dual wavelengths of 660nm (red light) and 810/850nm (near-infrared) are most commonly used for clinical PBM. Red light is mainly absorbed in the epidermis and superficial tissues, while near-infrared light can penetrate the skull and reach the brain parenchyma - this is the basis for transcranial PBM.

### 2.2 Scattering and Penetration Depth Quantification

The scattering coefficient of light by tissue is much greater than the absorption coefficient. Scattering causes the photon path to become a "random walk", and the effective penetration depth (light intensity attenuates to the surface 1/e≈37%) is about 1–2mm in the red light region and about 2–5mm in the near-infrared region, but this is a direct penetration of **single irradiation**. When applied transcranially, light has to pass through the scalp, skull (several millimeters), and cerebrospinal fluid, and the light energy reaching the brain parenchyma is often less than 1–5% of the surface** (Quote from the README of this topic: Light attenuation >99% cannot reach the hypothalamus). This is why deep targeting requires complementary means such as focused ultrasound (FUS) (see 04-fus.md for details). However, it should be noted that the PBM effect does not necessarily rely on light to reach deep neurons directly, because the signals generated by light in superficial blood vessels and meninges (such as NO release, blood flow changes) can propagate deep through the blood flow or glial cells. The "superficial light, deep effect" is one of the important mechanism disputes of tPBM.

## 3. The whole chain of molecular mechanism (core)

### 3.1 Photoreceptor: Cytochrome c oxidase (CCO/Complex IV)

**Cytochrome c oxidase (CCO)** is the terminal enzyme of the mitochondrial respiratory chain (oxidative phosphorylation). It catalyzes the transfer of electrons from cytochrome c to molecular oxygen to generate water, while driving proton pumping, establishing a transmembrane proton gradient, and synthesizing ATP. It is one of the largest mitochondrial enzymes (about 13 subunits in mammals), and its core catalytic site contains a variety of metal centers:

- **CuA double copper center**: receives electrons from cytochrome c (absorption peak approximately 620–670nm, red light region);
- **Heme a**: transfer electrons;
- **Heme a3-CuB binuclear center**: oxygen reduction site (absorption peak approximately 810–850nm, near-infrared region), and also a NO binding inhibition site.

**Evidence of **CCO as a photoreceptor**: ①The action spectrum of CCO is highly consistent with the CCO absorption spectrum - the wavelength peaks of the red light/near-infrared excitation PBM effect (about 660nm, 810nm, 850nm) correspond to the absorption peak of the CCO metal center; ②CCO absorption is enhanced under **hypoxia/deactivation state**, and the effect of PBM on cells in low energy states is more significant; ③CCO The PBM effect is weakened or disappeared after treatment with inhibitors (cyanide, carbon monoxide); ④ The metal-protein environment in the subunit structure causes these centers to have clear electronic transitions in the red light/NIR region. These four constitute the core evidence chain of "PBM photoreceptor = CCO".

### 3.2 Photon absorption → Electronic excitation → NO dissociation

The binding and photodissociation of NO in CCO are the core mechanisms of PBM, which can be decomposed into the following chains:

```
Red light/NIR photon (600-850nm, energy about 1.5-1.9 eV)
│
▼
The CCO metal center (CuA/Heme a3-CuB) absorbs photons and the electrons transition to the excited state
│
▼
NO and Heme a3 iron center/CuB coordination bonds are photodissociated (NO-iron bond energy is about 1 eV < photon energy 1.5 eV)
│
▼
[Effect 1] Release the inhibition of CCO by NO → Restart the respiratory chain → O2 reduction and recovery
│ Electron transfer restoration → Proton pump restoration → ATP synthesis improvement (about 35-40%)
▼
[Effect 2] Dissociated NO diffuses as a gaseous signal molecule
│
├─► Activate soluble guanylate cyclase (sGC) → cGMP → PKG → vascular smooth muscle relaxation → blood flow↑
│
├─► S-nitrosylation post-translational modification → regulates downstream proteins/transcription factors
│
└─► Endothelial nitric oxide synthase (eNOS)/inducible (iNOS) crossover → NO signal amplification
▼
Mitochondrial reactive oxygen species (mROS) transiently increase → act as signaling molecules to activate transcription factors
▼
NF-κB / Nrf2 / PGC-1α / CREB / HIF-1α → Antioxidant, mitochondrial biogenesis, angiogenesis, anti-inflammatory gene program
```

**Physiological significance of NO binding to CCO**: Under physiological conditions, cells endogenously produce submicromolar NO (primarily from eNOS). NO reversibly binds to the heme a3-CuB site of CCO to form a "NO inhibitory state", thereby **downregulating the activity of the respiratory chain** - this is an exquisite "physiological brake" that allows cells to regulate energy output based on NO concentration (reflecting oxygen supply and metabolic demand), and is also involved in oxygen sensing and neural signaling. However, when the concentration of NO is abnormal (iNOS is upregulated during endothelial dysfunction and inflammation) or the suppression time is too long, breathing is suppressed and energy is insufficient, which can aggravate cell dysfunction.

**The role of PBM** is to use photons to **photodissociate the NO brake**: the near-infrared energy of a single photon is about 1.5–1.9eV (810nm≈1.53eV), which is higher than the bond energy of the NO-heme iron coordination bond (about 1eV magnitude), and is enough to directly interrupt the coordination bond. After the photon is absorbed by the CCO metal center, the electron transitions to the excited state, changing the coordination environment of the metal center and dissociating NO from the binding site. This produces the above-mentioned dual effects: **release the brake (breathing recovery) + release the signal (NO release)**.

### 3.3 ATP boost and "5x/35-40%" data

Studies have reported that ATP levels can significantly increase within minutes after PBM. In vitro studies commonly report that ATP increases by about 35–40% after cells are irradiated by red light/NIR (such as 810nm irradiation of liver cells and neurons); some studies report that ATP can rise several times to the baseline 5 minutes after irradiation (the specific value depends on the cell type and dose, and there are large differences in different literatures. Caution is required when labeling "about 5 times" and the original literature should prevail). The increase in ATP is accompanied by an increase in oxygen consumption (O2 consumption) and a change in the oxidation state of CCO (absorption spectrum red shift). The three together support the "respiratory recovery" mechanism.

### 3.4 The core role of NO: from brake release to vascular signaling

NO in PBM is the key molecule that "kills two birds with one stone":

1. **As a product of the release of inhibition**: NO released by photodissociation escapes from the CCO site and enters the cytoplasm.
2. **As a vasodilation signal**: NO activates soluble guanylyl cyclase (sGC), catalyzes GTP → cGMP; cGMP activates protein kinase G (PKG), which phosphorylates myosin light chain phosphatase, reduces intracellular calcium in smooth muscle cells, and causes vascular smooth muscle relaxation - **increase in local blood flow and oxygen supply**, forming a positive feedback (blood flow ↑ → more oxygen → more active breathing).
3. **Interaction with eNOS/iNOS**: PBM can also upregulate endothelial nitric oxide synthase (eNOS) activity (partly through the AMPK/Akt pathway) and promote NO synthesis; at the same time, it inhibits the high expression of inducible nitric oxide synthase (iNOS) in inflammatory tissues - that is, "**promotes eNOS and suppresses iNOS**", and pulls the NO supply from "pathological high-concentration inflammation sources" back to "physiologically regulated concentrations".
4. **S-nitrosylation**: NO can form S-nitrosylation modification with protein cysteine ​​thiols, which regulates transcription factors (such as NF-κB p65, HIF-1α), metabolic enzymes and ion channel activity. It is the "non-cGMP branch" of NO signaling.

Be aware of the double-edged sword of NO: excess NO reacts with superoxide anion (O2⁻) to form **peroxynitrite (ONOO⁻)**, which has strong oxidative toxicity (see 01-foundations/03-no-basics.md for details). Therefore, the dose of PBM must be controlled at "physiological concentration release" rather than "pathological large-scale release" - this is the molecular basis of the biphasic curve.

### 3.5 Mitochondrial signaling: mROS as the "second messenger"

PBM is also accompanied by a **transient, low-level increase** in mitochondrial reactive oxygen species (mitochondrial ROS, mROS). This may seem like a contradiction (ROS are often harmful), but the key is **dosage vs. kinetics**:

- Low-dose PBM produces **brief, reversible pulses of mROS** that act as signaling molecules rather than damaging factors;
- mROS (mainly H2O2) can oxidatively modify and activate transcription factors, the typical representative is **Nrf2**: H2O2 oxidizes the cysteine residue of Keap1, dissociating the Keap1-Nrf2 complex, Nrf2 enters the nucleus and initiates the transcription of downstream antioxidant genes (HO-1, SOD, catalase, glutathione system) - this is "with a small amount of ROS The logic of hormesis (hormesis) in exchange for the overall upregulation of the antioxidant network is homologous to the "mitohormesis" produced by exercise;
- At the same time, mROS is also involved in activating **AMPK** (energy sensing kinase), **PGC-1α** (mitochondrial biogenesis master switch) and **HIF-1α** (hypoxia adaptation).

### 3.6 Downstream transcription network

| Pathways | Upstream triggers | Downstream effects |
|---|---|---|
| **Nrf2/Keap1** | mROS oxidation Keap1 | HO-1, SOD, CAT, NQO1 and other antioxidant genes↑; cell protection |
| **NF-κB** | Low-dose light → activity modulation | Anti-inflammatory program (suppresses excessive inflammation); high-dose pro-inflammatory (biphasic) |
| **PGC-1α** | AMPK/mROS | Mitochondrial biogenesis, fatty acid oxidation, oxidative phosphorylation genes↑ |
| **VEGF/angiogenesis** | NO/cGMP, HIF-1α | Endothelial proliferation, capillary neogenesis, tissue perfusion↑ |
| **CREB/cAMP** | Changes in cellular energy status | Neuroplasticity genes, BDNF expression ↑ (important for brain PBM) |
| **HIF-1α** | Oxygen sensing, mROS | Hypoxia adaptation, angiogenesis |

Note the **biphasic nature** of NF-κB: Physiological concentrations of NO and low-dose light tend to suppress excessive inflammation (suppressing iNOS), but excessive light production of excessive ROS/NO instead activates NF-κB to promote inflammation—this is one of the core mechanisms of the PBM dose window.

### 3.7 Summary of cellular effects

| Effect | Mechanism | Type of Evidence |
|---|---|---|
| Proliferation↑ | ATP↑, growth factor signaling↑ | In vitro/Animals |
| Migration↑ | Cytoskeleton, adhesion rearrangement | Wound healing model |
| Anti-inflammatory | NF-κB downregulation, iNOS inhibition, pro-resolvin | Animals/some humans |
| Anti-apoptosis | Stabilization of mitochondrial membrane potential and improvement of Bcl-2/Bax ratio | Nerve injury model |
| Anti-fibrosis | Collagen remodeling, MMP/TIMP balance | Animals |

## 4. PBM parameters and dosimetry: biphasic curve

The efficacy of PBM is highly dependent on the "dose-response" relationship, and its iconic feature is the **biphasic dose response**, that is, the **Arndt-Schulz law**: low-dose stimulation, medium-dose optimal, high-dose suppression or even harmful.

### 4.1 Key parameters

| Parameter | Meaning | Typical clinical range |
|---|---|---|
| **Wavelength** | Determine the penetration depth and absorption peak | 660nm (red light) / 810nm / 850nm (near infrared) |
| **Power Density (Irradiance)** | W/cm² | 5–100 mW/cm² (low power, no thermal effect) |
| **Energy density (dose)** | J/cm² | 1–60 J/cm² (depending on tissue and purpose) |
| **Total energy** | Power × time | According to target area |
| **Irradiation Time** | Seconds-Minutes | Seconds (laser spot) to minutes (LED array) |
| **Mode** | Continuous vs Pulsed | Pulsed (e.g. 10–100 Hz, 50% duty cycle) improves penetration and effect |

### 4.2 Arndt-Schulz biphasic curve

```
Effect strength
▲
│ ╱╲
│ ╱ ╲ ← Optimal dose window (stimulation zone)
│ ╱ ╲
│ ╱ ╲
│ ╱ ╲
│ ───╱ ╲___ ← Dose too high (inhibition/damage zone)
│Stimulation area────(baseline)
└──────────────────────────────► Energy density (J/cm²)
```

**Molecular Interpretation of the Biphasic Curve**: At low doses, a small amount of NO is photodissociated, mROS is slightly overshoot (hormesis), and cells benefit; when the dose is too high, excessive ROS and NO (→ONOO⁻), ATP depletion, excessive oxidative damage to CCO, and NF-κB pro-inflammation are produced, which turns harmful. Therefore **PBM is not "the more the better"** - the optimal window is narrow and **varies with the individual/tissue/state**, which is one of the biggest obstacles to clinical standardization.

### 4.3 Controversy: Dilemma of dose standardization

The wavelength, power, time, spot size, and irradiation methods used in different studies vary widely, making it difficult to directly compare the results and causing extremely high heterogeneity in meta-analysis. There is still a lack of a recognized "standard dose" in the PBM field, which is one of the potential explanations for some negative results, especially in the neurological field.

## 5. Grading of evidence

| Phenomenon | Level of evidence | Key documents |
|---|---|---|
| The CCO absorption spectrum is consistent with the PBM action spectrum | Strong (mechanism, spectroscopy measurements) | Karu 1999; Hamblin 2016 Review |
| NO binds to CCO, inhibits respiration, PBM photodissociation | Strong (in vitro biochemistry/spectroscopy) | Brown 1995; Lane 2006; Mason 2014 |
| Red light/NIR increases cellular ATP and oxygen consumption | Real results (in vitro, repeatable) | Wong-Riley 2005; Sommer 2019 |
| PBM promotes wound healing | Strong (partially positive human RCT) | Enwemeka 2004; Multiple meta-analyses |
| PBM reduces inflammation/pain | Strong (human RCT, musculoskeletal domain) | Bjordal 2003 (meta) |
| Transcranial PBM improves cerebral blood flow/oxygenation | Strong (human near-infrared imaging/NIRS measurements) | Salazar 2017; Nawashiro et al. |
| Transcranial PBM improves cognition/neuroprotection | Partially positive, heterogeneous (RCT limited) | Barrett 2013 (double-blind RCT, some domain improvement) |
| Low-dose PBM suppresses microglial inflammation | Strong (animals/cells) | Hamblin 2018 Review |
| PBM anti-aging/reversal of biological age | Early stage (animals/in vitro, long-term data in humans are missing) | Mainly speculation on the mechanism |
| Direct visualization of the entire chain of photons → CCO → NO → ATP in vivo | None (lack of direct observation in vivo) | — |

## 6. Clinical/experimental evidence details

### 6.1 Wound healing

The most classic clinical application of PBM. A large number of animals and humans have verified that PBM accelerates the healing of diabetic ulcers, surgical incisions, and pressure ulcers. The mechanism combines ATP↑, fibroblast proliferation, collagen synthesis, angiogenesis, and anti-inflammation. Several meta-analyses support the positive effects of PBM on chronic wounds, especially diabetic foot, but dose heterogeneity limits the strength of the conclusions.

### 6.2 Neuroprotection and transcranial PBM (tPBM)

The effect of PBM on the brain is the core of the topic "Light-Brain-Reverse Ageing" (see 02-light-spectrum.md for details). **Mechanism**: Near infrared penetrates the skull → cortical CCO absorption → ATP↑ + blood flow↑ + anti-inflammatory (inhibits microglial activation) + neuroplasticity (BDNF/cAMP). **evidence**:

- **Brain injury/cerebral ischemia**: In animal models (stroke, TBI), PBM reduces infarct volume and improves neurological recovery. The mechanism includes anti-apoptosis, anti-inflammation, and promotion of axonal regeneration;
- **Human tPBM cognitive research**: Barrett 2013 double-blind RCT used transcranial irradiation in patients with mild TBI, and improved some cognitive domains (such as memory, executive function); tPBM for depression also has exploratory positive results; however, the number of studies is small, the samples are small, and the heterogeneity is large, so it is still "promising preliminary evidence" rather than established.
- **Alzheimer related**: tPBM reduces Aβ deposition and improves synaptic plasticity and cognition in animal AD models (APP/PS1, etc.) (e.g., De Taboada 2011; Purushothaman et al.), but human data are extremely limited.

### 6.3 Pain and inflammation

PBM has been widely verified by humans in the fields of neck and shoulder pain, knee osteoarthritis, tendinopathy, etc. A meta-analysis by Bjordal et al. showed that it has a relieving effect on some inflammatory pain. The mechanism includes inhibiting inflammatory mediators (PG, COX-2) and promoting blood flow and tissue repair.

### 6.4 Alopecia (hair regrowth)

Low-intensity laser comb/cap (LLLT comb) receives FDA regulatory approval for androgenic alopecia. Mechanism: Red light stimulates the proliferation of hair follicle dermal papilla cells and improves scalp blood flow and inflammation. Multiple RCTs have shown that hair density increases, but the effect size is medium.

### 6.5 Macular Degeneration (AMD)

Dual-wavelength photobiomodulation (670nm/780nm, etc.) for dry macular degeneration: improves mitochondrial function (retina is a very high-metabolism tissue), reduces drusen, improves vision, clinical studies (LIGHTSITE series) are partially positive, but evidence is still accumulating.

### 6.6 Oral mucositis (chemotherapy/radiotherapy prevention)

The use of PBM to prevent/treat oral mucositis caused by cancer radiotherapy and chemotherapy has been recommended by many guidelines (such as the MASCC guidelines). The mechanism includes anti-inflammation, promoting mucosal repair, and reducing pain. It is one of the clinical indications for PBM with strong evidence.

### 6.7 Muscle Movement Recovery and Performance

PBM (pre-exercise warm-up) improves post-exercise recovery, reduces creatine kinase (CK), and improves some sports performance. It is commonly used in recovery training, and evidence is accumulating.

## 7. PBM and aging: mitochondrial recovery, SASP and anti-aging prospects

The connection between PBM and anti-aging is all based on the fact that "mitochondrial dysfunction is a core marker of aging" (see 01-foundations/01-aging-hallmarks.md and 02-vascular/04-mitochondria.md for details).

### 7.1 Restore mitochondrial function and delay mitochondrial aging

Decreased mitochondrial respiration, increased ROS, fragmentation and mitophagy disorders are common in aged cells. PBM restores respiration by releasing the NO brake, increasing the ATP/ADP ratio, and improving energy metabolism; low-dose mROS triggers antioxidant and mitochondrial quality control (PGC-1α→biosynthesis, mTOR/AMPK→mitophagy) through mitohormesis, and has the potential to bring "decreased mitochondria" back to a young metabolic state. Improvement of mitochondrial membrane potential and respiration in aged skin fibroblasts and aged skeletal muscle after PBM treatment in vitro/animals.

### 7.2 Suppression of SASP and chronic inflammation

The anti-inflammatory properties of PBM may delay "inflammaging": inhibit NF-κB and iNOS, reduce the expression of SASP factors (IL-6, TNF-α), and improve the cellular aging microenvironment. Some studies have shown that PBM can reduce the proportion of senescent cells/mitigate their paracrine toxicity, but long-term evidence in humans is still lacking.

### 7.3 Anti-aging skin

Red light/near infrared beauty (LED mask) claims to improve skin elasticity, reduce fine lines, and promote collagen. Mechanism: Recovery of fibroblast mitochondria, collagen synthesis↑, and skin blood flow↑. There is some clinical trial support (improving skin quality), but as an "anti-aging intervention" it needs to be distinguished from other means (vitamin A, sun protection), and it belongs to the auxiliary/aesthetic category.

### 7.4 Brain PBM and cognition: transcranial red light anti-aging

This is the core of this topic: transcranial PBM improves cerebral blood flow/oxygenation, reduces neuroinflammation, promotes BDNF and neuroplasticity, and has theoretical "age-reversing" value for aging-related cognitive decline and reduced brain energy metabolism. Animal models of aging have shown improved cognition and hippocampal function; humans are still in early stages of validation (heterogeneous, small sample size). It is necessary to clarify the **light attenuation problem** (>99% cannot reach the hypothalamus) - this is the source of the "superficial light, deep signal" hypothesis and the FUS joint solution (see 04-fus.md for details).

## 8. Contact NO / NAD+ / longevity network

PBM is naturally connected to the NO pathway (the core of this article), and also deeply intersects with the NAD+ network:

- **PBM → Mitochondria → NAD+/NADH balance**: After the respiratory chain is restored, the increase in electron transport activity affects the rate of NADH oxidation by complex I; however, whether the effect of PBM on **total NAD+ pool** increases or decreases requires caution - accelerated respiration consumes NADH, and the re-oxidation of NADH→NAD+ mainly occurs in complex I (NADH dehydrogenase), and this process is inhibited by NO (NO also inhibits complex I). Therefore, after PBM decomposes the NO brake, the activity of complex I is restored, **NADH oxidation is accelerated, and the NAD+/NADH ratio increases**, providing substrates for NAD+-dependent enzymes (SIRT1/3).
- **SIRT1/3 axis**: Elevated NAD+ activates SIRT1 (nucleus) and SIRT3 (mitochondria), deacetylates and activates PGC-1α (promotes mitochondrial biogenesis) and antioxidant enzymes (SOD2). This constitutes a positive feedback candidate path of "PBM → respiratory recovery → NAD+↑ → SIRT → PGC-1α → mitochondrial rejuvenation" (see 01-foundations/03-no-basics.md for details).
- **Synergy with NAD+ precursor supplementation**: PBM (increase NAD+/NADH ratio) + NMN/NR (increase NAD+ total amount) can theoretically be synergistic, but direct joint research is lacking.
- **Double-edged Sword Reminder of the NO Pathway**: The release of NO by PBM is a beneficial "physiological concentration", but if combined with a drug-induced NO donor, it may exceed the limit → ONOO⁻ toxicity, and the combined use requires dose balance.

## 9. Intervention directions and executable suggestions

1. **Dose-response window system calibration** (detailed in this topic 05-experiment-design.md): Use three wavelengths of 660/810/850nm × dose gradient (such as 0.5/3/10/50 J/cm²) to measure ATP, CCO oxidation state (spectrum), NO release (DAR-4M fluorescence), and mROS at the cell layer, and draw each wavelength Arndt-Schulz curves and inflection points.
2. **Target verification**: Use CCO inhibitor (cyanide), NO donor/scavenger (cPTIO), and NOS inhibitor for orthogonal verification to confirm the specificity of "photons→CCO→NO" rather than the non-specific thermal effect (set up non-light band control).
3. **In vivo delivery strategy**: Superficial areas (skin, mucous membranes, peripheral muscles) are directly irradiated with LED/laser; deep areas (brain, hypothalamus) need to be combined with FUS deep targeting or rely on "superficial light → deep blood flow signal" transmission (see 04-fus.md for details).
4. **Monitoring system**: tPBM uses near-infrared spectroscopy (NIRS)/blood oxygenation to measure cerebral blood flow and oxygenation; peripherally, mitochondrial membrane potential, ATP, and inflammatory factors (IL-6, TNF-α) are used as endpoints.
5. **Combination strategy**: PBM (mitochondria recovery + NAD+/NADH elevation) + NAD+ precursor + aerobic exercise. The three share the "mitochondria-energy-blood vessel" axis and are theoretically synergistic; honest note: the current combination lacks direct RCT.
6. **Clinical Translation Note**: Eye safety (the retina is sensitive to visible light, eye protection must be provided), avoiding thermal damage (controlling power density), and insufficient data on long-term effects (see below).

## 10. Open issues and controversies

- **Missing dose standardization**: The biggest pain point in the PBM field. Wavelengths/powers/times/modes vary widely, meta-analysis heterogeneity is extremely high, and negative results are difficult to rule out "inappropriate dosage" rather than "invalidity".
- **CCO hypothesis vs other photoreceptors**: CCO is the mainstream hypothesis, but there are alternative explanations - such as light acting directly on water molecules (generating local heat/ROS), acting on transient receptor potential ion channels (TRP channels, such as TRPV1 are sensitive to heat), acting on other chromophores such as flavins/porphyrins. The strongest evidence for the CCO hypothesis is that "absorption spectrum = action spectrum + inhibitor makes the effect disappear", but the "only receptor" is not confirmed.
- **Lack of direct visualization of the entire "photon→CCO→NO→ATP" chain in the body**: Direct observation of NO photodissociation in vivo is extremely difficult (NO half-life is extremely short and spatial resolution is insufficient), and the mechanism is mostly extrapolated from in vitro spectroscopy and cell experiments - this is the "last mile" to demonstrate the PBM mechanism.
- **Placebo Effect**: Especially pain, emotional/cognitive endpoints, highly subjective outcomes are susceptible to placebo interference; double-blind equipment (real/sham irradiation) design is difficult but necessary.
- **Insufficient data on long-term effects and safety**: Most studies are short-term; there is a lack of long-term cohorts on the effects of long-term repeated irradiation on the eyes (retina), skin (photoaging/cancer risk?), and tumors (whether PBM promotes tumor proliferation - controversial, and some are worried about the benefits of high-metabolism tumors).
- **Maturity of anti-aging positioning**: The evidence for PBM as a "clinical indication treatment" is strong, but it is still in its early stages as a "systemic anti-aging/biological age reversal" - there is no RCT to prove that PBM can reverse human biological age, and the anti-aging narrative needs to be strictly distinguished from clinical evidence.

## References

1. Hamblin MR. Mechanisms and mitochondrial redox signaling in photobiomodulation. *Photochem Photobiol* 2018;94:199-212.
2. Hamblin MR. Photobiomodulation for the management of Alzheimer's disease: a systematic review. *J Alzheimers Dis* 2016;50:687-706.
3. Karu TI. Primary and secondary mechanisms of action of visible-to-near IR radiation on cells. *J Photochem Photobiol B* 1999;49:1-17.
4. Wong-Riley MT, et al. Photobiomodulation directly benefits primary neurons functionally inactivated by toxins. *J Biol Chem* 2005;280:4761-4771.
5. Mason MG, et al. Nitric oxide inhibition of respiration involves both bound and unbound forms of cytochrome c oxidase. *J Biol Chem* 2014;289:18675-18685.
6. Lane N. Cell biology: power games. *Nature* 2006;443:901-903. (A review perspective on NO inhibiting mitochondrial respiration)
7. Mester E, Szende B, Gärtner P. The effect of laser beams on the growth of hair in mice. *Radiobiol Radiother* 1968;9:621-626. (Subsequent publication of the 1967 experiment)
8. Enwemeka CS, Parker JC, Dowdy DS, et al. The efficacy of low-power lasers in tissue repair and pain control: a meta-analysis study. *Photomed Laser Surg* 2004;22:323-329.
9. Bjordal JM, Couppé C, Chow RT, et al. A systematic review of low level laser therapy with location-specific doses for shoulder pain. *BMC Musculoskelet Disord* 2003;4:16.
10. Barrett DW, Gonzalez-Lima F. Transcranial infrared laser stimulation produces beneficial cognitive and emotional effects in humans. *Neuroscience* 2013;230:13-23.
11. Salazar RH, et al. Transcranial laser therapy for acute ischemic stroke: a pooled analysis of NEST-1 and NEST-2. *Int J Stroke* 2013;8:315-320. (Summary of transcranial PBM stroke trials)
12. Whelan HT, Smits RL, Buchman EV, et al. Effect of NASA light-emitting diode irradiation on wound healing. *J Clin Laser Med Surg* 2001;19:305-314. (NASA LED light source research)
13. Sommer AP. Mitochondrial cytochrome c oxidase is not the primary acceptor for near infrared light—it is mitochondrial bound water. *Aging Dis* 2019;10:1261-1267. (Challenge to the CCO sole receptor hypothesis)
14. Anders JJ, Lanzafame RJ, Arany PR. Low-level light/laser therapy versus photobiomodulation therapy. *Photomed Laser Surg* 2015;33:183-184. (Discussion of terminology evolution)
