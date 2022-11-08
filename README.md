
<!-- badges: start -->

[![R-CMD-check](https://github.com/jhudsl/ottrpal/workflows/R-CMD-check/badge.svg)](https://github.com/jhudsl/ottrpal/actions)
[![CRAN
status](https://www.r-pkg.org/badges/version/ottrpal)](https://CRAN.R-project.org/package=ottrpal)
[![Downloads](http://cranlogs.r-pkg.org/badges/grand-total/ottrpal)](https://cran.r-project.org/package=ottrpal)
[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
<!-- [![GitHub release (latest by -->
<!-- date)](https://img.shields.io/github/v/release/jhudsl/ottrpal?style=social)](https://github.com/jhudsl/ottrpal/releases/tag/v1.0.0) -->
<!-- [![Codecov test -->
<!-- coverage](https://codecov.io/gh/jhudsl/ottrpal/branch/main/graph/badge.svg)](https://codecov.io/gh/jhudsl/ottrpal?branch=main) -->

<!-- badges: end -->
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ottrpal Package:

The goal of `ottrpal` is to provide tools to convert from Bookdown
content to Leanpub content and do some checks.

## Installation

You can install `ottrpal` from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("jhudsl/ottrpal")
```

## Example

Within a bookdown repository, you can run the following command to
convert your content to a Leanpub-ready format.

``` r
ottrpal::bookdown_to_leanpub()
```

By default the output files will be sent to a `manuscript` folder which
is what Leanpub looks for.

For an example of what this looks like, see [this template
repository](https://github.com/jhudsl/OTTR_Quizzes).
