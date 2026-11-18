# Immunosenescence

## Core concept

Immunosenescence is the systemic, progressive decline in immune function that occurs with age. Thymic involution depletes naïve T-cell output and narrows T-cell receptor (TCR) repertoire diversity; memory T cells—especially terminally differentiated cells—accumulate abnormally; B-cell antibody quality and class-switching capacity decline; NK-cell and innate immune functions change; and chronic low-grade inflammation (inflammaging) develops. This is not the failure of a single cell population, but coordinated dysregulation of the hematopoietic system’s “production” end (thymus and hematopoietic stem cells in bone marrow), “distribution” end (peripheral homeostatic proliferation and clonal expansion), and “effector” end (effector/memory differentiation). Immunosenescence directly shapes three major medical consequences of aging: greater susceptibility to infection and severe disease (influenza, COVID-19), weaker vaccine responses (lower seroconversion and faster loss of protection), and impaired tumor immune surveillance. It is the immunological hub of the “infection–cancer–frailty” risk chain and the point where two of the 12 hallmarks of aging—stem-cell exhaustion and chronic inflammation—intersect in the immune system (see 01-foundations/01-aging-hallmarks.md). Its relevance to anti-aging is that the immune system is one of the few systems that can be partially rebuilt: thymic regeneration, exercise, and pharmacological interventions all have evidence of reversibility, making it a rich target for interventions.

## The complete molecular mechanism

### 1. Thymic involution: atrophy at the source

The thymus is the only organ where naïve T cells develop. Its involution begins in puberty and is an upstream driver of immunosenescence:

```
FoxN1↓ ──▶ thymic epithelial cell (TEC) atrophy/apoptosis
                    │
Sex hormones↑ (puberty) ├──▶ cortical/medullary disorganization ──▶ positive/negative selection efficiency↓
                    │
PPARγ↑ ──▶ adipocyte infiltration replaces parenchyma ──▶ thymic parenchymal volume↓ (at 60, ≈10–15% of puberty)
                    │
                    └──▶ insufficient IL-7 and self-peptide–MHC signals ──▶ naïve T-cell output↓
                                                                  │
                                                       TREC (T-cell receptor excision circles)↓
```

Key molecular nodes: **FoxN1** is the master transcription factor governing TEC fate. Its expression declines with age and is both a cause and consequence of TEC atrophy (conditional FoxN1 overexpression can partially reverse thymic atrophy in old mice). **AIRE** (autoimmune regulator), expressed in medullary TECs, drives tissue-restricted antigen expression for negative selection. AIRE expression falls with age, weakening self-tolerance screening (associated with increased autoimmunity risk in older adults) and reducing the “pass rate” of T cells after positive selection. Sex hormones directly drive programmed involution: the pubertal surge accelerates it, while castration/sex-hormone ablation (GnRH agonists) can partially restore thymic output in rodents and men (TREC increases). Imaging (MRI/CT fat fraction) and histology agree: by age 60, thymic parenchyma is largely replaced by fat, naïve T-cell output falls to ~1% of its peak, and TREC content declines by roughly 1–2 orders of magnitude with age.

### 2. Depletion of naïve T cells

The adult peripheral naïve T-cell pool is maintained by early thymic output and **peripheral homeostatic proliferation** (low-level division driven by IL-7/IL-15). Human kinetic studies by den Braber et al. (2012) showed that after adulthood, human naïve T cells are maintained mainly by peripheral self-renewal rather than thymic input. With aging, sensitivity to IL-7 and IL-15 declines, homeostatic proliferation does not compensate sufficiently, and naïve T cells themselves undergo telomere shortening and lose the ability to maintain quiescence (downregulation of the FoxO1/miR-181a pathway—miR-181a lowers the TCR signaling threshold; its age-related decline raises the activation threshold and weakens clonal expansion responses). Quantitatively, **CD8⁺ naïve T cells decline by about 20–30% per decade**. CD4⁺ naïve T cells decline more slowly but also substantially. In healthy young adults, naïve cells constitute about 40–50% of the CD8⁺ pool; after age 65, only 5–10% remain. Their loss directly diminishes the ability to mount first responses to novel antigens (new pathogens, vaccines, and tumor neoantigens)—the immunological basis for older adults responding poorly to unfamiliar threats while retaining more responses to threats encountered before.

