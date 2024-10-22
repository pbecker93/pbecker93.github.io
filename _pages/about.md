---
permalink: /
title: "Philipp Becker"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
I am currently pursuing a PhD in Machine Learning at the Karlsruhe Institute of Technology (KIT), supervised by Prof. Gerhard Neumann. Simultaneously, I am involved with the FZI Research Center for Information Technology, working towards establishing a new research group under Prof. Neumann's direction.

Before my time at KIT, I worked with the Bosch Center for Artificial Intelligence and the University of Tübingen for eight months.
Furthermore, I have a Bachelor's degree in Computer Science and a Master's degree in Autonomous Systems (Computer Science) from the Technical University Darmstadt.

I aim to complete my PhD by Spring 2025.
</p>

<h2> Reserach </h2>
<p>
My research focuses on world models for Reinforcement Learning with multimodal and high-dimensional observations. 
Here, I combine probabilistic state space models with deep learning to learn dynamics models and concise representations as published in: 
<ul>
<li> <a href="https://pbecker93.github.io/publication/coral">Combining Reconstruction and Contrastive Methods for Multimodal Representations in RL (<i>RLC 2024</i>) </a></li>
<li> <a href="https://pbecker93.github.io/publication/vrkn">On Uncertainty in Deep State Space Models for Model-Based Reinforcement Learning (<i>TMLR 2022</i>)</a> </li>
<li> <a href="https://pbecker93.github.io/publication/rkn">Recurrent Kalman Networks: Factorized Inference in High-Dimensional Deep Feature Spaces (<i>ICML 2019</i>)</a> </li>
</ul>
</p>

<p>
Beyond this, I worked on projects covering a wide range of topics such as  
<ul>
<li> <a href="https://pbecker93.github.io/versatile_il">Imitation Learning for Versatile Behavior </a>    </li>
<li> <a href="https://pbecker93.github.io/dyn_learning">Dynamics and Representation Learning for Robotics  </a>  </li>
<li> <a href="https://pbecker93.github.io/mfrl">Model-Free RL with a Focus on Trust Region Methods  </a>  </li>
<li> <a href="https://pbecker93.github.io/bdl"> Bayesian Deep Learning </a> </li>
</ul>
These works are published in venues such as NeurIPS, ICLR, CoRL, etc... 
</p>

<p>
<a href="https://pbecker93.github.io/publications/">Here is a list of all my publications.</a>
</p>


<h2> Updates </h2>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
