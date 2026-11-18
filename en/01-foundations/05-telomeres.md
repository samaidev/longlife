## 8. Genomic Instability and DNA Repair

Genomic instability is another primary hallmark of aging, encompassing mutation accumulation, chromosomal abnormalities, epigenetic drift, and transposon activation. The DNA damage response (DDR) system is responsible for repair, and its efficiency declines with age:

| Repair pathway | Target damage | Core components | Age-related changes |
|---|---|---|---|
| Base excision repair (BER) | Oxidative/alkylated single-base damage (8-oxo-dG) | OGG1, APE1, PARP1, XRCC1, DNA Polβ | Activity declines (a key aging pathway) |
| Nucleotide excision repair (NER) | Bulky adducts, UV damage | XPC, XPA, XPB/XPD (TFIIH) | Activity declines |
| Homologous recombination (HR) | Double-strand breaks (S/G2) | BRCA1/2, RAD51, ATM | Efficiency declines |
| Non-homologous end joining (NHEJ) | Double-strand breaks (all cell-cycle phases) | Ku70/80, DNA-PKcs, XRCC4, Lig4 | Fidelity declines; errors increase |

**The repair–aging paradox**: Faithful HR repair depends on a homologous template, while NHEJ is fast but imprecise (and can introduce deletions/insertions). In aging cells, the contribution of NHEJ increases while HR declines, leading to a higher error rate in break repair—this is both a cause of accumulating genomic instability and the context in which end-to-end fusion (essentially an aberrant NHEJ or HR event) becomes more frequent when telomeres are extremely short.

### 8.1 Transposon Activation

Transposons such as **LINE-1 (L1)** are usually epigenetically silenced in adult somatic cells, but age-related derepression (loss of H3K9me3, decline in SIRT6) leads to:
- L1 retrotransposition and insertion that disrupt genes/regulatory elements;
- Activation of innate immunity (cGAS–STING), exacerbating the senescence-associated secretory phenotype (SASP);
- A vicious cycle involving short telomeres, DDR defects, and L1 derepression.

**Intervention targets**: SIRT6 overexpression suppresses L1 transposition and senescence; reverse transcriptase inhibitors (such as lamivudine) reduce L1 activation in vitro.

## 9. Integrating Telomeres, Aging Clocks, and Tissue Stem Cells

Telomere length and epigenetic clocks are two complementary “readouts” of aging: epigenetic clocks reflect a cell’s differentiation and stress history, while telomere length reflects its replication history. In large cohorts, the correlation between LTL and DNAmAge is only about r≈0.3, suggesting that the two capture different dimensions of aging—**epigenetic clocks are more sensitive to lifestyle interventions, while telomere length is more sensitive to a cell’s proliferation history**. At the tissue level, the direct consequence of telomere shortening is **stem cell exhaustion**: regenerative tissues such as the gut, blood-forming system, and skin depend on stem cell division, and excessively short telomeres trigger p53/p21-mediated senescence, reducing regenerative capacity (age-related telomere shortening in hematopoietic stem cells is associated with immune aging). Telomerase gene therapy (AAV-TERT vectors) has extended lifespan by about 24% and improved metabolic and neuromuscular function in aged mice (multiple studies in 2023, such as Bernardes de Jesus 2012 and subsequent work). However, hepatocyte proliferation and an increased risk of tumor promotion have also been observed at the same dose—the safety window remains a bottleneck to clinical translation.

**Integrating the “telomere–epigenetic–mitochondrial” three-axis system**: It is worth emphasizing that telomere shortening is not an isolated event; it forms a positive-feedback loop with epigenetic drift and mitochondrial dysfunction. Critically short telomeres activate p53, which suppresses PGC-1α and mitochondrial function (reducing oxidative metabolism). Mitochondrial ROS then cause oxidative damage to telomeric DNA (with 8-oxo-dG enriched in telomeric sequences), further accelerating telomere shortening. At the same time, telomere stress (TRF2 release and ATM activation) drives inflammation and SASP, which are mutually causal with the chronic inflammation described in [02-inflammaging](../03-immunity/02-inflammaging.md). Thus, “anti-aging through telomeres” cannot be pursued in isolation: telomere maintenance (stress reduction, exercise, and antioxidants) must go hand in hand with mitochondrial maintenance (exercise and fasting) and the maintenance of epigenetic homeostasis (reprogramming and NAD⁺). All three rest on the same foundation of “lifestyle + metabolic health.” This also explains why [09-immortality/02-breakthrough-candidates](../09-immortality/02-breakthrough-candidates.md) ranks telomerase activation as a low-priority approach: a single-target intervention cannot break the three-axis feedback loop, whereas combination strategies (exercise + NAD⁺ + weight loss), though “unremarkable,” can improve all three dimensions at once—**aging is a process involving multiple interconnected axes, and anti-aging interventions must also address multiple interconnected axes**.

