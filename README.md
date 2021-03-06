
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Reproducible Reprots

<!-- badges: start -->
<!-- badges: end -->

The goal of ReproducibleReprots is to go through an exercise where you
can go through many phases that could be used for reproducible research:

## Preparation

For this we will need the bookdown, sf, tidyverse, rmarkdown, tinytex,
and redoc packages, which you can install them by running the code

``` r
install.packages(c("bookdown", "sf", "tidyverse", "rmarkdown", "tinytex", "plotly"))
```

And for redoc using the following one

``` r
remotes::install_github("noamross/redoc")
```

Once you have installed all those packages it is highly recomended that
you run the following code:

``` r
tinytex::install_tinytex()
```

This will install a small latex generator in your r environment, which
will result in the option to render PDF reports

## Motivation

In this workshop we will see how you can use rmarkdown to generate
reproducible documents that can become the [webpage of a
project](https://danish-flora-and-vegetation.github.io/), including
interactive [plots and
documents](https://danish-flora-and-vegetation.github.io/MapAndnmds/map.html).
Presentations with [interactive
elements](https://rpubs.com/derek_corcoran/MolsRewild) and even fully
rendered manuscripts.

## Activities

1.  Clone a repository (this one).
2.  Generate a report with bookdown, using the template in this repo.
3.  Add bibliography (.bib file) to manage your references.
4.  Add a couple of plots and use
    [crossreferences](https://bookdown.org/yihui/rmarkdown-cookbook/cross-ref.html)
    for it.
5.  Generate a pdf report.
6.  Generate a .docx report, send it to someone else to edit it and
    check the control changes using the redoc package.
7.  if we have time, we can add a ioslides presentation

## Extra demos

1.  Generation of latex documents and further editing with overleaf
