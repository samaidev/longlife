# Molecular Structure Deep Dive 30: cGAS–STING — The Cytosolic DNA Sensor and the “Inflammation–Immunity” Alarm Axis

> **Series context**: Article 30 in 10-structures (Molecular Structure Deep Dives): a structural dissection of cGAS (cyclic GMP–AMP synthase) and STING (stimulator of interferon genes). It explains how cells sense “DNA that should not be in the cytosol,” how the cGAMP second messenger relays the alarm, and the role of this axis in “DNA leakage–inflammation” during aging. This provides the structural basis for the knowledge base’s inflammation thread ([14-nfkb-structure.md](14-nfkb-structure.md)/[19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)) and connects damage-associated molecular patterns (DAMPs) with immunosenescence.
> **Related articles**: NF-κB: [14-nfkb-structure.md](14-nfkb-structure.md); NLRP3: [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md); mitochondria: [12-complex1-structure.md](12-complex1-structure.md) (mtDNA leakage); autophagy: [18-lc3-autophagy.md](18-lc3-autophagy.md) (clearance of leakage sources).

---

## 0. Structural overview

**In one sentence:** cGAS–STING is the cytosolic DNA “sentinel-and-alarm axis.” cGAS (the DNA sensor) detects DNA where it should not be in the cytosol (viral/bacterial DNA, leaked mitochondrial DNA, or micronuclear DNA), synthesizes the second messenger cGAMP, and activates STING on the endoplasmic reticulum, ultimately initiating type I interferons and inflammatory mediators — the cell’s “DNA burglar alarm”: detect invading DNA and sound the “inflammation–immunity” alert.

```text
cGAS–STING pathway:
  cGAS (DNA sensor, cytosol): binds cytosolic DNA (>20 bp) → conformational activation → catalysis
      → synthesizes 2′3′-cGAMP (second messenger)
        │
  STING (alarm, ER membrane): binds cGAMP → conformational change → dimer → tetramer
      → moves from ER to Golgi → recruits TBK1/IRF3
        │
  Effects: IRF3 phosphorylation → type I interferon (IFN-β) + NF-κB → inflammatory mediators
      → antiviral/antitumor immunity + sterile inflammation (aging/autoimmunity)
```

**Three major structural features** (the atomic basis of function):
1. **cGAS DNA-binding surface**: a positively charged surface binds the DNA phosphate backbone; binding depends on DNA length (>20 bp required for activation) — the sensor “recognizes long DNA” as an invasion signal.
2. **cGAS catalytic domain**: a nucleotidyl-transferase fold synthesizes 2′3′-cGAMP (with a noncanonical 2′5′ linkage) — the alarm’s “transmitter.”
3. **STING cGAMP-binding pocket**: a dimeric ligand-binding domain (LBD); cGAMP binding changes its conformation and activates it — the alarm’s “receiver.”

**Core regulatory mechanism:**

```text
Resting: no cytosolic DNA → low cGAS activity (autoinhibited) → inactive STING dimer (ER)
        │
DNA leakage (virus/mitochondria/micronuclei): cGAS binds DNA → oligomerizes → synthesizes cGAMP
        │
cGAMP → binds STING → conformational change (closure) → transport from ER to Golgi
        │
TBK1 recruitment → IRF3 phosphorylation → IFN-β/inflammatory mediators → immunity/inflammation
        │
Aging: increased mitochondrial DNA leakage/genomic instability (micronuclei) → chronic cGAS–STING activation
     → chronic type I interferon/inflammation → aging (cellular senescence/tissue inflammation)
```

---

## 1. Why cGAS–STING structure matters

cGAS–STING is a “star pathway” of innate immunity:

