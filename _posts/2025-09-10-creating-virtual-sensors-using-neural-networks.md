---
layout: post
title: "Creating Virtual Sensors Using Neural Networks"
author: Björn Ludwig, Jonas Ehrhardt, Oliver Niggemann
categories: [ machine learning, sensor data, reconstruction, neural networks ]
citation: "B. Ludwig, J. Ehrhardt, O. Niggemann, “Creating Virtual Sensors Using Neural Networks,” *ETFA - IEEE Conference on Emerging Technologies and Factory Automation, 2025*. doi:[http://dx.doi.org/10.1109/ETFA65518.2025.11205672](http://dx.doi.org/10.1109/ETFA65518.2025.11205672). "
---

# Abstract
Reliable sensor data are essential for the effective operation and safety of cyber-physical systems (CPS) in industrial environments. However, sensors frequently experience faults or degradation, leading to compromised system performance. In order to increase the resilience of CPS, this paper proposes a novel approach to creating virtual sensors capable of reconstructing missing or faulty sensor data through gradient-based input reconstruction by leveraging neural networks. Specifically, we employ an LSTM-based autoencoder architecture trained both conventionally and with a masking strategy to handle potential sensor data loss scenarios effectively. Our method involves using automatic differentiation and gradient descent to iteratively optimize missing sensor inputs, guided by the pretrained network. We evaluate this approach comprehensively on both simulated and real-world plant data from cyber-phyiscal process plants, demonstrating robust reconstruction performance across various sensor failure scenarios. Additionally, we explore the efficacy of modular clustering methods versus single comprehensive models, highlighting the advantages and limitations inherent to each approach. Our findings reveal significant potential for improving system resilience and maintaining operational continuity in CPS through advanced virtual sensor implementations.

[Access the paper here](http://dx.doi.org/10.1109/ETFA65518.2025.11205672)

[Access the GitHub repo here]( https://github.com/B-Ludwig/Creating Virtual Sensors Using
Neural Networks/)

**Citation:** B. Ludwig, J. Ehrhardt, O. Niggemann, “Creating Virtual Sensors Using Neural Networks,” *ETFA - IEEE Conference on Emerging Technologies and Factory Automation, 2025*. doi:[http://dx.doi.org/10.1109/ETFA65518.2025.11205672](http://dx.doi.org/10.1109/ETFA65518.2025.11205672).
