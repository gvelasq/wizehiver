
<!-- README.md is generated from README.Rmd. Please edit that file -->
wizehiver
=========

[![CRAN status](https://www.r-pkg.org/badges/version/wizehiver)](https://cran.r-project.org/package=wizehiver) [![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

Zengine™ from WizeHive is a cloud-based platform that can organize the collection, review, and management of data and applications for grants and other business processes.

The goal of wizehiver is to build functionality to:

1.  Input and manage Zengine™ RESTful API tokens
2.  Input available API resources
3.  Execute API calls
4.  Process API request content
5.  Extract tibbles

This package has no relationship or affiliation with, sponsorship, or endorsement by WizeHive.

Installation
------------

You can install the development version of wizehiver from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ivelasq/wizehiver")
```

Setup
-----

### Get and store the API key

Generate the Zengine API key from your [Zengine account page](https://platform.zenginehq.com/account/developer).

wizehiver functions will read the API key from environment variable ZENGINE\_KEY.

To verify your Zengine API key, use function `get_key()`. If your Zengine API key is not stored in `.Renviron`, you will be able to create an .Renviron file in your home directory using function `set_key()`.

------------------------------------------------------------------------

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
