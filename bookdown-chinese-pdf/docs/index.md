--- 
title: "A Chinese Bookdown Template"
author: "Qiushi"
date: "2020-09-14"
documentclass: ctexbook
bibliography: [references.bib, packages.bib]
biblio-style: apalike
link-citations: yes
colorlinks: yes
lot: yes
lof: yes
geometry: [b5paper, tmargin=2.5cm, bmargin=2.5cm, lmargin=2.5cm, rmargin=1.5cm]
site: bookdown::bookdown_site
#nocite: '@*'
#cover-image: images/cover.jpg
---


# 前言 {#preface .unnumbered}



```r
plot(cars, main = "这是一个标题")
```



\begin{center}\includegraphics{index_files/figure-latex/unnamed-chunk-1-1} \end{center}



```r
xfun::session_info("bookdown")
#> R version 4.0.2 (2020-06-22)
#> Platform: x86_64-w64-mingw32/x64 (64-bit)
#> Running under: Windows 10 x64 (build 18362)
#> 
#> Locale:
#>   LC_COLLATE=Chinese (Simplified)_China.936 
#>   LC_CTYPE=Chinese (Simplified)_China.936   
#>   LC_MONETARY=Chinese (Simplified)_China.936
#>   LC_NUMERIC=C                              
#>   LC_TIME=Chinese (Simplified)_China.936    
#> 
#> Package version:
#>   base64enc_0.1.3 bookdown_0.20   digest_0.6.25   evaluate_0.14  
#>   glue_1.4.2      graphics_4.0.2  grDevices_4.0.2 highr_0.8      
#>   htmltools_0.5.0 jsonlite_1.7.1  knitr_1.29.5    magrittr_1.5   
#>   markdown_1.1    methods_4.0.2   mime_0.9        rlang_0.4.7    
#>   rmarkdown_2.3   stats_4.0.2     stringi_1.5.3   stringr_1.4.0  
#>   tinytex_0.25    tools_4.0.2     utils_4.0.2     xfun_0.17      
#>   yaml_2.2.1
```


\BeginKnitrBlock{rmdtip}
This is a custom block
\EndKnitrBlock{rmdtip}
