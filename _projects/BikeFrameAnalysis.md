---
layout: project
title: Bike Frame Analysis
description: Analysis using ANSYS, CAD
technologies: [ANSYS, Statics, CAD]
image: /assets/images/bikeframe.png
---

Bike Frame Design and Finite Element Optimization.

As part of the class Engineering Simulations using ANSYS, I designed and analyzed an electric bicycle frame intended for wide deployment in bike-share systems such as Ithaca Bikeshare. The project focused on balancing lightweight design, structural integrity, safety, and integration of an electric battery while using Finite Element Analysis to evaluate performance.

<!-- og bike deformation pic-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/oldbike.png' | relative_url }}" alt="oldbike">
  <figcaption>Origonal Bike Frame Deformation</figcaption>
</figure>

Starting from an initial frame geometry, I developed shell-based finite element models in ANSYS, applied realistic loading and boundary conditions, and evaluated displacement, stress, and safety factor distributions. I performed mesh convergence studies to verify simulation accuracy. Then I modified the frame geometry and incorporated the battery load. The updated design was compared against the original design to quantify changes in deformation and stress.

<!-- new bike deformation pic-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/newbike.png' | relative_url }}" alt="newbikeframe">
  <figcaption>Revised Bike Frame Deformation</figcaption>
</figure>

The final phase of the project focused on parametric optimization. By varying the thickness of the horizontal battery-support tube while constraining the minimum safety factor, I minimized the bike's structural mass without compromising strength. Through this project, I gained experience with finite element modeling, verification through mesh convergence, design iteration, and optimization workflows commonly used in the automotive and aerospace industries.

[Download the full project]({{ "/assets/BikeFrameANSYS.pdf" | relative_url }}) in PDF format.

