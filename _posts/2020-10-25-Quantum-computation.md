---
layout: post
title:  "Application of Quantum Computation to chemistry"
description:
date:   2020-10-26 20:01:21 -0400
type: card-img-top
image: http://placehold.it/750X300?text=Header+Image
caption:
last-updated: 2022-10-15 20:01:21 -0400
tag: Quantum computation
author: Hyukjoon Kwon
card: card-1
---

# 1. Intro

​		Understanding and simulating the nature of quantum system is significantly important, since it can provide insight in solving various problems and analyzing natural phenomena. As the classical computation capability started to show limitation in simulating large systems, the ’quantum computer’ that exploit entangled quantum states as a computational resource have been proposed
and developed recently. 

   

   

# 2. Variational Quantum Eigensolver (VQE)

​		One of the main application of quantum computing is Hamiltonian simulation, where the goal is to construct quantum circuit that demonstrates target Hamiltonian. When a Hamiltonian is decomposed into quantum circuit, we can investigate the time evolution or calculate
energy eigenstates out of it. However, for most cases applying direct Hamiltonian can be hard or even
impossible, and as a result various ’bypass’ algorithms were proposed.
​		The Variational Method is one result of such approaches, that give approximation to Hamiltonian with relatively short circuits compared to that of the exact solution. This algorithm is effective in mitigating error accumulation in deep circuits but suffered another problems, mainly related to efficiency and fidelity.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/XLXMZfjnhW0" allowfullscreen></iframe>
</div>

#### (My presentation at 2022 Quantum Information Contest)

​    

  

  

### 2.1. Application of VQE to 1-dimensional Ising model.

### 2.1.1. Construction of quantum circuits

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/VQE_formula(1).jpg" style="padding: 0;margin:0"></p>

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/VQE_qc.jpg" style="padding: 0;margin:0"></p>



### 2.1.2. Result (1)

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/VQE_result(1).jpg" style="padding: 0;margin:0"></p>

The above figure shows optimal number of parameters in Ansatz.

The error in energy showed a minimum value around at 3 parameter sets. It may be counter-intuitive because more parameters did not produce better results, which is called **Barren plateau problem**.



### 2.1.2. Result (2)

  <p align="center" style="color:gray">
  <img src="/assets/img/posts/VQE_result(2).jpg" style="padding: 0;margin:0"></p>

The energy error was checked by changing the number of shots for each measurement. Interestingly, however, the increased number of shots did not improve accuracy of the algorithm. Thus, I want to make this point very clear that **more accurate measurements lead to worse results.**

