# single-cell-omics

This repo is aim to store some useful tools that I adopted in analyzing single-cell omics data.

1. Vizgen FFPE-showcase_breast_cancer R.ipynb
    To perform spatial transcriptomic analysis, Seurat's guidelines propose a way of creating the Seurat object (https://satijalab.org/seurat/articles/spatial_vignette_2.html#mouse-brain-vizgen-merscope). Rather than downloading the whole dataset, which can consist of massive image data, the cell-by-gene and cell-metadata tables can be used to construct the Seurat object (1.58 GB and 99 MB, respectively, sourced from the Human breast cancer data of Vizgen, https://vizgen.com/data-release-program/). This approach saves time and enables quicker exploratory studies, as it eliminates the requirement of downloading cumbersome image files.
