---
layout: post
title: "Creating Automatic Semantic Device Descriptions for Brownfield Industrial Robots"
author: Jonas Ehrhardt, Anna Nordhausen, Alexander Guhl, Marcel Lewke, Constantin Hildebrandt, Oliver Niggemann
categories: [cyber-physical system, robot, semantic device description, convolutional neural network]
citation: "J. Ehrhardt, A. Nordhausen, Alexander Guhl, Marcel Lewke, Constantin Hildebrandt, Oliver Niggemann, “Creating Automatic Semantic Device Descriptions for Brownfield Industrial Robots,” *SAMPE Europe Conference*."

---

# Abstract
Semantic device descriptions (SDD) are formal models that map signals from field devices such as sensors, actuators, and programmable logic controllers to a meaningful system model. Therefore, a SDD provides explicit identification of signals and their meaning, e.g., motor temperatures or robot axis positions. With the increasing use of signals for higher-level automation, SDDs become more important. While SDDs are usually specified in advance for greenfield systems, they often have to be defined manually for brownfield systems. This paper proposes a novel approach to automatically generate SDD from signal channels of device controls. Our approach uses an artificial neural network to assign sensor signals from a robot control (e.g., joint angle) to its provenance (e.g., axis). By letting the robot follow a distinct motion path, the neural network can identify unique signal patterns and assign the correct signal to its component of provenance. A subsequent module transforms the model's predictions into an SDD for the device. We evaluate our approach on two industrial robots.

[Access the paper here](https://www.sampe-europe.org/about/library/)

**Citation:** J. Ehrhardt, A. Nordhausen, Alexander Guhl, Marcel Lewke, Constantin Hildebrandt, Oliver Niggemann, “Creating Automatic Semantic Device Descriptions for Brownfield Industrial Robots,” *SAMPE Europe Conference*.

