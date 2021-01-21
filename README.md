# Layerwise learning for QNNs in Pennylane-Pytorch

This repository is the result of my work as a mentee in the [Quantum Computing Mentorship Program](https://qosf.org/qc_mentorship/) of the _Quantum Open Source Foundation_.

Here, we provide a _proof-of-concept_ of the implementation of a training technique for Quantum Neural Networks in Pennylane's Pytorch [interface](https://pennylane.readthedocs.io/en/stable/introduction/interfaces/torch.html) known as [layerwise learning](https://arxiv.org/abs/2006.14904). 

binary classification on the MNIST dataset handwritten digits (images)

strategy to avoid [Barren Plateus](https://pennylane.ai/qml/demos/tutorial_barren_plateaus.html)

Phase I the size of the circuit is gradually increased at each step of the training while freezing previuos layers
## About us :flushed:

__For LinkedIn:__ My name is Felipe Oyarce. Master in Quantum Optics. Machine Learning Developer and Quantum Computing Enthusiast. Inspired in technological solutions to real-world problems. 

__Official description:__ I'm a Broccoli, excellent for health but I don't attract people's attention. Sometimes I cry a little.

## Overview of Layerwise learning :nerd_face:

### Training the circuit little by little
This task inspired me to propose a project that can be end in a blog post about the different metrics out there for measuring the _closeness_ between two quantum states. 

Since this task is about about finding the optimal parameters of a Quantum Circuit in order to optimize a _distance_ between the output state of the Quantum Circuit and a target quantum state, this opens a fundamental question in the theory of quantum mechanics about the feasibility of defining a measurable a distance metric between quantum states.

We compared different metrics implementing different optimization routines in __Qiskit__ and __Pennylane__ which are open-source frameworks for Quantum Computing.

Go to the [Jupyter Notebook](https://nbviewer.jupyter.org/github/fioyarce/qosf_mentorship_program/blob/master/Task%201/Task%201%20-%20Solution.ipynb) with my solution rendered with a nice visualization.

## References
[Barren Plateaus paper](https://arxiv.org/abs/1803.11173)
[blog post](https://blog.tensorflow.org/2020/08/layerwise-learning-for-quantum-neural-networks.html)

[Theodor Isacsson](https://github.com/thisac)
