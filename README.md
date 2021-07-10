# Multimode-fiber-Image-reconstruction
This repository stores my codes to improve the image reconstruction process for multimode fiber experiments. 

Multimode fibers (MMFs) have the potential to carry complex images for endoscopy and related applications, but decoding the complex speckle patterns produced by mode-mixing and modal dispersion in MMFs is a serious challenge. Several groups have recently shown that convolutional neural networks (CNNs) can be trained to perform high-fidelity MMF image reconstruction. We find that a considerably simpler neural network architecture, the single hidden layer dense neural network, performs at least as well as previously-used CNNs in terms of image reconstruction fidelity, and is superior in terms of training time and computing resources required. The trained networks can accurately reconstruct MMF images collected over a week after the cessation of the training set, with the dense network performing as well as the CNN over the entire period.

![Multimode Fiber Images](https://github.com/zhuchangyan/Multimode-fiber-Image-reconstruction/blob/master/images/2.PNG)

This work is published as: Zhu, C., Chan, E.A., Wang, Y. et al. Image reconstruction through a multimode fiber with a simple neural network architecture. Sci Rep 11, 896 (2021). https://doi.org/10.1038/s41598-020-79646-8
