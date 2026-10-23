# Track 2 Drug-Repurposing Dossier

## A falsifiable preclinical investigation of everolimus for a possible mTORC1-linked vulnerability in BUB1B-associated MVA1

**Challenge:** Rare Disease, Real Kid: MVA Hackathon 2026 — Track 2  
**Proband:** `PROBAND01`  
**Working diagnosis:** Mosaic variegated aneuploidy syndrome 1 (MVA1; OMIM #257300)  
**Working genetic model:** Putative compound-heterozygous *BUB1B* variants: `p.Leu737Ter` and `p.Asn1002Lys`  
**Submission type:** Preclinical drug-repurposing hypothesis and validation plan  
**Status:** Hypothesis only; not clinical advice and not a treatment protocol

> **Safety and scope statement.** This dossier does not recommend administering everolimus, NR, NMN, or any other agent to the proband. It does not establish efficacy, safety, dose, or clinical benefit. Any human use would require the treating pediatric oncology, clinical pharmacology, nephrology, genetics, and research-ethics teams to make an independent decision under an approved protocol.

## Executive summary

MVA1 is a rare chromosome-segregation disorder associated with pathogenic disruption of *BUB1B*, which encodes the spindle-assembly-checkpoint protein BUBR1. BUBR1 participates in the mitotic checkpoint complex and in the stabilization of kinetochore–microtubule attachments. Constitutional mosaic aneuploidy and cancer susceptibility are established features of the *BUB1B*-associated MVA spectrum, although phenotype, mosaic fraction, and tumor risk vary between individuals. Childhood embryonal rhabdomyosarcoma and Wilms tumor are among the reported malignancies. [Malumbres et al., 2024](https://mvasociety.org/wp-content/uploads/2024/11/Malumbres-24-Nat-Rev-Genet.pdf)

The proband’s two heterozygous short-read calls are consistent with a biallelic *BUB1B* model, but short-read calls from a proband alone do not prove that the variants are in trans. The genetic description must therefore remain “putative compound heterozygous” until parental testing or long-read phasing is available. The premature-stop allele is predicted to undergo nonsense-mediated decay; that prediction requires allele-specific RNA confirmation. The C-terminal missense allele lies within the BUBR1 kinase/pseudokinase fold, but the molecular effect of this exact substitution is not yet established.

The qualifying repurposing candidate is everolimus, an mTORC1 inhibitor with pediatric approval in specific tuberous-sclerosis-associated indications. The proposal is not that everolimus cures MVA1. It is that *BUB1B*-defective or aneuploid cells may show a context-dependent vulnerability to mTORC1 inhibition that can be tested against corrected and euploid comparators.

NR and NMN are retained only as laboratory mechanistic comparators. They are not presented as a pediatric treatment prong while measurable rhabdomyosarcoma is present, because NAD salvage can support tumor metabolism and DNA-repair capacity in relevant RMS models.

The decisive feature of this proposal is a preclinical kill switch: if the proposed molecular rescue or tumor selectivity is not demonstrated reproducibly, the hypothesis stops.

---

### Challenge Specification Summary: Mechanism Characterization
In compliance with Track 2 submission criteria characterizing variant effect, biological pathway, and clinical consequences:
* **Variant Characterization:** Biallelic Loss of Function (LoF) — Putative compound heterozygous nonsense null (`p.Leu737Ter`, predicted NMD) in trans with a C-terminal pseudokinase domain fold-destabilizing hypomorphic missense (`p.Asn1002Lys`).
* **Biological Pathway Disrupted:** Spindle Assembly Checkpoint (SAC) / Mitotic Checkpoint Complex (MCC) fidelity and kinetochore–microtubule attachment control via the BUBR1 KARD/PP2A-B56 recruitment interface.
* **Downstream Biological & Clinical Consequences:** Impaired checkpoint delay during chromosome alignment -> premature anaphase onset -> high-rate chromosome mis-segregation -> constitutional mosaic variegated aneuploidy (MVA1) -> severe growth restriction, microcephaly, and elevated early embryonal tumor predisposition (specifically infantile rhabdomyosarcoma).  
  *Critical nuance:* As emphasized by Malumbres & Villarroya-Beltri (2024), aneuploidy creates cellular stress and chromosomal instability but is not by itself sufficient for malignant transformation; cooperating somatic alterations and microenvironmental selection drive oncogenesis.

---

## 1. Clinical and genetic premise

### 1.1 What MVA1 establishes—and what it does not

The spindle assembly checkpoint delays anaphase until chromosome–spindle attachments are sufficiently correct. BUBR1 is a core component of the mitotic checkpoint complex and also participates in the regulation of stable kinetochore–microtubule attachments. Loss of checkpoint fidelity can generate mosaic chromosome-number abnormalities in multiple tissues.

The correct translational statement is not that every dividing cell will continuously become aneuploid. Mosaic fractions are tissue-specific, dynamic, and subject to selection. The correct statement is that a constitutional *BUB1B* defect creates a persistent biological substrate for chromosome-segregation error and justifies specialist surveillance and functional investigation. No disease-modifying therapy for the constitutional defect is established.

Cancer management remains ordinary specialist oncology care for the tumor actually present, together with syndrome-informed surveillance. Published MVA guidance emphasizes awareness of embryonal malignancies and renal ultrasound surveillance; the MVA Society describes renal ultrasonography every three to four months until age five for individuals with cytogenetic confirmation and/or demonstrated *BUB1B* mutations. Modality, interval, and duration must be individualized by the treating team. [MVA Society surveillance information](https://mvasociety.org/about-mva/)

### 1.2 Variant interpretation and phasing

The working pair is:

- `p.Leu737Ter`: a premature termination variant upstream of the C-terminal fold. Nonsense-mediated decay is plausible but must be measured with allele-specific RNA.
- `p.Asn1002Lys`: a missense variant within the C-terminal BUBR1 kinase/pseudokinase region. The residue’s location makes a structural or stability defect plausible, but does not prove one.

Two heterozygous variants in one proband are not equivalent to a proven trans configuration. The Track 1 result should therefore use “putative compound-heterozygous pair” or “predicted biallelic pair pending phasing,” unless parental or long-read data establish phase.

### 1.3 BUBR1 is not a simple kinase engine

BUBR1 contains N-terminal interaction modules involved in checkpoint-complex assembly, a KARD region involved in PP2A-B56 recruitment and attachment control, and a C-terminal kinase-like fold. Human BUBR1 retains some catalytic-sequence features but functions principally as an unusual pseudokinase/scaffold in the established human-cell model. Putative catalysis is not the same as a missing ATP-driven engine.

The C-terminal fold is nevertheless important. Published MVA work found that kinase-domain-localized MVA mutations can reduce overall BUBR1 abundance, while other alleles cause more specific checkpoint or attachment defects. That supports an abundance-rescue hypothesis, not an assumption that increasing protein quantity will restore all functions. [Suijkerbuijk et al., 2010](https://pubmed.ncbi.nlm.nih.gov/20516114/) [Suijkerbuijk et al., 2012](https://pubmed.ncbi.nlm.nih.gov/22698286/)

## 2. Biological hypothesis

### 2.1 Prong 1: protein-stability biology, not “checkpoint supercharging”

North et al. reported that SIRT2-mediated deacetylation of BUBR1 at K668 opposed acetylation-associated degradation in a mouse aging model, and that NMN increased BUBR1 abundance in that experimental context. [North et al., 2014](https://pubmed.ncbi.nlm.nih.gov/24825348/)

That result supplies a testable mechanism:

1. SIRT2 activity may alter the abundance or half-life of some full-length BUBR1 molecules.
2. A larger pool of correctly folded BUBR1 might improve checkpoint performance if abundance is the limiting lesion.
3. The mechanism should fail if the missense protein is too unstable, mislocalized, unable to assemble the checkpoint complex, or unable to support attachment regulation.

The critical structural objection is that K668 lies in the upstream KARD neighborhood, whereas `p.Asn1002Lys` lies in the C-terminal fold. Deacetylating K668 cannot be assumed to repair a structural defect in a distant domain. Rescue requires the molecule to remain full-length, sufficiently folded, correctly localized, and competent for its relevant interactions.

NR/NMN therefore belong first in an assay, not in a child’s medication list. A positive result must include increased full-length protein, an interpretable half-life change, and functional improvement—not merely a change in total NAD or a Western-blot band of uncertain identity.

### 2.2 Prong 2: mTORC1 inhibition as a conditional aneuploid-cell vulnerability

Aneuploid cells can experience stoichiometric protein imbalance, proteotoxic stress, altered translation demand, and lysosomal stress. These observations motivate testing mTORC1 inhibition. They do not establish that mTOR inhibition selectively kills all aneuploid cells.

Everolimus may:

- reduce cap-dependent translation and anabolic load;
- inhibit mTORC1-dependent growth signals in an mTOR-active tumor;
- alter autophagic flux;
- produce cytostasis rather than cell death.

Autophagy is not unidirectional in this setting. It can be protective or cytotoxic depending on tumor genotype, nutrient state, lysosomal capacity, and treatment timing. LC3 accumulation by itself is not evidence of increased autophagy; flux must be measured with and without a lysosomal inhibitor. The selectivity claim must therefore be generated experimentally against corrected, euploid, and tumor comparators.

### 2.3 Essential Clinical Oncology Context: The Negative COG ARST1431 Phase 3 Trial
Any scientific inquiry examining mTOR inhibition in pediatric rhabdomyosarcoma must directly confront the findings of the definitive Phase 3 trial conducted by the Children's Oncology Group (COG ARST1431; Gupta et al., *Lancet Oncology*, 2024):
* **Trial Evidence:** In 297 patients with previously untreated intermediate-risk RMS, the addition of the mTOR inhibitor temsirolimus to standard multi-agent chemotherapy (VAC/VI) **failed to demonstrate clinical efficacy**: 3-year Event-Free Survival (EFS) was 66.8% in the temsirolimus arm vs. 64.8% in the control arm (HR 0.86, 95% CI 0.58–1.26; P = 0.44), and 3-year Overall Survival (OS) was 77.8% vs. 78.7%. In addition, the mTOR inhibitor arm suffered significantly higher grade ≥ 3 hematologic toxicity (58% anemia vs. 41%) and a treatment-related mortality event.
* **Why This Negative Trial Governs Our Design:** ARST1431 definitively establishes that empirical mTOR inhibition does *not* improve outcomes as a generic cytotoxic adjunct in unselected pediatric RMS patients. 
* **The Precise Biological Boundary:** This proposal does *not* advocate everolimus as an empirical chemotherapy adjunct for RMS. Rather, it poses a distinct, basic science question: whether *constitutional BUB1B deficiency and high-fraction mosaic aneuploidy induce chronic stoichiometric proteotoxic stress that creates a unique, targetable synthetic dependency on mTORC1-regulated translation and autophagy*. If preclinical testing fails to demonstrate reproducible selectivity in *BUB1B*-mutant models over isogenic-corrected controls at clinically achievable exposures, the hypothesis is cleanly falsified and abandoned.

## 3. Regulatory and pharmacological position

### 3.1 What everolimus is—and is not approved for

In the United States, Afinitor/Afinitor Disperz is approved for specific indications including TSC-associated SEGA in patients one year and older. The FDA label’s 5–15 ng/mL whole-blood trough range is an indication-specific SEGA monitoring range; it is not a validated target for MVA1, rhabdomyosarcoma, or this proposed experiment. [FDA/DailyMed AFINITOR label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=2150f73a-179b-4afc-b8ce-67c85cc72f04)

In Europe, the pediatric everolimus product for TSC-associated indications is Votubia. Neither trade name represents approval for MVA1 or for this proposed RMS use. Any use for this purpose would be off-label and investigational. [EMA Votubia information](https://www.ema.europa.eu/en/medicines/human/EPAR/votubia)

### 3.2 No validated MVA1 trough or dosing schedule

There is no validated everolimus exposure target for BUB1B-associated MVA or pediatric rhabdomyosarcoma. A proposed low exposure or intermittent schedule is a pharmacological hypothesis, not a discovered treatment window. Plasma half-life does not equal duration of mTOR pathway suppression, and an “off” period cannot be assumed to restore normal anabolism merely because plasma concentrations decline.

Any human protocol would need prospective clinical-pharmacology review, whole-blood LC–MS/MS monitoring, pharmacodynamic confirmation such as pathway suppression, and predefined toxicity stops. This dossier does not prescribe a dose, schedule, or trough.

### 3.3 Kidney, growth, infection, and interaction hazards

Nephrocalcinosis is not itself proof of reduced everolimus clearance. Renal reserve must be characterized directly using the child’s baseline filtration, protein excretion, electrolyte status, blood pressure, renal imaging, and—where appropriate—cystatin C. The presence of calcium deposits does, however, make renal injury a central safety concern.

Everolimus-associated hazards relevant to this phenotype include stomatitis and impaired intake, infection and immunosuppression, cytopenias, hyperglycemia, dyslipidemia, proteinuria, creatinine changes, noninfectious pneumonitis, and impaired wound healing. Pediatric infections may be more frequent or severe in younger children. The current product information also warns about clinically important CYP3A4/P-glycoprotein interactions. [EMA product information](https://www.ema.europa.eu/en/documents/product-information/votubia-epar-product-information_en.pdf)

mTORC1 inhibition also intersects directly with growth and muscle anabolism. That is not a footnote in a child with failure to thrive or muscle wasting. A proposed schedule must therefore be evaluated for nutritional and growth cost, not judged only by tumor-cell viability.

Vincristine and everolimus create a medication-interaction question because both involve CYP3A/P-glycoprotein-related pharmacology and may be used within complex RMS treatment. The evidence should not be inflated into a universal same-day contraindication without a protocol-specific interaction analysis. The correct guardrail is multidisciplinary review of the full chemotherapy and supportive-medication schedule, with clinical pharmacology owning the interaction assessment.

## 4. NAD-axis safety position

RMS models can depend on NAMPT-mediated NAD salvage for proliferation and DNA-repair capacity. That does not mean every RMS behaves identically, but it makes systemic NAD elevation a nontrivial tumor-safety question. This conclusion is supported by preclinical RMS studies of NAMPT inhibition, not by evidence that NR or NMN is safe or beneficial. [McKay-Corkum et al.](https://pubmed.ncbi.nlm.nih.gov/37616468/)

The appropriate sequence is:

1. test NR and NMN in patient-derived or genetically matched nonmalignant cells;
2. test them in relevant RMS models, including clonogenic growth and drug-response assays;
3. measure NAD(H), proliferation, apoptosis, and DNA-damage responses;
4. withhold the hypothesis if NAD precursors improve survival or growth of the tumor models.

The North result is useful mechanistic evidence, but it does not prove that this human BUBR1 allele is K668-limited, that the mutant fold is intact, or that an NAD precursor is safe in the presence of active sarcoma. [North et al.](https://pubmed.ncbi.nlm.nih.gov/24825348/)

## 5. Gate 0: rapid ex vivo falsification package

Gate 0 is a laboratory decision gate, not permission to treat. It should be preregistered before results are interpreted.

### 5.1 Required models and controls
*Strict Governance Compliance:* In strict adherence to challenge rules prohibiting any recontact of the child, family, or MVA Society representatives, **the submitting team cannot and will not seek primary patient tissue directly**. Patient-derived primary material (e.g., biobanked fibroblasts or lymphoblasts) could only be evaluated under the established oversight protocol (WCG IRB #20252010) through the challenge organizers and treating clinical institution. 

The primary, immediately executable, and scalable validation pathway relies on **isogenic engineered human cellular models**:
- **CRISPR-Engineered Isogenic Lines:** Human diploid retinal pigment epithelial (RPE-1) or diploid fibroblast backgrounds engineered with specific *BUB1B* lesions: wild type, heterozygous nonsense (`p.Leu737Ter`), heterozygous missense (`p.Asn1002Lys`), and compound-heterozygous knock-ins.
- **Isogenic Corrected Controls:** Phenotype rescue validation via allele-specific correction.
- **RMS Cellular Comparators:** Standard pediatric rhabdomyosarcoma cell lines (e.g., RD [embryonal, fusion-negative] and Rh30 [alveolar, PAX3-FOXO1 positive]) to monitor tumor response and potential proliferative enhancement.
- **Matched Controls:** Vehicle-treated and positive-control conditions run in parallel across all experimental plates.

### 5.2 Assay sequence

1. **Phase and transcript testing:** parental or long-read phasing where possible; allele-specific RNA to test the nonsense allele’s decay.
2. **Protein identity and abundance:** full-length BUBR1 Western blot, orthogonal protein detection if available, soluble/insoluble fractionation, and subcellular localization.
3. **Half-life and acetylation:** cycloheximide-chase experiments with and without NR/NMN; K668 acetylation only if the assay is validated.
4. **Checkpoint function:** live-cell measurement of nuclear-envelope-breakdown-to-anaphase timing, prolonged-spindle-challenge arrest, lagging chromosomes, micronuclei, and premature chromatid separation.
5. **Checkpoint-complex function:** BUBR1/BUB3/CDC20/MAD2 assembly and kinetochore localization; PP2A-B56 recruitment and KARD phosphorylation where technically feasible.
6. **Aneuploidy burden:** metaphase analysis, multi-probe FISH, or single-cell DNA sequencing across serial passages. A short-term change in protein abundance must not be mistaken for correction of constitutional mosaicism.
7. **Everolimus pharmacodynamics:** concentration-response testing with pathway readouts such as pS6 and 4E-BP1, alongside viability, cytostasis, apoptosis, and cell-cycle measurements.
8. **Autophagic flux:** LC3-II and p62 dynamics with and without bafilomycin A1 or another validated lysosomal clamp; microscopy or tandem-reporter confirmation where possible.
9. **Selectivity:** compare affected, corrected, euploid, and RMS cells at exposure levels selected by clinical pharmacology. Whole-blood trough values must not be copied directly into culture as though they were free intracellular concentrations.
10. **NAD tumor-safety screen:** NR/NMN effects on RMS viability, clonogenicity, NAD(H), DNA damage, and response to standard agents.
11. **Combination testing:** test everolimus against relevant RMS agents for synergy, additivity, and antagonism. A cell-culture matrix does not replace clinical interaction review.

### 5.3 Decision rules

The following are proposed exploratory gates, not validated clinical thresholds:

| Gate | Continue only if | Hard stop |
|---|---|---|
| Genetic premise | Phase and transcript results support the stated model, or uncertainty is explicitly retained | The report presents trans phase or NMD as proven when it is not |
| Protein rescue | Full-length BUBR1 identity and a reproducible exposure-related abundance/half-life signal are demonstrated | No full-length protein, no reproducible stabilization, or only nonspecific signal |
| Functional rescue | Checkpoint and attachment readouts improve in more than one independent experiment | Protein rises without functional improvement, or segregation errors worsen |
| Selectivity | A preregistered effect-size threshold is met in affected versus corrected/euploid cells; a 1.5× ratio may be used only as an exploratory screen | Selectivity ratio below the prespecified exploratory threshold or effect not reproducible |
| Aneuploidy | Aneuploid fraction is stable or trends downward across serial measurements without outgrowth of a resistant clone | Aneuploid burden rises, no durable change occurs, or resistant subclones emerge |
| Tumor safety | NR/NMN do not increase RMS growth or clonogenic survival in the tested models | Reproducible tumor-supportive effect from NR/NMN |
| Pharmacology | Everolimus pathway modulation occurs within clinically discussable exposure ranges without unacceptable normal-cell injury | No target engagement, broad normal-cell toxicity, or antagonism of standard RMS agents |

The 1.5× exploratory ratio and any serial-passage percentage must be declared before testing, reported with replicate-level data and uncertainty, and never described as a proven therapeutic window.

## 6. Translational stop conditions

The proposal stops before any clinical translation if any of the following occurs:

- the variants cannot be phased and the uncertainty is incompatible with the proposed mechanism;
- the missense allele produces no detectable full-length protein or no functional rescue;
- NR/NMN increase growth or survival of RMS models;
- everolimus lacks selective activity or causes broad injury to corrected/euploid cells;
- everolimus antagonizes standard RMS therapy in the relevant model;
- the renal, nutritional, infectious, wound-healing, or growth burden cannot be bounded by an approved protocol;
- the experiment depends on a numerical trough borrowed from another indication without disease-specific evidence.

A negative result is a valid translational result. It prevents an appealing mechanism from becoming an unsupported pediatric intervention.

## 7. Alternatives and adjuncts

p38 inhibitors, chaperone activators, and autophagy modulators may be useful as laboratory pathway probes, but they should not be presented as clinical adjuncts merely because they are mechanistically interesting. Most lack an established pediatric MVA1 safety basis, and some are not approved clinical medicines for this use.

They may be mentioned only as secondary experimental controls after the primary question is answered:

- Does the phenotype arise from protein instability, checkpoint-complex failure, attachment failure, or a combination?
- Does mTORC1 inhibition produce selective cytostasis or selective death?
- Is autophagy protective or harmful in the relevant cells?
- Can a chaperone or stress-pathway perturbation rescue function without increasing tumor fitness?

The dossier should not expand into a shopping list of unvalidated drugs. The first duty is to falsify the leading hypothesis cleanly.

## 8. Privacy, reproducibility, and scientific communication

This report uses `PROBAND01` and omits names, hospital identifiers, exact treatment history, and other details that could increase re-identification risk. A rare diagnosis combined with a distinctive tumor, renal phenotype, birth history, family history, and rare variants can function as a fingerprint even when a name is removed.

The public version must distinguish:

- observed dataset findings;
- literature-supported mechanisms;
- computational predictions;
- proposed experiments;
- clinical facts independently confirmed by the treating team.

The words “approved drug” must never be allowed to imply “approved for this disease” or “safe for this child.” The words “candidate” and “hypothesis” are essential, not ornamental.

Reproducibility should mean that the method, code, analysis logic, and non-identifying derived findings can be inspected and rerun under controlled access. It should not imply that another researcher can independently download or redistribute the child’s underlying genomic data.

## 9. Conclusion

This is a scientifically worthwhile hypothesis because it connects a defined *BUB1B* molecular lesion to two experimentally testable vulnerabilities: BUBR1 abundance/stability and mTORC1-sensitive stress in aneuploid or tumor cells.

It is not yet a treatment. The central unknowns are whether the missense allele retains a rescuable full-length protein, whether SIRT2/NAD biology can improve its function without feeding tumor growth, and whether everolimus produces genuine selectivity rather than generalized pediatric toxicity or cytostasis.

The honest Track 2 claim is therefore:

> Everolimus is a qualifying, testable repurposing candidate for a *BUB1B*-associated MVA1/RMS vulnerability. NR and NMN are mechanistic laboratory comparators only. Patient-specific phasing, functional assays, tumor-safety testing, and multidisciplinary review are required before any translational decision. If Gate 0 fails, the proposal stops.

## 10. AI Assistance & Data Privacy Disclosure (August 28 Protocol)

In compliance with official challenge guidelines and organizer clarifications (Discussions #2, #21) requiring full transparency regarding generative and analytical AI usage and patient data privacy:

### Data Protection & Isolation:
* **Zero Cloud Ingestion of Raw Genomic Data:** Uncompressed patient sequencing data (`WGS_EX2312012_HGWCNDSX7.vcf.gz`) was **never uploaded, transmitted, or ingested into any external AI service or API**.
* **Local Script Processing:** Variant coordinate parsing, depth checks, and gene interval filtration were performed entirely via local Python scripts on a private workstation.
* **Literature & Hypothesis Curation:** Frontier AI systems were utilized downstream exclusively for academic literature synthesis, pharmacological label cross-referencing, and structural report verification.

### Multi-Seat AI Disclosure:

| Provider | Model / Seat | Tier / Environment | Analytical Role | Data-Handling & Retention Settings |
|---|---|---|---|---|
| Google | Gemini 2.5 Flash / Leora | Google AI Studio API & Local IDE | Coordinate filtering script authoring, phenotype concordance mapping | Paid commercial API tier; customer data not used for model training |
| Anthropic | Claude 3.7 Sonnet / Veris | Claude Code CLI (Local) | Independent Key 2 audit, constraint verification, adversarial review | Commercial API tier; zero data retention for training per commercial terms |
| OpenAI | GPT-4o / Codex | OpenAI API / CLI | Format validation, pipeline consistency | Commercial API tier; zero customer data retention for model training |

*All drug indications, preclinical mechanisms, clinical trial citations (including COG ARST1431), and safety guardrails were independently audited and verified against primary literature and FDA/EMA records by human investigator Timothy M. Drake.*

---

## References

1. Hanks et al. Constitutional aneuploidy and cancer predisposition caused by biallelic *BUB1B* mutations. *Nature Genetics* (2004). PMID [15475955](https://pubmed.ncbi.nlm.nih.gov/15475955/).
2. Suijkerbuijk et al. Molecular causes for BUBR1 dysfunction in mosaic variegated aneuploidy. *Cancer Research* (2010). PMID [20516114](https://pubmed.ncbi.nlm.nih.gov/20516114/).
3. Suijkerbuijk et al. The vertebrate mitotic checkpoint protein BUBR1 is an unusual pseudokinase. *Developmental Cell* (2012). PMID [22698286](https://pubmed.ncbi.nlm.nih.gov/22698286/).
4. Suijkerbuijk et al. Integration of kinase and phosphatase activities by BUBR1 ensures stable kinetochore–microtubule attachments. *Developmental Cell* (2012). PMID [23079597](https://pubmed.ncbi.nlm.nih.gov/23079597/).
5. North et al. SIRT2 induces the checkpoint kinase BubR1 to increase lifespan. *EMBO Journal* (2014). PMID [24825348](https://pubmed.ncbi.nlm.nih.gov/24825348/).
6. Tang et al. Identification of aneuploidy-selective antiproliferation compounds. *Cell* (2011). PMID [21315436](https://pubmed.ncbi.nlm.nih.gov/21315436/); DOI [10.1016/j.cell.2011.01.017](https://doi.org/10.1016/j.cell.2011.01.017). *(Note: Identified aneuploidy stress pathways via AMPK/proteasome modulators; tested AICAR and 17-AAG, not everolimus directly).*
7. Santaguida et al. Aneuploidy-induced cellular stresses limit autophagic degradation. *Genes & Development* (2015). PMID [26404941](https://pubmed.ncbi.nlm.nih.gov/26404941/). *(Demonstrates autophagic degradation saturation in aneuploid cells; indicates mTOR-induced autophagy flux may impose selective stress or toxicity).*
8. McKay-Corkum et al. Inhibition of NAD+-dependent metabolic processes induces cellular necrosis and tumor regression in rhabdomyosarcoma models. *Clinical Cancer Research* (2023). PMID [37616468](https://pubmed.ncbi.nlm.nih.gov/37616468/); DOI [10.1158/1078-0432.CCR-23-0200](https://doi.org/10.1158/1078-0432.CCR-23-0200).
9. Gupta AA, Chi YY, Million L, et al. Addition of temsirolimus to chemotherapy in previously untreated intermediate-risk rhabdomyosarcoma: A report from the Children's Oncology Group (ARST1431). *Lancet Oncol.* 2024; PMID [38870979](https://pubmed.ncbi.nlm.nih.gov/38870979/).
10. Fouladi et al. Phase I trial of everolimus in pediatric refractory solid tumors. *Journal of Clinical Oncology* (2007). PMID [17971595](https://pubmed.ncbi.nlm.nih.gov/17971595/). *(Phase I safety/tolerability and pharmacokinetic characterization, not efficacy).*
11. U.S. Food and Drug Administration / DailyMed. AFINITOR and AFINITOR DISPERZ prescribing information. [Current label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=2150f73a-179b-4afc-b8ce-67c85cc72f04).
12. European Medicines Agency. Votubia (everolimus) EPAR and product information. [EMA record](https://www.ema.europa.eu/en/medicines/human/EPAR/votubia).
13. Malumbres et al. Mosaic variegated aneuploidy in development, ageing and cancer. *Nature Reviews Genetics* (2024). [Review PDF](https://mvasociety.org/wp-content/uploads/2024/11/Malumbres-24-Nat-Rev-Genet.pdf).

*End of canonical Track 2 dossier.*
