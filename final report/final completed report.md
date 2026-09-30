# Cell & Molecular Biology Lab Activity: Characterization of a Plastid Genome

**Name:** Obiñeta, Inah Marie
**Course:** Cell and Molecular Biology
**Date Completed:** September 30, 2026
**Chosen Genus:** *Lycoris*

# 1. Purpose

In this activity, you will select one plant genus with an available complete plastid genome, retrieve one complete plastid/chloroplast genome from a public database, upload the genome to your own usegalaxy.org account, characterize its sequence and annotated genes, and document the complete exercise in a GitHub repository.

# 2. Learning Outcomes

- Locate and verify a complete plastid/chloroplast genome in NCBI.
- Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene, and GC content.
- Describe the overall organization and gene content of a selected plastid genome.
- Use Galaxy to upload a plastid genome and obtain basic sequence statistics.
- Compare plastid genomes with mitochondrial and nuclear genomes.
- Evaluate practical advantages and limitations of plastid genomes in biological studies.
- Document the data source, analysis steps, results, and interpretation in GitHub.

# 3. Choosing and Recording a Plant Genus

| Item | Answer |
|---|---|
| Genus | *Lycoris* |
| Species | *Lycoris radiata* |
| Accession | NC_045077.1 |
| URL | https://www.ncbi.nlm.nih.gov/nuccore/NC_045077 |

![Figure 1](../figures/01.%20Retrieval%20of%20Lycoris%20radiata%20in%20NCBI.png)

**Figure 1.** Retrieval of the *Lycoris radiata* chloroplast genome record (NC_045077.1) from the NCBI Nucleotide database.

# 4. Data Source and Genome Selection

| Item | Information |
|---|---|
| Chosen genus | *Lycoris* |
| Selected species | *Lycoris radiata* (red spider lily) |
| Family | Amaryllidaceae |
| Organelle | Chloroplast (plastid) |
| Genome type | Complete chloroplast genome |
| NCBI accession/version | **NC_045077.1** |
| Database | NCBI RefSeq / Nucleotide |
| Genome length | **158,335 bp** |
| Topology | Circular |
| Sequence status | Complete genome |
| Source | NCBI Nucleotide / RefSeq |
| Associated publication | Zhang et al. (2019), *The complete chloroplast genome sequence of Lycoris radiata*, Mitochondrial DNA Part B, DOI 10.1080/23802359.2019.1660265 |
| NCBI record | https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1 |

![Figure 2](../figures/02.%20Complete%20genome%20of%20Lycoris%20radiata.png)

**Figure 2.** Complete chloroplast genome record of *Lycoris radiata* (NC_045077.1) retrieved from NCBI, used as the genome sequence source for the study.

# 5. Files to Obtain

| File | Format | Purpose | File/Accession |
|---|---|---|---|
| Genome sequence | FASTA | Upload to Galaxy and obtain sequence statistics | *Lycoris radiata* chloroplast genome, **NC_045077.1** |
| Annotated genome | GenBank / RefSeq | Identify genes, coordinates, introns, pseudogenes, and other features | *Lycoris radiata* chloroplast genome, **NC_045077.1** |
| Source information | NCBI record link / accession | Document the origin of the genome used | **NC_045077.1**: https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1 |

# 6. Galaxy Workflow

Galaxy history: https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta

| Step | Result |
|---|---|
| History name | Plastid_Lycoris_OBIÑETA |
| Upload FASTA | Uploaded NC_045077.1 FASTA |
| Recognized as FASTA and renamed | Yes, format is fasta. Renamed to `Lycoris_radiata_NC_045077.1.fasta` |
| Tool used | Fasta Statistics |

| Statistic | Galaxy Result |
|---|---:|
| Genome length | 158,335 bp |
| Number of sequence records | 1 |
| GC content | 37.81% |
| Complete plastome represented by one sequence | Yes |

![Figure 3](../figures/03.%20Galaxy%20worklflow%20analyzing%20Lycoris%20radiata.png)

**Figure 3.** Galaxy workflow for analyzing the *Lycoris radiata* chloroplast genome using Fasta Statistics. The uploaded FASTA file (NC_045077.1) was processed to obtain sequence statistics, including genome length and GC content.

# 7. Plastid Genome Terms to Understand

| Term | Meaning |
|---|---|
| **Plastid genome / plastome** | The DNA genome found in a plastid; in green plants this often refers to the chloroplast genome. |
| **LSC** | Large Single-Copy region. |
| **SSC** | Small Single-Copy region. |
| **IR** | Inverted Repeat region; many plastomes contain two IR copies. |
| **CDS** | Protein-coding sequence. |
| **tRNA gene** | Gene encoding a transfer RNA used during translation. |
| **rRNA gene** | Gene encoding a ribosomal RNA component of plastid ribosomes. |
| **Intron** | A non-coding region removed from an RNA transcript during RNA processing. |
| **Pseudogene** | A gene-like sequence that has lost or may have lost normal function. |
| **GC content** | Percentage of G and C bases in the sequence. |
| **Accession** | Database identifier assigned to a sequence record. |
| **Annotation** | Information describing genes and other biological features in a genome sequence. |

