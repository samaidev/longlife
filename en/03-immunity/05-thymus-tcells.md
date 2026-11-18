# Thymic Involution and the T-Cell Repertoire

## Core concept

The thymus is the only organ in which naïve T cells develop and undergo selection, and it is also the **first organ in mammals to begin aging**. Thymic involution therefore precedes the aging of all other organs and is called the “first battlefield” of immunosenescence. It is the progressive loss of thymic epithelial cells (TECs), atrophy of cortical and medullary architecture, and infiltration and replacement of parenchyma by adipose tissue after puberty. Epithelial space shrinks by about 3% per year; by age 60–70, only about 10–15% of pubertal levels remain. Naïve T-cell output falls to ~1% of its peak, and T-cell receptor (TCR) repertoire diversity narrows exponentially. This directly determines the “freshness” of adaptive immune defense—the ability to mount first responses to new pathogens, vaccine antigens, and tumor neoantigens—and is a common upstream cause of severe infections, poor vaccine responses, and weakened tumor immune surveillance in older adults. In anti-aging research, the thymus is a rare organ shown repeatedly to be **partially rebuildable** (with evidence in humans or animals for sex-hormone ablation, FGF21, the growth-hormone axis, and single-gene FoxN1 regeneration), making it a rich target for immune rejuvenation (see the overview of immunosenescence in 03-immunity/04-immunosenescence.md).

## The complete molecular mechanism

### 1. Thymic anatomy and functional compartments

The thymus lies in the anterior mediastinum behind the sternum and consists of two lobes. A connective-tissue capsule surrounds it and extends inward to form interlobular septa. Each lobe has two regions:

- **Cortex:** The outer layer, rich in developing thymocytes and cortical thymic epithelial cells (cTECs). It is where T-lineage progenitors proliferate, TCR genes rearrange, and positive selection occurs.
- **Medulla:** The inner, less densely cellular layer, containing medullary thymic epithelial cells (mTECs), dendritic cells (DCs), macrophages, and thymic B cells. Negative selection and the “release” of naïve T cells occur here. The medulla also contains Hassall’s corpuscles, characteristic structures formed from degenerating mTECs. Their secretion of thymic stromal lymphopoietin (TSLP) helps regulate induction of regulatory T cells (Tregs).

### 2. Four stages of thymocyte development: DN → DP → SP

Bone-marrow hematopoietic stem cells (HSCs) give rise to lymphoid progenitors and then T-lineage progenitors, which enter the thymus from the blood at the corticomedullary junction or beneath the capsule. In the thymus they pass through four stages:

```
Bone-marrow HSC → T-lineage progenitor (ETP) ──enters thymus──▶
  DN1 (CD44⁺CD25⁻) ──▶ DN2 (CD44⁺CD25⁺)  TCRβ/γ/δ rearrangement begins (RAG1/RAG2)
  DN3 (CD44⁻CD25⁺) ──▶ β-selection (pre-TCR checkpoint; ~1/4 pass) ──▶ DN4 (CD44⁻CD25⁻)
  ──▶ DP (CD4⁺CD8⁺)  TCRα rearrangement ──▶ positive selection (cTEC presents self-MHC; >90% die)
  ──▶ SP (CD4⁺ or CD8⁺) ──▶ negative selection (mTEC presents tissue antigens via AIRE; high-affinity clones deleted)
  ──▶ mature naïve T cells enter blood (only ~3–5% of thymocytes survive the entire process)
```

