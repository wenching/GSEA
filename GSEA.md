---
title: "Gene Set Enrichment Analysis"
author:
  - name: Wenching Calvin Chan, Ph.D.  
    affiliation: Center for Research Informatics, University of Chicago, Chicago, IL 60637  
    email: wchan10@bsd.uchicago.edu  
date: "21 February, 2019"
package: "Gene Set Enrichment Analysis"
abstract: >
  - TBC
output:
  html_document:
    theme: united
    highlight: tango
    number_sections: true
    df_print: paged
    toc: true
    toc_depth: 3
    toc_float:
      collapsed: true
      smooth_scroll: false
    keep_md: true
bibliography: GSEA.bib
always_allow_html: yes
vignette: >
  %\VignetteIndexEntry{GSEA}
  %\VignetteEngine{knitr::rmarkdown}
  %\VignetteEncoding{UTF-8}
---



<a name="Top"/>


\newpage


[Top](#Top)

\newpage



# Enrichment Analysis

***

* *[clusterProfiler](https://bioconductor.org/packages/3.8/clusterProfiler)*: statistical analysis and visualization of functional profiles for genes and gene clusters

[What is GeneRatio and BgRatio?](https://www.biostars.org/p/220465/)

<img src="IMG/clusterProfiler.GeneRatio.BgRatio.png" width="100%" />
  
**Figure 1: GeneRatio & BgRatio in clusterProfiler** GeneRatio = $\frac{M}{N}$ & BgRatio = $\frac{k}{n}$

[Top](#Top)


# Session information


<!-- \blandscape -->

```
## R version 3.5.1 (2018-07-02)
## Platform: x86_64-apple-darwin15.6.0 (64-bit)
## Running under: macOS  10.14.3
## 
## Matrix products: default
## BLAS: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRblas.0.dylib
## LAPACK: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRlapack.dylib
## 
## locale:
## [1] en_GB.UTF-8/en_GB.UTF-8/en_GB.UTF-8/C/en_GB.UTF-8/en_GB.UTF-8
## 
## attached base packages:
## [1] grid      stats     graphics  grDevices utils     datasets  methods  
## [8] base     
## 
## other attached packages:
## [1] captioner_2.2.3.9000 dplyr_0.7.8          png_0.1-7           
## [4] kableExtra_1.0.1     knitr_1.21          
## 
## loaded via a namespace (and not attached):
##  [1] Rcpp_1.0.0         BiocManager_1.30.4 pillar_1.3.1      
##  [4] compiler_3.5.1     bindr_0.1.1        tools_3.5.1       
##  [7] digest_0.6.18      evaluate_0.12      tibble_2.0.1      
## [10] viridisLite_0.3.0  pkgconfig_2.0.2    rlang_0.3.1       
## [13] rstudioapi_0.9.0   yaml_2.2.0         xfun_0.4          
## [16] bindrcpp_0.2.2     httr_1.4.0         stringr_1.3.1.9000
## [19] xml2_1.2.0         hms_0.4.2          webshot_0.5.1     
## [22] tidyselect_0.2.5   glue_1.3.0         R6_2.3.0          
## [25] rmarkdown_1.11     readr_1.3.1        purrr_0.3.0       
## [28] magrittr_1.5       scales_1.0.0       htmltools_0.3.6   
## [31] assertthat_0.2.0   rvest_0.3.2        BiocStyle_2.10.0  
## [34] colorspace_1.4-0   stringi_1.2.4      munsell_0.5.0     
## [37] crayon_1.3.4
```
<!-- \elandscape -->



[Top](#Top)



# Reference  


