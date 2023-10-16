---
layout: page
title: Tools
dispname: Tools
permalink: /tools/
---

# Software

We enjoy testing and extending methods for understanding the world, and prefer such tools to be as open and accessible as possible. To that end we have developed and contributed to various pieces of software, including the below which are actively maintained.

---

## pavo  

**An R package for the organization, visualisation, and analysis of spectral and spatial colour data.**   
[_Rafael Maia_](http://rafaelmaia.net), [_Hugo Gruson_](https://www.normalesup.org/~hgruson/), [_Thomas White_](https://tomwhite.io)

<p align="center">
<img src="{{ site.baseurl }}/assets/tetra.gif" title="Profile" class="profile">  
</p>

`pavo` offers a flexible and integrated workflow for working with spectral and spatial colour data. It includes functions that take advantage of new data classes to work seamlessly from importing raw spectra and images, to publication-quality visualisations, and analyses via a suite of analytical methods and visual models.

If you **need help** with the package, take a look at the [documentation](http://pavo.colrverse.) and [extended vignettes](http://pavo.colrverse.com/articles/pavo-1-overview.html), and keep an eye on the [latest news](http://pavo.colrverse.com/news/index.html) for changes. We're always happy to receive feedback and suggestions via personal email or the mailing list: [r-pavo@googlegroups.com](mailto:r-pavo@googlegroups.com). If you have a bug to report, we’d appreciate it if you could also include a reproducible example when possible.

**Current release:** 2.9.0

**Development version:** 2.10.0

**Installation:** The current release of `pavo` is available on CRAN and can be installed using ```install.packages('pavo')``` within R. The bleeding-edge version is on [github](https://github.com/rmaia/pavo), and is most easily installed with the [remotes](https://github.com/hadley/devtools) package, by running ```remotes::install_github('rmaia/pavo')```.  

**Citation:** Maia R, Gruson H, Endler JA, White TE (2019) pavo 2: new tools for the spectral and spatial analysis of colour in R.  [_Methods in Ecology and Evolution_](http://dx.doi.org/10.1111/2041-210X.13174) 10, 1097-1107. 

---

## lightr 

**Import spectral data and metadata in R**  
[_Hugo Gruson_](https://www.normalesup.org/~hgruson/), [_Thomas White_](http://tomwhite.io), [_Rafael Maia_](http://rafaelmaia.net)

`lightr` offers a unified, user-friendly interface for reading UV-VIS reflectance, transmittance, and/or absorbance spectral files and associated metadata from a suite of proprietary (and generally unfriendly) file formats, across all systems.

**Current release:** 1.6.0  

**Development version:** 1.7.0  

**Installation** The current release of `lightr` is available on CRAN, and can be installed using ```install.packages('lightr')``` within R. The development version can be installed via [GitHub](https://github.com/ropensci/lightr) using ```remotes::install_github("ropensci/lightr")```.

**Citation:** Gruson H, White TE, Maia R (2019) lightr: import spectral data and metadata in R. [_Journal of Open Source Software_](https://doi.org/10.21105/joss.01857). 

---

## metadat

**Meta-analysis datasets in R**  
[_Thomas White_](http://tomwhite.io), [_Daniel Noble_](http://nobledan.com), [_Alistair Senior_](http://alistairmsenior.com), [_W. Kyle Hamilton_](http://kylehamilton.com), [_Wolfgang Viechtbauer_](http://www.wvbauer.com)

`metadat` contains a large collection of meta-analysis datasets, useful for teaching purposes, illustrating/testing meta-analysis methods, and validating published analyses.

**Current release:** 1.0.0  

**Development version:** 1.1.0  

**Installation** The current release of `metadat` is available on CRAN, and can be installed using ```install.packages('metadat')```. The development version is available via [GitHub](https://github.com/wviechtb/metadat) using ```remotes::install_github("wviechtb/metadat")```.

---

# Gadgets

We often build our own bits & pieces for experiments, which is made simpler with the help of 3D printing. Below are some odds & ends I've created that might be of use. For 3D printable models I've included the style (.sty) files, which are ready to be edited (if desired), 'sliced', and sent to your printer of choice. If you don't have access to a printer but feel something may be useful to you feel free to get in touch (especially students & ECRs) and I'll happily try and help as time & resources allow.

---

## Choice arena  

<p align="right">
<img src="{{ site.baseurl }}/tools/col_arena.png" title="Arena" class="profile">  
</p>

A small arena with slots in the walls to hold 30 mm<sup>2</sup> pieces of card. Useful for walking colour/stimulus choice assays. The download includes a six-card and eight-card version.

**[Download]({{ site.url }}/tools/col_arena.zip)** (.zip file) contains:
  - col_arena_6.sty: six-card version of the arena.
  - col_arena_8.sty: eight-card version of the arena.

---

## Artificial 'flowers' with base

<p align="right">
<img src="{{ site.baseurl }}/tools/flowers.png" title="Flowers" class="profile">  
</p>

A set of nine 'flower' discs and a base to hold them. Can be topped with coloured card for flying choice assays for various pollinators. Note the flowers have a small well in the centre, for holding liquids or materials (like cotton) to wick liquids. The flowers and base are included separately.

**[Download]({{ site.url }}/tools/flowers.zip)** (.zip file) contains:
  - flower_base.sty: the nine-hole base.
  - flower_set.sty: set of nine 'flowers', as depicted.

---