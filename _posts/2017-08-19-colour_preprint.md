---
layout: post
title: "New preprint on methods for comparing colour samples"
date: 2017-08-19
author: Thomas White
categories: papers 
---

<img src="{{ site.baseurl }}/assets/blog/threshold.png" title="Profile" class="profile">

The inimitable [Rafael Maia](http://rafaelmaia.net) and I have [a new preprint](http://www.biorxiv.org/content/biorxiv/early/2017/08/18/175992.full.pdf) out, which deals with some common statistical and methodological issues that arise when comparing groups of colours. Viewer-subjective ["colour spaces"](http://dx.doi.org/10.1111/brv.12230) are a common tool for studying colour traits, and the underlying analytical objective typically centres on estimating how similar or dissimilar samples of colours are to a given viewer (e.g. How effective is this cryptic colouration? Are these species sexually dichromatic? How conspicuous are these warning colours?). 

There are numerous methods for doing this, but they often rely on shaky implicit assumptions. We use a simulation-based approach to test the efficacy of the more popular approaches, and show that most aren't up to the job. We argue that an explicit analytical distinction should be drawn between estimating the _statistical presence_ versus the _perceptual magnitude_ of group differences in colour space, and suggest some (hopefully) useful ways of achieving each. Out preferred solutions are currently being woven into [pavo](http://rafaelmaia.net/pavo) as the paper makes its way through review, and we'd of course be happy to hear any thoughts in the interim.