### 3. Narrowing of TCR repertoire diversity

TCR repertoire diversity directly measures the breadth of adaptive immune defense. High-throughput TCRβ sequencing (Britanova et al., 2014; Naylor et al., 2005 spectral typing) shows:

- **Fewer clones with age:** older people have more than an order of magnitude fewer unique peripheral TCR clones than young people; narrowing is more severe in CD8⁺ than CD4⁺ repertoires.
- The Shannon diversity index declines monotonically with age and is positively correlated with thymic output (TREC).
- **Clonal expansion:** a small number of large clones (>0.1% frequency) occupy an increasingly large share of the repertoire. Many are CMV/EBV-specific memory clones (“memory inflation”). In CMV-seropositive older adults, CMV-specific T cells can make up 10–25% of the CD8⁺ memory pool.
- Consequences: fewer available precursor clones for novel pathogen peptides and tumor neoantigens, with corresponding declines in vaccine responses and response rates to immunotherapies such as PD-1 blockade.

```
Thymic output↓ ──▶ inadequate input to naïve pool
IL-7/IL-15 homeostatic compensation (clonal expansion) ──▶ large clones expand, small clones are lost
Chronic CMV/EBV antigen stimulation ──▶ memory inflation
        ──▶ Shannon diversity↓, repertoire skew↑ ──▶ gaps in responses to novel antigens
```

### 4. Accumulation and terminal differentiation of memory T cells

Repeated antigen stimulation shifts memory T cells toward terminal differentiation, accumulating **TEMRA** (CD45RA⁺CCR7⁻CD28⁻CD27⁻) and **CD57⁺/KLRG1⁺** effector-memory cells. The sequence is: chronic antigen (mainly CMV) → repeated TCR stimulation → loss of CD28 expression (the promoter region of this costimulatory molecule becomes methylated and irreversibly silenced) → loss of costimulatory signaling → limited proliferative capacity but retained ability to secrete IFN-γ/TNF-α/perforin. CD57⁺ cells have very short telomeres and are in proliferative arrest (pre-senescent), yet remain actively pro-inflammatory. CD28⁻CD57⁺ cells account for <5% of CD8⁺ cells in healthy young people but can reach 50–80% in CMV-positive older adults. These cells cause both “immune space occupation” (displacing naïve/central memory cells) and SASP-like inflammation, directly linking immunosenescence to inflammaging.

### 5. Clonal hematopoiesis (CHIP)

Hematopoietic stem cells (HSCs) accumulate somatic mutations with age. Clones with driver mutations in genes such as DNMT3A, TET2, and ASXL1 gain a selective advantage and expand, producing clonal hematopoiesis of indeterminate potential (CHIP). In aging HSCs, defective DNA-damage repair (especially NHEJ) promotes mutation accumulation. Loss of DNMT3A (a methyltransferase) biases HSCs toward self-renewal and myeloid differentiation; the myeloid-to-lymphoid output ratio in older HSCs rises 5–10-fold. Loss of TET2 promotes inflammatory myeloid differentiation and a pro-inflammatory macrophage phenotype. Immunological consequences include persistent production of pro-inflammatory cytokines (IL-6, IL-1β, TNF-α) by mutant myeloid clones, amplifying inflammaging and suppressing lymphoid output—a vicious “hematopoiesis–immunity–inflammation” cycle. Epidemiologically, CHIP is detected in about 10% of people over 65; carriers have approximately 40% higher all-cause mortality (HR≈1.4; Jaiswal 2014). The excess risk of atherosclerotic cardiovascular disease is largely attributable to TET2/DNMT3A clones (HR≈1.9; Jaiswal 2017).

### 6. B-cell aging

The B-cell lineage undergoes a decline in both “quantity and quality” with age:

- Bone-marrow B-cell production declines (B-1 and transitional B cells decrease), while the peripheral pool shifts toward a memory phenotype.
- **Defective class-switch recombination (CSR) and somatic hypermutation (SHM):** Frasca et al. (2008) showed substantial age-related reductions in the transcription factor E2A and activation-induced cytidine deaminase (AID) in B cells. IgG/IgA class switching becomes less efficient and antibody affinity maturation is impaired.
- Antibody repertoire diversity narrows; antibodies have lower affinity and less breadth. The direct clinical manifestation is **poor vaccine response**: influenza-vaccine seroconversion rates in older adults are about 30–50% lower than in young adults, peak titers are lower, and titers wane faster.
- Detection of autoantibodies (ANA, RF, etc.) rises with age (failure of self-tolerance screening plus B-cell regulatory imbalance), associated with increased risk of autoimmune disease in older adults.

