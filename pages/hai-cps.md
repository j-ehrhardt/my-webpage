---
layout: page
title: HAI-CPS
order: 3
permalink: "/hai-cps/"
image: assets/images/header-hai-cps.png
description: This page introduces the HAI-CPPS benchmark dataset. 
---

### An Open Access Dataset for Comprehensively Evaluating Your Machine Learning Model

When reading publications about Machine Learning approaches for improving technical systems, one thing becomes clear: evaluation is the weak link of many approaches. Many studies rely on narrowly defined use cases that lack the variance needed to truly assess the generalizability of the proposed algorithms. This limitation isn’t just due to the difficulty of accessing real system data—it’s also because a comprehensive benchmark simply did not exist yet.

This is why we developed **HAI-CPPS**, the *Hamburg AI Benchmark for Cyber-Physical Systems*.

HAI-CPPS is a modular benchmark specifically designed for evaluating AI models in **anomaly detection**, **diagnosis**, and **reconfiguration** tasks. It features ten scenarios based on a simulated modular process plant, each offering increasing complexity and diverse functionalities. This allows systematic testing of algorithms—not just on one isolated case but across a consistent, scalable framework.

**What HAI-CPPS offers:**

- **Ten datasets** with increasing CPPS complexity

- **OpenModelica models** for full system simulation

- **Pre-simulated datasets** for instant benchmarking

- **Docker integration** and **Python API** for creating your own simulations easily.

Each dataset comes in four distinct recording modes:

- **Discrete** (binary sensor/control values)

- **Continuous** (real-valued process measurements)

- **Hybrid** (discrete + continuous)

- **Including States** (hybrid + automaton states from each module)

For each mode, all permutations of anomalies—including multi-module and multi-fault combinations—are available as separate `.csv` files, along with a healthy baseline. This enables robust evaluation, especially for **unsupervised machine learning approaches**.

HAI-CPPS allows you to comprehensively evaluate your ML algorithm. 
You can check it out on [GitHub](https://github.com/j-ehrhardt/hai-cps-benchmark) and soon on [IEEE Dataport](https://ieee-dataport.org/open-access/hai-cpps-hamburg-ai-benchmark-cyber-physical-production-sytems). 

<p float="center">
    <img title="" src="https://ieee-dataport.org/themes/custom/dataport_bootstrap/logo.svg" width="300">
    <img title="" src="https://github.githubassets.com/assets/GitHub-Logo-ee398b662d42.png" width="190">
</p>


For a deeper insight into HAI-CPPS, check out our papers on the previous [benchmark dataset](https://jonas-ehrhardt.de/an-ai-benchmark-for-diagnosis-reconfiguration-and-planning/), the [HAI-CPPS benchmark dataset](https://jonas-ehrhardt.de/the-hai-cpps-benchmark/) itself and on our paper about [Design Principles for Falsifiable, Replicable, Reproducible Empirical Machine Learning Research](https://jonas-ehrhardt.de/design-principles-for-falsifiable-replicable-and-reproducible-empirical-machine-learning-research/).
