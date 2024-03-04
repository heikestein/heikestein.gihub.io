---
layout: post
title: "Modeling locomotion on complex surfaces"
author: "Heike Stein"
categories: projects
tags: [project]
image: locomotion.png
---

During my postdoc, I started being more and more drawn to time series modeling, especially of naturalistic behavior. In one project (together with experimental collaborators), we trained mice to walk on a ladder-like, motorized treadmill that would force them to adjust their natural gait to the complex, runged surface. We saw that mice needed up to 14 days to master this task and employ coordinated gait patterns.

We asked how coordination between the different paws would emerge over the course of learning. But to tackle this question, we first neeeded to understand in which way gaits lacked coordination in early phases of learning. By fitting dynamical models to the behavioral trajectories of single paws, we saw that single-paw stepping patterns are highly variable as mice attempt to adapt their steps to the uneven surface. As a result of having each paw trying to adapt to the surface, pairwise coordination patterns are dominated by multiple dynamical regimes that switch frequently over the course of a single session. I fitted hidden Markov models to disentangle these regimes. With this approach, I found that dynamics within a regime lawfully follow coupled oscillator equations that are commonly employed to model gait on flat surfaces. From fitted models, we saw that over the course of learning, coupling between paws became more efficient, and mice tended to switch less and less between different coordination regimes.

### Relevant publications

Stein, H., Andrianarivelo, A., Gabillet, J., Batifol, C., Jalil, A., Graupner, M., Cayco Gajic, N.A., The emergence of fixed points in interlimb coordination underlies the learning of stable gaits in mice, talk at COSYNE ‘22 and in preparation. [<i class="fab fa-youtube"></i> (English)](https://www.youtube.com/watch?v=DvsflwKOWs0&t=10960s) [<i class="fab fa-youtube"></i> (Spanish)](https://www.youtube.com/watch?v=gDxyvzCach4&t=3610s)

Andrianarivelo, A., Stein, H., Gabillet, J., Batifol, C., Jalil, A., Cayco Gajic, N. A., and Graupner, M. Cerebellar interneuron activity is triggered by reach endpoint during learning of a complex locomotor task. BioRxiv (2023). [<i class="fa fa-unlock"></i>](https://heikestein.github.io/assets/documents/Andrianarivelo_Biorxiv_2023.pdf)