### 7. Changes in NK cells and innate immunity

Total NK-cell numbers increase with age (with accumulation of mature CD56^dim CD57⁺ subsets), but **per-cell killing function declines**: degranulation (CD107a) and cytotoxic-granule release become less efficient, and ADCC is impaired. Clearance of tumor cells and virus-infected cells declines with age. Other innate changes include reduced neutrophil chemotaxis and phagocytosis; impaired macrophage phagocytosis and M2 reparative polarization, with stronger M1 pro-inflammatory polarization; and a marked age-related decrease in TLR7/9-induced IFN-α production by plasmacytoid dendritic cells (pDCs) (Agrawal et al., 2007), weakening the first line of antiviral defense. The net innate-immune effect is a mismatch: **more inflammatory output but less effective defense**.

### 8. Inflammaging

The processes above converge on chronic low-grade inflammation: chronic activation of NF-κB and the NLRP3 inflammasome → mildly elevated IL-6, IL-1β, TNF-α, and CRP (about 2–4 times higher in older than young adults) → further T- and B-cell dysfunction, tissue damage, and spread of SASP, creating a positive-feedback loop between immunosenescence and systemic aging. Inflammaging is both a consequence and an amplifier of immunosenescence. Whether “immunosenescence and inflammaging are mutually causal” remains a central debate in the field (see Open questions).

## Evidence grading

| Phenomenon | Evidence level | Key evidence/literature |
|---|---|---|
| Thymic involution and decline in naïve T-cell output | Established (human imaging + immunology) | MRI/CT fat fraction; TREC falls 1–2 orders of magnitude with age; den Braber 2012 |
| 20–30%/decade decline in CD8⁺ naïve T cells | Established (flow cytometry across cohorts) | Multiple cross-sectional cohorts; naïve CD8⁺ cells are 5–10% of the pool after 65 |
| Narrowing of TCR repertoire diversity | Established (high-throughput sequencing) | Deep TCRβ sequencing, Britanova 2014; Shannon index declines with age |
| CMV-driven memory inflation (accumulation of CD28⁻/CD57⁺ cells) | Established (human observational evidence) | Wertheimer 2014; in CMV⁺ older adults, CD28⁻CD57⁺ cells can reach 50–80% of CD8⁺ cells |
| Immune risk phenotype (IRP) predicts mortality in older adults | Strong association (prospective cohorts) | Swedish OCTO/NONA: CD4:CD8<1 + CMV⁺ + accumulation of CD28⁻ cells predicts 2-year mortality |
| CHIP and all-cause mortality/cardiovascular risk | Strong association (exome sequencing in tens of thousands) | Jaiswal 2014 (HR 1.4), 2017 (CHD HR≈1.9) |
| B-cell AID/E2A downregulation and poor vaccine response | Strong association (mechanistic + cohort evidence) | Frasca 2008; influenza seroconversion 30–50% lower in older adults |
| Elevated inflammatory markers predict disability/death | Strong association (prospective cohorts) | IL-6/CRP and mortality risk in older adults (e.g., Harris 1999) |
| Rapamycin improves vaccine response in older adults | RCT (small studies) | Mannick 2014/2018: everolimus raises influenza-vaccine antibodies ~20%, lowers respiratory infection rate ~30% |
| High-dose/adjuvanted influenza vaccines are more effective | Large RCTs | Fluzone HD relative efficacy +24.2% (DiazGranados 2014); MF59-adjuvanted vaccine outperforms standard vaccine |
| Thymic regeneration (GH+DHEA+metformin) | Small human study + animal evidence | TRIIM (Fahy 2019): thymic density increased in 7 of 9 participants; epigenetic age regressed 2.5 years |
| Immune “rejuvenation” (reprogramming/heterochronic parabiosis) | Established in animals; not feasible in humans | Partial reprogramming regenerates thymus; heterochronic parabiosis, Conboy 2005 |