## 10. Alternative Lengthening of Telomeres (ALT) and Clinical Applications

About 10–15% of tumors (including sarcomas and glioblastomas) extend their telomeres through **ALT (alternative lengthening of telomeres)** rather than relying on telomerase. ALT depends on homologous recombination and copy-mediated extension using telomeric DNA as a template. Its hallmarks include APBs (ALT-associated PML bodies) in PML bodies, C-circles, and increased telomeric sister chromatid exchange. The existence of ALT shows that “telomere maintenance” is a hard requirement for cancer cells—whether through telomerase or ALT, inhibiting telomere maintenance is a cancer treatment strategy (the telomerase inhibitor imetelstat has been approved for myeloproliferative neoplasms). Clinically, LTL testing is moving from research toward application: assessing inherited telomere disorders (for example, DKC diagnosis requires LTL below the 1st percentile), monitoring reconstitution after hematopoietic stem cell transplantation, and serving as a candidate endpoint in clinical trials of anti-aging interventions. However, because short-term within-person fluctuations are large and standardized calibration materials are lacking, it is not yet suitable as a routine test of “anti-aging effects” in healthy individuals.

## 11. Connection with the NO Pathway

- Exercise → eNOS/NO↑ → telomerase activation (NO upregulates TERT via the sGC/cGMP or Akt pathway); studies have also reported that NO increases telomerase activity.
- NO scavenges reactive oxygen species (especially superoxide), reducing oxidative damage from **8-oxo-dG** to G-rich telomeric sequences. G is the telomeric base most susceptible to oxidation, and oxidative damage directly causes single-strand breaks and accelerated telomere shortening.
- Chronic inflammation (high iNOS expression and excess NO → peroxynitrite, ONOO⁻) instead damages telomeres and DNA—again illustrating the biphasic effects of NO, depending on dose.

## 12. Evidence Grading and Open Questions

| Proposition | Evidence level |
|---|---|
| Telomeres shorten with age (replicative senescence) | A (mechanistic evidence + multiple species) |
| Telomeres act as a replication counter (Hayflick) | A |
| Short LTL is associated with mortality/disease risk | B (strong association; causality uncertain) |
| Telomerase activation extends lifespan | B (supported in animals, unconfirmed in humans) |
| Telomerase activation is safe as an anti-aging intervention | C (cancer-promoting risk unresolved) |
| Lifestyle can alter telomeres | B (primarily observational; moderate intervention evidence) |

**Open questions**:
1. The safety window for telomerase activation—can healthy lifespan be extended without significantly increasing cancer risk?
2. Is telomere length a “cause” or an “effect”? The association weakens substantially after adjustment for genetic and confounding factors (Mendelian randomization suggests that genetically determined telomere length and disease are mostly independent).
3. Can epigenetic reprogramming (iPSC/OSK factors) reset telomeres while maintaining genomic stability? Telomeres are significantly lengthened in iPSCs, suggesting that telomere length can be reprogrammed.
4. Clinical translation of “shortest telomere” as a more precise marker of aging.
5. Can genomic repair (especially HR fidelity) be enhanced pharmacologically without increasing cancer risk?

**Key references**: Epel ES et al. *PNAS* 2004;101(49):17312–17315. (stress and telomeres) / Blackburn EH, Epel ES, Lin J. *Science* 2015;350(6265):1193–1198. (review of telomeres and lifestyle) / de Lange T. *Genes Dev* 2005;19:2100–2110. (shelterin) / Hayflick L. *Exp Cell Res* 1965;37:614–636.
