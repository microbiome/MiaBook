# (PART) Appendix {-}

# Example data {#example-data}

<script>
document.addEventListener("click", function (event) {
    if (event.target.classList.contains("rebook-collapse")) {
        event.target.classList.toggle("active");
        var content = event.target.nextElementSibling;
        if (content.style.display === "block") {
            content.style.display = "none";
        } else {
            content.style.display = "block";
        }
    }
})
</script>

<style>
.rebook-collapse {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.rebook-content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>

## Package data {#package-data}

The datasets in `mia` are conversions of the `phyloseq` datasets 
`GlobalPatterns` `enterotype`, `esophagus` and `soilrep`.

### GlobalPatterns


```r
library(mia)
# Example how to load data
data("GlobalPatterns")

GlobalPatterns
```

```
## class: TreeSummarizedExperiment 
## dim: 19216 26 
## metadata(0):
## assays(1): counts
## rownames(19216): 549322 522457 ... 200359 271582
## rowData names(7): Kingdom Phylum ... Genus Species
## colnames(26): CL3 CC1 ... Even2 Even3
## colData names(7): X.SampleID Primer ... SampleType Description
## reducedDimNames(0):
## altExpNames(0):
## rowLinks: a LinkDataFrame (19216 rows)
## rowTree: a phylo (19216 leaves)
## colLinks: NULL
## colTree: NULL
```

### Enterotype


### Esophagus


### Soilrep


## Session Info {-}

<button class="rebook-collapse">View session info</button>
<div class="rebook-content">
```
R version 4.0.3 (2020-10-10)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 20.04.1 LTS

Matrix products: default
BLAS/LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.8.so

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
 [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
 [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=C             
 [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C            
[11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] parallel  stats4    stats     graphics  grDevices utils     datasets 
[8] methods   base     

other attached packages:
 [1] mia_0.98.21                      MicrobiomeExperiment_0.99.0.9014
 [3] Biostrings_2.58.0                XVector_0.30.0                  
 [5] TreeSummarizedExperiment_1.6.2   SingleCellExperiment_1.12.0     
 [7] SummarizedExperiment_1.20.0      Biobase_2.50.0                  
 [9] GenomicRanges_1.42.0             GenomeInfoDb_1.26.2             
[11] IRanges_2.24.1                   S4Vectors_0.28.1                
[13] BiocGenerics_0.36.0              MatrixGenerics_1.2.0            
[15] matrixStats_0.57.0               BiocStyle_2.18.1                
[17] rebook_1.0.0                     BiocManager_1.30.10             

loaded via a namespace (and not attached):
 [1] viridis_0.5.1               tidyr_1.1.2                
 [3] BiocSingular_1.6.0          splines_4.0.3              
 [5] viridisLite_0.3.0           DelayedMatrixStats_1.12.1  
 [7] scuttle_1.0.4               vipor_0.4.5                
 [9] GenomeInfoDbData_1.2.4      DirichletMultinomial_1.32.0
[11] yaml_2.2.1                  pillar_1.4.7               
[13] lattice_0.20-41             glue_1.4.2                 
[15] beachmat_2.6.4              digest_0.6.27              
[17] colorspace_2.0-0            htmltools_0.5.0            
[19] Matrix_1.3-0                XML_3.99-0.5               
[21] pkgconfig_2.0.3             bookdown_0.21              
[23] zlibbioc_1.36.0             purrr_0.3.4                
[25] scales_1.1.1                processx_3.4.5             
[27] BiocParallel_1.24.1         tibble_3.0.4               
[29] mgcv_1.8-33                 generics_0.1.0             
[31] ggplot2_3.3.3               ellipsis_0.3.1             
[33] magrittr_2.0.1              crayon_1.3.4               
[35] CodeDepends_0.6.5           evaluate_0.14              
[37] ps_1.5.0                    MASS_7.3-53                
[39] nlme_3.1-151                vegan_2.5-7                
[41] beeswarm_0.2.3              graph_1.68.0               
[43] tools_4.0.3                 scater_1.18.3              
[45] lifecycle_0.2.0             stringr_1.4.0              
[47] munsell_0.5.0               cluster_2.1.0              
[49] DelayedArray_0.16.0         irlba_2.3.3                
[51] callr_3.5.1                 compiler_4.0.3             
[53] rsvd_1.0.3                  rlang_0.4.10               
[55] grid_4.0.3                  RCurl_1.98-1.2             
[57] BiocNeighbors_1.8.2         bitops_1.0-6               
[59] rmarkdown_2.6               gtable_0.3.0               
[61] codetools_0.2-18            R6_2.5.0                   
[63] gridExtra_2.3               knitr_1.30                 
[65] dplyr_1.0.2                 permute_0.9-5              
[67] ape_5.4-1                   stringi_1.5.3              
[69] ggbeeswarm_0.6.0            Rcpp_1.0.5                 
[71] vctrs_0.3.6                 tidyselect_1.1.0           
[73] xfun_0.19                   sparseMatrixStats_1.2.0    
```
</div>