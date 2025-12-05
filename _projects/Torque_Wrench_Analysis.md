---
layout: project
title: Torque Wrench Analysis Using ANSYS 
description: Mechanics of Materials Final Torque Wrench Project
technologies: [MATLAB, Inventor, ANSYS]
image: /assets/images/normalstress.png
---

Designed a non-ratcheting, 3/8 inch drive instrumented torque wrench rated for 600 in-lbf. Torque was transduced using strain gauges bonded to the outer surfaces of the wrench at high strain locations. 

Learned how to use ANSYS via an FEM analysis of a provided ”baseline” design, used hand calculations to iterate the dimensions and material to meet all requirements, built a CAD model of the design, and then imported the CAD model to ANSYS. Once in ANSYS I performed the stress analysis, to ensure the design met the requirements and determined the torque wrench sensitivity.

___________________________________________________________________________________________________________________________

Project Design Requirements: 

- Attain at least 1.0 mV/V output at the rated torque of 600 in-lbf.
- Safety factor of Xo = 4 for yield or brittle failure
- Safety factor of XK = 2 for crack growth from an assumed crack of depth 0.04 inches
- Fatigue stress safety factor of XS = 1.5

Chosen Material: Al 7075 - T6
Young's modulus = 11e6 psi
Poisson's ratio = 0.33


![Photo of cad drawing]({{ "/assets/images/drawing.png" | relative_url }}){: .inline-image-l}
CAD Dimensions of Torque Wrench

Describe material used and its relevant mechanical properties.
Diagram communicating how loads and boundary conditions were applied to your FEM model.
Normal strain contours (in the strain gauge direction) from FEM
Contour plot of maximum principal stress from FEM
Summarize results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations
Torque wrench sensitivity in mV/V using strains from the FEM analysis
Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.






