---
layout: post
title: "Reconstruction-Based Diagnosis through Gödel-Regularized Virtual Observability"
author: Oliver Niggemann, Jonas Ehrhardt, Alexander Diedrich
categories: [ Diagnosis, Neuro-Symbolic AI, Anomaly Detection, Cyber-Physical Systems ]
citation: " O. Niggemann, J. Ehrhardt, A. Diedrich, “Reconstruction-Based Diagnosis through Gödel-Regularized Virtual Observability,” ArXiV, doi: https://doi.org/10.48550/arXiv.2611.04487 . "
---

# Abstract
Not every component in a technical system can be equipped with sensors. Hence, when a fault occurs, available sensors often detect it only after its effects have propagated. This makes the isolation of faults difficult. We approach this problem by introducing virtual sensors. For each combination of component and fault type, we let external knowledge describe the fault-sensitive variables. We introduce a novel neural observer that is only trained on normal data. For fault isolation, it uses available sensor measurements where it is possible and reconstructs missing variables as virtual sensors to predict normal behavior. It detects deviations between current values and nominal predictions and computes local symptoms, which are then compared by onset time. The result is a set of root causes describing the faulty behavior. We use Gödel logic to encode physical knowledge and guide training. We evaluate our approach on synthetic networks, the Tennessee Eastman Process, and datasets of two modular production plants. 

[Access the paper here](https://doi.org/10.48550/arXiv.2611.04487)

**Citation:** O. Niggemann, J. Ehrhardt, A. Diedrich, “Reconstruction-Based Diagnosis through Gödel-Regularized Virtual Observability,” ArXiV.* doi:[https://doi.org/10.48550/arXiv.2611.04487](https://doi.org/10.48550/arXiv.2611.04487).