- **Cytosolic DNA sensor**: cGAS is a major sensor of cytosolic DNA (“DNA where it does not belong = danger”) — the cell’s “DNA burglar alarm.”
- **Antiviral/antitumor defense**: cGAS–STING initiates antiviral immunity (type I interferons) and antitumor immunity — the alarm sounds and the immune system mobilizes.
- **Evidence relating to aging**: cGAS–STING is chronically activated during aging (mtDNA leakage/micronuclei) → chronic inflammation/cellular senescence → accelerated aging. Inhibiting cGAS–STING improves aging-related phenotypes in animals — an aging alarm that keeps going off.
- **Dialogue with mitochondria** ([12-complex1-structure.md](12-complex1-structure.md)): damaged mitochondria release mtDNA → cGAS activation — the “leaky generator” also leaks DNA.
- **Dialogue with autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): autophagy removes sources of leakage (damaged mitochondria/micronuclei) → suppresses cGAS — an efficient recycling system means fewer alarms.
- **Connection to cellular senescence**: senescent cells (SASP) interact with cGAS–STING (senescent cells release DNA/activate STING) — the “alarm” and secretory activity of senescent cells are linked.
- **Drug target**: cGAS/STING inhibitors (anti-inflammatory/anti-aging) and STING agonists (antitumor immunity) — bidirectional control of the alarm.

**Three key questions for structural research:**
1. How does cGAS recognize DNA (the length-/sequence-dependent mechanism)?
2. How is cGAMP synthesized (atomic details of catalysis)?
3. How is STING activated (the cGAMP-induced conformational change)?

These questions have been addressed by structures including 4O6A (cGAS + DNA, 2014) and 6NT5 (full-length STING, 2019).

---

## 2. Structural anatomy of cGAS–STING

### 2.1 cGAS — “DNA sensor + transmitter”

- **Location**: cytosol (soluble).
- **Structure**: nucleotidyl-transferase (NTase) fold — the transmitter’s “shape.”
- **DNA binding**: a positively charged surface binds the DNA phosphate backbone (no sequence specificity; it recognizes “length”) — it does not care about the DNA sequence, only that it is DNA.
- **Length dependence (>20 bp)**: DNA must be >20 bp for stable binding and activation; short DNA is insufficient. The sensor has a length threshold: short DNA (normal metabolic products) does not trigger an alarm, whereas long DNA (invasion/leakage) does. This is key to preventing false alarms.
- **Finding from 4O6A**: cGAS–DNA complexes form “oligomers” (2:2 or larger) → switch-like conformational change → activation. Multiple sensors assemble before sending the signal.
- **Catalysis**: DNA binding → open conformation → catalytic site exposed → synthesis of 2′3′-cGAMP. The transmitter powers up and sends cGAMP.

### 2.2 cGAMP — “second messenger”

- **Structure**: cyclic dinucleotide (2′3′ linkage, noncanonical) — the alarm’s “wireless signal.”
- **Distinctive feature**: 2′3′-cGAMP (one 2′5′ and one 3′5′ bond) differs from bacterial cyclic dinucleotides and specifically activates mammalian STING — a dedicated code recognized by the host receiver.
- **Role**: diffuses from cGAS and binds STING — the transmitter (cGAS) sends the signal and the receiver (STING) receives it.

### 2.3 STING — “alarm receiver + signal relay”

- **Location**: ER membrane (four transmembrane segments plus a cytosolic ligand-binding domain, LBD).
- **Resting state**: inactive dimer (LBD dimerization, as revealed by 6NT5) — the alarm is on standby.
- **cGAMP binding**: cGAMP binds a pocket in the LBD dimer → conformational change (“closure”) → activation — the signal is inserted and the alarm starts.
- **After activation**: STING moves from ER to Golgi → recruits TBK1 → phosphorylates IRF3 → IRF3 enters the nucleus → IFN-β — the alarm moves to the “command center” and sounds the interferon alert.
- **Oligomerization**: after cGAMP binding, STING can form tetramers or larger oligomers (revealed by 6NT5) → signal amplification — multiple alarms sound louder together.

---

## 3. Molecular logic of DNA sensing: from structure to chemistry

### 3.00 The engineering wisdom of “no sequence specificity”: why cGAS uses “length + location”

