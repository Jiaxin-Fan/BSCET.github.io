# BSCET.github.io

integrative analysis of Bulk and Single-cell RNA-seq data to detect CEll-Type-specific allelic expression imbalance (BSCET)
======================

`BSCET` characterizes cell-type-specific allelic expression imbalance (AEI) in bulk RNA-seq data by integrating cell-type composition information inferred from scRNA-seq samples. As a two-step regression-based procedure, BSCET first performs cell-type deconvolution analysis to infer cell type composition in bulk RNA-seq data using scRNA-seq data as the reference. Second, given estimated cell type proportions in bulk RNA-seq samples, BSCET tests cell-type-specific AEI using allele-specific bulk RNA-seq read counts.

<p align="center"> 
<img src="https://github.com/Jiaxin-Fan/BSCET/raw/master/Figure.jpeg" width="500">
</p>

How to cite `BSCET`
-------------------
Please cite the following publication:

> *Detecting cell-type-specific allelic expression imbalance by integrative analysis of bulk and single-cell RNA sequencing data*<br />
> <small>J. Fan, X. Wang, R. Xiao, M. Li<br /></small>

Installation
------------

``` r
# install devtools if necessary
if (!"devtools" %in% rownames(installed.packages())) {
  install.packages('devtools')
}
# install the BSCET package
if (!"BSCET" %in% rownames(installed.packages())) {
  devtools::install_github('Jiaxin-Fan/BSCET')
}
# load
library(BSCET)
```

More Information
-----------------
Please see [Tutorial](https://jiaxin-fan.github.io/BSCET/introduction.html).