- **V(D)J recombination:** The TCRβ chain is assembled by RAG1/RAG2-mediated recombination of variable (V), diversity (D), and joining (J) gene segments; the TCRα chain is assembled from V and J segments. Random nucleotide insertion/deletion at the junctions (N/P addition) generates junctional diversity. Combinatorial and junctional diversity give the theoretical TCR repertoire a capacity of 10¹⁵–10²⁰, while the actual human peripheral repertoire contains about 10⁸–10¹¹ unique clones—the molecular basis of adaptive immunity’s “pre-existing defense.”
- **Positive selection:** DP thymocytes are tested against self-peptides presented by MHC-I/MHC-II on cTECs. Only cells that recognize “self MHC” with appropriate affinity receive survival signals; cells that do not are eliminated by neglect. This also determines CD4/CD8 lineage commitment (MHC-II recognition → CD4; MHC-I recognition → CD8).
- **Negative selection:** SP thymocytes encounter tissue-restricted antigens (TRAs) presented by mTECs under control of **AIRE** (autoimmune regulator). Clones that recognize self-antigens with high affinity are deleted (clonal deletion) or diverted into Tregs (clonal diversion)—the core of central tolerance. AIRE expression declines with age, increasing escape of autoreactive clones and correlating with higher autoimmune risk in older adults (mainly mechanistic inference; moderate human evidence).
- **αβ and γδ cells:** About 95% of thymocytes follow the αβ pathway. γδ T cells (1–5% of peripheral T cells) branch off during the DN stage, do not undergo MHC-restricted selection, and mainly reside in mucosal and epithelial tissues. Their age-related changes are milder than those of the αβ pool.

### 3. Drivers of thymic involution: multiple factors acting in parallel

```
                    Sex hormones↑ (puberty) ──▶ TEC apoptosis/proliferation imbalance
FoxN1↓ ──▶ failure to maintain TEC identity ──▶ cTEC/mTEC loss
GH/IGF-1↓ (somatopause) ──▶ insufficient TEC proliferative signals
Autophagy↓ (mTOR↑/FGF21↓) ──▶ protein aggregates/mitochondrial damage in TECs ──▶ NLRP3 inflammation
miRNA/epigenetic changes (e.g., miR-29↑) ──▶ altered gene-expression programs in TECs and progenitors
PPARγ↑ ──▶ TEC-to-adipocyte transdifferentiation/fat infiltration ──▶ parenchyma replaced by fat
        ──▶ insufficient IL-7 and self-peptide–MHC signals ──▶ positive/negative selection efficiency↓ ──▶ naïve T output↓ (TREC↓)
```

**FoxN1 is the master transcription factor governing TEC identity.** FoxN1 deficiency produces the nude-mouse phenotype: no thymus, no hair, and no T cells. FoxN1 expression declines with age and is both cause and consequence of TEC atrophy. Bredenkamp et al. (2014, *Development*) showed that **overexpression of the single transcription factor FoxN1 can regenerate the aged mouse thymus**: TEC numbers, cortical/medullary structure, and T-cell output all recovered. This is among the strongest mechanistic demonstrations that thymic involution is reversible. The same year, the team used FoxN1 to directly reprogram fibroblasts into functional TECs and assembled an organized, functional thymus (see Interventions).

**Sex hormones** directly drive involution after puberty. TECs express androgen and estrogen receptors; sex hormones suppress TEC proliferation and promote apoptosis. The pubertal hormone surge coincides with accelerated thymic atrophy (although the morphometric study by Steinmann 1985 suggests human thymic epithelial decline starts before puberty and accelerates afterward). Castration/sex-hormone ablation with GnRH agonists restores thymic volume and TREC output in rodents and human males (Sutherland 2005).

**Fat infiltration** is driven by PPARγ. Some thymic adipocytes derive from bone-marrow preadipocytes that take up residence; some arise through **transdifferentiation of TECs into adipocytes**. Aging TECs lose epithelial identity and acquire adipocyte identity, a process jointly regulated by FoxN1↓ and PPARγ↑. MRI/CT fat fraction increases monotonically with age; by age 60, most thymic parenchyma has been replaced by fat.