The previous section discussed the length threshold. Here we examine **why cGAS does not read sequence like a transcription factor, but instead uses “location + length”** — an evolutionary solution for broad-spectrum pathogen recognition.

**“Sequence specificity = risk of letting pathogens escape.”** If cGAS recognized only particular DNA sequences (such as a viral motif), a virus could escape by mutating its sequence — like recognizing only one face: change the face and slip away. Sequence specificity is a fatal weakness against ever-changing pathogens.

**“Location + length = broad-spectrum recognition.”** Any DNA in the cytosol is abnormal, regardless of sequence (normal DNA is in the nucleus/mitochondria). cGAS recognizes the category “DNA,” not its sequence, and therefore covers all DNA pathogens — it does not recognize a face, but an identity (DNA); any DNA entering the cytosol counts as an invasion. Broad coverage means fewer escapees.

**“Cost and compensation.”** The cost of broad recognition is possible false alarms (leaked self-DNA can also trigger one). But “location (the cytosol)” is the first safeguard (self-DNA normally remains in the nucleus): as long as DNA does not enter the cytosol, it does not trigger the alarm. Location and length act as two safeguards against false alarms.

**“Comparison with Toll-like receptors (TLRs).”** TLR9 recognizes DNA in endosomes (also broadly), while cGAS recognizes DNA in the cytosol. These are two DNA sensors in different locations (endosome vs cytosol), covering different scenarios (phagocytosis vs intracellular infection) — layered DNA sensing provides defense in depth.

**Structural/evolutionary lesson:** cGAS’s “broad recognition + threshold” design is a general logic of innate immunity: not highly precise, but broad in coverage, with a threshold to prevent false alarms. Innate immunity uses “coarse but broad” recognition; adaptive immunity uses “precise and specialized” recognition. cGAS belongs to the former.

### 3.0 Atom by atom: why cGAS “doesn’t care about sequence, only length”

How does cGAS distinguish “self DNA” from “invader DNA”? The answer lies in two signals: “location + length.”

**“Location = the first signal.”** DNA in the nucleus/mitochondria is “legitimate” (membrane-enclosed); DNA in the cytosol is “illegitimate” (it should not be there). Cytosolic cGAS senses cytosolic DNA: what is inside the gate is not a thief; what is outside is. Location itself is a signal.

**“Length = the second signal (false-alarm prevention).”** Short DNA fragments (<20 bp, normal metabolic/degradation products) bind cGAS weakly and do not activate it. Long DNA (>20 bp, viral genomes/long leaked mtDNA fragments) binds stably and activates it. A short note is not an invasion; a long document is. The length threshold is a fuse against false alarms.

**“The wisdom of lacking sequence specificity.”** cGAS does not recognize specific sequences (unlike transcription factors reading particular motifs), so it can recognize any DNA. Viruses vary, but they are all DNA in this context. It recognizes identity (DNA itself), not appearance — a general-purpose sensor covers DNA pathogens broadly.

**“Oligomerization as a cooperative switch.”** 4O6A shows that cGAS–DNA forms oligomers; multiple catalytic sites cooperate, producing an “all-or-none” thresholded signal. Enough molecules must assemble before the signal is sent. Oligomerization prevents a single molecule from triggering the system accidentally.

**“Comparison with NLRP3.”** NLRP3 ([19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)) senses general damage signals (potassium efflux/ROS), whereas cGAS senses an abnormal DNA location. These are two danger sensors with different triggers; both use thresholds to prevent false alarms.

### 3.1 “The cGAMP signal relay”: from sending to receiving

The cGAMP signal relay is a classic example of a second messenger in innate immunity:

**“Send (cGAS)”**: cGAS binds DNA → synthesizes cGAMP (2′3′) → releases it into the cytosol — the transmitter sends a coded telegram.

**“Transmit (diffusion)”**: soluble cGAMP diffuses through the cytosol → reaches STING on the ER — the telegram reaches the receiver.

**“Receive (STING)”**: cGAMP binds STING-LBD → conformational change (closure) → activation — the receiver decodes it and the alarm starts.

