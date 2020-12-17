[![Travis build status](https://travis-ci.com/lisaxjiang/stat302project2part2.svg?branch=master)](https://travis-ci.com/lisaxjiang/stat302project2part2)

## Installation

To download the corncob package, use the code below.

``` r
# install.packages("stat302project2part2")
devtools::install_github("lisaxjiang/stat302project2part2")
library(stat302project2part2)
```

## Use

The vignette demonstrates example usage of all main functions. You can see the vignette by using the following code (note that this requires a TeX installation to view properly):

``` r
devtools::install_github("lisaxjiang/stat302project2part2", build_vignette = TRUE, build_opts = c())
library(stat302project2part2)
# Use this to view the vignette in the Demo HTML help
help(package = "stat302project2part2", help_type = "html")
# Use this to view the vignette as an isolated HTML file
utils::browseVignettes(package = "stat302project2part2")
```

## Bug Reports / Change Requests

If you encounter a bug or would like make a change request, please file it as an issue [here](https://github.com/lisaxjiang/stat302project2part2/issues).
