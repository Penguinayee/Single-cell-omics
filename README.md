# single-cell-omics

This repo is aim to store some useful tools that I adopted/modified in analyzing single-cell omics data.

### [Seurat_Vizgen-FFPE-showcase_breast_cancer](https://github.com/Penguinayee/single-cell-omics/blob/941db43a6bdebaf0f838a96e282178b46aac6dcf/Seurat_Vizgen-FFPE-showcase_breast_cancer.ipynb)
To perform spatial transcriptomic analysis, Seurat's [vignette](https://satijalab.org/seurat/articles/spatial_vignette_2.html#mouse-brain-vizgen-merscope) propose a way of creating the Seurat object. Rather than downloading the whole dataset, which can consist of massive image data, the cell-by-gene and cell-metadata tables can be used to construct the Seurat object (1.58 GB and 99 MB, respectively, sourced from the [Human breast cancer data of Vizgen](https://vizgen.com/data-release-program/)). This approach saves time and enables quicker exploratory studies, as it eliminates the requirement of downloading cumbersome image files.
