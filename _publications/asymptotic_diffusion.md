---
title: "On the Asymptotic Mean Square Error Optimality of Diffusion Models"
collection: publications
category: ml_conferences
permalink: /publication/asymptotic_diffusion
excerpt: ''
authors: ["Benedikt Fesl", "Benedikt Böck", "Florian Strasser", "Michael Baur", "Michael Joham", "Wolfgang Utschick"]
date: 2025-01-22
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'https://openreview.net/forum?id=XrXlAYFpvR'
bibtexurl: 'https://github.com/benediktfesl/Diffusion_MSE'
---
Diffusion models (DMs) as generative priors have recently shown great potential for denoising tasks but lack theoretical understanding with respect to their mean square error (MSE) optimality. This paper proposes a novel denoising strategy inspired by the structure of the MSE-optimal conditional mean estimator (CME). The resulting DM-based denoiser can be conveniently employed using a pre-trained DM, being particularly fast by truncating reverse diffusion steps and not requiring stochastic re-sampling. We present a comprehensive (non-)asymptotic optimality analysis of the proposed diffusion-based denoiser, demonstrating polynomial-time convergence to the CME under mild conditions. Our analysis also derives a novel Lipschitz constant that depends solely on the DM’s hyperparameters. Further, we offer a new perspective on DMs, showing that they inherently combine an asymptotically optimal denoiser with a powerful generator, modifiable by switching re-sampling in the reverse process on or off. The theoretical findings are thoroughly validated with experiments based on various benchmark datasets.