---
layout: post
title: "Learning Sound and Complete Preconditions in Complex Real-World Domains"
author: René Heesch, Björn Ludwig, Jonas Ehrhardt, Alexander Diedrich, Oliver Niggemann
categories: [ planning, precondition learning, neuro-symbolic AI ]
citation: " R. Heesch, B. Ludwig, J. Ehrhardt, A. Diedrich, O. Niggemann, “Learning Sound and Complete Preconditions in Complex Real-World Domains,” CAIPI'25 Workshop on Planning in Complex Real-World Scenarios @ European Conference on Artificial Intelligence (ECAI), 2025. urn: https://ceur-ws.org/Vol-4103/paper6.pdf. "
---

# Abstract
In this paper, we address the problem of learning sound and complete action preconditions in complex real-world planning domains, the remaining bottleneck in the N3PCP pipeline. Such planning domains involve hybrid state spaces including discrete and numerical variables. We propose a dependency-aware learning approach that captures interdependencies between discrete and numerical variables by constructing distinct convex hulls over the numerical subspace for each discrete state configuration. This poses a more accurate representation of hybrid preconditions in real-world domains than existing approaches for learning preconditions. We empirically compare our method against two other approaches: an exact baseline method that ensures soundness but lacks completeness, and a generalized variant of N-SAM, that achieves completeness but compromises soundness. We evaluate our approach across multiple planning problems and domains which are based on a real-world industrial system, demonstrating the practical benefits of our approach. An additional theoretical analysis confirms that, under standard convexity assumptions and sufficient coverage of discrete configurations within the training data, our proposed dependency-aware method guarantees both completeness and soundness.

[Access the paper here](https://ceur-ws.org/Vol-4103/paper6.pdf)

[Access GitHub repo here](https://github.com/RHeesch/Learning_
Hybrid_Preconditions)

**Citation:** R. Heesch, B. Ludwig, J. Ehrhardt, A. Diedrich, O. Niggemann, “Learning Sound and Complete Preconditions in Complex Real-World Domains,” *CAIPI'25 Workshop on Planning in Complex Real-World Scenarios @ European Conference on Artificial Intelligence (ECAI), 2025*. urn:[https://ceur-ws.org/Vol-4103/paper6.pdf](https://ceur-ws.org/Vol-4103/paper6.pdf).
