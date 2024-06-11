---
layout: post
title: "Using Modular Neural Networks for Anomaly Detection in Cyber-Physical Systems"
author: Jonas Ehrhardt, Philip Overlöper, Daniel Vranjes, Henrik Steude, Alexander Diedrich, Oliver Niggemann
categories: [ machine learning, neural networks, anomaly detection, cyber-physical systems ]
citation: " J. Ehrhardt, P. Overlöper, D. Vranjes, H. Steude, A. Diedrich, O. Niggemann, “Using Modular Neural Networks for Anomaly Detection in Cyber-Physical Systems,” *ETFA - IEEE Conference on Emerging Technologies and Factory Automation, 2024*. doi:[ ]( ). "
---

# Abstract
Autonomously detecting anomalous behavior based on system observations is a fundamental task for Cyber-Physical Systems (CPS). Due to the high system complexity and large number of subsystems in modern CPS, rule- or knowledge-based approaches for anomaly detection are more and more replaced by Machine Learning (ML) approaches which leverage on the recorded CPS data. Typically, ML approaches learn a system model based on the CPS data and identify anomalous behavior based on distance of the real CPS behavior to the inferred model behavior. However, most typical ML approaches for anomaly detection are monolithic, meaning a single ML model is fit on a global CPS observation, making them frail to spurious correlations and confounders that originate on CPS subsystem level. We hence propose a modular approach toward anomaly detection in CPS, specifically a novel Modular Neural Network (MNN) architecture. Our architecture not only models the behavior of individual CPS sub-systems in individual MNN modules, but additionally models the dependencies of the CPS subsystems into the MNN architecture. Thereby, we omit confounding effects and spurious correlations, enabling us to identify and allocate anomalies within the CPS on subsystem-level. We benchmark our MNN architecture against monolithic Neural Networks and MNN architectures that do not explicitly model CPS subsystem dependencies on a real-world dataset of an industrial robot with different anomalies. We show that by modeling real-world dependencies into a MNN architecture, we can improve the performance of autonomous anomaly detection in CPS. However, we also show that our approach is strongly dependent on the dataset.

[Access the paper here]( )

[Access GitHub repo here]( )

**Citation:** J. Ehrhardt, P. Overlöper, D. Vranjes, H. Steude, A. Diedrich, O. Niggemann, “Using Modular Neural Networks for Anomaly Detection in Cyber-Physical Systems,” *ETFA - IEEE Conference on Emerging Technologies and Factory Automation, 2024*. doi:[ ]( ).
