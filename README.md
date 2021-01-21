# Layerwise learning for QNNs in Pennylane-Pytorch

This repository is the result of my work as a mentee in the [Quantum Computing Mentorship Program](https://qosf.org/qc_mentorship/) of the _Quantum Open Source Foundation_.

Here, we provide a _proof-of-concept_ of the implementation of a technique for better training Quantum Neural Networks in Pennylane's Pytorch [interface](https://pennylane.readthedocs.io/en/stable/introduction/interfaces/torch.html) known as [layerwise learning](https://arxiv.org/abs/2006.14904).

The task selected for this _PoC_ is the same used in the original paper of binary classification between the handwritten digits _3_ and _6_ in the MNIST dataset.

## About us :flushed:

__For LinkedIn:__ My name is Felipe Oyarce. Master in Quantum Optics. Machine Learning Developer and Quantum Computing Enthusiast. Inspired in technological solutions to real-world problems. 

__Official description:__ I'm a Broccoli, excellent for health but I don't attract people's attention. Sometimes I cry a little.

## Overview of Layerwise learning :nerd_face:

binary classification on the MNIST dataset handwritten digits (images)

strategy to avoid [Barren Plateus](https://pennylane.ai/qml/demos/tutorial_barren_plateaus.html)

Phase I the size of the circuit is gradually increased at each step of the training while freezing previuos layers

### Training the circuit little by little :walking:


Go to the [Jupyter Notebook](https://nbviewer.jupyter.org/github/fioyarce/qosf_mentorship_program/blob/master/Task%201/Task%201%20-%20Solution.ipynb) with my solution rendered with a nice visualization.

## Our implementation

transform the quantum circuit into a [TorchLayer](https://pennylane.readthedocs.io/en/stable/code/api/pennylane.qnn.TorchLayer.html)

## References
[Barren Plateaus paper](https://arxiv.org/abs/1803.11173)
[blog post](https://blog.tensorflow.org/2020/08/layerwise-learning-for-quantum-neural-networks.html)

[Theodor Isacsson](https://github.com/thisac)
