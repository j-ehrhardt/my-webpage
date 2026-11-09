---
layout: page
title: Datasets
order: 3
permalink: "/datasets/"
image: assets/images/header-datasets.png
description: This page introduces datasets I created and help curating. 
---


Alongside developing AI methods, I contribute to datasets and benchmarks needed to evaluate them. Especially in the industrial context, this is important, as data-availability there is rather scarce. 
Below is a list of industry-near datasets and benchmarks, we developed for different tasks. 

## LayerWatch – Layer-wise visual defect detection in 3D printing

LayerWatch is a benchmark for detecting and classifying defects in **Fused Filament Fabrication (FFF)**. It provides annotated images of successive print layers, covering five defect types alongside defect-free examples. Beyond evaluating detection performance on familiar objects, it tests how well models generalize to unseen geometries and changes in appearance. The accompanying repository provides code for reproducible training and evaluation of baseline object detectors.

<p float="center">
    <img title="layer-watch" src="https://dataverse.org/dataverse-project-logo.svg" width="200">
</p>

[Paper](https://ieeexplore.ieee.org/document/11725015) · [Dataset](https://doi.org/10.7910/DVN/AWWBAZ) · [GitHub](https://github.com/SEilermann/LayerWatch) · [Publication page](https://jonas-ehrhardt.de/layerwatch-a-benchmark-for-layer-wise-multi-class-visual-defect-detection-in-fused-filament-fabrication)



## The Hamburg AI Benchmark for Cyber-Physical Production Systems

HAI-CPPS supports the systematic evaluation of AI methods for anomaly detection, diagnosis, reconfiguration, and planning. It builds on ten configurations of a simulated modular process plant, combining mixing, filtering, distillation, and bottling modules. Discrete, continuous, and hybrid recordings capture normal and faulty behaviour across systems of varying complexity. The datasets and OpenModelica simulation models support reproducible comparisons of data-driven, symbolic, and neuro-symbolic approaches.

<p float="center">
    <img title="hai-cpps" src="https://github.com/j-ehrhardt/hai-cpps-benchmark/raw/main/figs/logo-v2.2.png" width="150">
</p>


<p float="center">
    <img title="" src="https://ieee-dataport.org/themes/custom/dataport_bootstrap/logo.svg" width="200">
</p>


[Paper](https://ieeexplore.ieee.org/document/11205680) · [Datasets](https://ieee-dataport.org/open-access/hai-cpps-hamburg-ai-benchmark-cyber-physical-production-systems-v2) · [GitHub](https://github.com/j-ehrhardt/hai-cpps-benchmark) · [Publication page](https://jonas-ehrhardt.de/the-haicpps-benchmark/)


## BeRfiPl – A benchmark for diagnosis, reconfiguration, and planning

BeRfiPl brings several AI tasks into a shared benchmark based on simulated modular process plants. Its datasets cover different plant structures, functionalities, and levels of complexity, including individual and combined faults. This enables methods for diagnosis, reconfiguration, and planning to be evaluated in related settings. BeRfiPl laid the foundation for the later HAI-CPPS benchmark; its original simulation models remain available in a dedicated repository branch.

<p float="center">
    <img title="berfipl" src="https://github.com/j-ehrhardt/hai-cpps-benchmark/raw/berfipl/figures/BeRfiPl.jpeg" width="100">
</p>


[Paper](https://ieeexplore.ieee.org/document/9921546) · [GitHub (BeRfiPl version)](https://github.com/j-ehrhardt/hai-cpps-benchmark/tree/berfipl) · [Publication page](https://jonas-ehrhardt.de/an-ai-benchmark-for-diagnosis-reconfiguration-and-planning/)



