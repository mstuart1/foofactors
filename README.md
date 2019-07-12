
<!-- README.md is generated from README.Rmd. Please edit that file -->

# foofactors

<!-- badges: start -->

<!-- badges: end -->

The goal of foofactors is to combine factors

## Installation

You can install the
<!-- released version of foofactors from [CRAN](https://CRAN.R-project.org) with: -->

<!-- ``` r -->

<!-- install.packages("foofactors") -->

<!-- ``` -->

<!-- And  -->

the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("mstuart1/foofactors")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(foofactors)
## basic example code
fbind(iris$Species[c(1, 51, 101)], PlantGrowth$group[c(1, 11, 21)])
#> [1] setosa     versicolor virginica  ctrl       trt1       trt2      
#> Levels: ctrl setosa trt1 trt2 versicolor virginica
fcount(iris$Species)
#> # A tibble: 3 x 2
#>   f              n
#>   <fct>      <int>
#> 1 setosa        50
#> 2 versicolor    50
#> 3 virginica     50
```
