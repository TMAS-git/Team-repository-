# Project Name

Project 3: Quantum Algorithm as a PDE Solver for Computational Fluid Dynamics (CFD)


# Team Name

Start-QC


# Members' Name & WISER Enrollment ID

- Name: Alex Stephane Tieta Mbiezie
- Enrollment ID: gst-DasfSkKAyfORM5N


# Project Summary

To solve the 1-D Burgers' equation with shock tube, I designed a quantum-inspired algorithm based on Quantum Tensor Network (QTN), more precisely on Matrix Product States (MPSs), powerful objects that can represent 2N -dimensional quantum states as a set of 2N matrices. Thus, low-entangled states of 1D systems can be exponentially compressed by MPSs. Therefore, they provide state-of-the-art framework for simulating complex quantum dynamics. This also implies potential exponential scaling in execution time for algorithm using this framework compare to their classical counterparts. 

However, the algorithm I designed, while giving good approximation to the solution of the PDE, takes a huge amount of time for execution (~ 12 min) compare to the classical algorithm based on explicit upwind scheme with central diffusion that I designed for comparison (a few second), under the conditions (the parameters values). This essentially arises from MPSs/MPOs conversion to dense arrays in the time evolution loop that I implemented for solution evaluation at different step time using explicit Euler method. 

This leads to large possibilities of improvement of my algorithm in order to achieve efficient simulation while fully exploit quantum advantage. One path of improvement could be through a way of integrating either coarse-grained evaluation or pixel sampling to extract information directly from the Matrix Product States into the loop during time evolution.  


# Project Presentation deck

To get a quick visual overview of this project, check out the presentation deck:

[Presentation deck (Slides)](https://github.com/TMAS-git/Team-repository-/blob/main/Project%20Presentation%20deck.pdf)


# Note:
This repository contains all the files related to the project. This includes:

- Algorithm design (PDF)
- Open-source code (Jupyter Notebook)
- Validation and Benchmark (PDF)
- Resource and Noise Analysis (PDF)
- Project Presentation deck (Slides)
