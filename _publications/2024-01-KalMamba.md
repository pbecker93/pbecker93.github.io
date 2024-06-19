---
title: 'KalMamba: Towards Efficient Probabilistic State Space Models for RL under Uncertainty'
collection: publications
permalink: /publication/kalmamba
date: 2024-06-19
venue: 'Aligning Reinforcement Learning Experimentalists and Theorists Workshop @ ICML; Next Generation of Sequence Modeling Architectures @ ICML'
authors: ' <b>Philipp Becker</b>, Niklas Freymuth, Gerhard Neumann'
---

<p>
<h3> Abstract: </h3>
Probabilistic State Space Models (SSMs) are essential for Reinforcement Learning (RL) from high-dimensional, partial information as they provide concise representations for control. Yet, they lack the computational efficiency of their recent deterministic counterparts such as S4 or Mamba. We propose KalMamba, an efficient architecture to learn representations for RL that combines the strengths of probabilistic SSMs with the scalability of deterministic SSMs. KalMamba leverages Mamba to learn the dynamics parameters of a linear Gaussian SSM in a latent space. Inference in this latent space amounts to standard Kalman filtering and smoothing. We realize these operations using parallel associative scanning, similar to Mamba, to obtain a principled, highly efficient, and scalable probabilistic SSM. Our experiments show that KalMamba competes with state-of-the-art SSM approaches in RL while significantly improving computational efficiency, especially on longer interaction sequences.
</p>