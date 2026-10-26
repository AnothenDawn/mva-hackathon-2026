# Pre-registration: inter-allelic 3′ terminal-exon trans-splicing as a candidate repair route in compound-heterozygous recessive disease, with BUB1B-associated mosaic variegated aneuploidy as the first test case

**Investigator:** Timothy M. Drake  
**AI assistance (acknowledged, not authors):** Anthropic Claude, Google Gemini, OpenAI ChatGPT and Codex, xAI Grok, Meta Muse.  
**Role:** literature synthesis, drafting, adversarial audit, citation verification.  
**Date:** 2026-10-26  
**Target locus:** Human BUB1B (15q15.1), protein BubR1 (UniProt O60566, 1,050 aa)  
**Target condition:** Mosaic variegated aneuploidy syndrome 1 (MVA1; OMIM #257300)  
**Licence:** CC BY 4.0  
**Sealed appendix SHA-256:** `fa2c61ce75c79e513f48ecd7e669f6ae882752335119372aa93ae52ce47fcf65`  

---

## 0. What this document is, and what it is not

This registers a set of falsifiable predictions and their thresholds before any structural simulation, splice-site prediction, minigene assay or cell experiment is run. Its purpose is to prevent hypothesising after results are known.

It does not establish scientific priority. Priority comes from publication and from the prior art cited in §3. Several components of what follows are published work by others, and are cited as such. The contribution claimed here is narrow and stated explicitly in §2.

No patient-identifying information appears in this document. The work arises from a gated dataset held under the Sage Bionetworks MVA Hackathon 2026 Data Use Agreement. Exact variant coordinates, cDNA and protein changes, residue identities, gestational age and birth weight are withheld. They are fixed in advance in a private sealed appendix whose SHA-256 hash is published above, so that the specific predictions can be verified later as having been made in advance without those values being published now. A rare diagnosis combined with a distinctive tumour, a renal finding, a birth history and two ultra-rare variants functions as a fingerprint even without a name attached.

No clinical recommendation is made. Nothing here proposes treating any person. No dose, schedule or route of administration is specified, and none should be inferred.

Publication status. Release of this document respects the hackathon's publication embargo. Nothing in it reproduces or redistributes gated data.

---

## 1. Genetic premise, stated without patient identifiers

A compound-heterozygous recessive genotype in BUB1B in which the two alleles are disrupted at different positions in the gene:

| Label | Lesion | Consequence |
|---|---|---|
| **Allele N** | Nonsense variant, exon 17 of 23 | Premature termination. Exons 18–23 are present and sequence-normal on this allele but are not translated. Nonsense-mediated decay is plausible and must be measured. |
| **Allele M** | Missense variant, exon 23 (terminal exon), within the annotated pseudokinase domain (residues 766–1050) | Full-length protein predicted, with a single substituted residue near the C-terminus. Functional consequence unestablished. |

Phase between the alleles is unconfirmed. Two heterozygous short-read calls in a proband do not establish a trans configuration. The observed recessive phenotype is consistent with trans but does not prove it. See Kill Switch 1.

The observation this document turns on. Because the two lesions sit in different exons, neither allele is wholly defective and, taken together, the two alleles contain a complete sequence-normal set of coding exons. Allele N supplies a normal terminal exon; Allele M supplies every exon upstream of it. Both transcripts are present in the same nucleus.

Carrier arithmetic sets the bar. Each heterozygous parent of such a child is unaffected, which demonstrates that one functional allele's output is sufficient for normal development. The therapeutic target is therefore not complete correction but the output of approximately one functional allele in a sufficient fraction of relevant cells.

---

## 2. The contribution claimed

Narrowly:

1. That for a compound-heterozygous pair whose lesions lie in different exons, and specifically where one lesion lies in the terminal exon, the required repair is a single splice junction, and the donor exon is already present, intact and transcribed in the patient's own cells.
2. That BUB1B-associated MVA1 is a favourable first test case, for the reasons in §4.
3. A pre-specified falsification protocol (§6) with numerical stop rules fixed in advance.

Not claimed: invention of trans-splicing, of interhomolog repair, or of the use of a homologous chromosome as an endogenous template. All three are published prior art (§3).

---

## 3. Prior art, with verified citations

Every reference below was checked against PubMed on 2026-10-25/26. Journal, volume, pages and PMID were confirmed per record.

### Disease and gene
1. Hanks S, et al. Constitutional aneuploidy and cancer predisposition caused by biallelic BUB1B mutations. *Nat Genet* 2004;36(11):1159–61. PMID 15475955.
2. Malumbres M, Villarroya-Beltri C. Mosaic variegated aneuploidy in development, ageing and cancer. *Nat Rev Genet* 2024;25(12):864–78. PMID 39169218.
3. Suijkerbuijk SJE, et al. Molecular causes for BUBR1 dysfunction in the human cancer predisposition syndrome mosaic variegated aneuploidy. *Cancer Res* 2010;70(12):4891–900. PMID 20516114.

### BubR1 domain architecture and function
4. Suijkerbuijk SJE, et al. The vertebrate mitotic checkpoint protein BUBR1 is an unusual pseudokinase. *Dev Cell* 2012;22(6):1321–9. PMID 22698286.
5. Suijkerbuijk SJE, et al. Integration of kinase and phosphatase activities by BUBR1 ensures formation of stable kinetochore–microtubule attachments. *Dev Cell* 2012;23(4):745–55. PMID 23079597.
6. Legal T, Hayward D, Gluszek-Kustusz A, et al. The C-terminal helix of BubR1 is essential for CENP-E-dependent chromosome alignment. *J Cell Sci* 2020;133(16):jcs246025. PMID 32665320.
7. Gama Braga L, Cisneros AF, Mathieu MM, et al. (Elowe S, senior author). BUBR1 pseudokinase domain promotes kinetochore PP2A-B56 recruitment, spindle checkpoint silencing, and chromosome alignment. *Cell Rep* 2020;33(7):108397. PMID 33207204.

**Correction note on references 6 and 7.** Earlier internal drafts of this work attributed reference 6 to "Ciossani et al." and/or to *Nat Commun*, and reference 7 to "Elowe et al., *PNAS*". Both attributions were incorrect and are corrected here. Reference 6 is Legal et al. in *J Cell Sci*; reference 7 is Gama Braga et al. in *Cell Reports*, with Elowe as senior author.

**What references 6 and 7 do and do not establish.** Reference 6 establishes that the basic C-terminal helix of BubR1 is necessary but not sufficient for CENP-E interaction, and that a minimal acidic patch on CENP-E's kinetochore-targeting domain is also required. It does not establish that any particular substitution in that region abolishes docking. Reference 7 establishes that the pseudokinase domain promotes KARD phosphorylation and thereby PP2A-B56 recruitment, checkpoint silencing and alignment. Neither reference reports premature chromatid separation or a cohesion defect. Any claim linking either mechanism to premature chromatid separation requires its own source and is not made here.

**Domain boundaries.** UniProt O60566 annotates BubR1 as 1,050 residues with a protein-kinase (pseudokinase) domain spanning residues 766–1050. UniProt does not map the boundaries of the basic C-terminal helix described in reference 6. Internal drafts cited a helix spanning residues 1000–1043; the "1043" boundary has no identified source and is withdrawn. Whether the missense residue lies inside that helix is therefore unknown in both directions and is recorded as such.

### Using an allele's own homologue as the repair template
8. Tomita A, Sasanuma H, Owa T, et al. Inducing multiple nicks promotes interhomolog homologous recombination to correct heterozygous mutations in somatic cells. *Nat Commun* 2023;14(1):5607. PMID 37714828. Establishes the NICER method: Cas9 nickase-induced multiple nicks using the homologous chromosome as an endogenous repair template, without exogenous donor DNA. Reported features relevant here: correction of compound-heterozygous mutations in patient-derived fibroblasts; efficiency 3–6% unselected, rising with repeated application; secondary-nick offsets from 24 to 8,675 bp with no correlation between efficiency and offset distance; a nick on the donor allele both extends and restricts the incorporated tract; off-target indel frequencies ≤0.3% against >84% for conventional Cas9. Critically for this proposal: in FANCA-mutant, repair-deficient cells, 9–18% of corrected clones carried long deletions between nicks, versus background in repair-competent cells.
9. Wilde JJ, Aida T, Del Rosario RCH, et al. Efficient embryonic homozygous gene conversion via RAD51-enhanced interhomolog repair. *Cell* 2021;184(12):3267–3280.e18. PMID 34043941.
10. Meyer-Mueller C, Osborn MJ, Tolar J, et al. Revertant mosaicism in epidermolysis bullosa. *Biomedicines* 2022;10(1):114. PMID 35052793. Establishes that spontaneously corrected cells can form expanding, phenotypically normal patches and are being considered as an autologous therapeutic substrate — the empirical basis for the selection argument in §4.

### Aneuploid-cell stress biology (relevant to the companion everolimus hypothesis)
11. Torres EM, et al. Effects of aneuploidy on cellular physiology and cell division in haploid yeast. *Science* 2007;317(5840):916–24. PMID 17702937.
12. Santaguida S, Vasile E, White E, Amon A. Aneuploidy-induced cellular stresses limit autophagic degradation. *Genes Dev* 2015;29(19):2010–21. PMID 26404941.
13. Tang YC, Williams BR, Siegel JJ, Amon A. Identification of aneuploidy-selective antiproliferation compounds. *Cell* 2011;144(4):499–512. PMID 21315436. (AICAR, 17-AAG, chloroquine. No rapalog tested.)
14. Gupta AA, Xue W, Harrison DJ, et al. Addition of temsirolimus to chemotherapy in intermediate-risk rhabdomyosarcoma (ARST1431): a randomised, open-label, phase 3 trial. *Lancet Oncol* 2024;25(7):912–21. PMID 38936378. (3-year EFS 64.8% control vs 66.8% temsirolimus; HR 0.86, 95% CI 0.58–1.26; p = 0.44. No survival benefit.)
15. North BJ, et al. SIRT2 induces the checkpoint kinase BubR1 to increase lifespan. *EMBO J* 2014;33(13):1438–53. PMID 24825348.

### Citations required before any version of this document is finalised
- Primary methods literature for spliceosome-mediated RNA trans-splicing (SMaRT), including reported efficiency ranges and pre-trans-splicing molecule design.
- Primary literature for 3′ terminal-exon replacement specifically.
- SpliceAI / Pangolin primary methods papers.
- Any existing report of trans-splicing applied to BUB1B.

These are deliberately left as placeholders rather than filled from memory. A search of PubMed on 2026-10-25 for BUB1B together with gene correction returned nothing relevant, and NICER has one indexed publication (ref. 8). No claim of novelty should be made until the SMaRT literature has been searched properly.

---

## 4. Why BUB1B MVA1 is a favourable first test case

Each point is graded.

| Claim | Grade |
|---|---|
| The two alleles jointly contain a complete set of sequence-normal coding exons | Measured, from the submitted variant calls |
| One functional allele suffices for normal development | Measured, from unaffected heterozygous carriers |
| The required edit is a single splice junction at the final intron | Derived from the exon positions |
| The donor terminal exon is intact and transcribed | Hypothesis. Requires allele-specific RNA to confirm the nonsense allele's transcript is present and not fully degraded |
| Corrected cells will outcompete uncorrected cells | Hypothesis, by analogy to ref. 10 |
| BubR1 is a scaffold/pseudokinase rather than a catalytic enzyme | Measured (ref. 4) |
| A low rescue fraction suffices because BubR1 acts catalytically | Rejected. Contradicts ref. 4 and must not be used as a rationale |

**Note on the last row.** An internal draft justified a low rescue threshold by describing BubR1 as a "catalytic sensor". Reference 4 establishes the opposite: putative catalysis is dispensable and BubR1 functions as a pseudokinase scaffold. The low-threshold prediction is retained in §5 as an assumption to be measured, not as a consequence of catalysis.

---

## 5. Pre-registered predictions and thresholds

Thresholds are fixed now. Numerical values that depend on withheld patient detail are fixed in the sealed appendix and hashed above.

* **P1 — Structural effect of the missense allele.** Prediction: the substitution is destabilising at the modelled BubR1–CENP-E interface by $\Delta\Delta G_{\text{bind}} \ge +2.5\text{ kcal/mol}$. Methodological precondition, registered in advance: this metric is only meaningful on an experimentally determined structure of the complex. If no co-structure of the BubR1 C-terminal region with CENP-E exists in the PDB, P1 must be downgraded to a modelled estimate, reported as such, and cannot be cited as evidence of decoupling. This precondition is to be resolved by a PDB search before any run.
* **P2 — PP2A-B56 recruitment.** Prediction: kinetochore PP2A-B56 recruitment is reduced by $\ge 70\%$ in the missense isogenic line relative to isogenic wild type. Registered limitation: references 5 and 7 support the pathway. Neither supports extending it to premature chromatid separation. No PCS claim is registered.
* **P3 — Splice-site strength at the target junction.** Prediction: the native 3′ acceptor of the terminal exon scores below 0.80 by SpliceAI, making it plausibly outcompetable by an engineered donor. Registered limitation: SpliceAI and Pangolin were trained on native splicing and have never seen an engineered trans-splicing construct. A favourable score supports only that the target site behaves as modelled. It is not evidence that a construct will work.
* **P4 — Rescue threshold.** Prediction: trans-splicing at 10–15% of total BUB1B transcript restores checkpoint function in isogenic models. Registered as an assumption with no identified source. Failure of this threshold falsifies the threshold only, not the architecture. If the required fraction proves higher, that is a result, not a refutation.
* **P5 — Specificity.** Prediction: an engineered pre-trans-splicing molecule produces off-target chimeric transcripts at $< 1.0\%$ of total transcriptome reads.

---

## 6. Architecture, corrected

The junction is the final intron, between exon 22 and exon 23. Not intron 16–17.

| Component | Source allele | Rationale |
|---|---|---|
| Exons 1–22 | Allele M (missense) | Sequence-normal throughout, including exon 17 |
| Exon 23 (terminal) | Allele N (nonsense) | Sequence-normal, and unused because translation terminates in exon 17 |

**Why the intron 16–17 placement is wrong and must not be used.** A bridge at intron 16–17 transfers the message to Allele N before exon 17 is read, and therefore captures Allele N's nonsense codon. Such a construct would deliver the premature stop rather than remove it. This error appeared in an internal draft and is corrected here on the record.

**Consequences of the correction.** Terminal-exon (3′) replacement requires one junction at the last intron. This is the most tractable class of trans-splicing, requires no handling of internal exon order, and touches no DNA — so the long-deletion risk documented in repair-deficient cells in reference 8 does not apply to this route.

**Required pre-work before any construct design:**
1. Confirm phase (Kill Switch 1).
2. Confirm by allele-specific RNA that the nonsense allele's transcript is present in sufficient quantity to serve as a donor. If nonsense-mediated decay removes it, this architecture fails at the first step. This is the most likely way the whole idea dies, and it is cheap to test.
3. Determine the native acceptor strength at the final intron (P3).

---

## 7. Speculative annex — NOT pre-registered

The following is recorded as speculation for completeness. It is not a registered prediction, carries no thresholds, and must not be cited as a mechanism.

Trans-splicing efficiency may be limited by diffusion: donor molecules are dilute relative to nuclear volume, so the native cis-splice at the same site is kinetically favoured. It is conceivable that tethering the two homologous loci into a shared transcriptional condensate — for example with catalytically dead Cas9 or engineered zinc-finger anchors — would raise the effective local donor concentration and shift the kinetic competition.

**Why this is not registered.** No derivation has been performed for any concentration-gain figure, no experimental demonstration of homologous-locus tethering for this purpose has been identified, and the relationship between condensate residence and splice-site competition is not established. Earlier drafts stated a ">10,000× local concentration" increase and a confinement volume of "<0.001 µm³". Both figures were asserted without derivation and are withdrawn.

---

## 8. Kill switches — unconditional stop rules

Fixed in advance. Each specifies its own failure condition and action.

| # | Test | Falsifies | Action |
|---|---|---|---|
| **KS1** | Parental trio or long-read phasing | If the two variants are in cis, the compound-heterozygous premise is false and this entire architecture is void | **IMMEDIATE STOP** |
| **KS2** | Allele-specific RNA for the nonsense allele's transcript | If the donor transcript is absent or degraded below usable abundance, the trans-splicing route has no donor | **HARD STOP** on this route |
| **KS3** | Western blot in the missense isogenic line | If no full-length protein is detectable, the stabilisation premise of P1/P2 is false | **HARD STOP** |
| **KS4** | Dual-reporter minigene chimerism assay | If off-target chimeric transcripts exceed 1.0% of transcriptome reads, the construct is unsafe | **PERMANENT TERMINATION** of the construct |
| **KS5** | Long-deletion screen, NICER route only | If the DNA-editing route produces long deletions at or above the 9–18% seen in repair-deficient cells (ref. 8), the DNA route is abandoned in favour of the RNA route | **STOP** the DNA route |
| **KS6** | Isogenic selectivity for the companion everolimus hypothesis | If $\text{IC}_{50}\text{(euploid)} / \text{IC}_{50}\text{(aneuploid)} < 3.0$, the therapeutic-window hypothesis is falsified | **HARD STOP** |

A negative result at any gate is a valid and publishable result.

---

## 9. What this document explicitly does not claim
- Not a cure. Not a treatment. Not a clinical protocol.
- Not evidence that trans-splicing works in BUB1B. No such experiment has been run.
- Not evidence that the missense substitution disrupts CENP-E docking or PP2A-B56 recruitment. Both remain hypotheses, and reference 6's own finding is "necessary but not sufficient".
- Not a claim that the variants are in trans. Unconfirmed.
- Not a claim of novelty for trans-splicing, interhomolog repair, or homologue-templated repair.
- Not a claim that pre-registration confers priority.
- Not a claim that any threshold here is correct. They are commitments, so that they can fail.

---

## 10. Amendment log

| Date | Change |
|---|---|
| 2026-10-26 | Junction corrected from intron 16–17 to intron 22. Prior placement would have imported the premature stop codon. |
| 2026-10-26 | References 6 and 7 corrected: Legal/J Cell Sci, Gama Braga/Cell Reports. |
| 2026-10-26 | Residue "1043" helix boundary withdrawn as unsourced. Helix position recorded as unknown. |
| 2026-10-26 | "Catalytic sensor" rationale rejected as contradicting ref. 4. P4 retained as an unsourced assumption. |
| 2026-10-26 | Condensate concentration-gain and confinement-volume figures withdrawn; section moved to a non-registered speculative annex. |
| 2026-10-26 | Premature chromatid separation claim removed pending a source. |
| 2026-10-26 | All patient-identifying detail removed to a hashed sealed appendix. |
| 2026-10-26 | AI systems moved from authorship to acknowledgement, per hackathon rules. |
| 2026-10-26 | KS2 and KS5 added. |

*Thresholds fixed prior to execution of any structural simulation, splice prediction, or assay. Timothy M. Drake, 2026-10-26.*
