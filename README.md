## PCSF Network Analysis of RNA-seq Differential Expression

This repository implements a **Prize-Collecting Steiner Forest (PCSF)**–based network analysis to identify **key regulatory subnetworks** underlying RNA-seq differential expression.

Starting from **DESeq2-derived differentially expressed genes**, the pipeline integrates:

- **Protein–protein interaction (PPI) networks** from STRING  
- **Transcription factor–target relationships**  
- **Gene-level prizes** derived from log2 fold changes and statistical significance  

Using **OmicsIntegrator / PCSF**, the analysis reconstructs **parsimonious, biologically meaningful subnetworks** that connect high-confidence differentially expressed genes through intermediate signaling and regulatory nodes.

### Key features
- DESeq2-based differential expression input  
- STRING-derived PPI network construction  
- Integration of TF–target regulatory edges  
- PCSF optimization to extract core signaling modules  
- Network analysis and visualization using `igraph`  

### Applications
- Identification of central regulators and pathway hubs  
- Network-level interpretation of RNA-seq data  
- Hypothesis generation for downstream functional validation  

> This repository focuses on **downstream network modeling and interpretation**.  
> Raw sequencing data are not included.
