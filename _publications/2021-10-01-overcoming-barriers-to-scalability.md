---
title: "Overcoming barriers to scalability in variational quantum Monte Carlo"
collection: publications
permalink: /publication/overcoming_barriers_to_scalability.pdf
venue: 'Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis'
---
The variational quantum Monte Carlo (VQMC) method received significant attention in the recent past because of its 
ability to overcome the curse of dimensionality inherent in many-body quantum systems. Close parallels exist between 
VQMC and the emerging hybrid quantum-classical computational paradigm of variational quantum algorithms. VQMC overcomes 
the curse of dimensionality by performing alternating steps of Monte Carlo sampling from a parametrized quantum state 
followed by gradient-based optimization. While VQMC has been applied to solve high-dimensional problems, it is known to 
be difficult to parallelize, primarily owing to the Markov Chain Monte Carlo (MCMC) sampling step. In this work, we 
explore the scalability of VQMC when autoregressive models, with exact sampling, are used in place of MCMC. This 
approach can exploit distributed-memory, shared-memory and/or GPU parallelism in the sampling task without any 
bottlenecks. In particular, we demonstrate GPU-scalability of VQMC for solving up to ten-thousand dimensional 
combinatorial optimization problems.
[<a href="https://dl.acm.org/doi/10.1145/3458817.3476219?sid=SCITRUS">Paper</a>]

Recommended citation: Tianchen Zhao, Saibal De, Brian Chen, James Stokes, and Shravan Veerapaneni.  Overcoming barriers to scalability in variational quantum Monte Carlo. <i>Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis</i>, 2021.