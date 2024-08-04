This repository is a documentation for a project that utilizes GRTensor package, a powerful package for performing differential geometry and tensor calculus operations. GRTensor II is particularly tailored for applications in General Relativity and runs on both Maple and Mathematica. This project is split into two main sections: General Relativity, where we explore the mathematical structure of spacetime through various metrics, and Cosmology, where we apply these concepts to model the universe's large-scale dynamics.

## General Relativity

General Relativity (GR) describes gravitation through the curvature of spacetime, induced by mass-energy. The metrics considered in this section are solutions to Einstein's field equations, each under different assumptions about the symmetry and matter content of spacetime.

### Files and Metrics

- **Schwarzschild Metric (`Schwarzschild.mws`)**:
  - Describes a spherically symmetric, non-rotating body like a static black hole or a planet. This metric is crucial for understanding phenomena such as gravitational time dilation near massive bodies.
  - The file details the steps to set up and solve the Schwarzschild metric using GRTensor II, providing an essential foundation in handling static spacetime curvatures.

- **Kerr Metric (`Kerr_soln.mws`)**:
  - Extends the Schwarzschild metric to rotating bodies, representing the spacetime around rotating black holes. This metric introduces complexities such as the ergosphere and frame dragging.
  - The exercise included demonstrates how to verify the properties of the Kerr metric, including its role in explaining the rotational effects observed near celestial bodies.

- **Reissner-Nordström Metric (`Reissner-Nordstrom.mws`)**:
  - A charged, non-rotating black hole solution, which introduces electric charge as an additional factor influencing spacetime geometry.
  - This document explores how electric charge affects the structure of black holes and the surrounding spacetime.

These metrics allow us to probe fundamental questions about the nature of black holes, gravitational interaction in extreme conditions, and the theoretical predictions of black hole horizons and singularities.

## Cosmology

In the Cosmology section, we apply general relativistic concepts to understand the structure and evolution of the universe. These applications utilize different cosmological models to interpret observational data, such as redshifts from distant supernovae.

### Files and Analysis

- **FLRW Metric (`Friedmann_Eqns.mws`)**:
  - The Friedmann–Lemaître–Robertson–Walker metric describes a homogeneous and isotropic expanding universe. This file discusses solutions to the Friedmann equations, which are fundamental in cosmological models like the Big Bang theory.
  - It includes mathematical derivations and applications to various energy content scenarios of the universe, such as matter-dominated and radiation-dominated phases.

- **Supernova Data Analysis (`SCPUnion2.1_mu_vs_z2.mws`)**:
  - This file involves analyzing the redshift and luminosity distance data from the SCP Union2.1 supernova compilation to explore dark energy models and the expansion rate of the universe.
  - Techniques like data fitting and statistical analysis are employed to compare theoretical models with observational data, enhancing our understanding of the universe's acceleration.


The cosmological part of this project seeks to understand the dynamics of the universe's expansion, the role of dark energy, and the interplay between theoretical predictions and empirical observations.



## Acknowledgments

This project was completed as part of the 4th Summer School and Internship program of the Centre for Theoretical Physics (CTP) at the British University in Egypt (BUE). I would like to extend the deepest gratitude to Dr. Waleed Elhanafy for his invaluable guidance and mentorship throughout the duration of this project. His expertise and insights were crucial in shaping the research and educational outcomes. I also thank the coordinators and staff at CTP for their support and for providing a stimulating academic environment that enriched our learning experience.