**“Amplify (oligomerization)”**: activated STING oligomerizes and recruits TBK1 → IRF3 phosphorylation cascade → IFN-β transcription — one telegram alerts the whole city.

**“Signal termination”**: IFN-induced negative feedback (dephosphorylation/degradation) shuts off the alarm — it cannot ring forever.

**“The cGAMP receptor spectrum.”** STING is not necessarily the only cGAMP receptor — the signal can be distributed along multiple routes. (1) STING (the main receptor; type I interferons); (2) other cGAMP receptors (such as other ER sensors, still under investigation) → signaling diversity. One signal can have multiple recipients: second-messenger “multiplexing.”

**“cGAMP transmission to bystanders.”** cGAMP can pass to neighboring cells through gap junctions/vesicles → “bystander activation” (uninfected cells are also alerted). The alarm not only rings in one cell, but reaches its neighbors — a population-level immune effect of the second messenger.

**“Regulation of cGAMP degradation.”** Phosphodiesterases (such as ENPP1) degrade extracellular cGAMP → regulate signal duration. Enzymes determine the signal’s “shelf life”: too long, and inflammation may persist; too short, and the warning is lost. The second messenger has a timer.

**“Advantages of second-messenger design.”** (1) Amplification (one cGAS molecule synthesizes multiple cGAMP molecules → multiple STING molecules); (2) diffusibility (cytosol to ER membrane); (3) tunability (cGAMP degradation by phosphodiesterases). A second messenger amplifies, transmits, and can be regulated.

### 3.20 “Transport-mediated STING activation”: the journey from ER to Golgi

A distinctive feature of STING activation is that **transport itself is part of activation** — moving the alarm switches it on.

**“Resting: standby in the ER.”** The inactive STING dimer resides in the ER (as revealed by 6NT5) — the alarm is on standby in a warehouse.

**“cGAMP binding: conformational closure.”** cGAMP binds the LBD → the dimer “closes” (conformational change) → exposes a transport signal — the signal is inserted and the alarm is armed.

**“ER-to-Golgi transport.”** Activated STING moves from the ER to the Golgi in COPII vesicles → recruits TBK1 at the Golgi — the alarm moves from the warehouse to the command center.

**“TBK1 phosphorylates IRF3.”** At the Golgi, TBK1 phosphorylates STING itself and IRF3 → IRF3 dimerizes and enters the nucleus → IFN-β — the command center issues an order and the interferon alarm sounds.

**“Signal termination.”** STING after its Golgi phase is degraded (by lysosomes/autophagy) → signal termination — the alarm is dismantled after use to prevent it from ringing continuously (see [18-lc3-autophagy.md](18-lc3-autophagy.md)).

**“Significance of transport-mediated activation.”** STING uses a change of location as an activation switch (inactive in the ER, active at the Golgi) → multilayer control (cGAMP binding + transport + recruitment). The alarm must reach the right place to sound, preventing accidental activation; transport is an additional safety switch.

---

## 4. cGAS–STING and aging: a structural view of an “aging alarm”

### 4.1 Chronic cGAS–STING activation during aging

- **Increased mtDNA leakage** ([12-complex1-structure.md](12-complex1-structure.md)): mitochondrial damage in old age → mtDNA release into the cytosol → cGAS activation — the leaky generator also leaks DNA.
- **Genomic instability (micronuclei)**: age-related genomic instability (telomere damage/decreased DNA repair) → micronucleus formation → micronuclear rupture → DNA exposure to the cytosol → cGAS activation — the cell nucleus “leaks documents.”
- **Reduced autophagic clearance** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): reduced capacity to remove leakage sources → sustained cGAS activation — the recycling center shuts down and the alarm keeps ringing.
- **Consequences**: chronic type I interferon/inflammation (an interferonopathy-like state) → cellular senescence (SASP) → tissue inflammation → accelerated aging — a continuous alarm overloads immunity and inflames tissues.

### 4.2 Anti-aging strategies to “repair the alarm”

