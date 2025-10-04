---
title: "Physics-Informed Generative Modeling of Wireless Channels"
collection: publications
category: ml_conferences
permalink: /publication/physics_informed
excerpt: ''
date: 2025-08-11
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'https://openreview.net/forum?id=FFJFT93oa7'
bibtexurl: 'https://github.com/beneboeck/phy-inf-gen-mod-wireless'
---
Learning the site-specific distribution of the wireless channel within a particular environment of interest is essential to exploit the full potential of machine learning (ML) for wireless communications and radar applications. Generative modeling offers a promising framework to address this problem. However, existing approaches pose unresolved challenges, including the need for high-quality training data, limited generalizability, and a lack of physical interpretability. To address these issues, we combine the physics-related compressibility of wireless channels with generative modeling, in particular, sparse Bayesian generative modeling (SBGM), to learn the distribution of the underlying physical channel parameters. By leveraging the sparsity-inducing characteristics of SBGM, our methods can learn from compressed observations received by an access point (AP) during default online operation. Moreover, they are physically interpretable and generalize over system configurations without requiring retraining.