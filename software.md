---
layout: page
title: Software
dispname: Software
permalink: /software/
---
# pavo  

**An R package for the organization, visualisation, and analysis of spectral and spatial colour data.**   
[_Rafael Maia_](http://rafaelmaia.net), [_Hugo Gruson_](https://www.normalesup.org/~hgruson/), [_Thomas White_](https://tomwhite.io)

<p align="center">
<img src="{{ site.baseurl }}/assets/tetra.gif" title="Profile" class="profile">  
</p>

`pavo` offers a flexible and integrated workflow for working with spectral and spatial colour data. It includes functions that take advantage of new data classes to work seamlessly from importing raw spectra and images, to publication-quality visualisations, and analyses via a suite of analytical methods and visual models.

If you **need help** with the package, take a look at the [documentation](http://pavo.colrverse.) and [extended vignettes](http://pavo.colrverse.com/articles/pavo-1-overview.html), and keep an eye on the [latest news](http://pavo.colrverse.com/news/index.html) for changes. We're always happy to receive feedback and suggestions via personal email or the mailing list: [r-pavo@googlegroups.com](mailto:r-pavo@googlegroups.com). If you have a bug to report, we’d appreciate it if you could also include a reproducible example when possible.

**Current release:** 2.7.0

**Development version:** 2.8.0

**Installation:** The current release of `pavo` is available on CRAN and can be installed using ```install.packages('pavo')``` within R. The bleeding-edge version is on [github](https://github.com/rmaia/pavo), and is most easily installed with the [remotes](https://github.com/hadley/devtools) package, by running ```remotes::install_github('rmaia/pavo')```.  

**Citation:** Maia R, Gruson H, Endler JA, White TE (2019) pavo 2: new tools for the spectral and spatial analysis of colour in R.  [_Methods in Ecology and Evolution_](http://dx.doi.org/10.1111/2041-210X.13174) 10, 1097-1107. 

---

# lightr 

**Import spectral data and metadata in R**  
[_Hugo Gruson_](https://www.normalesup.org/~hgruson/), [_Thomas White_](http://tomwhite.io), [_Rafael Maia_](http://rafaelmaia.net)

`lightr` offers a unified, user-friendly interface for reading UV-VIS reflectance, transmittance, and/or absorbance spectral files and associated metadata from a suite of proprietary (and generally unfriendly) file formats, across all systems.

**Current release:** 1.6.0  

**Development version:** 1.7.0  

**Installation** The current release of `lightr` is available on CRAN, and can be installed using ```install.packages('lightr')``` within R. The development version can be installed via [GitHub](https://github.com/ropensci/lightr) using ```remotes::install_github("ropensci/lightr")```.

**Citation:** Gruson H, White TE, Maia R (2019) lightr: import spectral data and metadata in R. [_Journal of Open Source Software_](https://doi.org/10.21105/joss.01857). 

---

# metadat

**Meta-analysis datasets in R**  
[_Thomas White_](http://tomwhite.io), [_Daniel Noble_](http://nobledan.com), [_Alistair Senior_](http://alistairmsenior.com), [_W. Kyle Hamilton_](http://kylehamilton.com), [_Wolfgang Viechtbauer_](http://www.wvbauer.com)

`metadat` contains a large collection of meta-analysis datasets, useful for teaching purposes, illustrating/testing meta-analysis methods, and validating published analyses.

**Current release:** 1.0.0  

**Development version:** 1.1.0  

**Installation** The current release of `metadat` is available on CRAN, and can be installed using ```install.packages('metadat')```. The development version is available via [GitHub](https://github.com/wviechtb/metadat) using ```remotes::install_github("wviechtb/metadat")```.