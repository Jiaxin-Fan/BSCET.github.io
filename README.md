Detecting cell-type-specific AEI in bulk RNA-seq
======================

`BSCET` characterizes cell-type-specific allelic expression imbalance (AEI) in bulk RNA-seq data by integrating cell-type composition information inferred from scRNA-seq samples. As a two-step regression-based procedure, BSCET first performs cell-type deconvolution analysis to infer cell type composition in bulk RNA-seq data using scRNA-seq data as the reference. Second, given estimated cell type proportions in bulk RNA-seq samples, BSCET tests cell-type-specific AEI using allele-specific bulk RNA-seq read counts.

<p align="center"> 
<img src="./Figure.jpg?raw=true" width="500">
</p>

How to cite `BSCET`
-------------------
Please cite the following publication:

> *Detecting cell-type-specific allelic expression imbalance by integrative analysis of bulk and single-cell RNA sequencing data*<br />
> <small>J. Fan, X. Wang, R. Xiao, M. Li<br /></small>
> (https://www.biorxiv.org/content/10.1101/2020.08.26.267815v1) 

More Information
-----------------
Please see [Tutorial](https://jiaxin-fan.github.io/BSCET.github.io/Introduction.html).

***