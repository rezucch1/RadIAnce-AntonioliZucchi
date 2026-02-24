# RadIAnce
Repository of the introductory project of the course Scientific Computing Tools for Advanced Mathematical Modelling AY 2025/2026

# Introduction

Rooftop solar potential assessment is a central problem in building engineering, as roof geometry strongly influences incident solar radiation and, consequently, photovoltaic performance. Annual irradiance on complex roof surfaces depends on multiple interacting geometric parameters, including orientation, inclination, surface articulation, and mutual shading effects. Despite the widespread availability of high-fidelity solar analysis software, the computational cost associated with repeated simulations limits its applicability in large-scale optimization, sensitivity analysis, and early-stage design exploration.

In recent years, advances in computational modeling and surrogate-based methods have enabled the development of reduced-order representations of complex physical processes. In particular, emulator frameworks allow the approximation of simulation outputs by learning the relationship between parametric inputs and high-resolution numerical results, significantly reducing evaluation time while preserving predictive accuracy.

This project aims at developing an innovative scientific computing framework, RadIAnce, to emulate annual rooftop irradiance and surface area from a parametric roof model defined by eight geometric parameters. 

# Rules

Each group needs to create its branch of the main branch (name_of_your_new_branch=Surname1Surname2Surname3). 

Create the branch on your local machine and switch in this branch :

$ git checkout -b [name_of_your_new_branch]
Push the branch on github :

$ git push origin [name_of_your_new_branch]
