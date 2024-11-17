---
title: "Exploiting nonlinear dendritic adaptive computation in training deep Spiking Neural Networks."
collection: publications
category: manuscripts
permalink: /publication/nonlinear
date: 2023-9
venue: 'Neural Networks'
paperurl: 'http://floyeshen.github.io/files/nonlinear.pdf'
citation: 'Shen, G., Zhao, D., Shen, S., & Zeng, Y. (2024). Exploiting nonlinear dendritic adaptive computation in training deep Spiking Neural Networks. Neural Networks, 170, 190–201. Elsevier.'
---

Inspired by the information transmission process in the brain, Spiking Neural Networks (SNNs) have gained considerable attention due to their event-driven nature. However, as the network structure grows complex, managing the spiking behavior within the network becomes challenging. Networks with excessively dense or sparse spikes fail to transmit sufficient information, inhibiting SNNs from exhibiting superior performance. Current SNNs linearly sum presynaptic information in postsynaptic neurons, overlooking the adaptive adjustment effect of dendrites on information processing. In this study, we introduce the Dendritic Spatial Gating Module (DSGM), which scales and translates the input, reducing the loss incurred when transforming the continuous membrane potential into discrete spikes. Simultaneously, by implementing the Dendritic Temporal Adjust Module (DTAM), dendrites assign different importance to inputs of different time steps, facilitating the establishment of the temporal dependency of spiking neurons and effectively integrating multi-step time information. The fusion of these two modules results in a more balanced spike representation within the network, significantly enhancing the neural network’s performance. This approach has achieved state-of-theart performance on static image datasets, including CIFAR10 and CIFAR100, as well as event datasets like DVS-CIFAR10, DVS-Gesture, and N-Caltech101. It also demonstrates competitive performance compared to the current state-of-the-art on the ImageNet dataset.