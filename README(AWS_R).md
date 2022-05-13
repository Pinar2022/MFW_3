# MWF3

Analytical notebook looking at the change in time in the number of covid cases.
Notebook covers visualization and casual relationship model based on data from John Hopkins University.
https://github.com/CSSEGISandData/COVID-19

The data was downloaded on 10 February 2022.

sessionInfo(package = NULL)

> sessionInfo(package = NULL)
R version 4.0.2 (2020-06-22)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 18.04.5 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/openblas/libblas.so.3
LAPACK: /usr/lib/x86_64-linux-gnu/libopenblasp-r0.2.20.so

locale:
 [1] LC_CTYPE=C.UTF-8       LC_NUMERIC=C           LC_TIME=C.UTF-8        LC_COLLATE=C.UTF-8    
 [5] LC_MONETARY=C.UTF-8    LC_MESSAGES=C.UTF-8    LC_PAPER=C.UTF-8       LC_NAME=C             
 [9] LC_ADDRESS=C           LC_TELEPHONE=C         LC_MEASUREMENT=C.UTF-8 LC_IDENTIFICATION=C   

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] lubridate_1.7.9 forcats_0.5.0   stringr_1.4.0   dplyr_1.0.1     purrr_0.3.4    
 [6] readr_1.3.1     tidyr_1.2.0     tibble_3.0.3    ggplot2_3.3.2   tidyverse_1.3.0
[11] sparklyr_1.7.5 

loaded via a namespace (and not attached):
 [1] xfun_0.16         tidyselect_1.1.0  forge_0.2.0       haven_2.3.1       colorspace_1.4-1 
 [6] vctrs_0.4.1       generics_0.0.2    htmltools_0.5.0   yaml_2.2.1        base64enc_0.1-3  
[11] blob_1.2.1        rlang_1.0.2       pillar_1.4.6      glue_1.6.2        withr_2.2.0      
[16] DBI_1.1.0         rappdirs_0.3.1    dbplyr_1.4.4      modelr_0.1.8      readxl_1.3.1     
[21] lifecycle_0.2.0   munsell_0.5.0     gtable_0.3.0      cellranger_1.1.0  rvest_0.3.6      
[26] htmlwidgets_1.5.1 evaluate_0.14     knitr_1.29        parallel_4.0.2    curl_4.3         
[31] broom_0.7.0       r2d3_0.2.3        Rcpp_1.0.5        backports_1.1.8   scales_1.1.1     
[36] jsonlite_1.7.0    config_0.3        fs_1.5.0          hms_0.5.3         digest_0.6.25    
[41] stringi_1.4.6     rprojroot_1.3-2   grid_4.0.2        cli_3.3.0         tools_4.0.2      
[46] magrittr_1.5      crayon_1.3.4      pkgconfig_2.0.3   ellipsis_0.3.2    rsconnect_0.8.16 
[51] xml2_1.3.2        reprex_0.3.0      assertthat_0.2.1  rmarkdown_2.3     httr_1.4.2       
[56] rstudioapi_0.11   R6_2.4.1          compiler_4.0.2   