## Details of clinical and experimental evidence

**Differences in vaccine response (the most direct clinical phenotype):** Older adults respond less strongly to influenza, COVID-19, and shingles vaccines. For influenza, seroconversion among people over 65 is 30–50% lower than among those aged 18–49; peak antibody titers are lower and wane faster over six months. Evidence-based strategies include the high-dose trivalent vaccine Fluzone HD (60 μg/strain vs. 15 μg/strain), which reduced the relative risk of confirmed influenza by 24.2% in people over 65 (DiazGranados 2014, *NEJM*, RCT, n≈31,989); the MF59-adjuvanted vaccine (Fluad), which also outperforms standard-dose vaccine; and the recombinant subunit shingles vaccine Shingrix (adjuvant AS01), with 97.2% efficacy in people ≥50 (Lal 2015, *NEJM*). Shingrix is a textbook example of how an adjuvant system (AS01 activates TLR4 and cGAS–STING pathways to boost innate immunity) can rescue vaccine responses in aging.

**Rapamycin/everolimus (mTOR inhibition):** In Mannick 2014 (*Sci Transl Med*, RCT), adults over 65 received everolimus at 0.5 mg/day or 5 mg/week (low doses designed to stay below the immunosuppressive window). After Fluzone vaccination, antibody response was about 20% higher than with placebo (significant in the 0.5 mg group). A 2018 follow-up trial found that low-dose TORC1 inhibition reduced respiratory infection rates by about 30% over one year (rate ratio ≈0.7). Mechanistically, mTORC1 inhibition reduces the proportion of CD28⁻ senescent T cells and promotes renewal of naïve/memory pools and Th1 responses. “Mild mTOR inhibition” is one of the few human immune-rejuvenation strategies supported by RCTs.

**Human thymic-regeneration trial:** The TRIIM trial (Fahy 2019, *Aging Cell*) treated men aged 51–65 for 12 months with a combination of growth hormone (low-dose recombinant hGH three times weekly), DHEA (50 mg/day), and metformin (500 mg/day). In 7 of 9 participants, thymic MRI density/volume increased (imaging evidence of parenchymal regeneration); plasma TREC increased, and epigenetic age (Horvath clock) regressed by an average of about 2.5 years. The sample was small, there was no control group, and the mechanisms are confounded (the contribution of each drug is unknown), but the study provided the first combined evidence that the human thymus may be reversible. Animal evidence is clearer: sex-hormone ablation (GnRH agonists) boosts thymic output in male volunteers (Sutherland 2005, *J Clin Invest*); FoxN1 overexpression, FGF7/KGF (palifermin), and IL-7 supplementation restore thymic structure and T-cell output in old mice; and transient OSKM partial reprogramming regenerates the thymus and rejuvenates the immune repertoire in old mice (cancer risk limits translation).

**Immune risk phenotype (IRP):** The Swedish OCTO/NONA longitudinal studies (Wikby et al., 2006) defined IRP in adults over 85 as an inverted CD4:CD8 ratio (<1) + CMV seropositivity + accumulation of CD28⁻ cells. IRP carriers had significantly higher mortality within two years and elevated IL-6. This is the classic human evidence that immunosenescence markers predict mortality. T-cell telomere length, the proportion of CD28⁻ cells, and serum IL-6/CRP are a repeatedly validated combination of immunosenescence biomarkers.

**CHIP epidemiology:** Jaiswal 2014 (*NEJM*, n=17,182, exome sequencing) found that about 10% of people over 70 had CHIP with variant allele frequency ≥2%. Carriers had an all-cause mortality HR≈1.4 and about a tenfold higher risk of hematologic malignancy. Jaiswal 2017 (*NEJM*) further found higher coronary heart disease risk in CHIP carriers (HR≈1.9, with the largest contribution from TET2). The mechanism is IL-1β secretion by mutant myeloid clones, promoting atherosclerosis. CHIP has thus shifted from a “precancerous state” to an “accelerator of inflammatory aging,” motivating clinical trials targeting TET2 clones and IL-1β (canakinumab).

