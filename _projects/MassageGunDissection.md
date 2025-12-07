---
layout: project
title: Massage Gun Dissection
description: Dissection and System Dynamics Analysis of Massage Gun
technologies: [System Dynamics, MATLAB]
image: /assets/images/halfbody.png
---

Dissected and analyzed a multi-function massage gun with three different mechanical heads.

We first created a block diagram for the system. The input is the voltage provided to the motor, and the output is the position of the end of the massage gun. The output we are focusing on is clearly shown below.
<!-- output -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/inputgun.png' | relative_url }}" alt="Input image">
  <figcaption>The red arrow denotes the output of the system, the linear position of the ball</figcaption>
</figure>

Once we knew the system input and output, the next step was filling in the steps in-between to map out the full process. 

<!-- block diagram -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/blockdiagram.png' | relative_url }}" alt="Input image">
  <figcaption>Block Diagram of System</figcaption>
</figure>

After creating the Block Diagram, we found the transfer function. 
### Transfer Functions

$$
G(s) = \frac{X(s)}{F(s)} = \frac{1}{m s^2 + b s + k}
$$

$$
G_m(s) = \frac{F(s)}{U(s)} = \frac{k_m}{\tau s + 1}
$$

The overall system is:
$$
X(s) = G(s)G_m(s)U(s) = \frac{k_m}{(\tau s + 1)(m s^2 + b s + k)}\, U(s)
$$

