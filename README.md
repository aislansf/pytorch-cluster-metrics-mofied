# pytorch-cluster-metrics

![GitHub](https://img.shields.io/github/license/aislansf/pytorch-cluster-metrics.svg)
[![PyPI](https://img.shields.io/pypi/v/pytorch-cluster-metrics.svg)](http://pypi.org/project/pytorch-cluster-metrics/)
[![Documentation Status](https://readthedocs.org/projects/pytorch-cluster-metrics/badge/?version=latest)](https://pytorch-cluster-metrics.readthedocs.io/en/latest/?badge=latest)
[![GitHub last commit](https://img.shields.io/github/last-commit/aislansf/pytorch-cluster-metrics.svg)](https://github.com/aislansf/pytorch-cluster-metrics/commit/master)
[![DOI](https://zenodo.org/badge/585986858.svg)](https://zenodo.org/badge/latestdoi/585986858)

**[Documentation](https://pytorch-cluster-metrics.readthedocs.io/)** | 
**[Changelog](https://pytorch-cluster-metrics.io/en/latest/CHANGELOG/)** | 
**[Citation](https://pytorch-cluster-metrics.io/en/latest/citation/)**

## installation

the `pytorch-cluster-metrics` package is available in [PyPI](). to install, simply type the following command:

```
pip install pytorch-cluster-metrics
```

Pytorch implementation of standard metrics for clustering.
Test on PyTorch = 1.10.1 / cuda11.3_cudnn8_0

So far only the Silhouette score is implemented.
Code for the Silhouette score was developed in NumPy by Alexandre Abraham:
https://gist.github.com/AlexandreAbraham/5544803

# Installation

1. Open a terminal, navigate to the folder where you want to put the repository and clone it:
> git clone https://github.com/maxschelski/pytorch-cluster-metrics.git
2. Navigate into the folder of the repository (pytorch-cluster-metrics):
> cd pytorch-cluster-metrics
3. Install torchclustermetrics locally using pip:
> pip install -e .

For any questions feel free to contact me via E-Mail to max.schelski@googlemail.com.

# Usage

> from torchclustermetrics import silhouette
> 
> score = silhouette.score(X, labels)
