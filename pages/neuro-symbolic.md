---
layout: page
title: Neuro-Symbolic AI
order: 2
permalink: "/neuro-symbolic-ai/"
image: assets/images/header-neuro-symbolic.png
description: Read more about some work we have done in a pretty interesting research direction.
---


Neuro-symbolic AI emerges at the intersection between the classically separated research domains of subsymbolic AI, such as Deep Learning or other data-driven methods, and symbolic AI, such as formal languages, reasoning and knowledge representation. 
In Neuro-Symbolic methods subsymbolic and symbolic methods complement each other by leveraging on their individual strengths, while canceling out their individual drawbacks.

Though there is a plethora of work in Neuro-Symbolic AI, and a plethora of taxonomies that aim to cluster the work, Neuro-Symbolic architectures effectively boil down to three architectural choices: 
1. **Engineering or Learning an Interface:** These architectures use symbolic and subsymbolic methods in parallel. They are connected via an interface, e.g. a mapping function that maps the distributed numerical representation of subsymbolic concepts or states to the symbolic representation and back.
2. **Forcing the Subsymbolic in Symbolic Forms:** These architectures organize the subsymbolic architecture in a way that they resemble symbolic structures. E.g. a reasoning tree, which allows to assign individual neurons a symbolic function, but learn their weight in a data-driven way. 
3. **Using Symbolic Knowledge as a Learning Signal:** These architectures typically use the differentiable logics for regularizing the training of a subsymbolic model with an additional learning signal, e.g. a symbolic loss. 

These strategies can overlap. My research mainly focuses on using symbolic domain knowledge to improve sample-efficiency and safety for Reinforcement Learning. The following papers are a selection of different Neuro-Symbolic approaches:

### Neuro-Symbolic Action-Masking and Parameter Constraints for RL in PAMDPs

In **Knowledge- and Gradient-Guided Reinforcement Learning (KGRL)**, we augment a value-based RL algorithm with a knowledge base and a nested optimization loop to enable it to operate on Parametrized Action Markov Decision Processes. The knowledge base effectively does action (and parameter space masking). Symbolic reasoning masks inapplicable actions and constrains the continuous parameter space. Together with a gradient-guided parameter refinement, this helps the agent learn more efficiently and achieve higher returns in our evaluated tasks.

[Read the paper](https://arxiv.org/abs/2607.12924) · [Publication page](https://jonas-ehrhardt.de/publications/knowledge-and-gradient-guided-reinforcement-learning-for-parametrized-action-spaces)



### Augmenting Neural Policies with a Symbolic Policy

In **Multi-Agent Reinforcement Learning with integrated Knowledge (MARLiK)**, we augmented a learned RL policy in a Multi-Agent RL setup with a symbolic policy derived from Answer Set Programming rules. The symbolic policy suggests useful actions that guides the exploration and biases the action selection during exploitation. We could show that this guidance can improve early learning and sample efficiency.

[Read the paper]() · [Publication page]()



### Training neural models with differentiable logic

Symbolic knowledge can also guide learning through the training objective. In our work on **Reconstruction-based Diagnosis through Gödel-regularized Virtual Observability**, we encode physical knowledge using Gödel fuzzy logic and use it as an additional training signal for a neural observer. The observer reconstructs unmeasured process variables as virtual sensors, while the logical regularization encourages consistency with domain knowledge. These reconstructions help identify the root causes of faults in technical systems.

[Read the paper](https://arxiv.org/abs/2611.04487) · [Publication page](https://jonas-ehrhardt.de/publications/latent-goedel-observability)

