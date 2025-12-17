---
layout: project
title: Wind Turbine Blade Design & Testing (MAE 4272)
description: Designed and experimentally tested a small-scale wind turbine blade        
technologies: [Autodesk Fusion, MATLAB, Wind Tunnel Testing, Experimental Data Analysis]
image: /assets/images/wind-turbine-blade-cad.png       
---


<h4><strong>Project Overview</strong></h4>
I worked with a small team to design and test a small-scale wind turbine blade in Cornell’s Big Blue laboratory wind tunnel. The project mirrorec a real engineering design problem, where we were given clear performance goals and strict physical constraints. The goal was to maximize power production while meeting strict geometric, mechanical, and structural constraints. The design had to operate safely within limits on blade size, rotational speed, braking torque, and material strength, and it was validated experimentally using the wind tunnel and magnetic particle brake.

---

<h4><strong>Design and Modeling</strong></h4>
We selected a NACA 4412 airfoil based on its strong aerodynamic performance at low Reynolds numbers, which are typical for small-scale wind turbines. Using Airfoil theory and MATLAB-based modeling, we designed the blade to operate near a target rotation rate of 1000 RPM at the wind speed corresponding to the peak of a Weibull probability distribution, representing the most likely operating condition. 
The blade geometry was optimized by adjusting chord length and twist along the span so that each section operated near the optimal angle of attack, maximizing lift-to-drag ratio. Structural calculations were also performed to estimate bending stresses and confirm the design maintained an adequate factor of safety and did not exceed the material strength limits. 

![Figure 2: chord + pitch distribution across radius]({{ "/assets/images/chord&pitch-vs-radius.png" | relative_url }}){: .inline-image-r style="width: 2000px"}

---

<h4><strong>Testing and Results</strong></h4>
The finished blades were tested in the Big Blue wind tunnel using a magnetic particle brake to apply controlled loads. Wind speed was varied across the most probable operating range, and power versus rotational speed curves were measured. The experimentally observed optimal rotational speed closely matched the design prediction, validating the aerodynamic design approach. 
However, the measured power output was significantly lower than predicted due to real-world effects such as mechanical losses, aerodynamic tip losses, surface roughness from 3D printing, and early stall at low Reynolds numbers.

![Figure 3: Experimental Power vs. RPM Curves for each wind speed condiiton]({{ "/assets/images/power-vs-RPM.png" | relative_url }}){: .inline-image-l}

---

<h4><strong>My Contribution</strong></h4>
I contributed across multiple stages of the project, including helping make design choices, developing the experimental testing protocol, assisting with the CAD blade design and airfoil theory MATLAB model, and participating in wind tunnel testing. I also helped analyze the experimental data and compare the results to our analytical predictions. Overall, I worked closely with my teammates throughout the design, testing and analysis process.


