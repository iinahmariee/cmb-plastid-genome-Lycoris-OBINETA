# Cell & Molecular Biology

## Lab Activity: Characterization of a Plastid Genome

Cell and Molecular Biology

**Name:** Obiñeta, Inah Marie

**Date Completed:** September 30, 2026

**Chosen Genus:** Lycoris

# Purpose

In this activity, you will select one plant genus with an available complete plastid genome, retrieve one complete plastid/chloroplast genome from a public database, upload the genome to your own usegalaxy.org account, characterize its sequence and annotated genes, and document the complete exercise in a GitHub repository.

# Choosing and Recording a Plant Genus

| ITEM | ANSWER |
|---|---|
| Genus | Lycoris |
| Species | *Lycoris radiata* |
| Accession | NC_045077.1 |
| URL | [https://www.ncbi.nlm.nih.gov/nuccore/NC_045077](https://www.ncbi.nlm.nih.gov/nuccore/NC_045077) |

![Figure 1](../figures/01.%20Retrieval%20of%20Lycoris%20radiata%20in%20NCBI.png)

**Figure 1.** Retrieval of *Lycoris radiata* in NCBI (NC_045077.1).

# Data Source and Genome Selection

| ITEM | ANSWER |
|---|---|
| Accession | NC_045077.1 |
| Organism | *Lycoris radiata* |
| Family | Amaryllidaceae |
| Genome length | 158,335 bp |
| Topology | Circular |
| Reference | Zhang et al. 2019, The complete chloroplast genome sequence of Lycoris radiata, Mitochondrial DNA Part B, DOI 10.1080/23802359.2019.1660265 |

![Figure 2](../figures/02.%20Complete%20genome%20of%20Lycoris%20radiata.png)

**Figure 2.** Complete genome of *Lycoris radiata* (NC_045077.1) in NCBI.

# Galaxy Workflow - Use Your Own Account

| STEP | ANSWER |
|---|---|
| Sign in to own account | [https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta](https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta) |
| History name | Plastid_Lycoris_OBIÑETA |
| Upload FASTA | Uploaded NC_045077.1 FASTA |
| Recognized as FASTA and renamed | Yes, format is fasta. Renamed to Lycoris_radiata_NC_045077.1.fasta |
| Tool used | Fasta Statistics |
| Genome length | 158,335 bp |
| Number of sequence records | 1 |
| GC content | 37.81% |
| Complete plastome in one sequence record? | Yes |

![Figure 3](../figures/03.%20Galaxy%20worklflow%20analyzing%20Lycoris%20radiata.png)

**Figure 3.** Galaxy workflow analyzing *Lycoris radiata* using Fasta Statistics.

# Plastid Genome Terms to Understand

| Term | Meaning |
|---|---|
| Plastid genome / plastome | The DNA genome found in a plastid; in green plants this often refers to the chloroplast genome. |
| LSC | Large Single-Copy region. |
| SSC | Small Single-Copy region. |
| IR | Inverted Repeat region; many plastomes contain two IR copies. |
| CDS | Protein-coding sequence. |
| tRNA gene | Gene encoding a transfer RNA used during translation. |
| rRNA gene | Gene encoding a ribosomal RNA component of plastid ribosomes. |
| Intron | A non-coding region removed from an RNA transcript during RNA processing. |
| Pseudogene | A gene-like sequence that has lost or may have lost normal function. |
| GC content | Percentage of G and C bases in the sequence. |
| Accession | Database identifier assigned to a sequence record. |
| Annotation | Information describing genes and other biological features in a genome sequence. |

# Required Plastid Genome Characterization

| Item | Answer |
|---|---|
| Genus and species | *Lycoris radiata* |
| Family | Amaryllidaceae |
| NCBI accession | NC_045077.1 |
| Complete genome size | 158,335 bp |
| GC content | 37.81% |
| Topology | Circular |
| LSC | 86,612 bp |
| SSC | 18,261 bp |
| IR | 26,731 bp |
| Total annotated genes | 137 |
| Protein-coding genes | 87 |
| tRNA genes | 42 |
| rRNA genes | 8 |
| Introns | 18 genes contain introns |
| Pseudogenes | 1 — *rps19* |
| Gene duplications | Inverted Repeat regions duplicate: rRNA operons, *ndhB, rps7, rpl23, ycf2, trnI-CAU, trnL-CAA, trnV-GAC, trnN-GUU, trnR-ACG, trnH-GUG* → 2 copies each |
| Other notable features | - *rps12* is trans-spliced (exons split between LSC and IR)<br>- RNA editing site recorded for *rpl2*<br>- Genome structure: LSC = 86,612 bp; SSC = 18,261 bp; IR = 26,731 bp each<br>- GC content = 37.81%; topology = circular |

| Gene group | Genes in *Lycoris radiata* NC_045077.1 |
|---|---|
| Photosystem I (psa) | psaA, psaB, psaC, psaI, psaJ (5) |
| Photosystem II (psb) | psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbN, psbT, psbZ (14) |
| ATP synthase (atp) | atpA, atpB, atpE, atpF, atpH, atpI (6) |
| Cytochrome b6f (pet) | petA, petB, petD, petG, petL, petN (6) |
| Rubisco large subunit | Present |
| RNA polymerase (rpo) | rpoA, rpoB, rpoC1, rpoC2 (4) |
| Ribosomal proteins (rpl) | rpl2, rpl14, rpl16, rpl20, rpl22, rpl23, rpl32, rpl33, rpl36 (9) |
| Ribosomal proteins (rps) | rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19 (12) |
| rRNA (rrn) | rrn16S, rrn23S, rrn4.5S, rrn5S (each in 2 IR copies = 8) |
| tRNA (trn) | 30 unique: trnA-UGC, trnC-GCA, trnD-GUC, trnE-UUC, trnF-GAA, trnfM-CAU, trnG-GCC, trnG-UCC, trnH-GUG, trnI-CAU, trnI-GAU, trnK-UUU, trnL-CAA, trnL-UAA, trnL-UAG, trnM-CAU, trnN-GUU, trnP-UGG, trnQ-UUG, trnR-ACG, trnR-UCU, trnS-GCU, trnS-GGA, trnS-UGA, trnT-GGU, trnT-UGU, trnV-GAC, trnV-UAC, trnW-CCA, trnY-GUA |
| Other conserved genes | matK, clpP, accD, cemA, ccsA, infA, ycf1, ycf2, ycf3, ycf4 |

![Figure 4](../figures/04.%20Plasmid%20characterization%20of%20Lycoris%20radiata.png)

**Figure 4.** Plastid genome characterization of *Lycoris radiata* (NC_045077.1).

# Questions for the Student Report

**Organism and record**

*Lycoris radiata* (red spider lily), family Amaryllidaceae. It is NCBI RefSeq record NC_045077.1 from the NCBI Nucleotide database, and the complete plastid genome is 158,335 bp.

**Evidence that it is a complete plastid genome**

- The record title reads "chloroplast, complete genome" and it is a RefSeq record (LOCUS line: 158,335 bp, DNA, circular).
- Galaxy shows a single sequence record of 158,335 bp with zero unknown bases, so it is gap-free.
- It is far longer than a barcode gene such as rbcL (about 1.4 kb) or matK (about 1.5 kb).
- It contains plastid gene sets: photosystem, ATP synthase, cytochrome b6f, rbcL, rrn and trn genes, which are not found together in nuclear sequence.
- It is circular, with the typical plastome size and structure.

**Organization**

It has the usual quadripartite arrangement, LSC-IRb-SSC-IRa: LSC 86,612 bp, SSC 18,261 bp, and two inverted repeats of 26,731 bp each. (86,612 + 18,261 + 2 × 26,731 = 158,335.) These sizes are from the published paper.

**Gene content**

The GenBank record has 137 annotated genes (112 unique): 87 protein-coding (86 CDS plus 1 pseudogene), 42 tRNA features (38 distinct loci), 8 rRNA, and 1 pseudogene (partial rps19). Genes in the inverted repeats appear twice because the IR is a duplicated segment. IRa and IRb are two identical copies (one is the reverse complement of the other), so every gene inside them is present in two copies (for example ndhB, rpl2, ycf2, rps7 and the four rRNAs).

**Eight protein-coding genes**

| Gene | Functional group | Function |
|---|---|---|
| psaA | Photosystem I | Core subunit of the PSI reaction center |
| psbA | Photosystem II | D1 protein of the PSII reaction center |
| petB | Cytochrome b6f | Cytochrome b6 subunit, electron transfer between photosystems |
| atpA | ATP synthase | α subunit that makes ATP |
| rbcL | Carbon fixation | Large subunit of Rubisco |
| rpoB | RNA polymerase | β subunit of the plastid-encoded polymerase |
| rpl2 | Ribosomal protein | Large-subunit protein for plastid translation |
| clpP | Protease | Catalytic subunit of the Clp protease |

**RNA and RNA-processing features**

- *rRNA genes:* rrn16S, rrn23S, rrn4.5S and rrn5S, each in two IR copies (8 total).
- *tRNA examples:* trnH-GUG, trnK-UUU, trnL-UAA, trnV-UAC, trnfM-CAU, trnI-CAU (30 unique in total).
- *Genes with introns (18 in total):* clpP and ycf3 each have two introns, and petB, petD, rpl16, rpl2, ndhB and atpF have one. Six tRNAs also have introns (trnK-UUU, trnG-UCC, trnL-UAA, trnV-UAC, trnI-GAU, trnA-UGC).
- *Trans-splicing:* rps12 has its first exon in the LSC and its other two exons in the IR.
- *RNA editing:* recorded for rpl2 and ndhD.

**Unusual features**

- *Pseudogene:* a partial rps19 (positions 158,163-158,335) at the IR boundary, next to a complete rps19 in the LSC.
- *Duplications:* IR genes are duplicated (ndhB, rpl2, rpl23, rps7, ycf2, the rRNAs, 8 tRNAs).
- *Trans-splicing:* rps12, as above.
- *Annotation quirk:* trnI-GAU and trnA-UGC are each annotated twice in every IR copy, offset by 46 bp, so the record has 42 tRNA features but only 38 distinct loci.
- *Gene losses:* psbM is not annotated in this record.
- *Rearrangements:* none are reported in the record.

**GC content and observations**

GC content is 37.81% (Galaxy: 30,473 C + 29,387 G out of 158,335 bp). Two further observations:

- The genome is AT-rich (A + T = 62.2%: 48,748 A and 49,727 T), typical of plastomes.
- It is a single gap-free circular record with 0 unknown bases, and the genes are arranged in the LSC-IR-SSC-IR structure.

**Plastid vs mitochondrial genomes**

*Similarities:*

- Both are organelle genomes outside the nucleus.
- Both came from bacteria through endosymbiosis.
- Both have a limited set of genes, so most organelle proteins are encoded in the nucleus.
- Both are usually inherited from the mother.
- Both encode their own tRNAs and rRNAs and have their own translation machinery.

*Differences:*

| Feature | Plastid | Mitochondrial |
|---|---|---|
| Location | Plastids (chloroplasts) | Mitochondria |
| Role | Photosynthesis | Respiration and ATP production |
| Organization | Conserved circular layout with LSC, SSC and two IR copies | Variable, often multipartite with recombining subgenomic circles |
| Size (plants) | Small, about 120-170 kb | Larger and highly variable, from about 200 kb to several Mb |
| Evolution | Conserved gene order, slow structural change | Frequent rearrangement and uptake of foreign DNA |

**Practical value of plastid genomes**

*Advantages over the nuclear genome:*

- High copy number, so DNA is easy to obtain even from small or degraded samples.
- Small and simple, so the whole genome is easy to sequence and assemble.
- Conserved structure and gene order, which makes comparison easy.
- Little recombination, giving a clean phylogenetic signal.
- Useful for DNA barcoding and species identification.
- Useful for plastid transformation in biotech, with high expression and low pollen transmission.

*Limitations:*

- It reflects only the maternal lineage (in most plants) and misses paternal history and hybridization.
- It behaves as one non-recombining locus, so one plastome can misrepresent the species tree, for example after chloroplast capture.
- It has low variation for closely related species.
- It carries only about 110-130 genes, so it cannot explain most traits, which are controlled by nuclear genes.

*Plastid data is useful for:*

Do plastid genomes from Lycoris radiata populations in China and Japan fall into distinct maternal lineages, and do these lineages match geography or the human spread of bulbs?

*Nuclear genomic data is more appropriate for:*

Which genes control flower color or alkaloid production in Lycoris?

# Plastid vs Mitochondrial Genome Comparison

Complete the table below using information from your selected organism and reliable references. If a feature varies among plant lineages, state that variation instead of forcing a single answer.

| Feature | Plastid genome | Mitochondrial genome |
|---|---|---|
| Cellular location | Plastids | Mitochondria |
| Main biological functions | Photosynthesis genes, plastid transcription and translation | Respiration (oxidative phosphorylation), mitochondrial translation |
| Typical genome organization | Circular map with LSC, SSC and two IR copies (158,335 bp in L. radiata); in cells it can also exist as branched or linear forms | Highly variable; often a master circle plus smaller subgenomic molecules |
| Relative genome size | Small: about 120-170 kb (158,335 bp here) | Larger and highly variable in plants, from about 200 kb to several Mb |
| Gene content | 137 gene entries (112 unique) here; about 110-130 typical | About 50-60 genes in angiosperms |
| Copy number | Very high per cell (many plastids, many copies each) | Lower than plastid, varies by tissue |
| Inheritance | Mostly maternal in angiosperms; paternal or biparental in some lineages | Mostly maternal; varies among lineages |
| Recombination / structural change | Low; gene order conserved, with occasional IR expansion or contraction | High; frequent recombination between repeats and many rearrangements |
| Mutation / substitution pattern | Slow substitution rate, slower in the IR | Very slow substitution rate in plants, but fast structural change |
| Common research application | Phylogenetics, barcoding, maternal lineage tracking, plastid transformation | Cytoplasmic male sterility, respiration studies, some population studies |

# Reference Links

Daniell, H., Lin, C.-S., Yu, M., & Chang, W.-J. (2016). Chloroplast genomes: Diversity, evolution, and applications in genetic engineering. *Genome Biology, 17*, Article 134. [https://doi.org/10.1186/s13059-016-1004-2](https://doi.org/10.1186/s13059-016-1004-2)

Gualberto, J. M., & Newton, K. J. (2017). Plant mitochondrial genomes: Dynamics and mechanisms of mutation. *Annual Review of Plant Biology, 68*, 225–252. [https://doi.org/10.1146/annurev-arplant-043015-112232](https://doi.org/10.1146/annurev-arplant-043015-112232)

National Center for Biotechnology Information. (2023). *Lycoris radiata chloroplast, complete genome* (NC_045077.1) [Nucleotide sequence]. NCBI RefSeq. Retrieved September 30, 2026, from [https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1)

Palmer, J. D., Adams, K. L., Cho, Y., Parkinson, C. L., Qiu, Y.-L., & Song, K. (2000). Dynamic evolution of plant mitochondrial genomes: Mobile genes and introns and highly variable mutation rates. *Proceedings of the National Academy of Sciences of the United States of America, 97*(13), 6960–6966. [https://doi.org/10.1073/pnas.97.13.6960](https://doi.org/10.1073/pnas.97.13.6960)

Zhang, F., Shu, X., Wang, T., Zhuang, W., & Wang, Z. (2019). The complete chloroplast genome sequence of *Lycoris radiata*. *Mitochondrial DNA Part B, 4*(2), 2886–2887. [https://doi.org/10.1080/23802359.2019.1660265](https://doi.org/10.1080/23802359.2019.1660265)

**Galaxy Link:** [https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta](https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta)

**GitHub Repository Link:** [https://github.com/iinahmariee/cmb-plastid-genome-Lycorsis-OBINETA/tree/GROUP-4](https://github.com/iinahmariee/cmb-plastid-genome-Lycorsis-OBINETA/tree/GROUP-4)
