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



# 1. Introduction

​		Hydrogen diffusivity in metals has been extensively investigated due to its rich physical characteristics and importance in materials engineering. Many experimental studies have been devoted to various metals; however, there are often large deviations in the reported diffusion coefficients because of surface and trapping effects, which indicates that accurate measurements are inherently difficult, especially at low temperatures. 

​		For computational studies, several atomistic simulation methods have been proposed and used to determine the true hydrogen diffusivity in the lattice; however, their accuracy remains questionable because either the force field, dynamic effects, or nuclear quantum effects were not accurately simulated in most studies.

​		**In this research, I used PIMD with the machine learning potentials to estimate diffusivity & solubility of hydrogen in metals by MD simulations.**



# 2. Hydrogen diffusivity in bcc metals

### 2.1. Outline

- Diffusion coefficients of H, D, and T in bcc Nb, Fe, W, Mo over 100 K.

- The results of Fe, Nb, W are listed in Ref [2] 

### 2.2. Animation

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/Animation_diffusion.gif" style="padding: 0;margin:0;width:250px; height:200px;"></p>
### 2.3. Results (Mo)

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/H_diffusion_Mo.jpg" style="padding: 0;margin:0;width:500px; height:470px;"></p>
  Results

- Only Dr. Katsuta's data seem to represent **bulk diffusivity** since its activation energy is similar to my MD results.
- Dr. Katsuta's preexponential factors are comparable to my MD results at high temperature. However, it's uncertain which one is more accurate.



 **Abbreviation**

- CLMD: Classical molecular dynamics

- RPMD: Ring polymer molecular dynamics

# 3. Hydrogen solubility in bcc metals

### 3.1.  Outline

- Solubility of H, D, and T in bcc Fe, W, Mo
- High solution energy barrier was removed.

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/Solubility_MEP.jpg" style="padding: 0;margin:0;width:400px; height350px;"></p>



### 3.2. Animation

<p align="center" style="color:gray">
  <img src="/assets/img/posts/Solubility_Anmiation.gif" style="padding: 0;margin:0;width:250px; height200px;">
</p>



### 3.3. Results

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/H_solution_Fe.jpg" style="padding: 0;margin:0;width:500px; height:470px;"></p>


Results

- My solubility model produces quite similar results to experimental data.
- However, experimental data from gas permeation techniques are sometimes very unreliable, so more careful review is required. 




--------------

# Reference

[1] [M. Shiga, PIMD, version 2.5.0, (2022).](http://ccse.jaea.go.jp/software/PIMD/ index.en.html.) 

