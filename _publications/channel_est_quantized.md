---
title: "Channel Estimation for Quantized Systems Based on Conditionally Gaussian Latent Models"
collection: publications
category: journal
permalink: /publication/channel_est_quantized
excerpt: ''
authors: ["Benedikt Fesl", "Nurettin Turan", "Benedikt Böck", "Wolfgang Utschick"]
date: 2024-02-29
venue: 'IEEE Transactions on Signal Processing (TSP)'
paperurl: 'https://ieeexplore.ieee.org/document/10454252/'
bibtexurl: 'https://github.com/benediktfesl/Quantized_Channel_Estimation'
---
This work introduces a novel class of channel estimators tailored for coarse quantization systems. The proposed estimators are founded on conditionally Gaussian latent generative models, specifically Gaussian mixture models (GMMs), mixture of factor analyzers (MFAs), and variational autoencoders (VAEs). These models effectively learn the unknown channel distribution inherent in radio propagation scenarios, providing valuable prior information. Conditioning on the latent variable of these generative models yields a locally Gaussian channel distribution, thus enabling the application of the well-known Bussgang decomposition. By exploiting the resulting conditional Bussgang decomposition, we derive parameterized linear minimum mean square error (MMSE) estimators for the considered generative latent variable models. In this context, we explore leveraging model-based structural features to reduce memory and complexity overhead associated with the proposed estimators. Furthermore, we devise necessary training adaptations, enabling direct learning of the generative models from quantized pilot observations without requiring ground-truth channel samples during the training phase. Through extensive simulations, we demonstrate the superiority of our introduced estimators over existing state-of-the-art methods for coarsely quantized systems, as evidenced by significant improvements in mean square error (MSE) and achievable rate metrics.