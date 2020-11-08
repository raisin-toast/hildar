
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hildar

<!-- badges: start -->

[![R build
status](https://github.com/asiripanich/hildar/workflows/R-CMD-check/badge.svg)](https://github.com/asiripanich/hildar/actions)
<!-- badges: end -->

The goal of **hildar** is to help R users that use HILDA survey data in
their works.

Please note that, this package doesn’t include any parts of the HILDA
survey data. You must be authorised to have access to a release of HILDA
survey data.

## Installation

The development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("asiripanich/hildar")
```

## Import HILDA files

Basically, this package imports HILDA survey data in .dta format (STATA
format) and convert them into .fst files so they can be accessed very
quickly\!

TODO: write an instruction on how to import HILDA files.

## Example

Here is how you fetch HILDA data\!

``` r
library(hildar)

hilda_data <- fetch(years = 2001:2016, add_geography = T)

summary(hilda_data)
#> < table of extent 0 x 0 >
```