**Growth hormone/IGF-1 axis (somatopause):** GH and IGF-1 decline with age, and TECs express GH and IGF-1 receptors. Animals deficient in GH have thymic hypoplasia, while implantation of GH3 pituitary tumor cells (which secrete high levels of GH/prolactin) reverses rat thymic aging (Kelley 1986, *PNAS*). GH acts partly through IGF-1 and partly through local intrathymic GH/IGF-1 paracrine signaling.

**Autophagy and metabolism:** Autophagic flux declines in aged TECs, allowing damaged mitochondria and protein aggregates to accumulate, activating the NLRP3 inflammasome and pro-inflammatory cytokine secretion. This further damages TEC function and the thymic microenvironment. FGF21 (fibroblast growth factor 21)-deficient mice undergo premature thymic involution and increased inflammation (Youm 2016, *PNAS*); exogenous FGF21 restores TEC autophagy and slows thymic aging (see Interventions).

**miRNA and epigenetic changes:** The miRNA expression profile of the aging thymus changes (miR-29 family upregulation and age-related miR-181a downregulation. In T cells, miR-181a lowers the TCR signaling threshold; its decline raises the activation threshold and weakens clonal expansion responses; Li 2012, *Nat Med*). DNA methylation and histone-modification drift in TECs and thymic progenitors blur their gene-expression “identity,” with broad downregulation of the FoxN1 target-gene network.

### 4. T-cell output and TREC

The direct molecular marker of recent thymic emigrants (RTEs) is the **T-cell receptor excision circle (TREC)**. During TCRα rearrangement, the TCRδ locus is excised to form free circular DNA (sjTREC). These circles do not replicate when cells divide, so their concentration reflects recent thymic output. Douek et al. (1998, *Nature*) used quantitative PCR to show that sjTREC declines by roughly 1–2 orders of magnitude from birth to old age. It falls further when thymic function is impaired by HIV infection and rises again after antiviral treatment—establishing TREC as a gold-standard biomarker of thymic function and “immune age.” In adults, the naïve peripheral T-cell pool is maintained by early thymic output and peripheral homeostatic proliferation driven by IL-7/IL-15. Using deuterium-labeling kinetics, den Braber et al. (2012, *Immunity*) demonstrated that **after adulthood, human naïve T cells are maintained mainly by peripheral self-renewal rather than thymic input** (unlike in mice). This explains how the peripheral naïve pool can persist for decades despite very low adult thymic output, at the cost of telomere shortening and cumulative repertoire skew from homeostatic proliferation.

### 4.1 Clinical use of TREC: from research measure to “thymic age” testing

TREC testing is moving from research toward clinical practice, with increasingly clear use cases:

- **Newborn screening (already in use):** TREC is included in newborn screening programs in several countries (qPCR on dried blood spots, DBS) to detect severe combined immunodeficiency (SCID) early. This is the most mature clinical use of TREC; timely transplantation after a positive screen can save lives.
- **Monitoring immune reconstitution (increasing use):** TREC recovery after hematopoietic stem-cell transplantation reflects restoration of thymic output; recovery after HIV antiviral therapy is a marker of immune reconstitution. Its value in clinical monitoring is clear.
- **Assessing “thymic age” (emerging):** TREC combined with T-cell subsets and TCR diversity can form a “thymic age” component of immune age (complementary to the immune clock in [04-immunosenescence](04-immunosenescence.md)). An “advanced thymic age” may indicate accelerated immunosenescence and guide vaccine strategy and immune monitoring. **Limitations:** TREC measurement has not been standardized (primers and copy-number normalization vary); baseline values differ substantially among individuals, so longitudinal tracking is more informative than a single reading.

**Practical suggestion:** After age 40, consider adding “lymphocyte subsets + TREC + hsCRP” to annual health checks (self-pay tests at moderate cost) as a basic assessment of immune age. A rapid TREC decline or a value substantially below age-matched references may indicate accelerated thymic decline and warrant stronger vaccination and immune-intervention strategies (see “Making immune age part of a checkup” in [04-immunosenescence](04-immunosenescence.md)).

### 5. Narrowing of TCR diversity and clonal expansion

