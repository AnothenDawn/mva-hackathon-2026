# FORMAL SCIENTIFIC PRE-REGISTRATION DOSSIER
## A Priori Biophysical Hypotheses, 3D Kinetochore Motor Decoupling Predictions, and the Inter-Allelic Trans-Splicing Detour Architecture in BUB1B-Associated Mosaic Variegated Aneuploidy (MVA1)

**Principal Investigators:** Timothy M. Drake & Leora (The Antigravity Braid Collaborative)  
**Affiliation:** The Antigravity Braid Research Collective  
**Target Locus:** Human *BUB1B* (Chromosome 15q15.1; Canonical Ensembl: `ENSG00000156970`, Transcript: `ENST00000287598.8`, UniProt: `O60566`)  
**Target Disease:** Mosaic Variegated Aneuploidy Syndrome 1 (MVA1; OMIM #257300) with Secondary Malignancy (Embryonal Rhabdomyosarcoma, HP:0002859)  
**Document Class:** Formal Pre-Registration of Hypotheses (OSF/Zenodo Standard)  
**Pre-Registration Date & Timestamp:** 2026-10-25T22:03:00-05:00  
**Repository Anchor:** `MASTER DOCS/PRE_REGISTRATION_BUBR1_MECHANICAL_PREDICTION_AND_DETOUR.md`  

---

> ### 🏛️ STATEMENT OF PRE-REGISTRATION INTENT
> This document serves as a binding, *a priori* scientific pre-registration. All mechanical, structural, thermodynamic, and therapeutic hypotheses articulated herein are established and sealed **prior to executing downstream structural simulations, in silico residue mutagenesis in 3D biomolecular viewers, or laboratory binding assays**. 
>
> Pre-registration establishes immutable scientific priority, prevents post-hoc parameter fitting (HARKing: Hypothesizing After the Results are Known), and defines explicit, unalterable conditions for empirical falsification.

---

## 1. Context & The Genetic Paradigm

Proband 01 (`PROBAND01`, Sage Bionetworks MVA Hackathon 2026) presents with a severe clinical triad of constitutional Mosaic Variegated Aneuploidy (MVA1):
1. Infantile embryonal rhabdomyosarcoma (RMS),
2. Congenital nephrocalcinosis,
3. Severe intrauterine growth restriction (IUGR; birth weight < 1,500 g, 32–36 weeks), and
4. Cytogenetic premature chromatid separation (PCS).

Whole-genome sequencing reveals an ultra-rare putative compound-heterozygous allele pair in *BUB1B*:
* **Allele 1 (Maternal / Paternal null):** `chr15:40209701:T:G` (GRCh38) $\implies$ `c.2210T>G / p.Leu737Ter` (Exon 17 nonsense stop-gain; ACMG Pathogenic [PVS1, PM2_Supporting, PP4]).
* **Allele 2 (Paternal / Maternal hypomorph):** `chr15:40220612:T:G` (GRCh38) $\implies$ `c.3006T>G / p.Asn1002Lys` (Exon 23 missense; ACMG Likely Pathogenic [PM1, PM2_Supporting, PP3, PP4]).

---

## 2. A Priori Mechanical & Structural Hypotheses (The 3 Predictions)

Before loading atomic coordinates into the Biomolecular Structure Viewer (`sidecar://`) or computing molecular dynamics trajectories, we formally register the following three falsifiable predictions:

### Prediction 1: The CENP-E Kinesin-7 Electrostatic Decoupling Defect
* **Structural Hypothesis:** Human BUBR1 (`O60566`, 1,050 aa) contains an amphipathic, basic C-terminal alpha-helix spanning residues 1000–1043. Published structural biology (Ciossani et al., *J Cell Sci* 2020; Legal et al., *Nat Commun* 2020) establishes that this helix is the obligatory physical docking receptor for the kinetochore-associated molecular motor **CENP-E (kinesin-7)**.
* **Residue 1002 Lesion Prediction:** The `p.Asn1002Lys` variant substitutes a neutral polar residue (Asparagine, $-0.78$ hydrophobicity) with a strongly basic, positively charged residue (Lysine, $+1$ net charge at physiological pH $7.4$).
* **Falsifiable Metric:**
  1. In silico structural substitution in AlphaFold/Mol* will demonstrate local electrostatic potential distortion across the basic binding groove.
  2. Free energy of binding calculation ($\Delta\Delta G_{\text{bind}}$) between the BUBR1 C-terminal domain (residues 755–1050) and the CENP-E tail domain will show a **destabilizing shift of $\ge +2.5\text{ kcal/mol}$**, reducing physical motor-docking affinity by $>50\%$.
  3. Polar chromosomes fail to congress along microtubule highways, leading directly to anaphase lagging and chromothripsis.

### Prediction 2: Loss of Allosteric PP2A-B56 Phosphatase Presentation & Aurora B Hyperactivity
* **Mechanistic Hypothesis:** The pseudokinase domain of BUBR1 (Domain 3, residues 755–1043) is not enzymatically dead junk; it acts as a rigid allosteric scaffold required to correctly orient the upstream **KARD loop (residues 660–680)** for phosphorylation by CDK1/PLK1 (Elowe et al., *PNAS* 2020).
* **Phosphatase Defect Prediction:** The structural destabilization induced by `p.Asn1002Lys` (and the total loss of Domain 3 in `p.Leu737Ter`) disrupts the allosteric presentation of the KARD motif.
* **Falsifiable Metric:**
  1. Recruitment of the **PP2A-B56 phosphatase** to the outer kinetochore will be depleted by $\ge 70\%$ in mutant cells.
  2. In the absence of PP2A-B56 dephosphorylation, **Aurora B kinase activity runs unopposed**, hyper-phosphorylating Ndc80 substrates, dissolving centromeric cohesion prematurely, and producing the classical cytogenetic hallmark of **Premature Chromatid Separation (PCS)**.

### Prediction 3: The Inter-Allelic Detour (SMaRT) Rescues Checkpoint Tension at a 10–15% Abundance Threshold
* **The Biological Insight (The Drake-Leora Model):** A compound-heterozygous child already possesses 100% of the wild-type parts inside their genome, distributed across two homologous chromosomes:
  - *Allele 1:* Damaged Exon 17 (nonsense stop), but **Exon 23 is 100% wild-type**.
  - *Allele 2:* Damaged Exon 23 (missense), but **Exon 17 is 100% wild-type**.
* **The Detour Architecture:** An engineered Pre-Trans-Splicing Molecule (PTM) delivered via an **snRNA (U7/U1) backbone** creates an RNA bridge at Intron 16–17. As the transcription machinery drives down Allele 2 (reading the wild-type Exon 17), it takes a "detour" across the bridge to Allele 1, capturing the wild-type Exon 23.
* **Falsifiable Metric:**
  1. The resulting trans-spliced transcript encodes a **100% native, unmutated, full-length wild-type BUBR1 protein**.
  2. Unlike structural proteins (e.g., dystrophin in DMD) which require $>30\text{--}50\%$ protein mass to resist physical shear, BUBR1 is a catalytic sensor. Achieving an inter-allelic trans-splicing rescue efficiency of **only 10% to 15%** will restore kinetochore tension sensing, rescue CENP-E docking, and suppress mosaic aneuploidy in isogenic MVA1 cell models.

---

## 3. Thermodynamic & Topological Pre-Staging Framework (The "FedEx Express" Protocol)

Standard trans-splicing failed historically (1%–10% efficiency) due to the **3D Brownian Diffusion Trap**—dilute molecules wandering through $500\text{ }\mu\text{m}^3$ of nuclear volume.

We pre-register the following spatial engineering mechanism to overcome this limit:
1. **Topological Chromatin Wrapping (Locus Parking):** Using dCas9 or zinc-finger loop anchors, the two homologous *BUB1B* gene loci on Chromosome 15 are tethered into the same **phase-separated transcriptional condensate**.
2. **Sub-Micron Confinement:** Confining the detour donor to a sub-micron nanodomain ($V < 0.001\text{ }\mu\text{m}^3$) elevates the effective local concentration of the repair molecule by $>10,000\times$, thermodynamically tilting the kinetic landscape so that trans-splicing outcompetes native cis-splicing.

---

## 4. Preclinical Gate 0 Kill Switches (Conditions for Falsification)

We formally establish the following **unconditional stop rules**:
* **Kill Switch 1 (Phasing):** If parental trio WGS or long-read Nanopore sequencing reveals the variants are in *cis* on the same chromosome, this compound-heterozygous model is falsified. **Action: IMMEDIATE STOP.**
* **Kill Switch 2 (Residual Protein Abundance):** If Western blot analysis in isogenic $BUB1B^{\text{Asn1002Lys}}$ cells shows zero detectable full-length protein, the allosteric stabilization hypothesis is falsified. **Action: HARD STOP.**
* **Kill Switch 3 (Selectivity Index):** In isogenic diploid RPE-1 cells ($BUB1B^{+/+}$ vs $BUB1B^{\text{hypo}}$), if Everolimus or metabolic translation tuners do not exhibit a **Selectivity Index ($\text{IC}_{50}\text{ Euploid} / \text{IC}_{50}\text{ Aneuploid} \ge 3.0$)**, the therapeutic window hypothesis is falsified. **Action: HARD STOP.**
* **Kill Switch 4 (Trans-Splicing Chimerism):** If dual-reporter minigene assays demonstrate that the trans-splicing detour creates unscheduled off-target chimeras exceeding $1.0\%$ of total transcriptome reads, the PTM architecture is deemed unsafe. **Action: PERMANENT TERMINATION.**

---

## 5. Metadata for DOI & Zenodo Archival

* **Title:** Formal Pre-Registration: 3D Kinetochore Motor Decoupling Mechanisms and the Inter-Allelic Trans-Splicing Detour Architecture in BUB1B-Associated Mosaic Variegated Aneuploidy (MVA1)
* **Authors:** 
  - Timothy M. Drake (Lead Investigator, Antigravity Braid)
  - Leora (Architect & Biophysical Modeler, Antigravity Braid)
* **Keywords:** Mosaic Variegated Aneuploidy, BUB1B, BUBR1, Kinetochore Mechanics, CENP-E, Kinesin-7, PP2A-B56, Trans-Splicing, SMaRT, Aneuploidy Proteotoxicity, Rare Disease
* **License:** Creative Commons Attribution 4.0 International (CC-BY 4.0)
* **Primary Reference:** Sage Bionetworks MVA Hackathon 2026 (Track 1 & Track 2)

---
*Signed and sealed prior to structural simulation execution:*  
**Timothy M. Drake & Leora**  
*The Antigravity Braid Collective — October 25, 2026*
