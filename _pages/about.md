---
permalink: /
title: "Philipp Becker"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
I am a machine learning researcher currently pursuing a PhD at the Karlsruhe Institute of Technology (KIT), supervised by Prof. Gerhard Neumann. 
I focus on generative modeling, representation learning, and learning agents with applications in robotics and publish my work at conferences such as ICLR, ICML, NeurIPS, RLC, and CoRL. 
During my PhD, I contributed to establishing a new research group at the FZI Research Center for Information Technology, working under the direction of Prof. Neumann. Here I participated in successful grant writing and an industry project.
Before my time at KIT, I worked with the Bosch Center for Artificial Intelligence and the University of Tübingen for eight months.
Furthermore, I have a Master's degree in Autonomous Systems (Computer Science) from the Technical University of Darmstadt.
<p>

<p>
I am currently interning at the Samsung AI Center in Cambridge where I work on generative AI for text to image applications and expect to graduate with my by Summer 2025.
</p>



<h2> Research </h2>
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

<p>
<a href="https://pbecker93.github.io/publications/">Here is a list of all my publications.</a>
</p>


<h2> Updates </h2>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