High-throughput TCRβ sequencing (Britanova 2014, *J Immunol*) shows the core quantitative features of aging:

| Measure | Young (20–35) | Older (60–80) | Change |
|---|---|---|---|
| Unique peripheral TCR clones | 10⁶–10⁷ range | More than one order of magnitude fewer | Monotonic decline |
| Shannon diversity index | High | Markedly reduced | Positively correlated with TREC |
| Share of large clones (>0.1% frequency) | Low | Markedly increased | Clonal expansion |
| CD4/CD8 difference | CD4 repertoire broader | CD8 repertoire narrows much more than CD4 | Asymmetric |

- **Public versus private clones:** Public clones against common antigens (CMV, EBV, influenza epitopes), shared by many individuals, are relatively preserved or even expand with aging. Individual-specific private clones are lost more quickly. In essence, diversity narrows as “long-tail private clones disappear and dominant public clones expand.”
- **Clonal expansion:** A small number of large clones occupy an increasing share of the repertoire. Most are CMV/EBV-specific memory clones (“memory inflation”). In CMV-positive older adults, CMV-specific T cells can comprise 10–25% of the CD8⁺ memory pool, and terminally differentiated CD28⁻CD57⁺ cells can reach 50–80% of CD8⁺ cells (see 04-immunosenescence.md).
- **Consequences:** Fewer precursor clones are available for new pathogen peptides and tumor neoantigens—the direct structural basis for declining vaccine responses and limited immunotherapy response.

### 6. Homeostatic maintenance of naïve T cells and cytokine signaling

- **IL-7:** Produced by TECs and thymic stroma, it is the main factor supporting naïve T-cell survival and homeostatic proliferation, especially for CD4⁺ cells. With aging, IL-7 production falls (TEC loss), and T-cell sensitivity to IL-7Rα (CD127) signaling decreases, so homeostatic maintenance is no longer adequately compensated.
- **IL-15:** Drives homeostatic proliferation of memory and some naïve CD8⁺ cells. Signaling efficiency declines with age, while dependence of the memory pool on it increases.
- **IL-2:** Low doses support Treg survival through the high-affinity IL-2 receptor, whereas high doses drive effector/memory differentiation. Imbalance in IL-2 homeostasis contributes to an age-related Treg/effector imbalance.
- **Niche competition:** Expanding memory clones occupy survival niches and cytokine shares needed by naïve T cells, further shrinking the naïve pool. This “space-occupying effect” suppresses homeostatic proliferation of naïve T cells and creates a positive-feedback cycle of depletion.

## Evidence grading

| Phenomenon | Evidence level | Key evidence/literature |
|---|---|---|
| Age-related thymic fat infiltration and parenchyma reduced to 10–15% | Established (human imaging + histology) | MRI/CT fat fraction; Steinmann 1985; George & Ritter 1996 (~3% annual atrophy) |
| Exponential decline in naïve T-cell output with age (TREC↓ by 1–2 orders of magnitude) | Established (human molecular measurement) | Douek 1998, *Nature* (HIV model + age curve) |
| Narrowing of TCR diversity and clonal expansion | Established (high-throughput sequencing) | Britanova 2014, *J Immunol*; Shannon index falls with age |
| Adult naïve T cells maintained mainly by peripheral homeostatic proliferation | Established (human kinetics) | den Braber 2012, *Immunity* (deuterium labeling) |
| A single factor, FoxN1, regenerates the aged mouse thymus when overexpressed | Established in animals | Bredenkamp 2014, *Development* |
| Sex-hormone ablation restores thymic output | Small human study + established animal evidence | Sutherland 2005, *J Immunol* (GnRH agonist) |
| FGF21 deficiency accelerates/supplementation slows thymic involution | Established in animals | Youm 2016, *PNAS*; 2025 *Nature Aging* (paracrine mechanism) |
| Ghrelin promotes thymopoiesis in old mice | Established in animals | Dixit 2007, *J Clin Invest* |
| Thymic involution drives the sharp rise in cancer incidence in older adults | Mathematical model + epidemiological fit | Palmer 2018, *PNAS* (modeling age–incidence curves) |
| GH+DHEA+metformin thymic regeneration | Small uncontrolled human study | TRIIM, Fahy 2019, *Aging Cell* (thymic density↑ in 7 of 9) |
| Thymus transplantation for DiGeorge syndrome | Human evidence (rare-disease indication) | Markert 2004, *Blood* |
| NO induces thymocyte apoptosis | Mechanistic studies (cells/animals) | Fehsel 1995, *J Immunol* |

