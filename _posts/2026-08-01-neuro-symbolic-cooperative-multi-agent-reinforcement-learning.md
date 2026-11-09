---
layout: post
title: "Neuro-Symbolic Cooperative Multi-Agent Reinforcement Learning"
author: Kim Paulke, Jonas Ehrhardt, René Heesch, Oliver Niggemann
categories: [ Multi-Agent Reinforcement Learnning, Neuro-Symbolic RL, Cooperative ]
citation: " K. Paulke, J. Ehrhardt, R. Heesch, O. Niggemannn, “Neuro-Symbolic Cooperative Multi-Agent Reinforcement Learning,” Joint Workshop on AI Planning for Complex Real World Applications (CAIPI) & Bridgeing the Gap between Planning and Reinforcement Learning (PRL) @ IJCAI-ECAI 2026, Bremen. doi: http:// . "
---

# Abstract
While Reinforcement Learning (RL) provides a powerful framework for sequential decision-making problems, model-free RL often remains sample-inefficient in sparse-reward domains with long task horizons.
This limitation is amplified in cooperative Multi-Agent Reinforcement Learning (MARL), where agents must not only discover task-relevant behavior, but also coordinate with their team-mates.
However, in many domains (incomplete) symbolic domain knowledge is available.
Though recent work already demonstrated performance boosts when integrating such knowledge in Neuro-Symbolic single-agent RL setups, these approaches have not been evaluated on multi-agent setups, so far.
Hence in this paper, we propose our novel Multi-Agent Reinforcement Learning
with integrated Knowledge (MARLiK) algorithm, a neuro-symbolic value-decomposition approach that integrates symbolic domain knowledge into cooperative MARL.
MARLiK extends a Value Decomposition Network learner with an Answer-Set-Program which is evaluated in every step.
This guides action selection by (i) biasing exploration and (ii) adding a soft bonus to rule-consistent actions during exploitation.
We evaluate our approach in a cooperative OfficeWorld domain with sparse terminal rewards.
Our results indicate improved early learning and sample efficiency, especially in tasks requiring structured coordination, while overly specific knowledge bases can reduce policy flexibility.

[Access the paper here](http://)

**Citation:** K. Paulke, J. Ehrhardt, R. Heesch, O. Niggemannn, “Neuro-Symbolic Cooperative Multi-Agent Reinforcement Learning,” *Joint Workshop on AI Planning for Complex Real World Applications (CAIPI) & Bridgeing the Gap between Planning and Reinforcement Learning (PRL) @ IJCAI-ECAI 2026, Bremen.* doi:[https://](http://).
