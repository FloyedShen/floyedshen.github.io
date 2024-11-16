---
title: "Backpropagation with biologically plausible spatiotemporal adjustment for training deep spiking neural networks"
collection: publications
category:  Spiking Neural Networks
permalink: /publication/back
date: 2023-9
venue: 'Journal'
paperurl: 'http://floyeshen.github.io/files/back.pdf'
citation: 'Shen, G., Zhao, D., & Zeng, Y. (2022). Backpropagation with biologically plausible spatiotemporal adjustment for training deep spiking neural networks. Patterns, 3(6). Elsevier.'

---

The spiking neural network (SNN) mimics the information-processing operation in the human brain. Directly applying backpropagation to the training of the SNN still has a performance gap compared with traditional deep neural networks. To address the problem, we propose a biologically plausible spatial adjustment that rethinks the relationship between membrane potential and spikes and realizes a reasonable adjustment of gradients to different time steps. It precisely controls the backpropagation of the error along the spatial dimension. Secondly, we propose a biologically plausible temporal adjustment to make the error propagate across the spikes in the temporal dimension, which overcomes the problem of the temporal dependency within a single spike period of traditional spiking neurons. We have verified our algorithm on several datasets, and the experimental results have shown that our algorithm greatly reduces network latency and energy consumption while also improving network performance.