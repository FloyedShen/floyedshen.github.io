---
title: "Brain-inspired neural circuit evolution for spiking neural networks"
collection: publications
category: manuscripts
permalink: /publication/neuevo
date: 2023-9
venue: 'Proceedings of the National Academy of Sciences'
paperurl: 'http://floyeshen.github.io/files/neuevo.pdf'
citation: 'Shen, G., Zhao, D., Dong, Y., & Zeng, Y. (2023). Brain-inspired neural circuit evolution for spiking neural networks. Proceedings of the National Academy of Sciences, 120(39), e2218173120. National Acad Sciences.'

---

In biological neural systems, different neurons are capable of self-organizing to form different neural circuits for achieving a variety of cognitive functions. However, the current design paradigm of spiking neural networks is based on structures derived from deep learning. Such structures are dominated by feedforward connections without taking into account different types of neurons, which significantly prevent spiking neural networks from realizing their potential on complex tasks. It remains an open challenge to apply the rich dynamical properties of biological neural circuits to model the structure of current spiking neural networks. This paper provides a more biologically plausible evolutionary space by combining feedforward and feedback connections with excitatory and inhibitory neurons. We exploit the local spiking behavior of neurons to adaptively evolve neural circuits such as forward excitation, forward inhibition, feedback inhibition, and lateral inhibition by the local law of spike-timing-dependent plasticity and update the synaptic weights in combination with the global error signals. By using the evolved neural circuits, we construct spiking neural networks for image classification and reinforcement learning tasks. Using the brain-inspired Neural circuit Evolution strategy (NeuEvo) with rich neural circuit types, the evolved spiking neural network greatly enhances capability on perception and reinforcement learning tasks. NeuEvo achieves state-of-the-art performance on CIFAR10, DVS-CIFAR10, DVS-Gesture, and N-Caltech101 datasets and achieves advanced performance on ImageNet. Combined with on-policy and off-policy deep reinforcement learning algorithms, it achieves comparable performance with artificial neural networks. The evolved spiking neural circuits lay the foundation for the evolution of complex networks with functions.