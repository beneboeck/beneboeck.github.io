---
title: "Reverse Ordering Techniques for Attention-Based Channel Prediction"
collection: publications
category: journal
permalink: /publication/reverse_ordering
excerpt: ''
authors: ["Valentina Rizzello", "Benedikt Böck", "Michael Joham", "Wolfgang Utschick"]
date: 2023-12-18
venue: 'IEEE Open Journal of Signal Processing'
paperurl: 'https://ieeexplore.ieee.org/document/10363354'
bibtexurl: 'https://github.com/vrizz/reverse-ordering'
---
Channel state information (CSI) is crucial for enhancing the performance of wireless systems by allowing to adjust the transmission strategies based on the current channel conditions. However, obtaining precise CSI is difficult because of the fast-changing channel conditions caused by multi-path fading. An inaccurate CSI hinders the performance of various adaptive wireless systems, highlighting the need for channel prediction techniques to effectively mitigate the drawbacks of outdated CSI. Conventional methods typically depend on assumptions regarding user velocity or require knowledge of the Doppler frequency. In contrast to existing approaches, we aim for a more robust and practical solution by training neural networks without making any assumptions about user velocity, relying solely on noisy channel observations during training. Specifically, we adapt both the sequence-to-sequence with attention (Seq2Seq-attn) and transformer models for channel prediction. Additionally, a new technique called reverse positional encoding is introduced in the transformer model to improve the robustness of the model against varying sequence lengths. Similarly, the encoder outputs of the Seq2Seq-attn model are reversed prior to the application of attention mechanisms. By means of simulations, we show that these proposed techniques enable the models to effectively capture relationships within sequences of channel snapshots without increasing the complexity. Importantly, this capability remains robust across varying sequence lengths, representing a substantial improvement over existing methodologies.