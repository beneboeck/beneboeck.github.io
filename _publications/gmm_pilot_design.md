---
title: "Variational Autoencoder for Channel Estimation: Real-World Measurement Insights"
collection: publications
category: ieee_conferences
permalink: /publication/gmm_pilot_design
excerpt: ''
authors: ["Nurettin Turan", "Benedikt Fesl", "Benedikt Böck", "Michael Joham", "Wolfgang Utschick"]
date: 2024-03-17
venue: 'International Symposium on Wireless Communicaton Systems (ISWCS)'
paperurl: 'https://ieeexplore.ieee.org/document/10639137'
---
In this work, we propose to utilize Gaussian mixture models (GMMs) to design pilots for downlink (DL) channel estimation in frequency division duplex (FDD) systems. The GMM captures prior information during training that is leveraged to design a codebook of pilot matrices in an initial offline phase. Once shared with the mobile terminal (MT), the GMM is utilized to determine a feedback index at the MT in the online phase. This index selects a pilot matrix from a codebook, eliminating the need for online pilot optimization. The GMM is further used for DL channel estimation at the MT via observation-dependent linear minimum mean square error (LMMSE) filters, parametrized by the GMM. The analytic representation of the GMM allows adaptation to any signal-to-noise ratio (SNR) level and pilot configuration without re-training. With extensive simulations, we demonstrate the superior performance of the proposed GMM-based pilot scheme compared to state-of-the-art approaches.