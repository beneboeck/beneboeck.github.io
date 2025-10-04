---
title: "Gohberg-Semencul Toeplitz Covariance Estimation via Autoregressive Parameters | [Paper](https://ieeexplore.ieee.org/document/10857370/)"
collection: publications
category: journal
permalink: /publication/gohberg_semencul
excerpt: ''
authors: ["Benedikt Böck", "Dominik Semmler", "Benedikt Fesl", "Michael Baur", "Wolfgang Utschick"]
date: 2025-01-29
venue: 'IEEE Transactions on Signal Processing (TSP)'
paperurl: 'https://ieeexplore.ieee.org/document/10857370/'
bibtexurl: 'https://github.com/beneboeck/toep-cov-estimation'
---
The use of prior structural knowledge is essential for the estimation of covariance matrices and their inverses when only few data samples are accessible. A well-known example is the knowledge that the covariance matrix is Toeplitz-structured, which occurs when dealing with wide-sense-stationary processes. Exploiting the close relation between autoregressive parameters and inverse covariance matrices, this paper introduces a new class of estimators for Toeplitz-structured covariance matrices and their inverses. To achieve this, we derive novel constraint sets for autoregressive parameters by leveraging their connection to the so-called Gohberg-Semencul decomposition. While these constraint sets guarantee the corresponding inverse covariance matrix to be positive definite and, thus, enable a proper estimation of the covariance matrix by inversion, they also build a means to control the estimator's performance by hyperparameter tuning. The derived constraint sets comprise simple box constraints enabling computationally cheap estimators in closed form. Due to the ensured positive definiteness, the proposed estimators perform well for both the estimation of the covariance matrix and its inverse. Extensive simulation results validate the proposed estimators’ efficacy for several standard Toeplitz-structured covariance matrices commonly employed in a wide range of applications.