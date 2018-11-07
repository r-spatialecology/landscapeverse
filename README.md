
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis build
status](https://travis-ci.org/r-spatialecology/landscapeverse.svg?branch=master)](https://travis-ci.org/r-spatialecology/landscapeverse)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/r-spatialecology/landscapeverse?branch=master&svg=true)](https://ci.appveyor.com/project/r-spatialecology/landscapeverse)
<!-- [![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing) -->

# landscapeverse

The goal of **landscapeverse** is to make it easy to install and load
core packages for landscape analysis in a single command.

## Installation

You can install the released version of landscapeverse from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("landscapeverse")
```

Or the development version from GitHub:

``` r
# install.packages("devtools")
devtools::install_github("hadley/tidyverse")
```

## Usage

`library(landscapeverse)` will load the core landscapeverse
    packages:

  - [landscapemetrics](https://r-spatialecology.github.io/landscapemetrics/),
    for calculating landscape metrics for categorical landscape patterns
    in a tidy workflow.
  - [NLMR](https://ropensci.github.io/NLMR/), for simulating neutral
    landscape models (NLM).
  - [landscapetools](https://ropensci.github.io/landscapetools/),
    provides utility functions to work with landscape data.
