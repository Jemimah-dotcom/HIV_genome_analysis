# HIV_genome_analysis
HIV-1 genome analysis including nucleotide composition, GC content, BLAST-based similarity analysis, pairwise alignment, and mutation profiling.
## Overview
This project explores the HIV-1 genome using core bioinformatics techniques.  
The analysis focuses on understanding nucleotide composition, sequence similarity, pairwise alignment, and mutation patterns by comparing a query HIV-1 genome with a reference genome.
This project is part of my bioinformatics learning journey, moving from beginner-level sequence analysis to more intermediate concepts.

## Data Sources 📂
- HIV-1 complete genome sequence (NCBI GenBank)
- HIV-1 reference genome (NCBI GenBank)

## Methods & Workflow ⚙️
### 1️⃣ Sequence Composition Analysis
- Counted nucleotide frequencies (A, T, G, C) for both query and reference genomes
- Calculated and compared GC content between the two sequences
### 2️⃣ Sequence Similarity Analysis (BLAST)
- Performed BLASTn to compare the HIV-1 genome against reference databases
- Examined alignment length, gaps, and conserved regions
- Inspected coding sequence (CDS) regions including **gag**, **pol**, and **env**
### 3️⃣ Pairwise Alignment
- Conducted pairwise alignment between the query and reference HIV-1 genomes
- Visualized gaps and conserved regions
- Compared sequence lengths and alignment structure
### 4️⃣ Mutation Analysis
- Identified nucleotide-level mutations between query and reference sequences
- Generated a mutation table with reference and query bases
- Counted total mutations and summarized mutation distribution
### 5️⃣ Gene-Level Mutation Summary
- Mapped mutations to gene regions (e.g., gag, pol, env, intergenic)
- Visualized mutation counts per gene using bar plots

---

## Visualizations 📊

### Mutation Distribution by Nucleotide
This bar chart shows the frequency of observed mutations across nucleotide bases (A, T, G, C) in the HIV-1 genome.

### Mutation Distribution Across HIV-1 Genes
This visualization highlights how mutations are distributed across major HIV-1 genes and intergenic regions.

---

## Tools & Libraries 🛠️
- Python
- Biopython
- Pandas
- Matplotlib
- Jupyter Notebook

---
## Key Findings & Biological Insights 🧠
- Both the query and reference HIV-1 genomes showed a higher abundance of adenine (A), reflecting known nucleotide bias in retroviral genomes.
- GC content was relatively low compared to AT content, consistent with HIV-1’s RNA-based genome and its evolutionary adaptation to host cellular machinery.
- Pairwise alignment revealed regions of strong conservation alongside large gaps, particularly within coding regions such as **gag**, **pol**, and **env**, highlighting functional constraints on essential viral proteins.
- The **pol** gene showed a high mutation burden, which aligns with its role in viral replication enzymes and its known association with drug resistance.
- Intergenic regions displayed comparatively fewer functional constraints, allowing for greater sequence variability.
- BLAST analysis confirmed close similarity to known HIV-1 reference genomes while revealing sequence-level divergence at specific loci.
---

## Next Steps 🚀
- SARS-CoV-2 genome analysis
- Differential expression (DE) analysis
- Volcano plots and comparative viral genomics
- Differential expression (DE) analysis
- Volcano plots and comparative viral genomics
