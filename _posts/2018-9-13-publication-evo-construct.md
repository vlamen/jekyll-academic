---
layout: post
title:  Evolutionary Construction of Convolutional Neural Networks
authors: Marijn van Knippenberg, Vlado Menkovski, Sergio Consoli
excerpt:  van Knippenberg, M., Menkovski, V., & Consoli, S. (2018, September). Evolutionary Construction of Convolutional Neural Networks. In International Conference on Machine Learning, Optimization, and Data Science (pp. 293-304). Springer, Cham.
modified: 06/9/2019, 9:00:24
tags: [computer vision, convolutional neural networks, evolutionary computing]
comments: true
category: publication
---

**Authors: Marijn van Knippenberg, Vlado Menkovski, Sergio Consoli**

**Abstract** 
Neuro-Evolution is a field of study that has recently gained significantly increased traction in the deep learning community. It combines deep neural networks and evolutionary algorithms to improve and/or automate the construction of neural networks. Recent Neuro-Evolution approaches have shown promising results, rivaling hand-crafted neural networks in terms of accuracy.

A two-step approach is introduced where a convolutional autoencoder is created that efficiently compresses the input data in the first step, and a convolutional neural network is created to classify the compressed data in the second step. The creation of networks in both steps is guided by an evolutionary process, where new networks are constantly being generated by mutating members of a collection of existing networks. Additionally, a method is introduced that considers the trade-off between compression and information loss of different convolutional autoencoders. This is used to select the optimal convolutional autoencoder from among those evolved to compress the data for the second step.

The complete framework is implemented, tested on the popular CIFAR-10 data set, and the results are discussed. Finally, a number of possible directions for future work with this particular framework in mind are considered, including opportunities to improve its efficiency and its application in particular areas.

**[Springer link](https://link.springer.com/chapter/10.1007/978-3-030-13709-0_25)**
