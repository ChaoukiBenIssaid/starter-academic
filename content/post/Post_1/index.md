---
title: Paper accepted
subtitle:
summary: Our Paper "Q-GADMM: Quantized Group ADMM for Communication Efficient Decentralized Machine Learning" has been accepted in IEEE Transactions on Communications.
authors:
- admin
tags: []
categories: []
date: "2020-02-10T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""

projects: []
---

Our paper [**Q-GADMM: Quantized Group ADMM for Communication Efficient Decentralized Machine Learning**](https://ieeexplore.ieee.org/document/9205203), joint work with Anis Elgabli, [**Jihong Park **](https://sites.google.com/view/jihong-park/),  [**Amrit S. Bedi**](https://sites.google.com/view/amritsinghbedi), [**Mehdi Bennis**](https://sites.google.com/view/dr-mehdi-bennis/) and [**Vaneet Aggarwal**](https://web.ics.purdue.edu/~vaneet/), has been accepted in IEEE Transactions on Communications.

Abstract:

In this article, we propose a communication-efficient decentralized machine learning (ML) algorithm, coined quantized group ADMM (Q-GADMM). To reduce the number of communication links, every worker in Q-GADMM communicates only with two neighbors, while updating its model via the group alternating direction method of multipliers (GADMM). Moreover, each worker transmits the quantized difference between its current model and its previously quantized model, thereby decreasing the communication payload size. However, due to the lack of centralized entity in decentralized ML, the spatial sparsity and payload compression may incur error propagation, hindering model training convergence. To overcome this, we develop a novel stochastic quantization method to adaptively adjust model quantization levels and their probabilities, while proving the convergence of Q-GADMM for convex objective functions. Furthermore, to demonstrate the feasibility of Q-GADMM for non-convex and stochastic problems, we propose quantized stochastic GADMM (Q-SGADMM) that incorporates deep neural network architectures and stochastic sampling. Simulation results corroborate that Q-GADMM significantly outperforms GADMM in terms of communication efficiency while achieving the same accuracy and convergence speed for a linear regression task. Similarly, for an image classification task using DNN, Q-SGADMM achieves significantly less total communication cost with identical accuracy and convergence speed compared to its counterpart without quantization, i.e., stochastic GADMM (SGADMM).
