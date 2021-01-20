# Layerwise learning for QNNs in Pennylane-Pytorch

The aim of this repository is to provide some thoughts, ideas and solutions to the screening tasks released by the _Quantum Open Source Foundation_ for applying to the __Mentorship Program__. If you want to read more about the screening tasks go to this [link](https://docs.google.com/document/d/1Ow3v8Y4rYBdgxXNxKV9ZUAM4bwL6211U6DWCcByZ4A4/edit).

## About us :flushed:

__For LinkedIn:__ My name is Felipe Oyarce. Master in Quantum Optics. Machine Learning Developer and Quantum Computing Enthusiast. Inspired in technological solutions to real-world problems. 

__Official description:__ I'm a Broccoli, excellent for health but I don't attract people's attention. Sometimes I cry a little.

## Overview of Layerwise learning :nerd_face:

### How can we know that two quantum states are close?
This task inspired me to propose a project that can be end in a blog post about the different metrics out there for measuring the _closeness_ between two quantum states. 

Since this task is about about finding the optimal parameters of a Quantum Circuit in order to optimize a _distance_ between the output state of the Quantum Circuit and a target quantum state, this opens a fundamental question in the theory of quantum mechanics about the feasibility of defining a measurable a distance metric between quantum states.

We compared different metrics implementing different optimization routines in __Qiskit__ and __Pennylane__ which are open-source frameworks for Quantum Computing.

Go to the [Jupyter Notebook](https://nbviewer.jupyter.org/github/fioyarce/qosf_mentorship_program/blob/master/Task%201/Task%201%20-%20Solution.ipynb) with my solution rendered with a nice visualization.
