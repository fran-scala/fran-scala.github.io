---
title: "Quantum variational learning for entanglement witnessing"
meta_title: ""
description: "Entanglement witnessing with QML"
date: 2022-07-18T00:07:00Z
image: "/images/fs/papers/witness.png"
categories: ["Quantum Machine Learning"]
author: ["Francesco Scala", "Stefano Mangini", "Chiara Macchiavello", "Daniele Bajoni", "Dario Gerace"]
tags: ["Algorithms", "QML", "Entanglement"]
draft: false
summary: "[2022 International Joint Conference on Neural Networks (IJCNN), 1-8](https://ieeexplore.ieee.org/abstract/document/9892080)"
---

[2022 International Joint Conference on Neural Networks (IJCNN), 1-8](https://ieeexplore.ieee.org/abstract/document/9892080)

**Authors:** Francesco Scala, Stefano Mangini, Chiara Macchiavello, Daniele Bajoni, Dario Gerace

Several proposals have been recently introduced to implement Quantum Machine Learning (QML) algorithms for the analysis of classical data sets employing variational learning means. There has been, however, a limited amount of work on the characterization and analysis of quantum data by means of these techniques, so far. This work focuses on one such ambitious goal, namely the potential implementation of quantum algorithms allowing to properly classify quantum states defined over a single register of $n$ qubits, based on their degree of entanglement. This is a notoriously hard task to be performed on classical hardware, due to the exponential scaling of the corresponding Hilbert space as $2^n$. We exploit the notion of “entanglement witness”, i.e., an operator whose expectation values allow to identify certain specific states as entangled. More in detail, we made use of Quantum Neural Networks (QNNs) in order to successfully learn how to reproduce the action of an entanglement witness. This work may pave the way to an efficient combination of QML algorithms and quantum information protocols, possibly outperforming classical approaches to analyse quantum data. All these topics are discussed and properly demonstrated through a simulation of the related quantum circuit model.