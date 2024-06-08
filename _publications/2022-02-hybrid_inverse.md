---
title: 'End-to-End Learning of Hybrid Inverse Dynamics Models for Precise and Compliant Impedance Control'
collection: publications
permalink: /publication/hybrid_inverse
date: 2022-05-27
venue: 'Robotics: Science and Systems'
authors: 'Moritz Reuss, Niels van Duijkeren, Robert Krug, <b>Philipp Becker</b>, Vaisakh Shaj, Gerhard Neumann'
paperurl: 'https://arxiv.org/abs/2205.13804'
#codeurl: 'https://github.com/Onur4229/SVSL_LMOE'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<p>
<h3> Abstract: </h3>
It is well-known that inverse dynamics models can improve tracking performance in robot control. These models need to precisely capture the robot dynamics, which consist of well-understood components, e.g., rigid body dynamics, and effects that remain challenging to capture, e.g., stick-slip friction and mechanical flexibilities. Such effects exhibit hysteresis and partial observability, rendering them, particularly challenging to model. Hence, hybrid models, which combine a physical prior with data-driven approaches are especially well-suited in this setting. We present a novel hybrid model formulation that enables us to identify fully physically consistent inertial parameters of a rigid body dynamics model which is paired with a recurrent neural network architecture, allowing us to capture unmodeled partially observable effects using the network memory. We compare our approach against state-of-the-art inverse dynamics models on a 7 degree of freedom manipulator. Using data sets obtained through an optimal experiment design approach, we study the accuracy of offline torque prediction and generalization capabilities of joint learning methods. In control experiments on the real system, we evaluate the model as a feed-forward term for impedance control and show the feedback gains can be drastically reduced to achieve a given tracking accuracy.
</p>