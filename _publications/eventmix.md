---
title: "Eventmix: An efficient data augmentation strategy for event-based learning"
collection: publications
category: manuscripts
permalink: /publication/eventmix
date: 2023-9
venue: 'Information Sciences'
paperurl: 'http://floyeshen.github.io/files/eventmix.pdf'
citation: 'Shen, G., Zhao, D., & Zeng, Y. (2023). Eventmix: An efficient data augmentation strategy for event-based learning. Information Sciences, 644, 119170. Elsevier.'
---

High-quality and challenging event stream datasets play an important role in the design of an efficient event-driven mechanism that mimics the brain. Although event cameras can provide high dynamic range and low-energy event stream data, the scale is smaller and more difficult to obtain than traditional frame-based data, which restricts the development of neuromorphic computing. Data augmentation can improve the quantity and quality of the original data by processing more representations from the original data. This paper proposes an efficient data augmentation strategy for event stream data: EventMix. We carefully design the mixing of different event streams by Gaussian Mixture Model (GMM) to generate random 3D masks and achieve arbitrary shape mixing of event streams in the spatio-temporal dimension. By computing the relative distances of event streams, we propose a more reasonable way to assign labels to the mixed samples. The experimental results on multiple neuromorphic datasets have shown that our strategy can improve performance on neuromorphic classification tasks as well as neuromorphic human action recognition tasks both for ANNs and SNNs, and we have achieved state-of-the-art performance on DVS-CIFAR10, N-Caltech101, and DVS-Gesture datasets.