
<!-- README.md is generated from README.Rmd. Please edit that file -->

# phsverse

This package is created with
[metamakr](https://github.com/jdtrat/metamakr) and combines three of our
[Public Health Scotland (PHS)](https://www.publichealthscotland.scot/)
packages on GitHub:

-   [phstemplates](https://github.com/Public-Health-Scotland/phstemplates)
-   [phsmethods](https://github.com/Public-Health-Scotland/phsmethods)
-   [phsstyles](https://github.com/Public-Health-Scotland/phsstyles)

## Installation

To install `phsverse`, the package `remotes` is required, and can be
installed with `install.packages("remotes")`.

You can then install `phsverse` on RStudio server from GitHub with:

``` r
remotes::install_github("Public-Health-Scotland/phsverse",
  upgrade = "never"
)
```

Network security settings may prevent `remotes::install_github()` from
working on RStudio desktop. If this is the case, `phsverse` can be
installed by downloading the [zip of the
repository](https://github.com/Public-Health-Scotland/phsverse/archive/master.zip)
and running the following code (replacing the section marked `<>`,
including the arrows themselves):

``` r
remotes::install_local("<FILEPATH OF ZIPPED FILE>/phsverse-master.zip",
  upgrade = "never"
)
```

## Using phsverse

Load `phsverse` using `library()`:

``` r
library(phsverse)
#> -- Attaching packages ----------------------------------- phsverse 0.0.0.9000 --
#> v phstemplates 0.9.6     v phsstyles    0.1.0
#> v phsmethods   0.2.0
```