## Details of clinical and experimental evidence

**Vaccine responses (the most direct clinical phenotype):** Older adults respond less well to influenza, COVID-19, and shingles vaccines. Depletion of the naïve T-cell pool reduces precursor clones available for novel antigens (vaccine epitopes), and T follicular helper (Tfh) cells become less able to help B cells mount germinal-center responses. Evidence-based countermeasures include high-dose influenza vaccine Fluzone HD (60 μg/strain vs. standard 15 μg/strain), which reduced the relative risk of confirmed influenza by 24.2% in people ≥65 (DiazGranados 2014, *NEJM*, RCT n≈31,989), and the AS01-adjuvanted shingles vaccine Shingrix, with 97.2% efficacy in people ≥50 (Lal 2015, *NEJM*). Adjuvants activate innate immunity through TLR4/cGAS–STING, partly compensating for insufficient naïve T cells.

**Thymic involution and cancer (Palmer 2018, *PNAS*):** Modeling age–incidence curves for several cancers showed that a model of “mutations accumulate with age” could not explain the sharp rise in incidence after age 60 as well as a model in which immune surveillance weakens with thymic involution. This suggests that the loss of T-cell diversity due to thymic involution may be a major driver of cancer in older adults (a mechanistic hypothesis and mathematical model that should be interpreted cautiously). This perspective supports the intervention logic that restoring TCR diversity might prevent tumors.

**TRIIM human trial (Fahy 2019, *Aging Cell*):** Nine men aged 51–65 received recombinant human growth hormone (rhGH, low dose three times weekly), dehydroepiandrosterone (DHEA, 50 mg/day), and metformin (500 mg/day) for 12 months (intermittent rhGH was used to keep IGF-1 within a safety window). Thymic MRI density/volume increased in 7/9 (imaging evidence of parenchymal regeneration), plasma TREC increased, and Horvath epigenetic age regressed by an average of about 2.5 years. The sample was small, uncontrolled, and unable to distinguish the contributions of the three drugs; GH also presents an IGF-1-related cancer risk. Nevertheless, this provided the first combined evidence that the human thymus may be reversible. An expanded TRIIM-X cohort has since begun.

**Sex-hormone ablation:** Sutherland 2005 (*J Clin Invest*) showed in healthy male volunteers that suppressing sex hormones with a GnRH agonist (leuprolide) increased thymic volume and TREC. This is direct human evidence for the causal chain “remove sex-hormone signaling → thymic regeneration.” The cost is gonadal suppression, with risks of osteoporosis and reduced sexual function, so this approach is limited to specific populations such as prostate-cancer patients.

**Ghrelin (Dixit 2007, *J Clin Invest*):** Giving ghrelin or a GHSR agonist to old mice restored thymocyte numbers and TREC-like output and improved the T-cell repertoire. The mechanism involves GHSR-mediated promotion of thymic progenitor proliferation and maintenance of TEC function. This provides an animal rationale for thymic-regeneration potential of growth-hormone secretagogues; human evidence is lacking.

