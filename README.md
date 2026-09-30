# Characterization of the Plastid Genome of *Paeonia suffruticosa*

## Student Information

**Name:** Villegas, Kyla Rose D.  
**Course:** Cell & Molecular Biology  
**Activity:** Characterization of a Plastid Genome  
**Genus:** *Paeonia*  
**Species:** *Paeonia suffruticosa*  
**Family:** Paeoniaceae  

## 1. Selected Plastid Genome

The selected organism is *Paeonia suffruticosa* (tree peony). The complete chloroplast genome was obtained from the NCBI Reference Sequence (RefSeq) database.

**NCBI Accession:** NC_037879.1  
**Genome:** Complete chloroplast genome  
**Genome Size:** 153,119 bp  
**Topology:** Circular  
**Source:** NCBI RefSeq  

NCBI Record: https://www.ncbi.nlm.nih.gov/nuccore/NC_037879.1

## 2. Genome Sequence

The complete plastid genome sequence was downloaded from NCBI in FASTA format and uploaded to Galaxy for sequence statistics.

The FASTA analysis produced the following results:

| Statistic | Result |
|---|---:|
| Genome length | 153,119 bp |
| Number of sequence records | 1 |
| GC content | 38.38% |
| Number of gaps | 0 |
| Number of N bases | 0 |
| N50 | 153,119 bp |
| L50 | 1 |

## 3. Galaxy Analysis

The FASTA sequence was analyzed using Galaxy.

**Galaxy History:** `Plastid_Paeonia_Villegas`

The uploaded dataset was named:

`Paeonia_suffruticosa_NC_037879.1`

The Galaxy results confirmed that the FASTA contains one continuous sequence of 153,119 bp with no gaps or ambiguous N bases.

## 4. Plastid Genome Organization

The *Paeonia suffruticosa* chloroplast genome follows the typical organization of an angiosperm plastid genome, consisting of a Large Single-Copy (LSC) region, two Inverted Repeat (IR) regions, and a Small Single-Copy (SSC) region.

The general organization is:

**LSC – IR – SSC – IR**

The region sizes and gene annotations were examined using the annotated GenBank record for NC_037879.1.

## 5. Gene Content and Functional Groups

The annotated plastid genome contains genes involved in photosynthesis, ATP synthesis, electron transport, transcription, translation, RNA processing, and other plastid functions.

Examples of protein-coding genes include:

- **psaA** – photosystem I
- **psbA** – photosystem II
- **atpA** – ATP synthase
- **petA** – electron transport
- **rbcL** – carbon fixation
- **rpoB** – transcription
- **rpl2** – ribosomal protein
- **matK** – RNA processing

The genome also contains transfer RNA (tRNA) and ribosomal RNA (rRNA) genes required for plastid gene expression and protein synthesis.

## 6. RNA and RNA-Processing Features

Important RNA genes include the ribosomal RNA genes **rrn16, rrn23, rrn4.5, and rrn5**, as well as numerous tRNA genes.

Several genes contain introns that must be removed during RNA processing. Examples include **rps16, atpF, clpP, ycf3, and rps12**.

## 7. Genome Observations

The Galaxy analysis showed an overall GC content of **38.38%**.

The genome is represented by a single sequence record measuring **153,119 bp**, with **0 gaps** and **0 N bases**. The complete circular chloroplast genome also has the characteristic LSC–IR–SSC–IR organization.

## 8. Galaxy Screenshots

The Galaxy analysis screenshots are stored in the `figures` folder.

- `01_Galaxy_FASTA_Statistics.png`
- `02_Galaxy_Sequence_Statistics.png`

## 9. Data Organization

```text
cmb-plastid-genome-paeonia-villegas/
├── data/
│   └── Paeonia_suffruticosa_NC_037879.1.fasta
├── figures/
│   ├── 01_Galaxy_FASTA_Statistics.png
│   ├── 02_Galaxy_Sequence_Statistics.png
│   └── README.md
├── results/
│   └── README.md
├── report/
│   └── README.md
└── README.md
## References and Links

- NCBI RefSeq: https://www.ncbi.nlm.nih.gov/nuccore/NC_037879.1
- Galaxy: https://usegalaxy.org/
- Galaxy Training Network: https://training.galaxyproject.org/
- GitHub: https://github.com/

## Reproducibility

The complete chloroplast genome was retrieved from NCBI using accession **NC_037879.1**. The FASTA sequence was uploaded to the student's Galaxy account under the history `Plastid_Paeonia_Villegas` and analyzed using FASTA statistics. The sequence data, Galaxy screenshots, results, and report are organized in this repository to document the workflow and support reproducibility.
