# CNEEP: Convolutional Neural Estimator for Entropy Production

Pytorch implementation of the convolutional neural estimator for entropy production (CNEEP).

Authors: Youngkyoung Bae<sup>1</sup>, Dong-Kyum Kim<sup>1</sup>, and Hawoong Jeong<sup>1,2</sup><br>

<sup>1</sup> <sub>Department of Physics, KAIST</sub>
<sup>2</sup> <sub>Center for Complex Systems, KAIST</sub>

## Introduction

This repository is for the code related to the paper "Attaining entropy production and dissipation maps from Brownian movies via neural networks".

## Abstract

 Quantifying entropy production (EP) is essential to understand stochastic systems at mesoscopic scales, such as living organisms or biological assemblies. However, without tracking the relevant variables, it is challenging to figure out where and to what extent EP occurs from recorded time-series image data from experiments. Here, applying a convolutional neural network (CNN), a powerful tool for image processing, we develop an estimation method for EP through an unsupervised learning algorithm that calculates only from movies. Together with an attention map of the CNN’s last layer, our method can not only quantify stochastic EP but also produce the spatiotemporal pattern of the EP (dissipation map). We show that our method accurately measures the EP and creates a dissipation map in two nonequilibrium systems, the bead-spring model and a network of elastic filaments. We further confirm high performance even with noisy, low spatial resolution data, and partially observed situations. Our method will provide a practical way to obtain dissipation maps and ultimately contribute to uncovering the nonequilibrium nature of complex systems.


