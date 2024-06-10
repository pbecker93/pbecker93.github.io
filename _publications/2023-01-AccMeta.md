---
title: 'Accurate Bayesian Meta-Learning by Accurate Task Posterior Inference'
collection: publications
permalink: /publication/acc_meta
date: 2023-02-01
venue: 'International Conference on Learning Representations (ICLR)'
authors: 'Michael Volpp, Philipp Dahlinger, <b>Philipp Becker</b>, Christian Daniel, Gerhard Neumann'
paperurl: 'https://openreview.net/forum?id=sb-IkS8DQw2'
codeurl: 'https://github.com/pbecker93/vrkn'
tag: "bdl"
#codeurl: 'https://github.com/Onur4229/SVSL_LMOE'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<p>
<h3> Abstract: </h3>
Bayesian meta-learning (BML) enables fitting expressive generative models to small datasets by incorporating inductive priors learned from a set of related tasks. The Neural Process (NP) is a prominent deep neural network-based BML architecture, which has shown remarkable results in recent years. In its standard formulation, the NP encodes epistemic uncertainty in an amortized, factorized, Gaussian variational (VI) approximation to the BML task posterior (TP), using reparametrized gradients. Prior work studies a range of architectural modifications to boost performance, such as attentive computation paths or improved context aggregation schemes, while the influence of the VI scheme remains under-explored. We aim to bridge this gap by introducing GMM-NP, a novel BML model, which builds on recent work that enables highly accurate, full-covariance Gaussian mixture (GMM) TP approximations by combining VI with natural gradients and trust regions. We show that GMM-NP yields tighter evidence lower bounds, which increases the efficiency of marginal likelihood optimization, leading to improved epistemic uncertainty estimation and accuracy. GMM-NP does not require complex architectural modifications, resulting in a powerful, yet conceptually simple BML model, which outperforms the state of the art on a range of challenging experiments, highlighting its applicability to settings where data is scarce.
</p>