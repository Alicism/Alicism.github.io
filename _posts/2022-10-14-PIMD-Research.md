---
layout: post
title:  "PIMD - Research"
description: "Research outline"
type: card-dated
date:   2020-10-28 20:01:21 -0400
categories: Dumabrton style
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
last-updated: 2022-10-14 20:01:21 -0400
categories: post
tag: H transport in metals
author: Hyukjoon Kwon
card: card-1
---



# 1. Outline

​		Hydrogen diffusivity in metals has been extensively investigated due to its rich physical characteristics and importance in materials engineering. Many experimental studies have been devoted to various metals; however, there are often large deviations in the reported diffusion coefficients because of surface and trapping effects, which indicates that accurate measurements are inherently difficult, especially at low temperatures. 

​		For computational studies, several atomistic simulation methods have been proposed and used to determine the true hydrogen diffusivity in the lattice; however, their accuracy remains questionable because either the force field, dynamic effects, or nuclear quantum effects were not accurately simulated in most studies.

​		**In this research, I used PIMD with the machine learning potentials to estimate diffusivity & solubility of hydrogen in metals by MD simulations.**



# 2. Hydrogen diffusivity in bcc metals

### 2.1. Target quantity

- Diffusion coefficients of H, D, and T in bcc Nb, Fe, W, Mo over 100 K.

- The results of Fe, Nb, W are listed in Ref [2] 

### 2.2. Animation

<img alt="" src="/assets/img/posts/Animation_diffusion.gif" style="width:250px; height:200px;"/>

  

### 2.3. Results (Mo)

<img alt="" src="/assets/img/posts/H_diffusion_Mo.jpg" style="width:500px; height:475px;"/>

  

**Abbreviation**

- CLMD: Classical molecular dynamics

- RPMD: Ring polymer molecular dynamics

--------------

# Reference

Ref [1] [M. Shiga, PIMD, version 2.5.0, (2022).](http://ccse.jaea.go.jp/software/PIMD/ index.en.html.) 

