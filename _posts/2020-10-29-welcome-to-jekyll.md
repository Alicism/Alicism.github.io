---
layout: post
title:  "Machine learning Interatomic Potentials (MLIPs) for LAMMPS API"
description: "Hydrogen diffusivity & solubility in metals"
type: card-dated
date:   2020-10-29 20:01:21 -0400
categories: jekyll update
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
last-updated: 2022-10-10 20:01:21 -0400
categories: post
tag: Moment Tensor Potentials
author: Hyukjoon Kwon
card: card-2
---

# 1. Moment Tensor Potentials (MTP)

- A typer of machine learning interatomic potentials (MLIP).
- For mathematical definition of MTP, read Ref. [1]  
- If you want to learn active learning of MTP, read Ref. [2]

# 2. Hydrogen diffusion in bcc metals for PIMD.

Developer's comments:

- The active learning [2] was applied to make the MTPs in reference to density functional theory (DFT) calculations.
- For the specific information on the active learning process, please each document.



### 2.1.1. For public

Ref [3].

###### [Niobium (**Nb**): pot_NbH_bulk.mtp](https://drive.google.com/file/d/1_IPQdBVMCilcIC2Mk-dPVRQFPfzlv0Tz/view?usp=sharing)

###### [Iron (**Fe**): pot_FeH_bulk.mtp](https://drive.google.com/file/d/1KdhpEOihazRp-p3V-ddv0U7LpoUTTzkG/view?usp=sharing)

###### [Tungsten (**W**): pot_WH_bulk.mtp](https://drive.google.com/file/d/1yfsHRGCGW0S6rS8uoinhvAX7onw7TVQK/view?usp=sharing)



### 2.1.2. Preparing for publication

###### Molybdenum (**Mo**): pot_MoH_bulk.mtp ()



# Hydrogen 









-----------------------------------------

# Reference

[[1] A. V. Shapeev, *Moment Tensor Potentials: A Class of Systematically Improvable Interatomic Potentialsm*, 2016 MULTISCALE MODEL. SIMUL. Vol. 14, No. 3, pp. 1153–1173](https://epubs.siam.org/doi/10.1137/15M1054183)

[[2] I. Ivan S Novikov *et al*, *The MLIP package: moment tensor potentials with MPI and active learning*, 2021 *Mach. Learn.: Sci. Technol.* **2** 025002](https://iopscience.iop.org/article/10.1088/2632-2153/abc9fe/meta)

