# Robust Control and Convex Optimization Project
## Overview
This was my final report submission for the project graded course "Robust Control and Convex Optimization" at ETH Zurich.
<br>
The project involved the robust control of a non trivially coupled MIMO linear system. Furthermore, the system had to be physically motivated. 
For my submission, I decided to choose as my system an inverted pendulum on a cart and as my control objective the control of the horizontal velocity of the cart and the angle of the inverted pendulum with respect to the horizontal plane. I further physically motivated this system by relating this abstract representation to actual physical systems such as Segways, cranes etc. To make the system a bit more complex, I also added 2 DC motors as actuators and tried using actual real world data for my simulations. 
<br>
All the plots in the report were generated using MATLAB and a Simulink model of the whole system (comprehensive of the system dynamics, actuator dynamics and uncertanties behaviour) was implemented in Simulink. For academic integrity reasons, I will not be sharing my code.
## Project requirements
- Description of the system and why it is important.
- Extensive literature review on how the system has been previously modelled and controlled.
- Derivation of the system.
- A nominal control policy that can regulate the system.
- Simulation of the closed loop system using the nominal control policy.
- Description of the sources of the uncertainties affecting the system.
- Formulation of the system dynamics with 2-5 uncertainties.
- Implementation of the Structured Singular Value (SSV) minimizing controller.
- Quantification and certification of robust performance for SSV controller.
- Comparison of SSV and nominal control policies with respect to closed loop trajectory simulations and robust performance metrics.
- Comparison of performance on experimental system operation.
- 
## Notes on report quality
I would like to preface the report with the fact that at the time, both during the midterm and the final, I had numerous other committments. As a result, there are actually many parts that could be improved, such as the part where I analyse the uncertainties and give them a physical motivation, and many more. 
<br>
Final grade: 5.5 / 6. 
<br>This score does not include an additional 0.25 points that could have been obtained by doing 7 of the 9 weekly homeworks, but because I was busy I didn't do them.

## Source code and discussion
To uphold academic integrity, I will not be sharing the MATLAB and Simulink code for this project.
<br>
However, I am available to provide explainations and discuss about my methodologies and results.
<br>
If you are a student looking to take this course, I can also share my opinion about it in private.
