<!-- README.md is generated from README.Rmd. Please edit that file -->

# Demonstration dataset for SVP

- `pdac_a_spe`: This is a `SpatialExperiement` object, which contains
  the gene counts of spatial transcriptome of a PDAC (sample A) from the
  [article](https://www.nature.com/articles/s41587-019-0392-8).

- `pdac_a_sce`: This is a `SingleCellExperiment` object, which contains
  the gene counts of single-cell transcriptome of a PDAC (sample A) from
  the same [article](https://www.nature.com/articles/s41587-019-0392-8).

# Usage

\|\> Note: In the `R` environment

``` r
# load spatial transcriptome
load(url("https://github.com/xiangpin/Data_for_Vignette_SVP/blob/main/data/pdac_a_spe.rda?raw=true"))

# load single-cell transcriptome
load(url("https://github.com/xiangpin/Data_for_Vignette_SVP/blob/main/data/pdac_a_sce.rda?raw=true"))
```