**CAR-T and adoptive cell therapy in older adults:** Anti-CD19 CAR-T is now routinely used for older people with relapsed/refractory lymphoma and acute lymphoblastic leukemia (approved indications include older adults). Real-world data show similar response rates in patients ≥65 and younger patients, although CRS and neurotoxicity are more frequent and require reduced-intensity pretreatment. This demonstrates that antitumor immunity can still be rebuilt by engineering in an aging host. Cancer immunotherapy (PD-1/PD-L1 blockade) is effective in older adults with non-small-cell lung cancer, but response is positively correlated with TCR diversity—immunosenescence directly limits the ceiling of immunotherapy (see other articles in 03-immunity).

**Multi-omics profiling of immunosenescence and the immune clock:** The field is moving from single biomarkers toward “multi-omics immune age.” An “immune clock” built from flow-cytometric T/B/NK subsets, TCR sequencing, serum inflammatory-cytokine profiles, and immune-cell methylation can output immune age (ImmAge). It is partly independent of and complementary to epigenetic clocks. Alpert 2019 (*PNAS*) found a strong association between survival and immune age derived from cell-subset proportions; the immune clock of Sayed 2021 (*Nat Aging*) integrates immune-cell composition and functional measures. **People whose immune age exceeds their chronological age (immunological aging) may have poor vaccine responses and infection resistance even when otherwise healthy.** Immune clocks provide a basis for “immune-age checkups” (complementary to the epigenetic clock in [02-aging-clocks](../01-foundations/02-aging-clocks.md): epigenetics assesses the whole body, while immune measures assess the defense system).

## Connections to NO, NAD⁺, and longevity networks

- **Age-related decline in iNOS/NO antimicrobial function:** Macrophages use iNOS-derived NO to kill intracellular pathogens (e.g., mycobacteria and *Leishmania*). Defective iNOS induction and reduced NO production in older macrophages are among the mechanisms behind the increased incidence of intracellular infections such as tuberculosis—a “NO gap” in immune defense.
- **Biphasic dose effects of NO on T cells:** Low NO concentrations (from eNOS/nNOS) promote T-cell proliferation and Th1 differentiation via sGC/cGMP/PKG; high concentrations (from iNOS in an inflammatory microenvironment) inhibit T cells through S-nitrosylation and apoptotic pathways. Aging combines reduced eNOS (insufficient NO) with iNOS overexpression in inflammatory lesions (excess local NO), producing systemic NO deficiency alongside local nitrosative stress and further disrupting T-cell polarization (Th1/Th17 shifts).
- **NO inhibits NF-κB:** NO directly S-nitrosylates NF-κB p65 Cys38, reducing DNA binding, or deacetylates p65 via SIRT1. Insufficient NO removes this restraint on NF-κB and amplifies inflammaging (see cellular senescence in 01-foundations/01-aging-hallmarks.md).
- **eNOS protects the thymic microenvironment:** eNOS/NO maintains thymic microvascular endothelial function and perfusion. Age-related eNOS downregulation accelerates ischemic thymic involution, creating a “NO↓–thymic involution” vicious cycle. NO also regulates HSC quiescence and homing (HSC self-renewal is impaired in eNOS-knockout mice).
- **NAD⁺/SIRT1 crosstalk:** NAD⁺ decline → lower SIRT1 activity → increased NF-κB acetylation (pro-inflammatory) and impaired T-cell metabolic adaptation (SIRT1 regulates the Treg/effector balance). Some immune benefits of NAD⁺ precursors (NMN/NR) in older adults may come from SIRT1-mediated anti-inflammation and maintenance of T-cell function. NO and NAD⁺ are deeply coupled through the SIRT1 axis (see 01-foundations/03-no-basics.md). Age-related accumulation of ONOO⁻-mediated protein 3-nitrotyrosine modifications reflects the damaging side of the “double-edged sword” of NO in immunosenescence.

## Intervention directions and actionable recommendations

