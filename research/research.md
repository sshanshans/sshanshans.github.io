---
layout: default
title: research
description: Research
---
My research focuses on problems in diffusion geometry and Bayesian statistics, that are motivated
by the open challenges of extracting stable and interpretable information from high-dimensional
data. On the theory side, I build algorithms and probabilistic models on geometric objects for
dimension reduction, inference, regression and related machine learning problems. On the applied
side, I use my work on anatomical surfaces (typically, teeth and bones of primates) to gain in-
sights about evolutionary processes. On the implementation side, I develop robust and easy-to-use
software to bridge the gap between research and practice.

My advisor is [Ingrid Daubechies](https://math.duke.edu/people/ingrid-daubechies). 

#### Robust Curvature Computation
Curvature on surface is a fundamental concept of study in geometry for thousands of years, and now plays an important role in computer graphics and machine learning. Despite being well-understood in the continuous setting, the task of computing curvature remains challenging on discretized surfaces. One critical issue is that the computation must not be sensitive to the discretization. To this end, I used weighted Principal Component Analysis (PCA) to develop a robust algorithm for computing curvature on triangular meshes. Experiments demonstrated signicant improvement of our algorithm with greater stability under various perturbations to the mesh attributes. I further used this algorithm to improve the implementation for computing the Dirichlet energy of the normal, a continuous surface attribute that is widely used in characterising biological surfaces. By its stability under different mesh acquisition methods and preparation procedures, the new implementation dramatically enhanced the assessment, accuracy and reproducibility of biological research.

* ariaDNE: [(project page)](/articles/ariadne.html) 

Shan, S., Kovalsky, S. Z., Winchester, J. M., Boyer, D. M., & Daubechies, I. aria DNE: A Robustly Implemented Algorithm for Dirichlet Energy of the Normal. Methods in Ecology and Evolution. <br />

#### Improing Diffusion Maps via Semigroup Property