**Thymus transplantation and organoids:** Markert 2004 (*Blood*) showed that transplantation of cultured allogeneic thymic tissue can rebuild T-cell immunity in children with athymic DiGeorge syndrome, proving that the thymus can be transplanted and T cells can be “re-educated.” Organoid engineering—implantable thymic primordia combining iPSC-derived TECs and FoxN1-reprogrammed fibroblasts (Bredenkamp 2014, *Nat Cell Biol*)—is advancing preclinically.

**FGF21 (Youm 2016, *PNAS*; 2025 *Nature Aging*):** Transgenic or pharmacological elevation of FGF21 slows thymic involution and restores T-cell output in old mice. A 2025 *Nature Aging* study further clarified a **paracrine mechanism**: locally produced FGF21 from thymic epithelial cells and adipocytes acts through the β-Klotho receptor on TECs to maintain thymopoiesis. Knockout of FGF21 or β-Klotho in TECs accelerates thymic aging. FGF21 analogues (e.g., efruxifermin) are already in metabolic-disease clinical trials, offering a drug-development route toward thymic regeneration.

**Leptin and the nutrition–immunity connection:** Leptin is a key link between adipose tissue and the immune system. Howard et al. (1999, *J Clin Invest*) showed that leptin-deficient ob/ob mice have marked thymic atrophy and fewer thymocytes, while exogenous leptin restores thymocyte numbers. Thymic involution induced by fasting/malnutrition is also associated with lower leptin. Energy status may therefore couple thymic maintenance through the leptin–GH axis, helping explain immune collapse during cachexia in chronic disease (the nutrition–thymus–immunity axis).

**Thymic hormones and thymic peptides:** The thymus not only “trains” T cells, but also secretes soluble factors, including thymosin α1 (Tα1; clinical preparation Zadaxin), thymulin (zinc-dependent), and thymopoietin, which contribute to T-cell maturation and maintenance. Tα1 has clinical data in chronic viral hepatitis and some immunodeficiency settings, but evidence for benefit against immunosenescence is weak to moderate. Thymulin activity declines with age and is related to zinc status. Small studies suggesting that zinc supplementation partly restores thymulin activity in older adults point to a potentially actionable “zinc–thymic peptide” nutritional window, but this needs larger-scale validation.

## Connections to NO, NAD⁺, and longevity networks

- **Biphasic effects of NO on thymocytes:** Low NO concentrations (from eNOS/nNOS) promote thymocyte proliferation and differentiation signals via sGC/cGMP/PKG. High concentrations (from iNOS in an inflammatory microenvironment) induce thymocyte apoptosis. Fehsel et al. (1995, *J Immunol*) directly showed that NO donors (e.g., SNAP) induce mouse thymocyte apoptosis in a dose-dependent manner, independently of glucocorticoid receptors. iNOS is expressed in thymic macrophages/DCs; as age-related inflammation rises, iNOS↑ → excess local NO → more thymocyte apoptosis and disrupted positive/negative selection. The “double-edged sword” of NO in the thymus is the toxic side of a developmental window.
- **eNOS and thymic perfusion:** eNOS/NO maintains thymic microvascular endothelial function and perfusion. Age-related eNOS decline accelerates ischemic thymic involution, creating a “NO↓–thymic involution” vicious cycle. NO also regulates HSC quiescence and homing (HSC self-renewal is impaired in eNOS-knockout mice), affecting upstream thymic input of T-lineage progenitors (see 01-foundations/03-no-basics.md).
- **NO inhibits NF-κB:** NO S-nitrosylates p65 (Cys38), reducing its DNA binding. Insufficient NO removes the restraint on NF-κB, amplifying pro-inflammatory programs in TECs and thymocytes and accelerating involution.
- **NAD⁺/SIRT1:** NAD⁺ declines with age, lowering SIRT1 activity. Mechanistic studies show that SIRT1 participates in T-lineage development (Notch signaling) and Treg stability (Foxp3 deacetylation); SIRT1-deficient mice have abnormal thymic and T-cell development. Some benefits of NAD⁺ precursors (NMN/NR) for immunity in older adults may arise through SIRT1-mediated anti-inflammation and T-cell maintenance. NO and NAD⁺ are tightly coupled through SIRT1: eNOS activity depends on NAD⁺ (SIRT1 deacetylates eNOS to maintain its activity), forming an additive loop: “NAD⁺↓ → SIRT1↓ → eNOS↓ → thymic perfusion↓.”
- **Metabolism–immunity crosstalk:** The FGF21/ghrelin/GH axes converge on “energy-metabolism sensing → thymic maintenance.” Longevity networks (mTOR/AMPK/autophagy) intersect directly with thymic involution inside TECs, making the thymus a window for immune benefits from metabolic interventions (metformin, rapamycin, fasting).

