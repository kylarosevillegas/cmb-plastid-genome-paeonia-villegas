# Characterization of the Plastid Genome of *Paeonia suffruticosa*

**Name:** Villegas, Kyla Rose D.  
**Course:** Cell & Molecular Biology  
**Activity:** Characterization of a Plastid Genome  

---

## Question 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size.

The selected organism is *Paeonia suffruticosa*, commonly known as tree peony. It belongs to the family **Paeoniaceae**. The complete chloroplast genome was obtained from the **NCBI Reference Sequence (RefSeq)** database under accession **NC_037879.1**. The complete plastid genome has a length of **153,119 bp** and is reported as circular.

---

## Question 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record identifies NC_037879.1 as the **complete chloroplast genome of *Paeonia suffruticosa***. It is reported as a circular DNA molecule with a length of 153,119 bp, and the record states that the sequence is full length. The sequence is also annotated with many chloroplast genes involved in photosynthesis, electron transport, ATP synthesis, transcription, translation, and RNA processing.

The Galaxy analysis also supports this interpretation because the uploaded FASTA contains **one sequence record**, is **153,119 bp** long, and contains **0 gaps and 0 N bases**. These observations support that the sequence represents a complete plastid genome rather than a short barcode marker or genome fragment.

---

## Question 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement?

The plastid genome has the typical quadripartite organization of an angiosperm chloroplast genome:

**LSC – IR – SSC – IR**

The annotated regions of NC_037879.1 are:

| Region | Size |
|---|---:|
| Large Single-Copy (LSC) | 84,564 bp |
| Inverted Repeat B (IRb) | 25,751 bp |
| Small Single-Copy (SSC) | 17,059 bp |
| Inverted Repeat A (IRa) | 25,745 bp |
| **Total** | **153,119 bp** |

The two IR regions are nearly equal in size and contain duplicated portions of the plastid genome.

---

## Question 4. Summarize the annotated gene content and explain why IR genes may appear in two copies.

The annotation contains **131 gene features**, including **83 CDS features, 37 tRNA features, and 8 rRNA features**. No gene feature was explicitly annotated as a pseudogene in the record used for this analysis.

Some genes occur in two copies because they are located within the two inverted-repeat regions. Since IRa and IRb contain repeated DNA sequences, genes located within these regions can be present once in each IR.

---

## Question 5. Choose at least eight protein-coding plastid genes from different functional groups and explain their functions.

| Gene | Functional group | Function |
|---|---|---|
| **psaA** | Photosystem I | Encodes a core component of photosystem I involved in light-driven electron transfer. |
| **psbA** | Photosystem II | Encodes a core photosystem II protein involved in photosynthesis. |
| **atpA** | ATP synthase | Encodes a component of ATP synthase involved in ATP production. |
| **petA** | Electron transport | Encodes a component of the cytochrome b6f complex involved in photosynthetic electron transport. |
| **rbcL** | Carbon fixation | Encodes the large subunit of Rubisco involved in carbon fixation. |
| **rpoB** | Transcription | Encodes a subunit of the plastid RNA polymerase. |
| **rpl2** | Translation | Encodes a ribosomal protein involved in plastid protein synthesis. |
| **matK** | RNA processing | Encodes a maturase associated with processing intron-containing RNAs. |

---

## Question 6. Identify important RNA and RNA-processing features.

The plastid genome contains **8 rRNA features** and **37 tRNA features**. The major rRNA genes include **rrn16, rrn23, rrn4.5, and rrn5**.

Examples of tRNA genes include **trnH, trnK, trnL, trnM, trnN, trnF, trnS, trnT, trnE, trnD, trnC, trnQ, and trnY**.

Several genes contain introns that require RNA processing. Examples include **rps16, atpF, rpoC1, ycf3, clpP, petB, petD, and ndhA**. The **rps12** gene is also notable because it has a trans-spliced organization.

---

## Question 7. Describe pseudogenes, gene losses, duplications, rearrangements, or other unusual features.

No gene feature in the NC_037879.1 annotation was explicitly marked as a pseudogene.

The major duplication is associated with the two inverted-repeat regions. Genes located in the IRs can occur in two copies. The genome also contains intron-containing genes and the trans-spliced **rps12** gene, which are notable features of plastid genomes.