# 8. Required Plastid Genome Characterization

| Characteristic | *Lycoris radiata* chloroplast genome |
|---|---|
| **Genus** | *Lycoris* |
| **Species** | *Lycoris radiata* |
| **Family** | Amaryllidaceae |
| **NCBI accession/version** | **NC_045077.1** |
| **Genome size** | **158,335 bp** |
| **GC content** | **37.81%** |
| **Topology** | Circular |
| **LSC size** | **86,612 bp** |
| **SSC size** | **18,261 bp** |
| **IR size** | **26,731 bp each** |
| **Number of sequence records** | **1** |
| **Total annotated genes** | **137** (112 unique) |
| **Protein-coding genes** | **87** (86 CDS plus 1 pseudogene) |
| **tRNA genes** | **42** features (38 distinct loci; 30 unique tRNA types) |
| **rRNA genes** | **8** (4 types, each in 2 IR copies) |
| **Introns** | 18 genes contain introns |
| **Pseudogenes / gene fragments** | 1: partial *rps19* |
| **Gene duplications** | IR regions duplicate the rRNA operons, *ndhB*, *rps7*, *rpl23*, *ycf2*, *trnI-CAU*, *trnL-CAA*, *trnV-GAC*, *trnN-GUU*, *trnR-ACG* and *trnH-GUG* (2 copies each) |
| **Other notable features** | *rps12* is trans-spliced (exons split between LSC and IR); RNA editing recorded for *rpl2* |
| **Overall organization** | LSC–IRb–SSC–IRa |

### Gene Groups Identified

| Gene group | Genes in *Lycoris radiata* NC_045077.1 | Main function |
|---|---|---|
| **psa** | *psaA, psaB, psaC, psaI, psaJ* (5) | Photosystem I subunits |
| **psb** | *psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbN, psbT, psbZ* (14) | Photosystem II subunits |
| **atp** | *atpA, atpB, atpE, atpF, atpH, atpI* (6) | ATP synthase components |
| **pet** | *petA, petB, petD, petG, petL, petN* (6) | Cytochrome b6f complex, electron transport |
| **rbcL** | *rbcL* (present) | Large subunit of Rubisco, carbon fixation |
| **rpo** | *rpoA, rpoB, rpoC1, rpoC2* (4) | Plastid RNA polymerase subunits |
| **rpl** | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23, rpl32, rpl33, rpl36* (9) | Large ribosomal subunit proteins |
| **rps** | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* (12) | Small ribosomal subunit proteins |
| **rrn** | *rrn16S, rrn23S, rrn4.5S, rrn5S* (each in 2 IR copies = 8) | Ribosomal RNA |
| **trn** | 30 unique: *trnA-UGC, trnC-GCA, trnD-GUC, trnE-UUC, trnF-GAA, trnfM-CAU, trnG-GCC, trnG-UCC, trnH-GUG, trnI-CAU, trnI-GAU, trnK-UUU, trnL-CAA, trnL-UAA, trnL-UAG, trnM-CAU, trnN-GUU, trnP-UGG, trnQ-UUG, trnR-ACG, trnR-UCU, trnS-GCU, trnS-GGA, trnS-UGA, trnT-GGU, trnT-UGU, trnV-GAC, trnV-UAC, trnW-CCA, trnY-GUA* | Transfer RNAs for protein synthesis |
| **Other conserved genes** | *matK, clpP, accD, cemA, ccsA, infA, ycf1, ycf2, ycf3, ycf4* | Maturase, protease subunit, fatty-acid biosynthesis, envelope membrane protein, cytochrome c biogenesis, translation initiation, and conserved genes of varied or uncertain function |

![Figure 4](../figures/04.%20Plasmid%20characterization%20of%20Lycoris%20radiata.png)

**Figure 4.** Plastid genome characterization of *Lycoris radiata* (NC_045077.1), summarizing the genome size, topology, and annotated features used for the characterization.

# 9. Questions for the Student Report

**1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.**

My selected organism is *Lycoris radiata* (red spider lily), family Amaryllidaceae. The complete chloroplast genome is NCBI RefSeq record NC_045077.1 from the NCBI Nucleotide database. The genome has a total length of 158,335 bp.

**2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?**

