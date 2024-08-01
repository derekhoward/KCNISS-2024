# KCNI Summer School 2024
## Intro to Single Cell Transcriptomics

**Analysis of human brian single cell gene expression data in health and disease.** 
Day1: How to define celltypes using gene expression?
Day2: How can we use single cell data to define cell-type specific gene expression changes in brain disorders?

### What’s this project about? 

**Main idea:** perform analysis of two human neocortical single-cell datasets, which will lead into an analysis of cell type-specific differential gene expression between individuals with dementia and controls.

**Key questions:**

1. How can we visualize and define cell-types by their gene expression patterns?

2. How does cell type-specific gene expression change in the context of dementia?
    - What types of genes are most affected by the condition within a given cell type?

**What datasets are available to help answer these questions?**

- [Allen Institute for Brain Sciences Cell Types database](https://celltypes.brain-map.org/)

- [Human Multiple Cortical Areas SMART-seq](https://portal.brain-map.org/atlases-and-data/rnaseq/human-multiple-cortical-areas-smart-seq)

-  [Human MTG 10x SEA-AD](https://portal.brain-map.org/atlases-and-data/rnaseq/human-mtg-10x_sea-ad)

## Resources

Seurat tutorials:

- [Dataset integration workflow](https://satijalab.org/seurat/articles/integration_introduction.html)

- [Differential expression analysis](https://satijalab.org/seurat/articles/de_vignette.html)

- [Data visualization methods](https://satijalab.org/seurat/articles/visualization_vignette.html)

- [Cell type annotation](https://satijalab.org/seurat/articles/integration_mapping.html)

- [Pseudobulk differential expression tutorial](https://hbctraining.github.io/scRNA-seq/lessons/pseudobulk_DESeq2_scrnaseq.html)

## Datasets
Download the datasets from:
https://drive.google.com/drive/folders/1VOGGuPjDT49vz95mk4huWOIX9s9-FIQ8?usp=sharing

Put the datasets in the `data/` directory of this project.

Your working directory should look like this:
```
KCNISS-2024
├── data
│   ├── AIBS_smart_counts_mini.csv
│   ├── AIBS_smart_meta_mini.csv
│   ├── astro_pseudobulk
│   │   ├── astro_pseudobulk.csv
│   │   ├── astro_pseudobulk_gene_info.csv
│   │   └── astro_pseudobulk_meta_updated.csv
│   ├── SEA-AD_10x_counts_mini.csv
│   ├── SEA-AD_10x_meta_mini.csv
├── KCNISS-2024.Rproj
├── part1.Rmd
├── part2.Rmd
├── part3.Rmd
└── README.md
```

## Schedule
**Part 1:** Intro to single-cell RNAseq analysis, R, and Seurat

**Part 2:** Intro to differential expression, cell type identification & visualizations

**Part 3:** Case-control differential expression with pseudobulks

