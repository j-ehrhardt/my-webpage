---
layout: post
title: "A lazy Approach to Neural Numerical Planning with Control Parameters"
author: René Heesch, Alessandro Cimatti, Jonas Ehrhardt, Alexander Diedrich, Oliver Niggemann
categories: [ numerical planning, satisfiability modulo theory, machine learning ]
citation: " R. Heesch, A. Cimatti, J. Ehrhardt, A. Diedrich, O. Niggemann, “A lazy Approach to Neural Numerical Planning with Control Parameters,” *ECAI - European Conference on Artificial Intelligence, 2024*. doi:[ ]( ). "
---

# Abstract
In this paper we tackle the problem of planning in complex numerical domains, where actions are indexed by control parameters, and their effects may be described by neural networks. We propose a lazy, hierarchical approach based on two ingredients. First, a Satisfiability Modulo Theory solver looks for an abstract plan where the neural networks in the model are abstracted into uninterpreted functions. Then, we attempt to concretize the abstract plan by querying the neural network to determine the control parameters. If the concretization fails and no valid control parameters could be found, suitable information to refine the abstraction is lifted to the Satisfiability Modulo Theory model. We contrast our work against the state of the art in NN-enriched numerical planning, where the neural network is eagerly and exactly represented as terms in SMT over nonlinear real arithmetic. The evaluation of various planning problems from four different domains clearly show that avoiding symbolic reasoning about the neural network leads to substantial efficiency improvements.

[Access the paper here]( )

[Access GitHub repo here]( )

**Citation:** R. Heesch, A. Cimatti, J. Ehrhardt, A. Diedrich, O. Niggemann, “A lazy Approach to Neural Numerical Planning with Control Parameters,” *ECAI - European Conference on Artificial Intelligence, 2024*. doi:[ ]( ).