- **Reduce sources of leakage**: mitochondrial health ([12-complex1-structure.md](12-complex1-structure.md))/genomic stability (telomeres/repair) → less leakage — reduce DNA escape.
- **Enhance autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): remove damaged mitochondria/micronuclei → suppress cGAS — keep the recycling system active and the alarm quieter.
- **cGAS/STING inhibitors**: investigational inhibitors (e.g., RU.521) → suppress chronic activation → improve aging phenotypes in animals — turn down the alarm’s sensitivity.
- **Principle of moderation**: complete cGAS–STING inhibition impairs antiviral/antitumor immunity — do not dismantle the alarm; repair it. Preserve anti-infective capacity while reducing chronic false alarms.

### 4.3 “Cellular senescence (SASP) and cGAS–STING”: an interlocked alarm and senescence

The interaction between cellular senescence and cGAS–STING is a focus of aging research:

**“DNA leakage from senescent cells.”** Senescent cells (SASP) → genomic instability/micronuclei → DNA leakage → cGAS activation — senescent cells leak DNA and sound the alarm.

**“cGAS–STING drives SASP.”** cGAS–STING activation → IFN/inflammatory mediators → maintenance or enhancement of SASP — the alarm keeps senescent cells inflamed for longer.

**“Positive-feedback loop.”** Senescent cells → DNA leakage → cGAS–STING → SASP → more cellular senescence → more DNA leakage — a vicious alarm–senescence cycle.

**“Anti-aging implication.”** Break the cycle (inhibit cGAS–STING or clear senescent cells; see [03-senolytics](../04-drugs/03-senolytics.md)) → slow aging — breaking the alarm–senescence cycle is a key part of anti-aging.

---

## 5. Evidence grading

| Structural fact | Evidence level | Basis |
|---|---|---|
| cGAS has a nucleotidyl-transferase (NTase) fold | ★★★★★ Established | 4O6A and others |
| cGAS binds DNA (without sequence specificity) | ★★★★★ Established | 4O6A (2014, *Cell Rep*) |
| DNA-length dependence (>20 bp) | ★★★★★ Established | Biochemistry + structure |
| cGAS synthesizes 2′3′-cGAMP | ★★★★★ Established | Foundational work (Sun 2013) |
| STING is an ER membrane protein (4TM + LBD) | ★★★★★ Established | 6NT5 (2019, *Nature*) |
| cGAMP binding changes STING conformation | ★★★★★ Established | 6NT5 |
| Chronic cGAS–STING activation during aging | ★★★★ Strong | Multiple studies |
| cGAS–STING inhibition improves aging phenotypes | ★★★★ Strong | Animal studies |

---

## 6. Connections to the knowledge-base themes

### 6.0 “Overview of inflammation sensors”: the danger-sensing family in the 10-structures series

The inflammation/danger-sensing family in the 10-structures series now has three members:

| Sensor | Senses | Downstream output | Structural article |
|---|---|---|---|
| NF-κB | Inflammatory signals (TNF/IL-1) | Inflammatory mediators | [14-nfkb-structure.md](14-nfkb-structure.md) |
| NLRP3 | General damage signals | IL-1β/pyroptosis | [19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md) |
| cGAS–STING | Cytosolic DNA | Type I interferons/inflammation | [30-cgas-sting.md](30-cgas-sting.md) |

**“Division of labor among the three sensors.”** NF-κB senses “external inflammatory signals” (receptor-mediated); NLRP3 senses “general damage signals” (metabolic/crystalline); cGAS senses “abnormal DNA location” (nucleic acids). Three alarms cover different types of danger. During aging, all three may generate chronic false alarms (NF-κB↑/NLRP3↑/cGAS–STING↑) → chronic inflammation (inflammaging).

### 6.00 “Chronic false alarms”: a shared mechanism of inflammaging

Chronic false alarms from the three systems (NF-κB/NLRP3/cGAS–STING) are central to inflammaging — alarms become old and their sensitivity becomes dysregulated.