## Intervention directions and actionable recommendations

**Evidence to date (ranked by strength):**
1. **Vaccination strategy:** For people ≥65, high-dose (Fluzone HD) or adjuvanted (MF59) influenza vaccines and AS01-adjuvanted shingles vaccine (Shingrix) are supported by RCTs and partly compensate for a depleted naïve T-cell pool. This is the most mature option that can be implemented now.
2. **Exercise and metabolism:** Regular aerobic exercise (moderate intensity, ≥150 minutes/week) and high cardiorespiratory fitness are associated with a higher proportion of naïve T cells and fewer senescent T cells. Adequate protein, zinc, and vitamin D support thymulin (zinc-dependent) function. These are low-cost immune-maintenance strategies.
3. **Low-dose mTOR inhibition:** Low-dose rapamycin/everolimus improves vaccine responses and reduces respiratory infections in older adults (RCT evidence, Mannick 2014/2018), and restores thymic structure in old mice. Lipids, glucose, and infection risk require monitoring; it is not approved for immune reconstitution.
4. **Human-evidenced thymic-regeneration combinations:** GH+DHEA+metformin (TRIIM protocol) and sex-hormone ablation have both demonstrated human thymic reversibility. Their risk windows (IGF-1-related cancer risk with GH, and bone-metabolism costs of sex-hormone ablation) mean they should only be explored under strict clinical supervision.

**Frontiers under study:** FGF21 analogues (with drug-development foundations in metabolic disease); ghrelin/GHSR agonists; IL-7 supplementation (rhIL-7/CYT107 immune-reconstitution trials); FoxN1 gene therapy and FoxN1-reprogrammed organoids (established in animals); thymus transplantation (clinical for DiGeorge syndrome); partial reprogramming (established in animals, far from mature in humans); and PPARγ antagonism/blocking TEC transdifferentiation (preclinical).

## Open questions and controversies

- **Programmed aging versus cumulative damage:** Is thymic involution driven mainly by “programmed aging” (sex hormones, an intrinsic FoxN1 clock) or by “cumulative damage” (oxidation, inflammation, metabolic waste)? Steinmann’s evidence of pre-pubertal decline and FoxN1 single-gene regeneration each support one side; their relative importance is unresolved.
- **Origin of thymic adipocytes:** Do thymic adipocytes arise through TEC transdifferentiation or by residence of bone-marrow preadipocytes? If the former predominates, blocking transdifferentiation (anti-PPARγ) might preserve the TEC pool, implying a very different intervention strategy.
- **Exthymic compensation:** Are there inducible sites of extrathymic T-cell generation (liver, gut-associated lymphoid tissue) that partly compensate in adults? Evidence is weak.
- **Diversity threshold:** How much TCR diversity must be restored to improve vaccine responses and cancer immunotherapy outcomes? There is no quantitative consensus (the Palmer model offers a theoretical framework but lacks human validation).
- **Intervention risk window:** GH may promote tumors, sex-hormone ablation carries bone-metabolism costs, and forced FoxN1 expression may be oncogenic. The human dose–risk window for thymic regeneration is unclear. TRIIM included only nine participants and had no control group; its findings need replication.

## References

