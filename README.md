

# Desiccation-Responsive Transcriptomic and Proteomic Analysis of *Bryum argenteum*

## Overview

This project investigates the molecular response of *Bryum argenteum* to desiccation stress using RNA-Seq and protein modeling approaches. It integrates transcriptome analysis to identify differentially expressed genes (DEGs) and structural analysis of stress-related proteins, such as LEA proteins.

---

## Objectives

- Identify key genes involved in desiccation tolerance.
- Analyze differential gene expression using RNA-Seq data.
- Perform GO/KEGG enrichment analysis to determine affected pathways.
- Predict and visualize 3D structures of desiccation-related proteins.

---

## Tools & Technologies

| Category                  | Tools Used                                               |
|---------------------------|----------------------------------------------------------|
| Data Retrieval            | NCBI GEO, SRA, ENA                                       |
| Quality Control           | FastQC, Trimmomatic                                      |
| Alignment                 | HISAT2, STAR, SAMtools                                   |
| Read Counting             |  HTSeq FeatureCounts,                                      |
| Differential Expression   | DESeq2 (R Bioconductor)                                  |
| Functional Annotation     | g:Profiler, DAVID, Blast2GO                              |
| Protein Domain Analysis   | InterPro, Pfam, BLASTp                                   |
| Structure Prediction      | SWISS-MODEL, AlphaFold                                   |
| Visualization             | UCSF Chimera, PyMOL, Cytoscape, ggplot2 (R)              |

---

## Pipeline Summary

### 1. RNA-Seq Data Analysis

- Retrieved raw desiccation/control RNA-Seq datasets.
- Performed quality check and trimming.
- Aligned reads to reference genome using HISAT2.
- Counted gene expression levels using FeatureCounts.
- Identified DEGs with DESeq2.
- Visualized DEGs using volcano plots and heatmaps.
- Performed GO and KEGG enrichment analysis on significant genes.

### 2. Protein Modeling

- Retrieved amino acid sequences of LEA and stress-related proteins.
- Annotated domain structures via InterPro and Pfam.
- Predicted 3D models using SWISS-MODEL and AlphaFold (if available).
- Visualized models in UCSF Chimera/PyMOL for interpretation.

---

## Key Findings

- Upregulation of LEA, antioxidant, and osmoprotectant genes under desiccation.
- Enrichment of pathways related to stress response, water retention, and ROS detoxification.
- LEA proteins modeled showed hydrophilic, flexible structures—suitable for protecting cellular machinery.

---

## Future Directions

- Validate key DEGs using qPCR.
- Comparative analysis with other moss species.
- Experimental protein purification and structure validation.

---

## Credits

- RNA-Seq datasets retrieved from NCBI GEO/SRA.
- Bioinformatics analysis conducted using open-source tools.


---

## License

This project is for academic and educational purposes.


---