**“Why do false alarms occur during aging?”** (1) Danger signals persist (mtDNA leakage/crystals/damage-associated molecules), so the alarm has “something to report”; (2) negative feedback becomes blunted (autophagy↓/dephosphorylation↓), so the alarm “keeps ringing after being switched off”; (3) damage to the alarm itself (oxidative modifications) alters its sensitivity — there is always an incident, the alarm cannot shut off, and it becomes oversensitive.

**“Consequences of chronic false alarms.”** Chronic low-grade inflammation (inflammaging) → tissue damage (vascular/metabolic/neural) → accelerated aging — the alarm rings continuously, keeping the body on prolonged alert and exhausting it.

**“Interlocking among the three alarms.”** cGAS–STING → NF-κB (downstream); NLRP3 and cGAS share mtDNA as a trigger; NF-κB increases inflammatory mediators → more damage → more alarms. The alarms reinforce one another and inflammation snowballs.

**“Alarm management” for anti-aging:** (1) Reduce triggers (mitochondrial/metabolic health) → fewer incidents; (2) restore negative feedback (autophagy/dephosphorylation) → enable shutdown; (3) inhibit moderately (NF-κB/NLRP3/cGAS inhibitors) → reduce sensitivity. Fewer incidents + the ability to shut off + lower sensitivity — a three-pronged route to restoring normal sensitivity.

**“Overall value of structural knowledge.”** Understanding the trigger–amplification–termination mechanisms of all three alarms at the structural level → designing precise modulation (do not dismantle the alarm; adjust its sensitivity). From structure to strategy: learn how the alarm works so it rings only when needed.

### 6.1 Connections to the main themes

- **NF-κB** ([14-nfkb-structure.md](14-nfkb-structure.md)): cGAS–STING activates NF-κB downstream — the alarm sounds and the master inflammation switch turns on.
- **NLRP3** ([19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)): both cGAS and NLRP3 may be activated by mtDNA — both alarms monitor mitochondria.
- **Complex I** ([12-complex1-structure.md](12-complex1-structure.md)): damaged mitochondria release mtDNA — the leaky generator leaks DNA.
- **LC3/autophagy** ([18-lc3-autophagy.md](18-lc3-autophagy.md)): clearing sources of leakage suppresses cGAS — an active recycling system means fewer alarms.
- **Cellular senescence/SASP** ([03-senolytics](../04-drugs/03-senolytics.md)): cGAS–STING and SASP are interlocked — the alarm–senescence cycle.
- **Immunosenescence** ([04-immunosenescence](../03-immunity/04-immunosenescence.md)): chronic type I interferons and immunosenescence — continuous alarms overload immunity.

---

## 7. Five structure-and-aging questions

| Question | Structural answer |
|---|---|
| How does cGAS sense DNA? | A positively charged surface binds the DNA phosphate backbone (no sequence specificity) + a length threshold (>20 bp) |
| How does it send the alarm? | DNA binding → oligomerization → synthesis of 2′3′-cGAMP (second messenger) |
| How does STING receive it? | cGAMP binds the LBD → conformational closure → ER-to-Golgi transport → TBK1/IRF3 |
| Why is it chronically activated during aging? | Increased mtDNA leakage + micronuclei + reduced autophagy — more leakage, less clearance, continuous alarms |
| How might it be targeted for anti-aging? | Reduce leakage (mitochondria/genome) + enhance autophagy + moderate inhibition — less leakage, better clearance, repair the alarm |

**Structural intuition beyond the five questions:** the cGAS–STING story reveals the “location philosophy” of immune recognition: **the immune system asks not only “what is it?” but also “where is it?”** DNA in the nucleus is “self”; DNA in the cytosol is an “enemy.” The same molecule’s location determines friend or foe — the principle of immune compartmentalization. TLRs recognize invaders in endosomes, cGAS recognizes DNA in the cytosol, and NLRP3 senses cytosolic damage ([19-nlrp3-inflammasome.md](19-nlrp3-inflammasome.md)). The immune system uses location as the first layer of identity verification. **Membranes are not only cellular structures but also immune boundaries.** **Anti-aging implication:** (1) Maintain compartment integrity (mitochondrial and nuclear membranes/autophagic clearance of micronuclei) → prevent immune misclassification — intact boundaries prevent alarms; (2) aging involves “compartment leakage” (membrane damage/mtDNA leakage/micronuclei) → immune misclassification → inflammation — when boundaries break, self can become “enemy.” Part of anti-aging therefore involves “repairing boundaries” (membrane health/mitochondria/autophagy) so location-based immune judgments are not disrupted.

