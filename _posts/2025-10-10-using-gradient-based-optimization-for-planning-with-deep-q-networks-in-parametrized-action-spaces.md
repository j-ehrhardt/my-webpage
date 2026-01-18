---
layout: post
title: "Using Gradient-based Optimization for Planning with Deep Q-Networks in Parametrized Action Spaces"
author: Jonas Ehrhardt, Johannes Schmidt, René Heesch, Oliver Niggemann
categories: [ deep q-networks, offline RL, planning, parametrized actions ]
citation: " J. Ehrhardt, J. Schmidt, R. Heesch, O. Niggemann, “Using Gradient-based Optimization for Planning with Deep Q-Networks in Parametrized Action Spaces,” *CAIPI'25 Workshop on Planning in Complex Real-World Scenarios @ European Conference on Artificial Intelligence (ECAI), 2025*. urn:[https://ceur-ws.org/Vol-4103/paper5.pdf](https://ceur-ws.org/Vol-4103/paper5.pdf). "
---

# Abstract
Many real-world planning problems feature parametrized action spaces, where each action is augmented by continuous parameters. Though deep Reinforcement Learning has achieved remarkable results in solving control and planning problems, it falls short at two central challenges of real-world planning problems with parametrized action spaces: (i) There is an infinite number of action-parameter candidates in every step of solving a planning problem, (ii) interacting with the planning domain is typically prohibitively expensive and available recordings from the planning domain are sparse.To counter these challenges, we introduce our novel Goal-Conditioned Model-Augmented Deep Q-Networks algorithm (GCM-DQN). The intuition behind GCM-DQN is to use gradient-based optimization on the surface of the Q-Function, instead of blunt estimators, to estimate the optimal parameters of an action in a state. In combination with a goal-conditioning of the DQN, and a state transition model, this allows us to find plans for planning problems in planning domains with parametrized action spaces. Our algorithm outperforms state-of-the-art Reinforcement Learning algorithms for planning in parametrized action spaces.

[Access the paper here](https://ceur-ws.org/Vol-4103/paper5.pdf)

[Access the GitHub repo here](https://github.com/j-ehrhardt/gcmdqn)

**Citation:** J. Ehrhardt, J. Schmidt, R. Heesch, O. Niggemann, “Using Gradient-based Optimization for Planning with Deep Q-Networks in Parametrized Action Spaces,” *CAIPI'25 Workshop on Planning in Complex Real-World Scenarios @ European Conference on Artificial Intelligence (ECAI), 2025*. urn:[https://ceur-ws.org/Vol-4103/paper5.pdf](https://ceur-ws.org/Vol-4103/paper5.pdf).
