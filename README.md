# Generalized best practices workflow (Luecken & Theis, 2019)
FASTGenomics presents a generalized best practice workflow for the preprocessing of single-cell RNA-seq data. It is a simplified and slightly modified version of the single-cell-tutorial as presented in 'Best practices in single-cell RNA-seq analysis: a tutorial' by Luecken and Theis (2019).


## Workflow
In this simplified best practices preprocessing workflow, we go through the typical first steps of a scRNA-seq data analysis workflow. We start with general preprocessing steps, which include cell and gene quality control, normalization, batch correction, selection of highly variable genes, visualization, and cell cycle scoring. In these steps the overall structure of the data is explored and filtered to produce optimal downstream analysis results. With the clustering of the data and application of PAGA, we also have a glimpse of the downstream scRNA-seq analysis.

The calculation steps are documented in detail in Luecken & Theis (2019). For the sake of generality, we here restrict the analysis (mostly) to the upstream analysis, namely
1. Load the data
2. Pre-processing and visualization
	1. Quality Control
	2. Normalization
	3. Batch correction
	4. Highly variable genes
	5. Visualization
	6. Cell cycle scoring
3. Downstream analysis
	1. Clustering
	2. Marker genes & cluster annotation
	3. Partition-based graph abstraction
4. Save results
5. Summary


## Datasets
This FASTGenomics app runs successfully on several datasets that are available from FASTGenomics, namely
* 3k PBMCs 10x
* Haber et al. (2017)
* Mass et al. (2016)
* Paul et al. (2015)
* Tirosh et al. (Nature, 2016)
* Tirosh et al. (Science, 2016)
* Zeisel et al. (2015)