### 8.1 “Clinical prospects for cGAS–STING”: from antitumor therapy to anti-aging

The bidirectional clinical development of cGAS–STING reflects the alarm’s “two faces.”

**“STING agonists (antitumor immunity).”** STING activation → enhanced antitumor immunity (cGAS–STING activation in the tumor microenvironment → IFN → T-cell infiltration). STING agonists (cGAMP analogues) are in clinical development — a positive use of the alarm, alerting the immune system to clear tumors.

**“cGAS/STING inhibitors (anti-inflammation/anti-aging).”** Inhibit cGAS–STING → reduce chronic inflammation (autoimmunity/inflammaging) — the reverse use of the alarm. cGAS inhibitors (e.g., RU.521)/STING inhibitors (e.g., H-151) are in preclinical development — quiet the alarm’s false positives.

**“Clinical applications in aging.”** Inhibiting cGAS–STING improves aging-related phenotypes in animal models (kidney/metabolic/neural) — a potential anti-inflammatory, anti-aging target.

**“The challenge of balance.”** Complete inhibition → impaired anti-infective/antitumor immunity; complete activation → inflammation/autoimmunity. The alarm should sound when it should, and remain quiet when it should. The key to bidirectional drugs is timing, tissue, and dose.

**“From structure to clinic.”** Understanding the cGAS–DNA and STING–cGAMP binding pockets (4O6A/6NT5) → design selective modulators that precisely control activation/inhibition. Knowing the pocket’s shape lets us design the key (drug). cGAS–STING is a hub for immune–inflammatory balance, and structural knowledge is a map for bidirectional drug design.

---

## 8. Open questions

1. **Precise mechanism of DNA-length recognition by cGAS**: structural basis of the length threshold (>20 bp).
2. **Dynamics of cGAS oligomerization**: oligomerization induced by DNA binding.
3. **Complete STING activation pathway**: structural dynamics of ER-to-Golgi transport.
4. **“Noncanonical” STING functions**: autophagy induction/other signaling.
5. **Tissue specificity**: differences in cGAS–STING sensitivity among tissues.
6. **Development of cGAS–STING inhibitors/agonists**: compounds for selective modulation.

### 8.2 “cGAS–STING and the mitochondria–immunity axis”: from mtDNA to inflammation

The intersection of cGAS–STING and mitochondria is central to the “mitochondria–immunity axis” — the connection between a leaky generator and the alarm.

**“Immunogenicity of mtDNA.”** Mitochondrial DNA contains “unmethylated CpG” (resembling bacterial DNA) → recognized as an “invader” by cGAS/TLR9. Mitochondrial DNA resembles bacterial DNA, so the immune system may not distinguish them — the bacterial origin of mitochondria (endosymbiosis) makes them an immune target.

**“mtDNA release through BAX/BAK pores.”** Apoptosis/mitochondrial stress → BAX/BAK pores → mtDNA release into the cytosol → cGAS activation. During mitochondrial “suicide,” DNA spills out and triggers the alarm.

**“The role of mitophagy in preventing leakage.”** PINK1/Parkin ([24-pink1-parkin.md](24-pink1-parkin.md)) → timely removal of damaged mitochondria → prevent mtDNA release → suppress cGAS. Efficient quality control keeps the alarm quiet — mitophagy is cGAS’s “firewall.”

**“The aging mtDNA–cGAS cycle.”** Mitochondrial damage in old age → mtDNA leakage → cGAS activation → inflammation → further mitochondrial damage → more leakage — a vicious cycle of leak, alarm, damage, and more leakage.