**Human-supported options (ranked by strength of evidence):**
1. **Vaccination strategy:** Older adults should receive high-dose influenza vaccine (Fluzone HD), MF59-adjuvanted influenza vaccine, and AS01-adjuvanted shingles vaccine (Shingrix). RCTs show these can partly compensate for immunosenescence; this is the most mature and immediately actionable approach.
2. **Exercise:** Regular aerobic exercise (moderate intensity, ≥150 minutes/week) and higher cardiorespiratory fitness are associated with a higher proportion of naïve T cells, fewer CD28⁻ senescent T cells, and better NK cytotoxicity. Endurance athletes have longer leukocyte telomeres (Werner 2009). Exercise is the lowest-cost immune-rejuvenation intervention.
3. **Low-dose mTOR inhibition:** Low-dose everolimus/rapamycin improves vaccine responses and reduces respiratory infections (RCT evidence), but lipids, glucose, and infection risk need monitoring; it is not approved for immune reconstitution.
4. **Nutrition and metabolism:** Maintain adequate vitamin D, zinc, and protein. Caloric restriction preserves TCR diversity in primates (Messaoudi et al.); intermittent fasting/metformin may improve immunometabolism via AMPK/autophagy (moderate-to-weak evidence).

**Frontiers under study:** Thymic regeneration (GH+DHEA+metformin combinations, sex-hormone ablation, FoxN1/FGF7/IL-7 supplementation, thymic organoids and thymus transplantation—already used clinically for patients with DiGeorge syndrome); epigenetic reprogramming (established in animals, far from mature in humans); senolytics to clear senescent immune cells (e.g., dasatinib + quercetin, early human trials); CHIP-targeted treatment (post hoc analysis of the CANTOS canakinumab IL-1β-blockade trial found reduced cardiovascular events in carriers); and CAR-T/adoptive cell therapy (already routinely used in older cancer patients).

### Making immune age part of a checkup: monitoring and interventions individuals can undertake

Based on the mechanisms and evidence for immunosenescence, personal “immune-age management” can be implemented at three levels:

**1. Monitoring (lower-cost health-check items):** Lymphocyte-subset analysis in a blood count (CD4:CD8 ratio and proportion of CD28⁻ senescent T cells—the core IRP components); hsCRP/IL-6 (inflammatory burden); vitamin D and zinc (immune substrates). If feasible, add TCR-repertoire sequencing or an immune-clock test (emerging and relatively expensive).

**2. Behaviors (strongest evidence):** (1) Regular aerobic exercise (≥150 minutes/week at moderate intensity)—associated with a higher naïve T-cell proportion, fewer CD28⁻ cells, and better NK function. (2) Vaccination: after age 65, prioritize high-dose/adjuvanted influenza vaccines (Fluzone HD/Fluad), Shingrix for shingles, and pneumococcal vaccines (PCV20/PPSV23 as appropriate). These are immediately effective anti-immunosenescence measures. (3) Adequate sleep (NK cells and naïve T cells are mobilized at night; see [05-sleep-optimization](../07-interventions/05-sleep-optimization.md)). (4) Adequate protein (1.2–1.5 g/kg/day) to support immune-cell renewal.

**3. Medical options (require clinician assessment):** Low-dose mTOR inhibitors (RCT-supported enhancement of vaccine response but off-label); thymic-regeneration combinations (GH+DHEA+metformin, based on TRIIM but with a small sample); assessment of CMV status (CMV positivity accelerates immunosenescence, but antiviral strategies are controversial); and CHIP testing (consider after age 65; positive results warrant closer cardiovascular and hematological follow-up).

**Key message:** Immunosenescence is modifiable. **Vaccines + exercise + sleep + nutrition** are the basic package; mTOR inhibition and thymic regeneration are advanced options. Immune-age management should accompany epigenetic-age and metabolic-age management as part of a “multi-system age checkup” (echoing the annual monitoring framework in [01-daily-checklist](../07-interventions/01-daily-checklist.md)). **Build immune reserve early:** immunosenescence accelerates after 40. Exercise and vaccination strategies started now will help determine immune baseline at 70; earlier intervention means more reserve and greater future benefit.

## Open questions and controversies

