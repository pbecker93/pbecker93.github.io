---
title: 'Switching Recurrent Kalman Networks'
collection: publications
permalink: /publication/switch_rkn
date: 2021-11-16
venue: 'Machine Learning for Autonomous Driving Workshop @ NeurIPS'
authors: 'Giao Nguyen-Quynh, <b>Philipp Becker</b>, Chen Qiu, Maja Rudolph, Gerhard Neumann'
paperurl: 'https://arxiv.org/abs/2111.08291'
#codeurl: 'https://github.com/Onur4229/SVSL_LMOE'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<p>
<h3> Abstract: </h3>
Forecasting driving behavior or other sensor measurements is an essential component of autonomous driving systems. Often real-world multivariate time series data is hard to model because the underlying dynamics are nonlinear and the observations are noisy. In addition, driving data can often be multimodal in distribution, meaning that there are distinct predictions that are likely, but averaging can hurt model performance. To address this, we propose the Switching Recurrent Kalman Network (SRKN) for efficient inference and prediction on nonlinear and multi-modal time-series data. The model switches among several Kalman filters that model different aspects of the dynamics in a factorized latent state. We empirically test the resulting scalable and interpretable deep state-space model on toy data sets and real driving data from taxis in Porto. In all cases, the model can capture the multimodal nature of the dynamics in the data.
</p>