**“Anti-aging implication.”** Maintain mitochondrial quality (exercise/NAD⁺/mitophagy) → reduce mtDNA leakage → suppress chronic cGAS activation. Repair the generator (mitochondria), keep up quality control (autophagy), and reduce unnecessary alarms (cGAS): three measures to break the mitochondria–inflammation cycle. From mtDNA to chronic inflammation, cGAS–STING is the hub of the mitochondria–immunity axis — the most direct connection between mitochondria and inflammation among the 30 structural articles.

---

## 9. Guide to structural data

- **PDB entries**:
  - 4O6A: cGAS + DNA (1.86 Å, Zhang 2014, *Cell Rep*) — oligomerization + switch-like conformation.
  - 4O67/4O68/4O69: other states from the same study.
  - 6NT5: full-length human STING in an inactive state (4.10 Å cryo-EM, Shang 2019, *Nature*).
  - 6NT6/6NT7/6NT8: cGAMP-bound STING (dimeric/tetrameric states).
  - 4LOJ and others: cGAS catalytic domain + cGAMP product.
  - AlphaFold: AF-Q8N884 (human cGAS), AF-Q86WV6 (human STING).
- **Viewing tools**: RCSB online 3D viewer, PyMOL/ChimeraX.

---

## 10. References (published works)

1. Zhang X, Wu J, Du F, et al. The cytosolic DNA sensor cGAS forms an oligomeric complex with DNA and undergoes switch-like conformational changes in the activation loop. *Cell Rep* 2014;6:421–430. (PDB 4O6A)
2. Shang G, Zhang C, Chen ZJ, Bai XC, Zhang X. Cryo-EM structures of STING reveal its mechanism of activation by cyclic GMP-AMP. *Nature* 2019;567:389–393. (PDB 6NT5 and others)
3. Sun L, Wu J, Du F, Chen X, Chen ZJ. Cyclic GMP-AMP synthase is a cytosolic DNA sensor that activates the type I interferon pathway. *Science* 2013;339:786–791. (Discovery of cGAS)
4. Wu J, Sun L, Chen X, et al. Cyclic GMP-AMP is an endogenous second messenger in innate immune signaling by cytosolic DNA. *Science* 2013;339:826–830. (Discovery of cGAMP)
5. Cai X, Chiu YH, Chen ZJ. The cGAS-cGAMP-STING pathway of cytosolic DNA sensing and signaling. *Mol Cell* 2014;54:289–296. (Pathway review)
6. Decout A, Katz JD, Venkatraman S, Ablasser A. The cGAS-STING pathway as a therapeutic target in inflammatory diseases. *Nat Rev Drug Discov* 2021;20:548–567. (cGAS–STING as a therapeutic target)
7. Glück S, Guey B, Gulen MF, et al. Innate immune sensing of cytosolic chromatin fragments through cGAS promotes senescence. *Nat Cell Biol* 2017;19:1061–1070. (cGAS and cellular senescence)

---

> **Structural overview:** cGAS–STING is the **cytosolic DNA “sentinel-and-alarm axis.”** cGAS (the DNA sensor) binds cytosolic DNA (no sequence specificity + a length threshold >20 bp; 4O6A revealed activation by oligomerization) → synthesizes **2′3′-cGAMP** (second messenger) → binds STING (an ER membrane protein; 6NT5 revealed the conformational change) → ER-to-Golgi transport → TBK1/IRF3 → **type I interferons/inflammatory mediators**. **During aging: increased mtDNA leakage + micronuclei + reduced autophagy → chronic cGAS–STING activation → chronic inflammation/cellular senescence (SASP) → accelerated aging.** **Anti-aging strategies:** reduce leakage (mitochondrial/genomic health) + enhance autophagy (remove leakage sources) + moderate inhibition (cGAS/STING inhibitors) — less leakage, better clearance, and repair the alarm; do not let the DNA burglar alarm ring continuously. This is a key part of anti-inflammatory, anti-aging approaches.
