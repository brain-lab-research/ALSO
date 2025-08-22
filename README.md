# Aligning Distributionally Robust Optimization with Practical Deep Learning Needs
This repo contains the official implementation for the paper Aligning Distributionally Robust Optimization with Practical Deep Learning Needs

## Abstract:

While traditional Deep Learning (DL) optimization methods treat all training samples equally, Distributionally Robust Optimization (DRO) adaptively assigns importance weights to different samples. However, a significant gap exists between DRO and current DL practices. Modern DL optimizers require adaptivity and the ability to handle stochastic gradients, as these methods demonstrate superior performance. Additionally, for practical applications, a method should allow weight assignment not only to individual samples, but also to groups of objects (for example, all samples of the same class). This paper aims to bridge this gap by introducing ALSO – Adaptive Loss Scaling Optimizer – an adaptive algorithm for a modified DRO objective that can handle weight assignment to sample groups. We prove the convergence of our proposed algorithm for non-convex objectives, which is the typical case for DL models. Empirical evaluation across diverse Deep Learning tasks, from Tabular DL to Split Learning tasks, demonstrates that ALSO outperforms both traditional optimizers and existing DRO methods.



# Release Date: Sep 29 '25
Do not miss!)
