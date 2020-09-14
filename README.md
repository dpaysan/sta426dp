# Course work for the STA426DP module
---
This is repository is intended to document the course work by the author for the course [STA426DP](https://studentservices.uzh.ch/uzh/anonym/vvz/index.html#/details/2020/003/SM/50727733).

The course covers a range of topics "including basic molecular biology, genomics technologies and in particular, a wide range of statistical and computational methods that have been used in the analysis of DNA microarray, high throughput sequencing and cytometry experiments."<sup>1</sup>

---
An essential component of the course work will be a project report that should also include publication-ready figures that convey the results of the applied statistical analysis. The following provides an example of such a figure<sup>2<sup>.
  
  
  
  
<p align="center">
  
  <img align="center" src="https://www.biorxiv.org/content/biorxiv/early/2019/12/18/2019.12.13.875922/F2.large.jpg" alt="Yang et al.(2019)" width="600"/>

</p>

  
  
Additionally it might necessary to display some equations like e.g. the definition for Pearson correlation coefficient

<p align="center">
  
  <a href="https://www.codecogs.com/eqnedit.php?latex=\rho_{XY}=\frac{Cov(X,Y)}{\sigma_X\sigma_Y}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho_{XY}=\frac{Cov(X,Y)}{\sigma_X\sigma_Y}" title="\rho_{XY}=\frac{Cov(X,Y)}{\sigma_X\sigma_Y}" align="center" /></a>

</p>

or some code to e.g. install some software packages to be used for the analysis by R when documenting the work like e.g.

```r
(!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("M3C")
```



---
## Sources
1. [Course Catalogue UZH](https://studentservices.uzh.ch/uzh/anonym/vvz/index.html#/details/2020/003/SM/50727733)
2. [Yang et al.: "Multi-Domain Translation between Single-Cell Imaging and Sequencing Data using Autoencoders." bioRxiv 2019.12.13.875922 (2019)](https://www.biorxiv.org/content/10.1101/2019.12.13.875922v1.full)
