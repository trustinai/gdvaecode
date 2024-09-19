# The Gaussian Discriminant Variational Autoencoder (GdVAE) - A Self-Explainable Model with Counterfactual Explanations
## ECCV 2024 Paper

<div style="text-align: justify">

<div align="center">

![Example](https://trustinai.github.io/gdvae/static/images/GdVAECounterfactuals.gif)
</div>


Copyright &copy; 2024 Ruhr West University of Applied Sciences,
Bottrop, Germany AND e:fs TechHub GmbH, Gaimersheim, Germany.

This Source Code Form is subject to the terms of the Apache License 2.0.
If a copy of the APL2 was not distributed with this file, You can obtain
one at <https://www.apache.org/licenses/LICENSE-2.0.txt>.

For more info visit [project page](https://trustinai.github.io/gdvae/).

**[Architecture](#architecture)**
| **[Installation](#installation)**
| **[Example](#example)**
| **[Citation](#citation)**

[![arXiv](https://img.shields.io/badge/arXiv-XXXXX.XXXXX-a.svg)](https://arxiv.org/abs/XXXX.XXXXX)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Pytorch](https://img.shields.io/badge/PyTorch-2.1-red.svg)](https://pytorch.org)



## Architecture

![Architecture](https://trustinai.github.io/gdvae/static/images/carousel2.png)

## Installation

### Anaconda environment

Begin by creating an empty anaconda environment

```
conda create -n gdvae
```

Activate the `gdvae` environment: 

```
conda activate gdvae
```

Install pip with

```
conda install pip
```

Finally install the required packages with 

```
pip install -r requirements.txt 
```
## Example

### CelebA Regularized Latent Space

![CelebA regularized latent space](https://trustinai.github.io/gdvae/static/images/carousel3.png)

### FFHQ Examples

![FFHQ Example](https://trustinai.github.io/gdvae/static/images/carousel1.png)

### Multi-class MNIST Counterfactual Examples

![FFHQ Example](https://trustinai.github.io/gdvae/static/images/carousel7.png)

## Citation

If this code is useful to your work, please cite [our paper](https://arxiv.org/abs/XXXX.XXXX) as follows: 

```
@InProceedings{Haselhoff_2024_ECCV,
  author    = {Haselhoff, Anselm and Trelenberg, Kevin and Küppers, Fabian and Schneider, Jonas},
  title     = {The Gaussian Discriminant Variational Autoencoder (GdVAE): A Self-Explainable Model with Counterfactual Explanations},
  booktitle = {European Conference on Computer Vision (ECCV)},
  year      = {2024}
}
```