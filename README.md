Welcome to the research code repository for my Master's Thesis work on Deep Learning Based Recommendation Systems. This work is still in progress.

![header-image](https://miro.medium.com/max/1400/1*lJhKb5Rl47RSrwI8mVB_5g.png)

# Background

Recommendation systems are technologies and techniques that can provide recommendations for items to be of use to a user.
The recommendations provided are aimed at supporting their users in various decision-making processes, such as what products to purchase, what music to listen, or what routes to take.
Correspondingly, various techniques for recommendation generation have been proposed and deployed in commercial environments.
The goal of this research is to impose a degree of order upon this diversity by presenting a coherent and unified repository of the most common recommendation methods to solve the collaborative filtering problem:
from classic matrix factorization to cutting-edge deep neural networks.

# Dataset

For my experiments thus far, I worked with the [MovieLens1M Dataset](https://github.com/khanhnamle1994/transfer-rec/tree/master/ml-1m), a famous dataset within the recommendation systems research community.
The data contains 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

# Research Models

## [Autoencoders](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments)

Here are the 6 different Autoencoders models for Collaborative Filtering:

* [AutoRec](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/AutoRec-TensorFlow) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/AutoRec-Autoencoders-Meet-Collaborative-Filtering.pdf))
* [DeepRec](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/NVIDIA-DeepRec-TensorFlow) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/Training-Deep-Autoencoders-For-Collaborative-Filtering.pdf))
* [Collaborative Denoising Autoencoders](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/CDAE-PyTorch) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/Collaborative-Denoising-Autoencoders-for-TopN-Recommendation-System.pdf))
* [Multinomial Variational Autoencoders](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/VAE-PyTorch) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/Variational-Autoencoders-for-Collaborative-Filtering.pdf))
* [Sequential Variational Autoencoders](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/SVAE-PyTorch) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/Sequential-Variational-Autoencoders-for-Collaborative-Filtering.pdf))
* [Embarrassingly Shallow Autoencoders](https://github.com/khanhnamle1994/transfer-rec/tree/master/Autoencoders-Experiments/ESAE-PyTorch) ([paper](https://github.com/khanhnamle1994/transfer-rec/blob/master/Autoencoders-Experiments/Embarrassingly-Shallow-Autoencoders-for-Sparse-Data.pdf))