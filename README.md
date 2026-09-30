# Characterization of a Plastid Genome — Cell & Molecular Biology Lab

## Student Information
- **Name:** Obiñeta, Inah Marie
- **Course/Section:** Cell & Molecular Biology
- **Date Completed:** September 30, 2026

## Organism & Genome Selection
- **Genus & species:** *Lycoris radiata* (red spider lily)
- **Family:** Amaryllidaceae
- **NCBI accession/version:** NC_045077.1
- **Source link:** https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1
- **Reference:** Zhang, F., Shu, X., Wang, T., Zhuang, W., & Wang, Z. (2019). *The complete chloroplast genome sequence of Lycoris radiata*. Mitochondrial DNA Part B, 4(2), 2886–2887. https://doi.org/10.1080/23802359.2019.1660265

## Plastome Summary
| Feature | Value |
|---|---|
| Total genome size | 158,335 bp |
| GC content | 37.81% |
| Topology | Circular |
| LSC size | 86,612 bp |
| SSC size | 18,261 bp |
| IR size (each) | 26,731 bp |
| Total annotated genes | 137 (112 unique) |
| Protein‑coding genes | 87 (86 CDS + 1 pseudogene) |
| tRNA genes | 42 annotated features; 38 distinct loci / 30 unique species |
| rRNA genes | 8 — *rrn16S, rrn23S, rrn4.5S, rrn5S* — each duplicated in IR regions |
| Pseudogenes | 1 — partial *rps19* at IR boundary |
| Notable features | - Quadripartite structure: LSC–IRb–SSC–IRa<br>- *rps12* is trans‑spliced (exon 1 in LSC; exons 2–3 in IR)<br>- 18 genes contain introns; *clpP* and *ycf3* each have 2 introns<br>- RNA editing sites recorded for *rpl2* and *ndhD*<br>- *psbM* not annotated in this record<br>- AT‑rich genome: A+T = 62.2% |

## Galaxy Workflow
- **Account:** https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta
- **History name:** Plastid_Lycoris_OBIÑETA
- **Steps:**
  1. Downloaded FASTA from NCBI Nucleotide (NC_045077.1)
  2. Uploaded to Galaxy → renamed: `Lycoris_radiata_NC_045077.1.fasta`
  3. Recognized as valid FASTA; single sequence record
  4. Ran **Fasta Statistics** → length = 158,335 bp; GC = 37.81%; 0 ambiguous bases
- **Key results:** Complete gap‑free plastome; single circular molecule; matches published length exactly

## Gene Content Overview
| Functional Group | Genes Present |
|---|---|
| Photosystem I (*psa*) | *psaA, psaB, psaC, psaI, psaJ* (5) |
| Photosystem II (*psb*) | *psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbN, psbT, psbZ* (14) |
| ATP synthase (*atp*) | *atpA, atpB, atpE, atpF, atpH, atpI* (6) |
| Cytochrome b₆/f complex (*pet*) | *petA, petB, petD, petG, petL, petN* (6) |
| Carbon fixation | *rbcL* (present) |
| RNA polymerase (*rpo*) | *rpoA, rpoB, rpoC1, rpoC2* (4) |
| Ribosomal proteins (*rpl*) | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23, rpl32, rpl33, rpl36* (9) |
| Ribosomal proteins (*rps*) | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* (12) |
| rRNA (*rrn*) | *rrn16S, rrn23S, rrn4.5S, rrn5S* — 2 copies each in IR = 8 total |
| tRNA (*trn*) | 30 unique species including *trnH‑GUG, trnK‑UUU, trnL‑UAA, trnV‑UAC, trnfM‑CAU, trnI‑CAU*; 6 tRNAs contain introns |
| Other conserved genes | *matK, clpP, accD, cemA, ccsA, infA, ycf1, ycf2, ycf3, ycf4* |

## Data Sources & References
1. National Center for Biotechnology Information. (2023). *Lycoris radiata* chloroplast, complete genome (NC_045077.1). Retrieved September 30, 2026, from https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1
2. Zhang, F., et al. (2019). The complete chloroplast genome sequence of *Lycoris radiata*. *Mitochondrial DNA Part B*, 4(2), 2886–2887. https://doi.org/10.1080/23802359.2019.1660265
3. Daniell, H., Lin, C.‑S., Yu, M., & Chang, W.‑J. (2016). Chloroplast genomes: Diversity, evolution, and applications in genetic engineering. *Genome Biology*, 17, 134. https://doi.org/10.1186/s13059-016-1004-2
4. Gualberto, J. M. & Newton, K. J. (2017). Plant mitochondrial genomes: Dynamics and mechanisms of mutation. *Annual Review of Plant Biology*, 68, 225–252. https://doi.org/10.1146/annurev-arplant-043015-112232
5. Palmer, J. D., et al. (2000). Dynamic evolution of plant mitochondrial genomes. *PNAS*, 97(13), 6960–6966. https://doi.org/10.1073/pnas.97.13.6960

## Reproducibility — How to Repeat This Analysis
Another student can reproduce this work exactly by following these steps:
1. Go to NCBI Nucleotide → search accession **NC_045077.1** → download the FASTA file
2. Sign in to https://usegalaxy.org/ → create a new history named **Plastid_Lycoris_[YourName]**
3. Upload the FASTA file → rename it to match the accession
4. Run **Fasta Statistics** → record genome length, GC%, and number of sequences
5. Open the NCBI GenBank "Features" table → extract gene counts and coordinates
6. Calculate LSC/SSC/IR boundary sizes from the published values: LSC = 86,612 bp; SSC = 18,261 bp; IR = 26,731 bp each
7. Compile tables and answers following the lab report template
8. Create your own GitHub repository with the same folder structure and document your workflow

## Repository Structure
