---
title: "A general approach to Dropout in Quantum Neural Networks"
meta_title: ""
description: "Analysis of dropout technique in Quantum Machine Learning"
date: 2023-10-05T00:06:00Z
image: "/images/fs/papers/classical_vs_quantum.png"
categories: ["Quantum Machine Learning"]
author: ["Francesco Scala", "Andrea Ceschini", "Massimo Panella","Dario Gerace"]
tags: ["QML", "QNN", "Algorithms", "Entanglement"]
draft: false
summary: "Adv. Quantum Technol. 2023, 2300220"
---

[Adv. Quantum Technol. 2023, 2300220](https://doi.org/10.1002/qute.202300220)
[arXiv:2310.04120](https://arxiv.org/abs/2310.04120)

**Authors:** Francesco Scala, Andrea Ceschini, Massimo Panella, Dario Gerace

In classical Machine Learning, “overfitting” is the phenomenon occurring when a given model learns the training data excessively well, and it thus performs poorly on unseen data. A commonly employed technique in Machine Learning is the so called “dropout”, which prevents computational units from becoming too specialized, hence reducing the risk of overfitting. With the advent of Quantum Neural Networks as learning models, overfitting might soon become an issue, owing to the increasing depth of quantum circuits as well as multiple embedding of classical features, which are employed to give the computational nonlinearity. Here we present a generalized approach to apply the dropout technique in Quantum Neural Network models, defining and analysing different quantum dropout strategies to avoid overfitting and achieve a high level of generalization. Our study allows to envision the power of quantum dropout in enabling generalization, providing useful guidelines on determining the maximal dropout probability for a given model, based on overparametrization theory. It also highlights how quantum dropout does not impact the features of the Quantum Neural Networks model, such as expressibility and entanglement. All these conclusions are supported by extensive numerical simulations, and may pave the way to efficiently employing deep Quantum Machine Learning models based on state-of-the-art Quantum Neural Networks.