- The record title reads "chloroplast, complete genome" and it is a RefSeq record (LOCUS line: 158,335 bp, DNA, circular).
- Galaxy shows a single sequence record of 158,335 bp with zero unknown bases, so it is gap-free.
- It is far longer than a barcode gene such as *rbcL* (about 1.4 kb) or *matK* (about 1.5 kb).
- It contains plastid gene sets (photosystem, ATP synthase, cytochrome b6f, *rbcL*, *rrn* and *trn* genes) that are not found together in nuclear sequence.
- It is circular, with the typical plastome size and structure.

**3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.**

Yes, the *Lycoris radiata* chloroplast genome has the usual quadripartite LSC–IRb–SSC–IRa arrangement.

**LSC:** 86,612 bp

**SSC:** 18,261 bp

**IR:** 26,731 bp each

The sizes add up to the genome length (86,612 + 18,261 + 2 × 26,731 = 158,335 bp). The two IR regions are identical repeated copies that separate the LSC and SSC regions. These sizes are from the published paper.

**4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.**

The GenBank record has 137 annotated genes (112 unique): 87 protein-coding (86 CDS plus 1 pseudogene), 42 tRNA features (38 distinct loci), 8 rRNA genes, and 1 pseudogene (partial *rps19*). Genes located in the inverted repeats appear twice because the IR is a duplicated segment. IRa and IRb are two identical copies (one is the reverse complement of the other), so every gene inside them is present in two copies, for example *ndhB*, *rpl2*, *ycf2*, *rps7* and the four rRNAs.

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Gene | Functional Group | Function |
|---|---|---|
| **psaA** | Photosystem I | Core subunit of the PSI reaction center |
| **psbA** | Photosystem II | D1 protein of the PSII reaction center |
| **petB** | Cytochrome b6f | Cytochrome b6 subunit, electron transfer between photosystems |
| **atpA** | ATP synthase | α subunit that makes ATP |
| **rbcL** | Carbon fixation | Large subunit of Rubisco |
| **rpoB** | RNA polymerase | β subunit of the plastid-encoded polymerase |
| **rpl2** | Ribosomal protein | Large-subunit protein for plastid translation |
| **clpP** | Protease | Catalytic subunit of the Clp protease |

**6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.**

- **rRNA genes:** *rrn16S, rrn23S, rrn4.5S* and *rrn5S*, each in two IR copies (8 total).
- **tRNA examples:** *trnH-GUG, trnK-UUU, trnL-UAA, trnV-UAC, trnfM-CAU, trnI-CAU* (30 unique in total).
- **Genes with introns (18 in total):** *clpP* and *ycf3* each have two introns, and *petB, petD, rpl16, rpl2, ndhB* and *atpF* have one. Six tRNAs also have introns (*trnK-UUU, trnG-UCC, trnL-UAA, trnV-UAC, trnI-GAU, trnA-UGC*).
- **Trans-splicing:** *rps12* has its first exon in the LSC and its other two exons in the IR.
- **RNA editing:** recorded for *rpl2* and *ndhD*.

**7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.**

- **Pseudogene:** a partial *rps19* (positions 158,163–158,335) at the IR boundary, next to a complete *rps19* in the LSC.
- **Duplications:** IR genes are duplicated (*ndhB, rpl2, rpl23, rps7, ycf2*, the rRNAs, 8 tRNAs).
- **Trans-splicing:** *rps12*, as described above.
- **Annotation quirk:** *trnI-GAU* and *trnA-UGC* are each annotated twice in every IR copy, offset by 46 bp, so the record has 42 tRNA features but only 38 distinct loci.
- **Gene losses:** *psbM* is not annotated in this record.
- **Rearrangements:** none are reported in the record.

**8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.**

The GC content of my *Lycoris radiata* chloroplast genome is 37.81%, based on my Galaxy Fasta Statistics result (30,473 C + 29,387 G out of 158,335 bp).

Two other notable observations are:

1. The genome is AT-rich (A + T = 62.2%: 48,748 A and 49,727 T), which is typical of plastomes.
2. It is a single gap-free circular record with 0 unknown bases, and the genes are arranged in the LSC–IR–SSC–IR structure.

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

**Similarities**

1. Both are organelle genomes outside the nucleus.
2. Both came from bacteria through endosymbiosis.
3. Both have a limited set of genes, so most organelle proteins are encoded in the nucleus.
4. Both are usually inherited from the mother.
5. Both encode their own tRNAs and rRNAs and have their own translation machinery.

**Differences**

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Location** | Plastids (chloroplasts) | Mitochondria |
| **Role** | Photosynthesis | Respiration and ATP production |
| **Organization** | Conserved circular layout with LSC, SSC and two IR copies | Variable, often multipartite with recombining subgenomic circles |
| **Size (plants)** | Small, about 120–170 kb | Larger and highly variable, from about 200 kb to several Mb |
| **Evolution** | Conserved gene order, slow structural change | Frequent rearrangement and uptake of foreign DNA |

