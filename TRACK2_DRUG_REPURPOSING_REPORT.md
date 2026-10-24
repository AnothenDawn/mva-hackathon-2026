# Track 2 Drug-Repurposing Dossier (v5 Final Audited Consensus)
## A Falsifiable Preclinical Investigation of Everolimus for a Possible mTORC1-Linked Vulnerability in BUB1B-Associated MVA1

- **Challenge:** Rare Disease, Real Kid: MVA Hackathon 2026, Track 2
- **Proband:** PROBAND01
- **Working Diagnosis:** Mosaic variegated aneuploidy syndrome 1 (MVA1; OMIM #257300)
- **Working Genetic Model:** A candidate compound-heterozygous *BUB1B* pair, p.Leu737Ter and p.Asn1002Lys, that matched the Track 1 answer key; phase unconfirmed
- **Submission Type:** Preclinical drug-repurposing hypothesis and validation plan
- **Status:** Basic science hypothesis only; not clinical advice and not a treatment protocol

---

### Safety and Scope Statement
This dossier does not recommend administering everolimus, NR, NMN, or any other agent to the proband. It does not establish efficacy, safety, dose, or clinical benefit. Any human use would require the treating pediatric oncology, clinical pharmacology, nephrology, genetics, and research-ethics teams to make an independent decision under an approved protocol.

---

## Executive Summary

MVA1 is a rare chromosome-segregation disorder associated with pathogenic disruption of *BUB1B*, which encodes the spindle-assembly-checkpoint protein BUBR1. BUBR1 participates in the mitotic checkpoint complex (MCC) and in the stabilization of kinetochore–microtubule attachments. Constitutional mosaic aneuploidy and cancer susceptibility are established features of the *BUB1B*-associated MVA spectrum, although phenotype, mosaic fraction, and tumor risk vary between individuals. Childhood embryonal rhabdomyosarcoma and Wilms tumor are among the reported malignancies (Malumbres et al., 2024; PMID: 39169218).

The proband's two heterozygous short-read calls are consistent with a biallelic *BUB1B* model, but short-read calls from a proband alone do not prove that the variants are in *trans*. The genetic description therefore remains **candidate compound heterozygous, phase unconfirmed** until parental testing or long-read phasing is available. The premature-stop allele is predicted to undergo nonsense-mediated decay; that prediction requires allele-specific RNA confirmation. The C-terminal missense allele lies within the BUBR1 kinase/pseudokinase region, but the molecular effect of this exact substitution is not yet established.

The qualifying repurposing candidate is **everolimus**, an mTORC1 inhibitor with pediatric approval in specific tuberous-sclerosis-associated indications (TSC/SEGA). The proposal is not that everolimus cures MVA1. It is that *BUB1B*-defective or aneuploid cells may show a context-dependent vulnerability to mTORC1 inhibition that can be tested against corrected and euploid comparators. The direction of that effect is not known in advance: mTORC1 inhibition could expose a selective vulnerability, or it could harm normal tissue, and the preclinical gate is designed to decide which.

NR and NMN are retained **strictly as laboratory mechanistic comparators**. They are not presented as a pediatric treatment prong, because NAD salvage can support tumor metabolism and DNA-repair capacity in relevant RMS models.

The decisive feature of this proposal is an **unconditional preclinical kill switch**: if the proposed molecular rescue or tumor selectivity is not demonstrated reproducibly, the hypothesis stops.

---

## Challenge Specification Summary: Mechanism Characterization

- **Variant Characterization:** Loss of function. One putative null allele (p.Leu737Ter, exon 17 of 23, expected to trigger nonsense-mediated decay) and one C-terminal missense allele (p.Asn1002Lys) of uncertain significance, with phase unconfirmed.
- **Biological Pathway:** Spindle assembly checkpoint (SAC) and mitotic checkpoint complex (MCC), plus BUBR1's KARD/PP2A-B56 control of kinetochore attachment and its C-terminal role in CENP-E-dependent chromosome alignment.
- **Consequence:** Chromosome mis-segregation, then mosaic variegated aneuploidy, then growth restriction and cancer predisposition. Critical nuance: as emphasized by Malumbres and colleagues (2024), aneuploidy creates cellular stress and chromosomal instability but is not by itself sufficient for malignant transformation; cooperating somatic alterations and microenvironmental selection drive oncogenesis.

---

## 1. Clinical and Genetic Premise

### 1.1 What MVA1 Establishes, and What It Does Not
The spindle assembly checkpoint delays anaphase until chromosome–spindle attachments are sufficiently correct. BUBR1 is a core component of the mitotic checkpoint complex and also participates in the regulation of stable kinetochore–microtubule attachments. Loss of checkpoint fidelity can generate mosaic chromosome-number abnormalities in multiple tissues.

The correct translational statement is not that every dividing cell will continuously become aneuploid. Mosaic fractions are tissue-specific, dynamic, and subject to selection. The correct statement is that a constitutional *BUB1B* defect creates a persistent biological substrate for chromosome-segregation error and justifies specialist surveillance and functional investigation.

No disease-modifying therapy for the constitutional defect is established. Cancer management remains ordinary specialist oncology care for the tumor actually present, together with syndrome-informed surveillance. Published MVA guidance emphasizes awareness of embryonal malignancies and renal ultrasound surveillance; the MVA Society describes renal ultrasonography every three to four months until age five for individuals with cytogenetic confirmation and/or demonstrated *BUB1B* mutations. Modality, interval, and duration must be individualized by the treating team (MVA Society surveillance information).

### 1.2 Variant Interpretation and Phasing
The working pair is:
- **p.Leu737Ter:** a premature termination variant upstream of the C-terminal fold. Nonsense-mediated decay is plausible but must be measured with allele-specific RNA.
- **p.Asn1002Lys:** a missense variant within the C-terminal BUBR1 kinase/pseudokinase region, classified here as a variant of uncertain significance. The residue's location makes a structural or stability defect plausible, but does not prove one.

Two heterozygous variants in one proband are not equivalent to a proven *trans* configuration. Matching the Track 1 answer key confirms which variants were identified; it does not establish phase.

### 1.3 BUBR1 Is Not a Simple Kinase Engine
BUBR1 contains N-terminal interaction modules involved in checkpoint-complex assembly, a KARD region involved in PP2A-B56 recruitment and attachment control, and a C-terminal kinase-like fold. Human BUBR1 retains some catalytic-sequence features but functions principally as an unusual pseudokinase/scaffold in the established human-cell model (Suijkerbuijk et al., 2012a). Putative catalysis is not the same as a missing ATP-driven engine.

The C-terminal region is nevertheless important. Published MVA work found that kinase-domain-localized MVA mutations can reduce overall BUBR1 abundance, while other alleles cause more specific checkpoint or attachment defects (Suijkerbuijk et al., 2010; Suijkerbuijk et al., 2012b). Those findings concern other MVA alleles and are not assumed to generalize to p.Asn1002Lys.

Two further published mechanisms involve this region:
- The C-terminal helix of BUBR1 is essential for CENP-E-dependent chromosome alignment (Legal et al., 2020; PMID: 32665320).
- The BUBR1 pseudokinase domain promotes kinetochore PP2A-B56 recruitment, spindle-checkpoint silencing, and chromosome alignment (Gama-Braga et al., 2020; PMID: 33207204).

Whether p.Asn1002Lys may disrupt CENP-E docking or PP2A-B56 recruitment is a hypothesis to be tested in Gate 0, not an established finding.

---

## 2. Biological Hypothesis

### 2.1 Prong 1: Protein-Stability Biology, Not "Checkpoint Supercharging"
North et al. reported that SIRT2-mediated deacetylation of BUBR1 at K668 opposed acetylation-associated degradation in a mouse aging model, and that NMN increased BUBR1 abundance in that experimental context (North et al., 2014; PMID: 24825348).

That result supplies a testable mechanism:
- SIRT2 activity may alter the abundance or half-life of some full-length BUBR1 molecules.
- A larger pool of correctly folded BUBR1 might improve checkpoint performance if abundance is the limiting lesion.
- The mechanism should fail if the missense protein is too unstable, mislocalized, unable to assemble the checkpoint complex, or unable to support attachment regulation.

The critical structural objection is that K668 lies in the upstream KARD neighborhood, whereas p.Asn1002Lys lies in the C-terminal region. Deacetylating K668 cannot be assumed to repair a structural defect in a distant domain. Rescue requires the molecule to remain full-length, sufficiently folded, correctly localized, and competent for its relevant interactions.

NR/NMN therefore belong first in an assay, not in a child's medication list. A positive result must include increased full-length protein, an interpretable half-life change, and functional improvement, not merely a change in total NAD or a Western-blot band of uncertain identity.

### 2.2 Prong 2: mTORC1 Inhibition as a Conditional Aneuploid-Cell Vulnerability
The rationale runs through a chain of published work, each link with its own limits:
1. Biallelic *BUB1B* mutations cause constitutional aneuploidy and cancer predisposition (Hanks et al., 2004), and MVA alleles impair BUBR1 by distinct mechanisms (Suijkerbuijk et al., 2010).
2. Aneuploidy imposes stoichiometric protein imbalance and proteotoxic stress, first shown in yeast (Torres et al., 2007), and aneuploidy-induced stresses limit autophagic degradation in mammalian cells (Santaguida et al., 2015).
3. Aneuploid cells can be selectively targeted: the energy-stress agent AICAR, the protein-folding inhibitor 17-AAG, and the autophagy inhibitor chloroquine each showed aneuploidy-selective activity (Tang et al., 2011). Tang et al. did not test everolimus or any rapalog; the link to mTORC1 is indirect, through AMPK signalling downstream of AICAR.
4. In rhabdomyosarcoma, adding the rapalog temsirolimus to chemotherapy did not improve event-free survival (COG ARST1431; Section 2.3). This narrows the question to selectivity for aneuploid cells, not general antitumor activity.
5. Gate 0 tests that narrower question in isogenic *BUB1B* RPE-1 models, with predefined stop rules (Section 5).

**Direction of Effect:** mTORC1 inhibition increases autophagic flux. Because chloroquine, which blocks autophagy, was selectively toxic to aneuploid cells in Tang et al., and because Santaguida et al. found autophagic degradation impaired under aneuploidy-induced proteotoxic stress in mammalian cells, increasing autophagic flux could either impose a selective stress on aneuploid cells or relieve it and harm normal tissue instead. This dossier does not assume the direction; Gate 0 decides it.

Everolimus may:
- reduce cap-dependent translation and anabolic load;
- inhibit mTORC1-dependent growth signals in an mTOR-active tumor;
- alter autophagic flux;
- produce cytostasis rather than cell death.

Autophagy is not unidirectional in this setting. It can be protective or cytotoxic depending on tumor genotype, nutrient state, lysosomal capacity, and treatment timing. LC3 accumulation by itself is not evidence of increased autophagy; flux must be measured with and without a lysosomal inhibitor. The selectivity claim must therefore be generated experimentally against corrected, euploid, and tumor comparators.

### 2.3 Essential Clinical Oncology Context: The Negative COG ARST1431 Phase 3 Trial
Any inquiry into mTOR inhibition in pediatric rhabdomyosarcoma must confront the Children's Oncology Group phase 3 trial ARST1431 (Gupta et al., *Lancet Oncology*, 2024; PMID: 38936378):
- **Trial Evidence:** In 297 evaluable patients with previously untreated intermediate-risk RMS, adding the mTOR inhibitor temsirolimus to VAC/VI chemotherapy did not improve outcomes. Three-year event-free survival was 66.8% (95% CI 57.5–76.2) with temsirolimus versus 64.8% (95% CI 55.5–74.1) without it (Hazard Ratio 0.86, 95% CI 0.58–1.26; log-rank $p = 0.44$). Grade 3–4 anemia occurred in 58% of patients in the temsirolimus arm versus 41% in the control arm, and there was one treatment-related death in the temsirolimus arm.
- **Why this negative trial shapes our design:** ARST1431 indicates that adding an mTOR inhibitor to chemotherapy does not improve outcomes in unselected intermediate-risk RMS. It tested temsirolimus, not everolimus, so it is cited as evidence about the drug class.
- **The precise biological boundary:** This proposal does not advocate everolimus as a chemotherapy adjunct for RMS. It asks a narrower basic-science question: whether constitutional *BUB1B* deficiency and mosaic aneuploidy create a selective dependency on mTORC1-regulated translation and autophagy. If preclinical testing fails to show reproducible selectivity in *BUB1B*-mutant models over isogenic-corrected controls, the hypothesis is falsified and abandoned.

---

## 3. Regulatory and Pharmacological Position

### 3.1 What Everolimus Is, and Is Not, Approved For
- In the United States, Afinitor/Afinitor Disperz is approved for specific indications including TSC-associated SEGA in patients one year and older. The label's trough monitoring range is specific to that indication; it is not a validated target for MVA1, rhabdomyosarcoma, or this proposed experiment (FDA/DailyMed AFINITOR label).
- In Europe, the pediatric everolimus product for TSC-associated indications is Votubia. Neither trade name represents approval for MVA1 or for this proposed RMS use. Any use for this purpose would be off-label and investigational (EMA Votubia information).

### 3.2 No Validated MVA1 Exposure Target
There is no validated everolimus exposure target for *BUB1B*-associated MVA or pediatric rhabdomyosarcoma, and this dossier proposes none. Plasma half-life does not equal duration of mTOR pathway suppression.

Any human protocol would need prospective clinical-pharmacology review, whole-blood LC–MS/MS monitoring, pharmacodynamic confirmation such as pathway suppression, and predefined toxicity stops. This dossier does not prescribe a dose, schedule, or trough.

### 3.3 Kidney, Growth, Infection, and Interaction Hazards
- **Nephrocalcinosis:** Nephrocalcinosis is not itself proof of reduced everolimus clearance. Renal reserve must be characterized directly by the treating team. The presence of calcium deposits does, however, make renal injury a central safety concern.
- **Pediatric Hazards:** Everolimus-associated hazards relevant to this phenotype include stomatitis and impaired intake, infection and immunosuppression, cytopenias, hyperglycemia, dyslipidemia, proteinuria, creatinine changes, noninfectious pneumonitis, and impaired wound healing. Pediatric infections may be more frequent or severe in younger children. The current product information also warns about clinically important CYP3A4/P-glycoprotein interactions (EMA product information).
- **Growth and Anabolism:** mTORC1 inhibition also intersects directly with growth and muscle anabolism. That is not a footnote in a child with growth restriction. Any proposal must therefore be evaluated for nutritional and growth cost, not judged only by tumor-cell viability.
- **Drug Interactions:** Vincristine and everolimus raise a medication-interaction question because both involve CYP3A/P-glycoprotein-related pharmacology and may be used within complex RMS treatment. The correct guardrail is multidisciplinary review of the full chemotherapy and supportive-medication schedule, with clinical pharmacology owning the interaction assessment.

---

## 4. NAD-Axis Safety Position in Rhabdomyosarcoma

RMS models can depend on NAMPT-mediated NAD salvage for proliferation and DNA-repair capacity. That does not mean every RMS behaves identically, but it makes systemic NAD elevation a nontrivial tumor-safety question. This conclusion is supported by preclinical RMS studies of NAMPT inhibition, not by evidence that NR or NMN is safe or beneficial (McKay-Corkum et al., 2023; PMID: 37616468).

The appropriate sequence is:
1. test NR and NMN in isogenic engineered nonmalignant cells (patient-derived material only through the challenge organisers and treating team under approved institutional oversight (WCG IRB #20252010));
2. test them in relevant RMS models, including clonogenic growth and drug-response assays;
3. measure NAD(H), proliferation, apoptosis, and DNA-damage responses;
4. withhold the hypothesis if NAD precursors improve survival or growth of the tumor models.

The North result is useful mechanistic evidence, but it does not prove that this human BUBR1 allele is K668-limited, that the mutant fold is intact, or that an NAD precursor is safe in the presence of rhabdomyosarcoma (North et al., 2014).

---

## 5. Gate 0: Rapid Ex Vivo Falsification Package

Gate 0 is a laboratory decision gate, not permission to treat. It should be preregistered before results are interpreted.

### 5.1 Required Models and Controls
- **Governance:** Challenge rules prohibit any contact with the participant, the family, or MVA Society representatives, so the submitting team cannot and will not seek primary patient tissue directly. Patient-derived material could only be evaluated through the challenge organisers and the treating team under the study's oversight protocol (WCG IRB #20252010).
- **Primary Scalable Models:** The primary, immediately executable, and scalable validation pathway uses isogenic engineered human cell models:
  - **CRISPR-engineered isogenic lines:** diploid RPE-1 or diploid fibroblast backgrounds engineered with specific *BUB1B* lesions: wild type, heterozygous nonsense (p.Leu737Ter), heterozygous missense (p.Asn1002Lys), and compound-heterozygous knock-ins.
  - **Isogenic corrected controls:** phenotype rescue validation via allele-specific correction.
  - **RMS cellular comparators:** standard pediatric rhabdomyosarcoma cell lines (for example RD [embryonal, fusion-negative] and Rh30 [alveolar, PAX3-FOXO1 positive]) to monitor tumor response and potential proliferative enhancement.
  - **Matched controls:** vehicle-treated and positive-control conditions run in parallel across all experimental plates.

### 5.2 Assay Sequence
1. **Phase and transcript testing:** parental or long-read phasing where available through the organisers; allele-specific RNA to test the nonsense allele's decay.
2. **Protein identity and abundance:** full-length BUBR1 Western blot, orthogonal protein detection if available, soluble/insoluble fractionation, and subcellular localization.
3. **Half-life and acetylation:** cycloheximide-chase experiments with and without NR/NMN; K668 acetylation only if the assay is validated.
4. **Checkpoint function:** live-cell measurement of nuclear-envelope-breakdown-to-anaphase timing, prolonged-spindle-challenge arrest, lagging chromosomes, micronuclei, and premature chromatid separation.
5. **Checkpoint-complex and kinetochore function:** BUBR1/BUB3/CDC20/MAD2 assembly and kinetochore localization; PP2A-B56 recruitment, KARD phosphorylation, and CENP-E-dependent chromosome alignment where technically feasible.
6. **Aneuploidy burden:** metaphase analysis, multi-probe FISH, or single-cell DNA sequencing across serial passages. A short-term change in protein abundance must not be mistaken for correction of constitutional mosaicism.
7. **Everolimus pharmacodynamics:** concentration-response testing with pathway readouts such as pS6 and 4E-BP1, alongside viability, cytostasis, apoptosis, and cell-cycle measurements.
8. **Autophagic flux:** LC3-II and p62 dynamics with and without bafilomycin A1 or another validated lysosomal clamp; microscopy or tandem-reporter confirmation where possible.
9. **Selectivity:** compare affected, corrected, euploid, and RMS cells across a concentration range chosen with clinical pharmacology input. Whole-blood trough values must not be copied directly into culture as though they were free intracellular concentrations.
10. **NAD tumor-safety screen:** NR/NMN effects on RMS viability, clonogenicity, NAD(H), DNA damage, and response to standard agents.
11. **Combination testing:** test everolimus against relevant RMS agents for synergy, additivity, and antagonism. A cell-culture matrix does not replace clinical interaction review.

### 5.3 Decision Rules

| Gate | Continue Only If | Hard Stop |
|---|---|---|
| **Genetic Premise** | Phase and transcript results support the stated model, or uncertainty is explicitly retained | Phase or transcript results contradict the stated model |
| **Protein Rescue** | Full-length BUBR1 identity and a reproducible exposure-related abundance/half-life signal are demonstrated | No full-length protein, no reproducible stabilization, or only nonspecific signal |
| **Functional Rescue** | Checkpoint and attachment readouts improve in more than one independent experiment | Protein rises without functional improvement, or segregation errors worsen |
| **Selectivity** | A preregistered effect-size threshold is met in affected versus corrected/euploid cells; a 1.5× ratio may be used only as an exploratory screen | Selectivity ratio below the prespecified exploratory threshold, effect not reproducible, or greater harm to euploid than to affected cells |
| **Aneuploidy** | Aneuploid fraction is stable or trends downward across serial measurements without outgrowth of a resistant clone | Aneuploid burden rises, no durable change occurs, or resistant subclones emerge |
| **Tumor Safety** | NR/NMN do not increase RMS growth or clonogenic survival in the tested models | Reproducible tumor-supportive effect from NR/NMN |
| **Pharmacology** | Everolimus pathway modulation occurs without unacceptable normal-cell injury | No target engagement, broad normal-cell toxicity, or antagonism of standard RMS agents |

The 1.5× exploratory ratio and any serial-passage percentage must be declared before testing, reported with replicate-level data and uncertainty, and never described as a proven therapeutic window.

---

## 6. Translational Stop Conditions

The proposal stops before any clinical translation if any of the following occurs:
1. the variants cannot be phased and the uncertainty is incompatible with the proposed mechanism;
2. the missense allele produces no detectable full-length protein or no functional rescue;
3. NR/NMN increase growth or survival of RMS models;
4. everolimus lacks selective activity or causes broad injury to corrected/euploid cells;
5. everolimus antagonizes standard RMS therapy in the relevant model;
6. the renal, nutritional, infectious, wound-healing, or growth burden cannot be bounded by an approved protocol;
7. the experiment depends on a numerical exposure target borrowed from another indication without disease-specific evidence.

A negative result is a valid translational result. It prevents an appealing mechanism from becoming an unsupported pediatric intervention.

---

## 7. Alternatives and Adjuncts

p38 inhibitors, chaperone activators, and autophagy modulators may be useful as laboratory pathway probes, but they should not be presented as clinical adjuncts merely because they are mechanistically interesting. Most lack an established pediatric MVA1 safety basis, and some are not approved clinical medicines for this use.

They may be mentioned only as secondary experimental controls after the primary question is answered:
- Does the phenotype arise from protein instability, checkpoint-complex failure, attachment failure, or a combination?
- Does mTORC1 inhibition produce selective cytostasis or selective death?
- Is autophagy protective or harmful in the relevant cells?
- Can a chaperone or stress-pathway perturbation rescue function without increasing tumor fitness?

The dossier should not expand into a list of unvalidated drugs. The first duty is to falsify the leading hypothesis cleanly.

---

## 8. Privacy, Reproducibility, and Scientific Communication

This report uses **PROBAND01** and omits names, hospital identifiers, exact treatment history, and other details that could increase re-identification risk. A rare diagnosis combined with a distinctive tumor, renal phenotype, birth history, family history, and rare variants can function as a fingerprint even when a name is removed.

The public version must distinguish:
- observed dataset findings;
- literature-supported mechanisms;
- computational predictions;
- proposed experiments;
- clinical facts independently confirmed by the treating team.

No public material may present *trans* phase or nonsense-mediated decay as proven unless phasing and allele-specific RNA data establish them.

The words "approved drug" must never be allowed to imply "approved for this disease" or "safe for this child." The words "candidate" and "hypothesis" are essential, not ornamental.

Reproducibility should mean that the method, code, analysis logic, and non-identifying derived findings can be inspected and rerun under controlled access. It should not imply that another researcher can independently download or redistribute the child's underlying genomic data.

---

## 9. Conclusion

This is a scientifically worthwhile hypothesis because it connects a defined *BUB1B* molecular lesion to two experimentally testable vulnerabilities: BUBR1 abundance/stability and mTORC1-sensitive stress in aneuploid or tumor cells. It is not yet a treatment.

The central unknowns are whether the missense allele retains a rescuable full-length protein, whether SIRT2/NAD biology can improve its function without feeding tumor growth, and whether everolimus produces genuine selectivity rather than generalized pediatric toxicity or cytostasis.

The honest Track 2 claim is therefore:
> Everolimus is a qualifying, testable repurposing candidate for a *BUB1B*-associated MVA1/RMS vulnerability. NR and NMN are mechanistic laboratory comparators only. Phasing, functional assays, tumor-safety testing, and multidisciplinary review are required before any translational decision. If Gate 0 fails, the proposal stops.

---

## 10. AI Assistance, Collaboration, and Data Privacy Disclosure

Per the organisers' clarifications (Discussions #2 and #21, update of 28 August 2026), each human contributor and AI used is listed below with its provider, plan or tier, and data-handling setting.

### Data Protection & Medical Privacy
- **Raw Genomic Data Protection:** No raw patient whole-exome or whole-genome sequencing files (e.g., FASTQ, BAM, VCF) were uploaded to or processed by any commercial cloud AI service or API. Variant parsing, depth filtering, and gene-interval extraction were performed entirely with local Python scripts on a private workstation.
- **Variant Source & Text Input:** No raw VCF records were given to any AI system in the sessions we can verify. AI systems saw variant identities and coordinates only as text strings provided in prompts or discussion, derived locally by our Track 1 pipeline from the sequencing data provided under the challenge Data Use Agreement. No AI system saw the patient clinical chart itself.
- **Model Training Opt-Out:** Data sharing and model training were explicitly set to **OFF** across all AI accounts in all instances. No user conversations were shared with third parties or used for provider model training.
- **Evaluation Feedback:** No AI outputs generated during this hackathon work were rated or submitted as model training feedback.

### Team and AI Collaborator Disclosure

| Collaborator / Team Member | Role | Provider / Model | Plan or Tier | Data-Handling / Model Training Setting |
|---|---|---|---|---|
| **Timothy M. Drake** | Principal Investigator (Human Author) | N/A | N/A | N/A — Reviewed all drug indications, mechanisms, trial citations, and safety boundaries. |
| **Angela Snider** | Team Member | Meta (Muse app) | Personal account | **OFF** (Opted out / disabled) — Boundary review and voiceover mechanism-sentence review. |
| **Veris** | Independent Key 2 Auditor & Adversarial Reviewer | Anthropic Claude (Cowork mode on claude.ai) | Claude Pro (personal) | **OFF** (Model-training opt-out enabled) — Line-by-line adversarial audit, citation verification, and boundary enforcement. |
| **Grok Bot** | Rules Check, Trial Citation Verification, Scientific Council | xAI Grok Bot (`grok.com`) | Personal paid tier | **OFF** (Model-training opt-out enabled) — Rules check, PubMed citation verification, and report edits. |
| **Leora** | Literature Synthesis, Script Authoring, Integration | Google Gemini (Gemini app; AI Studio API / IDE) | Google AI Pro (personal); AI Studio paid tier | **OFF** (Gemini app training opt-out enabled; paid API tier not used for training) — Biological pathway synthesis, pipeline scripts, dossier assembly. |
| **Codex** | Format and Pipeline Validation, Citation Auditing | OpenAI Codex / ChatGPT | ChatGPT Plus (personal) | **OFF** (Model-training opt-out enabled) — Format and pipeline validation, citation checks. Earlier Codex sessions are not individually certified. |
| **ChatGPT** | Scientific Scrutiny and Claim Review | OpenAI ChatGPT | ChatGPT Plus (personal) | **OFF** (Model-training opt-out enabled) — Scientific scrutiny and claim review. |

*AI collaborators are disclosed here transparently and are not listed as authors. The human investigator, Timothy M. Drake, reviewed all drug indications, mechanisms, trial citations, and safety guardrails.*

---

## References

1. **Hanks S, et al.** Constitutional aneuploidy and cancer predisposition caused by biallelic *BUB1B* mutations. *Nature Genetics* (2004) 36(11):1159–1161. PMID: [15475955](https://pubmed.ncbi.nlm.nih.gov/15475955/).
2. **Suijkerbuijk SJ, et al.** Molecular causes for BUBR1 dysfunction in the human cancer predisposition syndrome mosaic variegated aneuploidy. *Cancer Research* (2010) 70(12):4891–4900. PMID: [20516114](https://pubmed.ncbi.nlm.nih.gov/20516114/).
3. **Suijkerbuijk SJ, et al.** The vertebrate mitotic checkpoint protein BUBR1 is an unusual pseudokinase. *Developmental Cell* (2012a) 22(6):1321–1329. PMID: [22698286](https://pubmed.ncbi.nlm.nih.gov/22698286/).
4. **Suijkerbuijk SJ, et al.** Integration of kinase and phosphatase activities by BUBR1 ensures stable kinetochore–microtubule attachments. *Developmental Cell* (2012b) 23(4):745–755. PMID: [23079597](https://pubmed.ncbi.nlm.nih.gov/23079597/).
5. **North BJ, et al.** SIRT2 induces the checkpoint kinase BubR1 to increase lifespan. *EMBO Journal* (2014) 33(13):1438–1453. PMID: [24825348](https://pubmed.ncbi.nlm.nih.gov/24825348/).
6. **Tang YC, Williams BR, Siegel JJ, Amon A.** Identification of aneuploidy-selective antiproliferation compounds. *Cell* (2011) 144(4):499–512. PMID: [21315436](https://pubmed.ncbi.nlm.nih.gov/21315436/).
7. **Santaguida S, et al.** Aneuploidy-induced cellular stresses limit autophagic degradation. *Genes & Development* (2015) 29(19):2010–2021. PMID: [26404941](https://pubmed.ncbi.nlm.nih.gov/26404941/).
8. **McKay-Corkum G, et al.** Inhibition of NAD+-dependent metabolic processes induces cellular necrosis and tumor regression in rhabdomyosarcoma models. *Clinical Cancer Research* (2023) 29(21):4479–4491. PMID: [37616468](https://pubmed.ncbi.nlm.nih.gov/37616468/).
9. **Gupta AA, Xue W, Harrison DJ, et al.** Addition of temsirolimus to chemotherapy in children, adolescents, and young adults with intermediate-risk rhabdomyosarcoma (ARST1431): a randomised, open-label, phase 3 trial from the Children's Oncology Group. *Lancet Oncology* (2024) 25(7):912–921. PMID: [38936378](https://pubmed.ncbi.nlm.nih.gov/38936378/).
10. **Fouladi M, et al.** Phase I study of everolimus in pediatric patients with refractory solid tumors. *Journal of Clinical Oncology* (2007) 25(30):4806–4812. PMID: [17947729](https://pubmed.ncbi.nlm.nih.gov/17947729/).
11. **Legal T, et al.** The C-terminal helix of BubR1 is essential for CENP-E-dependent chromosome alignment. *Journal of Cell Science* (2020) 133(16):jcs246025. PMID: [32665320](https://pubmed.ncbi.nlm.nih.gov/32665320/).
12. **Gama-Braga L, et al.** BUBR1 pseudokinase domain promotes kinetochore PP2A-B56 recruitment, spindle checkpoint silencing, and chromosome alignment. *Cell Reports* (2020) 33(7):108397. PMID: [33207204](https://pubmed.ncbi.nlm.nih.gov/33207204/).
13. **Malumbres M, et al.** Mosaic variegated aneuploidy in development, ageing and cancer. *Nature Reviews Genetics* (2024) 25(12):864–878. PMID: [39169218](https://pubmed.ncbi.nlm.nih.gov/39169218/).
14. **Torres EM, et al.** Effects of aneuploidy on cellular physiology and cell division in haploid yeast. *Science* (2007) 317(5840):916–924. PMID: [17702937](https://pubmed.ncbi.nlm.nih.gov/17702937/).
15. **U.S. Food and Drug Administration / DailyMed.** AFINITOR and AFINITOR DISPERZ (everolimus) prescribing information. Current FDA label.
16. **European Medicines Agency.** Votubia (everolimus) EPAR and product information. EMA record.

---
*End of Track 2 Dossier, Version 5 (Audited Final Consensus).*
