---
title: "Understanding Simulated Annealing via Optimal Transport"
collection: talks
permalink: /talks/2026-06-14-annealing
venue: "ACM-Class Student Academic Festival."
location: "Shanghai, China (virtual)."
slides: '/files/annealing_slides.pdf'
event: 'https://sites.google.com/view/aco-student-seminar-gatech/home'
---

Simulated annealing is a classical strategy for sampling from difficult, multimodal distributions: instead of targeting the final distribution directly, one follows a path of easier intermediate distributions. I will present a discrete optimal transport framework that quantifies when this strategy succeeds for finite-state Markov chains. Its central object is an action functional derived from the sampler's local dynamics. A general path-measure comparison theorem shows that the KL tracking error of annealed local dynamics is bounded by this action, giving a discrete analogue of recent transport-based analysis of annealed Langevin dynamics.

I will apply the framework to two mean-field spin systems. For the Ising model, symmetry reduces the analysis to a one-dimensional projected chain and yields rapid convergence of annealed single-site Glauber dynamics at all temperatures. For the Potts model, a folded color-count projection and block updates give polynomial-time convergence at low temperatures beyond the spinodal threshold. These results show how transport geometry, annealing schedules, and model symmetry allow local dynamics to overcome macroscopic multimodality.