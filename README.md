# explainable-autoencoders
> Implementation of autoencoders with different features from principle component analysis

This repository explores neural network autoencoders and the information loss due to compression. These studies are inspired by the studies of Ladjal et al. [1] and extend those to the case of multiple input units. The `additional` folder contain excursions to some specific details which are not relevant for the main idea - get a feeling for how deep neural networks compress data and make the compressed representation more explainable from a classical viewpoint without destroying the advantage of deep networks. This is done by forcing the latent space into a representation which shows similar features as a PCA compression.

[1] https://arxiv.org/abs/1904.01277
