---
title: "SpikeGoogle: Spiking Neural Networks with GoogLeNet‐like inception module"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'SpikeGoogle is an SNN with GoogLeNet-like Inception modules that improves feature extraction for event-based vision. It achieves 85% accuracy on NMNIST, outperforming previous SNNs by 15%, while addressing scalability and training challenges. This architecture combines CNN efficiency with SNN energy savings, advancing neuromorphic systems for low-power applications.'
date: 2022-05-08
venue: 'CAAI Trans. Intell. Technol'
paperurl: 'https://www.researchgate.net/publication/359744999_SpikeGoogle_Spiking_Neural_Networks_with_GoogLeNet-like_inception_module'
citation: 'Wang, X., et al.: SpikeGoogle: Spiking Neural Networks with GoogLeNet-like inception module. CAAI Trans. Intell. Technol. 7(3), 492–502 (2022). https://doi.org/10.1049/cit2.12082'
---

We introduce **SpikeGoogle**, a spiking neural network (SNN) incorporating GoogLeNet-like Inception modules to enhance feature extraction for event-based vision. While SNNs offer energy-efficient, biologically inspired computation, their training remains challenging due to non-differentiable spikes and limited scalability. Our architecture integrates multi-scale Inception layers—combining parallel convolutions and max-pooling—to capture spatial-temporal features efficiently, addressing overfitting in sparse datasets like NMNIST. Leveraging the SLAYER framework, we enable gradient-based training by reassigning errors across time, optimizing synaptic weights and axonal delays. Experiments on NMNIST demonstrate SpikeGoogle’s superiority, achieving **​85%** accuracy (15% higher than prior SCNNs) with faster convergence. This work bridges CNNs’ structural strengths with SNNs’ event-driven efficiency, advancing neuromorphic systems for real-world applications such as robotics and low-power edge devices.