**10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.**

**Advantages of plastid genomes**

- High copy number, so DNA is easy to obtain even from small or degraded samples.
- Small and simple, so the whole genome is easy to sequence and assemble.
- Conserved structure and gene order, which makes comparison easy.
- Little recombination, giving a clean phylogenetic signal.
- Useful for DNA barcoding and species identification.
- Useful for plastid transformation in biotechnology, with high expression and low pollen transmission.
- Nuclear sex chromosomes are not a consideration in this genome analysis.

**Limitations**

- It reflects only the maternal lineage (in most plants) and misses paternal history and hybridization.
- It behaves as one non-recombining locus, so one plastome can misrepresent the species tree, for example after chloroplast capture.
- It has low variation for closely related species.
- It carries only about 110–130 genes, so it cannot explain most traits, which are controlled by nuclear genes.

**Research question where plastid data would be useful**

**Do plastid genomes from *Lycoris radiata* populations in China and Japan fall into distinct maternal lineages, and do these lineages match geography or the human spread of bulbs?**

Plastid genomes would be useful because they trace maternal lineages and are easy to compare between populations.

**Research question where nuclear genomic data would be more appropriate**

**Which genes control flower color or alkaloid production in *Lycoris*?**

Nuclear genomic data would be more appropriate because these traits are controlled by nuclear genes.

# 10. Plastid vs Mitochondrial Genome Comparison

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Cellular location** | Plastids | Mitochondria |
| **Main biological functions** | Photosynthesis genes, plastid transcription and translation | Respiration (oxidative phosphorylation), mitochondrial translation |
| **Typical genome organization** | Circular map with LSC, SSC and two IR copies (158,335 bp in *L. radiata*); in cells it can also exist as branched or linear forms | Highly variable; often a master circle plus smaller subgenomic molecules |
| **Relative genome size** | Small: about 120–170 kb (158,335 bp here) | Larger and highly variable in plants, from about 200 kb to several Mb |
| **Gene content** | 137 gene entries (112 unique) here; about 110–130 typical | About 50–60 genes in angiosperms |
| **Copy number** | Very high per cell (many plastids, many copies each) | Lower than plastid, varies by tissue |
| **Inheritance** | Mostly maternal in angiosperms; paternal or biparental in some lineages | Mostly maternal; varies among lineages |
| **Recombination / structural change** | Low; gene order conserved, with occasional IR expansion or contraction | High; frequent recombination between repeats and many rearrangements |
| **Mutation / substitution pattern** | Slow substitution rate, slower in the IR | Very slow substitution rate in plants, but fast structural change |
| **Common research application** | Phylogenetics, barcoding, maternal lineage tracking, plastid transformation | Cytoplasmic male sterility, respiration studies, some population studies |

# References

NCBI Nucleotide: https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1

usegalaxy.org: https://usegalaxy.org/u/inah.obineta2/h/plastid-lycoris-obiñeta

GitHub: https://github.com/iinahmariee/cmb-plastid-genome-Lycorsis-OBINETA/tree/GROUP-4

Daniell, H., Lin, C.-S., Yu, M., & Chang, W.-J. (2016). Chloroplast genomes: Diversity, evolution, and applications in genetic engineering. *Genome Biology, 17*, Article 134. https://doi.org/10.1186/s13059-016-1004-2

Gualberto, J. M., & Newton, K. J. (2017). Plant mitochondrial genomes: Dynamics and mechanisms of mutation. *Annual Review of Plant Biology, 68*, 225–252. https://doi.org/10.1146/annurev-arplant-043015-112232

National Center for Biotechnology Information. (2023). *Lycoris radiata chloroplast, complete genome* (NC_045077.1) [Nucleotide sequence]. NCBI RefSeq. Retrieved September 30, 2026, from https://www.ncbi.nlm.nih.gov/nuccore/NC_045077.1

Palmer, J. D., Adams, K. L., Cho, Y., Parkinson, C. L., Qiu, Y.-L., & Song, K. (2000). Dynamic evolution of plant mitochondrial genomes: Mobile genes and introns and highly variable mutation rates. *Proceedings of the National Academy of Sciences, 97*(13), 6960–6966. https://doi.org/10.1073/pnas.97.13.6960

Zhang, F., Shu, X., Wang, T., Zhuang, W., & Wang, Z. (2019). The complete chloroplast genome sequence of *Lycoris radiata*. *Mitochondrial DNA Part B, 4*(2), 2886–2887. https://doi.org/10.1080/23802359.2019.1660265
