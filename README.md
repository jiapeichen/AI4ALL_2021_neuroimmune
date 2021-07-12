# AI4ALL_2021_neuroimmune
Data and relevant code examples for UCSF AI4ALL 2021 summer program

### Data source
Heming, M., Li, X., Räuber, S., Mausberg, A. K., Börsch, A. L., Hartlehnert, M., … Meyer zu Hörste, G. (2021). Neurological Manifestations of COVID-19 Feature T Cell Exhaustion and Dedifferentiated Monocytes in Cerebrospinal Fluid. Immunity. https://doi.org/10.1016/j.immuni.2020.12.011

### Data download
Raw data and annotations downloaded from https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE163005

### Data preprocessing
- Annotations are paired with count matrix in a Seurat object
- Gene counts are normalized and split into 3 different cell types: mono2 (monocytes), treg (T regulatory cells), and cd4 (CD4+ T cells, downsized to 2000 cells for easy computation)
- Dx (diagnosis) labels are COVID, IIH, MS, VE

### Resources
- Download R: https://www.r-project.org/
- Download R studio: https://www.rstudio.com/products/rstudio/download/
- Crash course on R basics: https://www.youtube.com/watch?v=ZYdXI1GteDE
- Seurat tutorial: https://satijalab.org/seurat/articles/pbmc3k_tutorial.html
