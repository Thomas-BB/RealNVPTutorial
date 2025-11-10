# Real NVP Tutorial

Real NVP transformations are a computationally efficient subgroup of Normalizing Flows, which aim at estimating unknown or intractable probability distributions.
They were introduced by L.Dinh et al. in a paper called ''Density Estimation using Real NVP'' https://arxiv.org/pdf/1605.08803, which is also the basis of this tutorial: \
On a two-dimensional toy dataset it will be illustrated step by step, why Real NVPs work and how they can be implemented. 

## Requirements

torch 2.5.1 \
numpy 2.2.1 \
matplotlib 3.10.0 \
scikit-learn 1.7.2
