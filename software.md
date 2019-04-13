---
layout: page
title: Software
dispname: Software
permalink: /software/
---
# pavo  

**An R package for the organization, visualisation, and analysis of spectral and spatial colour data.**   
[_Rafael Maia_](http://rafaelmaia.net), [_Hugo Gruson_](https://www.normalesup.org/~hgruson/), [_Thomas White_](http://tomwhite.io)

<img src="{{ site.baseurl }}/assets/blog/jndplot.png" title="Profile" class="profile">  

If you **need help** with the package, take a look at the [documentation](http://rafaelmaia.net/pavo/reference/index.html) and [extended vignettes](http://rafaelmaia.net/pavo/articles/pavo.html), and keep an eye on the [latest news](http://rafaelmaia.net/pavo/news/index.html) for changes. We're always happy to receive feedback and suggestions via personal email or the mailing list: [r-pavo@googlegroups.com](mailto:r-pavo@googlegroups.com). If you have a bug to report, we’d appreciate it if you could also include a reproducible example when possible.

**Stable version:** 2.1.0 (09/03/2019)

**Development version:** 2.2

**Installation:** The current stable version of pavo is available on CRAN, and can simply be installed using ```install.packages('pavo')``` within R. The bleeding-edge version is on [github](https://github.com/rmaia/pavo), and is most easily installed with the [remotes](https://github.com/hadley/devtools) package, by running ```remotes::install_github('rmaia/pavo')```.  

**Citation:** Maia R, Gruson H, Endler JA, White TE (2019) pavo 2: new tools for the spectral and spatial analysis of colour in R.  [_Methods in Ecology and Evolution_](http://dx.doi.org/10.1111/2041-210X.13174), Early View. 

----------

# metadat

**A database of meta-analytic datasets in R**

The `metadat` package contains a large collection of meta-analytic datasets, useful for teaching purposes, illustrating/testing certain meta-analytic methods, and validating and extending published analyses.

**Browsing and searching datasets:** A listing of all datasets is available with `help(package=metadat}`. Each dataset is also tagged with one or multiple concept terms which refer to the field of research, the outcome measure used for the analysis, the model(s)/package(s) used for analyzing the data, and the methods/concepts that can be illustrated with the dataset.

Alternatively, the `search_dat()` function can be used to query the existing data in the package to explore their help files. It uses fuzzy matching, and queries the data name, title, keyword and concept fields to identify relevant datasets that may be of interest.

**Contributing new datasets:** We welcome contributions of new published datasets to the package. For full instructions on how to contribute, take a look at the [package repository](https://github.com/wviechtb/metadat).

**Development version:** 0.1.0

**Installation:** `metadat` in not yet on cran, but the current development version can be most easily installed from github via ```remotes::install_github("wviechtb/metadat")```


