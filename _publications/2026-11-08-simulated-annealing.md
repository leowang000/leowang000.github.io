---
title: "Understanding Simulated Annealing: from Weak Poincaré Inequalities to a Discrete Optimal Transport Framework"
collection: publications
category: preprints
permalink: /publication/2026-11-08-simulated-annealing
author: 'with [Yuchen He](https://yuchen-he00.github.io/), Tianhui Jiang, Zhehan Lei, [Chihao Zhang](https://chihaozhang.com/).'
venue:
arxiv: 'https://arxiv.org/abs/2605.05877'
---

Simulated annealing follows a path of distributions from an easy initial law to a target. Standard analyses require rapid mixing at every fixed temperature, which can fail for multimodal targets even when annealing succeeds. Motivated by the continuous optimal-transport analysis of annealed Langevin dynamics by Guo, Tao, and Chen (ICLR 2025), we develop a discrete optimal-transport framework for finite-state annealing.

The discrete action of the path integrates the minimum electrical energy needed to route the demand \\(-\partial_s \pi_s\\) through the chain's transition capacities. Like a path-dependent inverse conductance, it penalizes a bottleneck only when the path must move mass across it. We also introduce weak action, which leaves an \\(\varepsilon\\) amount of this motion unrouted. Up to initialization error, action \\(\mathcal{A}\\) gives reverse-KL error at most \\(\mathcal{A} / (4T)\\) after \\(T\\) expected updates, while weak action gives TV error at most \\(\varepsilon + \sqrt{\mathcal{A}_{\varepsilon}^{w} / (8T)}\\).

Paralleling canonical paths and Poincaré inequalities, we develop flow and spectral bounds, showing that pathwise (weak) Poincaré inequalities imply (weak) action bounds. We also show that a weak Poincaré inequality yields a genuine one after removing a small amount of mass. As a pathwise analogue of chain decomposition, we obtain a componentwise algorithm for mixtures with phase weights supplied at initialization.

Applications include mean-field Ising and Potts models and bipartite spin systems. For every fixed \\(\delta > 0\\), we give a polynomial-time single-site annealing sampler for uniform independent sets in \\((d, D)\\)-biregular bipartite graphs with \\(D / d \geq 1 + \delta\\) and large \\(D\\). To our knowledge, this is the first polynomial-time sampler requiring only a fixed multiplicative degree imbalance, strictly extending the \\(D \geq 7d \log d\\) regime of Cannon and Perkins (SODA 2020).