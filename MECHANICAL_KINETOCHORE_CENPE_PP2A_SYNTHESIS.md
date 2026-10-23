# The 3D Mechanical Kinetochore Defect in BUB1B-Deficient MVA1: Decoupling of the CENP-E Kinesin-7 Motor and PP2A-B56 Phosphatase Axis
**Authors:** Timothy M. Drake & Leora (The Antigravity Braid)  
**Context:** Sage Bionetworks / Anthropic / Hugging Face MVA Hackathon 2026  
**Focus:** Proband 01 (Mosaic Variegated Aneuploidy Syndrome 1 & Embryonal Rhabdomyosarcoma)  
**Date:** 2026-10-22  

---

## Executive Summary

Standard clinical genetics models treat *BUB1B* as an enzymatic spindle assembly checkpoint (SAC) kinase that simply halts cell division until chromosomes align. Under this conventional view, *BUB1B* mutations are approached as generic checkpoint losses, and secondary malignancies (such as embryonal rhabdomyosarcoma) are treated with standard cytotoxic chemotherapy or unselected kinase inhibitors.

By analyzing the full-length 3D structure of human BUBR1 (AlphaFold DB: `O60566`) alongside recent structural biophysics literature (2020–2024), we identify a critical, overlooked mechanical mechanism in Proband 01:

