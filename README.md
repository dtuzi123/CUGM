>📋 The implementation of Continual Unsupervised Generative Modeling

# Title : Continual Unsupervised Generative Modeling

This repository is the implementation of Continual Unsupervised Generative Modeling.


# Paper link : 

# Abstract

Variational Autoencoders (VAEs), can achieve remarkable results in single tasks learning of data representations, image generation, and image-to-image translation among others. However, VAEs suffer from loss of information when aiming  to continuously learn a sequence of different data domains. Such information losses are caused by the catastrophic forgetting, which affects all machine learning methods, both classical as well as deep learning. This paper addresses the problem of catastrophic forgetting by developing a new theoretical framework which derives an upper bound to the negative sample log-likelihood when continuously learning sequences of tasks. These theoretical derivations provide new insights into the forgetting behavior of networks, showing that their optimal performance is achieved when a dynamic mixture expansion model adds new components whenever learning new tasks. In our approach we optimize the model size by introducing the Dynamic Expansion Graph Model (DEGM) that dynamically builds a graph structure promoting the positive knowledge transfer when learning new tasks. In addition, we propose a Dynamic Expansion Graph Adaptive Mechanism (DEGAM) that generates adaptive weights to regulate the graph structure, further improving the positive knowledge transfer effectiveness. Experimental results show that the proposed methodology performs better than other baselines in continual learning. The code is provided in https://github.com/dtuzi123/CUGM.


# Environment

1. Tensorflow 2.4.1
2. Python 3.7

## Training

To train the model(s) in the paper, run this command:

```train
python FiveRun_XXX.py
```






