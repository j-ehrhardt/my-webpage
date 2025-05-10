---
layout: page
title: HAI-CPS
order: 2
permalink: "/hai-cps/"
image: assets/images/header-hai-cps.png
description: This page introduces the HAI-CPS benchmark dataset. 
---

### An Open Access Dataset for Comprehensively Evaluating Your Machine Learning Model

When reading publications about Machine Learning approaches for improving technical systems, one thing becomes clear: evaluation is the weak link of many approaches. Many studies rely on narrowly defined use cases that lack the variance needed to truly assess generalizability of the proposed algorithms. This limitation isn’t just due to the difficulty of accessing real system data—it’s also because a comprehensive benchmark simply did not exist, yet.

This is why we developed **HAI-CPS**, the *Hamburg AI Benchmark for Cyber-Physical Systems*.

HAI-CPS is a modular benchmark specifically designed for evaluating AI models in **anomaly detection**, **diagnosis**, and **reconfiguration** tasks. It features ten scenarios based on a simulated modular process plant, each offering increasing complexity and diverse functionalities. This allows systematic testing of algorithms—not just on one isolated case, but across a consistent, scalable framework.

**What HAI-CPS offers:**

- **Ten datasets** with increasing CPS complexity

- **OpenModelica models** for full system simulation

- **Pre-simulated datasets** for instant benchmarking

- **Docker integration** and **Python API** for creating your own simulations easily.

Each dataset comes in four distinct recording modes:

- **Discrete** (binary sensor/control values)

- **Continuous** (real-valued process measurements)

- **Hybrid** (discrete + continuous)

- **Including States** (hybrid + automaton states from each module)

For each mode, all permutations of anomalies—including multi-module and multi-fault combinations—are available as separate `.csv` files, along with a healthy baseline. This enables robust evaluation, especially for **unsupervised machine learning approaches**.

HAI-CPS allows you to comprehensively evaluate your ML algorithm. 
You can check it out on [GitHub](https://github.com/j-ehrhardt/hai-cps-benchmark) and soon on IEEE Dataport. 

For a deeper insight into HAI-CPS check out our papers on the [bencmark](https://jonas-ehrhardt.de/an-ai-benchmark-for-diagnosis-reconfiguration-and-planning/) itself and on [Design Principles for Falsifiable, Replicable, Reproducible Empiricial Machine Learning Research](https://jonas-ehrhardt.de/design-principles-for-falsifiable-replicable-and-reproducible-empirical-machine-learning-research/).