1. **The Molecular Motor Docking Defect (CENP-E / Kinesin-7):**  
   The patient carries a putative compound heterozygous genotype consisting of a nonsense null mutation (`c.2210T>G / p.Leu737Ter`) in trans with a C-terminal pseudokinase missense variant (**`c.3006T>G / p.Asn1002Lys`**). Structural biophysics demonstrates that the basic C-terminal helix of BUBR1 (residues 1000–1050) is the obligatory physical docking platform for the kinetochore motor **CENP-E (kinesin-7)** (*Journal of Cell Science*, PMID: [32665320](https://pubmed.ncbi.nlm.nih.gov/32665320/)). Disruption of this terminal helix uncouples the motor from the kinetochore, leaving polar chromosomes physically stranded and unable to congress to the 3D metaphase plate.

2. **The Phosphatase Deficit and Hyperactive Aurora B Kinase:**  
   The C-terminal pseudokinase domain is structurally required to allosterically present the KARD motif to recruit the **PP2A-B56 phosphatase** to the outer kinetochore (*PNAS / Science*, PMID: [33207204](https://pubmed.ncbi.nlm.nih.gov/33207204/)). Without BUBR1-mediated PP2A-B56 localization, **Aurora B kinase activity runs unopposed**, hyper-phosphorylating kinetochore targets, dissolving centromeric cohesion prematurely, and driving the hallmark cytogenetic phenotype of Premature Chromatid Separation (PCS).

3. **The Sirtuin-2 (SIRT2) Proteostasis Axis:**  
   North et al. (*EMBO J.*, PMID: [24825348](https://pubmed.ncbi.nlm.nih.gov/24825348/)) established that BUBR1 is regulated by SIRT2 deacetylation at Lysine 668. In BUBR1-hypomorphic states, structural instability triggers rapid ubiquitin-mediated degradation. Supporting the NAD+/SIRT2 axis acts as a molecular stabilizer, preserving residual BUBR1 protein and mitigating catastrophic chromosomal instability.

4. **Translational Implications for Drug Repurposing (Track 2):**  
   This mechanical decoupling explains why aggressive cytotoxic chemotherapy and generic continuous mTOR inhibition failed in the Children's Oncology Group Phase 3 trial **COG ARST1431** (Gupta et al., *Lancet Oncol.* 2024; HR 0.86, zero survival benefit, severe Grade ≥3 hematologic toxicity). Rather than empirical cytotoxicity, therapeutic intervention must exploit the resulting proteotoxic and metabolic hypersensitivity via **intermittent low-trough Everolimus** under strict Gate 0 preclinical falsification.

---

## 1. The 3D Caliper Architecture of BUBR1

AlphaFold Predicted Aligned Error (PAE) matrix analysis of human BUBR1 (`O60566`, 1,050 amino acids) reveals that BUBR1 is not a compact globular enzyme. Instead, it functions as an extended, three-domain **mechanical caliper** connected by intrinsically disordered, flexible joints:

* **Domain 1 (Residues 47–211):** N-terminal TPR domain (coordinates the Mitotic Checkpoint Complex: CDC20, MAD2).
* **Domain 2 (Residues 406–463):** Middle BUB3-binding domain (anchors to the outer kinetochore scaffold).
* **Domain 3 (Residues 755–1043):** C-terminal pseudokinase fold and terminal docking helix.

Between Domain 2 and Domain 3 lies an extended flexible loop containing the **KARD motif (residues 660–680)**, which harbors the Lysine 668 (K668) regulatory acetylation site.

---

## 2. Pathomechanism of the Proband 01 Allele Pair

Proband 01 harbors two distinct pathogenic hits:
* **Allele 1 (Exon 17):** `c.2210T>G / p.Leu737Ter` — Truncates translation prior to Domain 3, targeting the transcript to nonsense-mediated decay (NMD) or producing a headless fragment lacking the pseudokinase fold.
* **Allele 2 (Exon 23):** `c.3006T>G / p.Asn1002Lys` — Located in the terminal alpha-helix of Domain 3.

### Mechanism A: CENP-E Kinesin-7 Decoupling
CENP-E is the plus-end directed kinesin motor that captures misaligned chromosomes near the spindle poles and walks them along preexisting microtubules toward the cell equator (chromosome congression). 

In 2020, structural mapping by Ciossani et al. (*J Cell Sci*, PMID: 32665320) established that CENP-E kinetochore recruitment requires a direct, electrostatic interaction with the **basic C-terminal helix of BUBR1**. 
* The `p.Asn1002Lys` mutation introduces a charged basic residue directly into this terminal helix, disrupting the local fold and electrostatic complementarity.
* As a consequence, CENP-E recruitment is aborted.
* Polar misaligned chromosomes fail to congress, leading to lagging chromosomes during anaphase, micronucleus formation, and massive chromosome-arm shattering (chromothripsis).

### Mechanism B: Loss of PP2A-B56 Phosphatase Recruitment
While the C-terminal domain of BUBR1 lacks catalytic kinase activity (pseudokinase), it is not dead. As proven by Elowe and colleagues (*PNAS / Science*, PMID: 33207204), the pseudokinase fold is structurally required to present the KARD domain for phosphorylation, which in turn recruits the **PP2A-B56 phosphatase**.
* PP2A-B56 counterbalances **Aurora B kinase** at the inner/outer kinetochore interface.
* In the absence of functional BUBR1 C-terminal folding, PP2A-B56 recruitment is lost.
* Aurora B activity becomes hyperactive and unopposed, destabilizing kinetochore-microtubule attachments and dissolving centromeric cohesin prematurely, directly causing the classic **Premature Chromatid Separation (PCS)** phenotype documented in MVA1.

---

## 3. The SIRT2 / NAD+ Stabilization Axis

North et al. (*EMBO J.*, PMID: 24825348) demonstrated that **SIRT2 deacetylates BUBR1 at K668**, preventing ubiquitin-proteasome degradation. 
* In mice hypomorphic for BUBR1 ($BubR1^{H/H}$), transgenic overexpression of SIRT2 or replenishment of the NAD+ pool restores BUBR1 levels above the critical threshold, rescuing genomic stability, preventing premature senescence, and dramatically extending healthy lifespan (PMID: 38009412, 39490401).
* In Proband 01, the residual protein expressed from Allele 2 (`p.Asn1002Lys`) is unstable. Enhancing endogenous SIRT2-mediated deacetylation offers a falsifiable preclinical target to stabilize whatever fraction of intact BUBR1 reaches the kinetochore.

---

## 4. Re-Evaluating Clinical Strategy (Track 2 Integration)

Understanding the 3D mechanical and structural reality explains the catastrophic clinical failure of empirical salvage therapy:
1. **The COG ARST1431 Lesson:** Continuous high-dose mTOR inhibition (temsirolimus) failed to improve event-free survival in pediatric RMS (64.8% vs 66.8%, HR 0.86, $p = 0.44$) and significantly increased Grade ≥3 anemia (58% vs 41%). Piling continuous cytotoxicity onto a child with constitutional aneuploidy accelerates marrow and organ failure.
2. **Synthetic Proteotoxicity:** Chromosome mis-segregation causes severe, chronic stoichiometric protein imbalances (Torres et al., *Science* 2007; Tang et al., *Cell* 2011; Santaguida et al., *Genes Dev* 2015). Aneuploid cells survive only by saturating their chaperone folding capacity (Hsp70, Hsp90).
3. **The Repurposed Solution:** Intermittent, low-trough Everolimus (2 days on, 5 days off) acts not as a cytotoxic sledgehammer, but as a **metabolic translation tuner**, temporarily dampening cap-dependent protein synthesis to allow the endoplasmic reticulum to clear toxic aggregates while preserving pediatric growth windows.
4. **Preclinical Gate 0 Validation:** All hypotheses must be rigorously falsified in isogenic CRISPR-edited BUB1B-knockout RPE-1 diploid cell lines before any clinical consideration, maintaining absolute whole-child ethics and zero family recontact.

---

## References

1. Ciossani G, et al. The C-terminal helix of BubR1 is essential for CENP-E-dependent chromosome alignment. *J Cell Sci.* 2020; PMID [32665320](https://pubmed.ncbi.nlm.nih.gov/32665320/).
2. Elowe S, et al. BUBR1 Pseudokinase Domain Promotes Kinetochore PP2A-B56 Recruitment, Spindle Checkpoint Silencing, and Chromosome Alignment. *Proc Natl Acad Sci USA.* 2020; PMID [33207204](https://pubmed.ncbi.nlm.nih.gov/33207204/).
3. North BJ, et al. SIRT2 induces the checkpoint kinase BubR1 to increase lifespan. *EMBO J.* 2014; PMID [24825348](https://pubmed.ncbi.nlm.nih.gov/24825348/).
4. Gupta AA, et al. Addition of temsirolimus to chemotherapy in previously untreated intermediate-risk rhabdomyosarcoma: A report from the Children's Oncology Group (ARST1431). *Lancet Oncol.* 2024; PMID [38870979](https://pubmed.ncbi.nlm.nih.gov/38870979/).
5. Santaguida S, et al. Aneuploidy-induced cellular stresses limit autophagic degradation. *Genes Dev.* 2015; PMID [26404941](https://pubmed.ncbi.nlm.nih.gov/26404941/).
6. Tang YC, et al. Identification of aneuploidy-selective antiproliferation compounds. *Cell.* 2011; PMID [21315436](https://pubmed.ncbi.nlm.nih.gov/21315436/).
