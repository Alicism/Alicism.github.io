---
layout: post
title:  "PIMD - code repository"
description: 
date:   2020-10-26 20:01:21 -0400
type: card-img-top
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
last-updated: 2022-10-14 20:01:21 -0400
tag: PIMD
author: Hyukjoon Kwon
card: card-2
---



# 1. Outline

​		The original PIMD code ([Link](https://ccse.jaea.go.jp/software/PIMD/index.en.html)) does not provide forcefield calculation library for moment tensor potentials (MTP). To estimate nuclear quantum effects (NQEs) with MTP, I made a MTP library for the PIMD code. Also, parallel efficiency was enhanced by modifying the RESPA algorithms in the update of thermostats.

​		**Please note that this post follows the license agreement of the original developer ([Link](https://ccse.jaea.go.jp/software/PIMD/license.en.html)). I give up my copyright of this modification.**



# 2. Code 

### 2.1. 2022-02-20

Download: [**PIMD_2022_02_20_Kwon.tar**](https://drive.google.com/file/d/1Mtr_geK3m9Xv45ESJHMwki8UQPCtWnPS/view?usp=sharing)

Developer's note:

- You can use moment tensor potential as a forcefield. Just write

  \<ipotential>
  MTP

  A filename of MTP should be "pot.mtp"

- Parallelization efficiency of RESPA algorithm was enhanced.

    <p align="center" style="color:gray">
    <img src="/assets/img/posts/RESPA.jpg" style="padding: 0;margin:0;width:500px; height:400px;"></p>