- **Causal direction:** Which comes first, immunosenescence or inflammaging? Most evidence supports reciprocal positive feedback (immune dysregulation → inflammation → further immune damage), but long-term human trials have not established whether anti-inflammatory treatment reverses immunosenescence. Canakinumab (anti-IL-1β) reduced cardiovascular events without a corresponding observed reduction in infection rates, suggesting that anti-inflammation alone is not immune reconstitution.
- **The role of CMV:** Is CMV-driven memory inflation harmful, or an adaptive immune-system reprioritization? Some centenarians are CMV-positive yet have favorable immune phenotypes, indicating large individual differences. Whether CMV clearance or vaccine prevention (a CMV vaccine is in development) can delay immunosenescence is unknown.
- **Translational risks of thymic regeneration:** GH may increase cancer risk, reprogramming may cause teratogenic effects, and sex-hormone ablation may cause osteoporosis. The dose–risk window for human thymic regeneration is far from clear.
- **Threshold for TCR diversity:** How much diversity must be restored to yield clinical benefit (vaccine response or immunotherapy response)? There is no consensus.
- **The CHIP paradox:** People with DNMT3A/TET2 mutations do not necessarily have shorter lifespans (some studies show increased all-cause mortality, yet CHIP is also detected in centenarians). Whether CHIP is a “damage marker” or an “intervention target” remains debated.

## References

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. Hallmarks of aging: An expanding universe. *Cell*. 2023;186(2):243-278.
2. Goronzy JJ, Weyand CM. Mechanisms underlying T cell ageing. *Nat Rev Immunol*. 2019;19(9):573-583.
3. Nikolich-Žugich J. The twilight of immunity: emerging concepts in aging of the immune system. *Nat Immunol*. 2018;19(1):10-19.
4. Franceschi C, Garagnani P, Parini P, Giuliani C, Santoro A. Inflammaging: a new immune-metabolic viewpoint for age-related diseases. *Nat Rev Endocrinol*. 2018;14(10):576-590.
5. Pawelec G. Hallmarks of human immunosenescence. *Ageing Res Rev*. 2020;62:101111.
6. den Braber I, Mugwagwa T, Vrisekoop N, et al. Maintenance of peripheral naive T cells is sustained by thymus output in mice but not humans. *Immunity*. 2012;36(2):288-297.
7. Britanova OV, Putintseva EV, Shugay M, et al. Age-related decrease in TCR repertoire diversity measured with deep and normalized sequence profiling. *J Immunol*. 2014;192(6):2689-2698.
8. Jaiswal S, Fontanillas P, Flannick J, et al. Age-related clonal hematopoiesis associated with adverse outcomes. *N Engl J Med*. 2014;371(26):2488-2498.
9. Jaiswal S, Natarajan P, Silver AJ, et al. Clonal hematopoiesis and risk of atherosclerotic cardiovascular disease. *N Engl J Med*. 2017;377(2):111-121.
10. Frasca D, Landin AM, Lechner SC, et al. Aging down-regulates the transcription factor E2A, activation-induced cytidine deaminase, and Ig class switch in human B cells. *J Immunol*. 2008;180(8):5283-5290.
11. Mannick JB, Del Giudice G, Lattanzi M, et al. mTOR inhibition improves immune function in the elderly. *Sci Transl Med*. 2014;6(268):268ra179.
12. Mannick JB, Morris M, Hockey HP, et al. TORC1 inhibition enhances immune function and reduces infections in the elderly. *Sci Transl Med*. 2018;10(449):eaaq1564.
13. Fahy GM, Brooke RT, Watson JP, et al. Reversal of epigenetic aging and immunosenescent trends in humans. *Aging Cell*. 2019;18(6):e13028.
14. DiazGranados CA, Dunning AJ, Kimmel M, et al. Efficacy of high-dose versus standard-dose influenza vaccine in older adults. *N Engl J Med*. 2014;371(7):635-645.
15. Lal H, Cunningham AL, Godeaux O, et al. Efficacy of an adjuvanted herpes zoster subunit vaccine in older adults. *N Engl J Med*. 2015;372(22):2087-2096.
16. Wikby A, Nilsson BO, Forsey R, et al. The immune risk phenotype is associated with IL-6 in the terminal decline stage: findings from the Swedish NONA immune longitudinal study of very late life. *Mech Ageing Dev*. 2006;127(8):695-704.
17. Sutherland JS, Goldberg GL, Hammett MV, et al. Activation of thymic regeneration in mice and humans following androgen blockade. *J Immunol*. 2005;175(4):2741-2753.
18. Werner C, Fürster T, Widmann T, et al. Physical exercise prevents cellular senescence in circulating leukocytes and in the vessel wall. *Circulation*. 2009;120(24):2438-2447.
19. Agrawal A, Agrawal S, Tay J, Gupta S. Biology of dendritic cells in aging. *J Leukoc Biol*. 2007;82(6):1445-1454.