The overall genome retains the typical conserved organization of an angiosperm chloroplast genome.

---

## Question 8. What is the GC content? Give two other notable observations.

The overall GC content obtained from the Galaxy FASTA Statistics analysis is **38.38%**.

Two notable observations are:

1. The genome consists of **one sequence record** with a length of **153,119 bp**.
2. The sequence contains **0 gaps and 0 N bases**, indicating that there are no ambiguous or missing nucleotide positions in the uploaded FASTA.

The annotation also shows the characteristic **LSC–IR–SSC–IR** organization.

---

## Question 9. Compare plastid and mitochondrial genomes.

### Similarities

1. Both are organelle genomes.
2. Both contain their own DNA.
3. Both contain genes needed for organelle functions.
4. Both can occur in multiple copies within plant cells.
5. Both can be used in evolutionary and phylogenetic studies.

### Differences

| Feature | Plastid genome | Mitochondrial genome |
|---|---|---|
| Organelle | Chloroplast/plastid | Mitochondrion |
| Main function | Photosynthesis and related plastid functions | Cellular respiration and oxidative phosphorylation |
| Organization | Commonly has LSC–IR–SSC–IR structure | Highly variable in plants |
| Size | Generally compact | Usually much larger and more variable in plants |
| Gene content | Includes photosynthesis, electron transport, ATP synthesis, transcription, and translation genes | Mainly contains genes associated with respiration and mitochondrial gene expression |
| Structural variation | Generally more conserved | Often highly dynamic |
| Research uses | Plant identification, phylogeny, systematics, and comparative genomics | Mitochondrial evolution, inheritance, and genome rearrangement studies |

---

## Question 10. Explain the practical value of plastid genomes, their advantages and limitations, and give research questions.

Plastid genomes are useful in plant identification, DNA barcoding, phylogenetic analysis, systematics, evolutionary studies, population studies, and comparative genomics. A complete plastid genome provides more information than using only a single barcode region.

### Advantages

- Relatively small compared with nuclear genomes
- Generally more conserved in organization
- Contains many genes useful for phylogenetic studies
- Useful for plant identification and systematics
- Useful for comparing plant species and lineages
- Can provide information about cytoplasmic genetic lineages
- Easier to analyze than a complete nuclear genome

### Limitations

Plastid genomes represent only the plastid genetic compartment and therefore do not contain the complete genetic information of the organism. Plastid inheritance can vary among plant groups. Plastid data are therefore not sufficient for studying many traits controlled primarily by nuclear genes.

The nuclear genome is much larger and contains most of the organism's genetic information, including the **nuclear sex chromosomes** where applicable. Nuclear genomic data are more appropriate for questions involving genome-wide variation, complex traits, and nuclear-controlled characteristics.

### Research question suitable for plastid data

**How are different *Paeonia* species or cultivars related based on their complete chloroplast genomes?**

### Research question suitable for nuclear genomic data

**Which nuclear genetic variants are associated with variation in a complex trait among *Paeonia* plants?**

---

## Galaxy Analysis

**Galaxy History:** `Plastid_Paeonia_Villegas`

**Uploaded Dataset:** `Paeonia_suffruticosa_NC_037879.1`

### Galaxy FASTA Statistics

| Statistic | Result |
|---|---:|
| Genome length | 153,119 bp |
| Sequence records | 1 |
| GC content | 38.38% |
| Gaps | 0 |
| N bases | 0 |
| N50 | 153,119 bp |
| L50 | 1 |

---

## References

1. **NCBI RefSeq.** *Paeonia suffruticosa* chloroplast, complete genome. Accession NC_037879.1.  
   https://www.ncbi.nlm.nih.gov/nuccore/NC_037879.1

2. **Galaxy Project.**  
   https://usegalaxy.org/

3. **Galaxy Training Network.**  
   https://training.galaxyproject.org/

---

## Reproducibility

The complete chloroplast genome was retrieved from NCBI using accession **NC_037879.1**. The FASTA sequence was uploaded to the Galaxy history `Plastid_Paeonia_Villegas` and analyzed using FASTA Statistics. The resulting sequence statistics and annotated GenBank information were used to characterize the plastid genome. The sequence, screenshots, results, and report are organized in this GitHub repository.