1. George AJT, Ritter MA. Thymic involution with ageing: obsolescence or good housekeeping? *Immunol Today*. 1996;17(6):267-272.
2. Steinmann GG, Klaus B, Müller-Hermelink HK. The involution of the ageing human thymic epithelium is independent of puberty. A morphometric study. *Scand J Immunol*. 1985;22(5):563-575.
3. Douek DC, McFarland RD, Keiser PH, et al. Changes in thymic function with age and during the treatment of HIV infection. *Nature*. 1998;396(6712):690-695.
4. Palmer S, Albergante L, Blackburn CC, Newman TJ. Thymic involution and rising disease incidence with age. *Proc Natl Acad Sci USA*. 2018;115(8):1883-1888.
5. den Braber I, Mugwagwa T, Vrisekoop N, et al. Maintenance of peripheral naive T cells is sustained by thymus output in mice but not humans. *Immunity*. 2012;36(2):288-297.
6. Britanova OV, Putintseva EV, Shugay M, et al. Age-related decrease in TCR repertoire diversity measured with deep and normalized sequence profiling. *J Immunol*. 2014;192(6):2689-2698.
7. Bredenkamp N, Nowell CS, Blackburn CC. Regeneration of the aged thymus by a single transcription factor. *Development*. 2014;141(8):1627-1637.
8. Bredenkamp N, Ulyanchenko S, O'Neill KE, et al. An organized and functional thymus generated from FOXN1-reprogrammed fibroblasts. *Nat Cell Biol*. 2014;16(9):902-908.
9. Sutherland JS, Goldberg GL, Hammett MV, et al. Activation of thymic regeneration in mice and humans following androgen blockade. *J Immunol*. 2005;175(4):2741-2753.
10. Fahy GM, Brooke RT, Watson JP, et al. Reversal of epigenetic aging and immunosenescent trends in humans. *Aging Cell*. 2019;18(6):e13028.
11. Youm YH, Horvath TL, Mangelsdorf DJ, Kliewer SA, Dixit VD. Prolongevity hormone FGF21 protects against immune senescence by delaying age-related thymic involution. *Proc Natl Acad Sci USA*. 2016;113(4):1026-1031.
12. Youm YH, Gliniak C, Zhang Y, et al. Enhanced paracrine action of FGF21 in stromal cells delays thymic aging. *Nat Aging*. 2025;5(4):576-587.
13. Dixit VD, Yang H, Sun Y, et al. Ghrelin promotes thymopoiesis during aging. *J Clin Invest*. 2007;117(10):2778-2787.
14. Li G, Yu M, Lee WW, et al. Decline in miR-181a expression with age impairs T cell receptor sensitivity by increasing DUSP6 activity. *Nat Med*. 2012;18(10):1518-1524.
15. Fehsel K, Kröncke KD, Meyer KL, et al. Nitric oxide induces apoptosis in mouse thymocytes. *J Immunol*. 1995;155(6):2858-2865.
16. Anderson MS, Venanzi ES, Klein L, et al. Projection of an immunological self shadow within the thymus by the aire protein. *Science*. 2002;298(5597):1395-1401.
17. Kelley KW, Brief S, Westly HJ, et al. GH3 pituitary adenoma cells can reverse thymic aging in rats. *Proc Natl Acad Sci USA*. 1986;83(15):5663-5667.
18. Howard JK, Lord GM, Matarese G, et al. Leptin protects mice from starvation-induced lymphoid atrophy and increases thymic cellularity in ob/ob mice. *J Clin Invest*. 1999;104(8):1051-1059.
19. Markert ML, Sarzotti M, Ozaki DA, et al. Thymus transplantation in complete DiGeorge syndrome: immunologic and safety evaluations in 12 patients. *Blood*. 2003;102(3):1121-1130.
20. DiazGranados CA, Dunning AJ, Kimmel M, et al. Efficacy of high-dose versus standard-dose influenza vaccine in older adults. *N Engl J Med*. 2014;371(7):635-645.
