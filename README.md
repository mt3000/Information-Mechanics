# Master's Thesis Figures

This repository contains resources and scripts used to generate figures for the following Master's thesis and publication.

  The Mechanics of CNN Filtering with Rectification
  Liam Frija-Altarac 2025
  
  [Thesis 2026](https://www.matthewtoews.com/thesis/Thesis_Liam_Frija-Altarac_2025.pdf "Arxiv")

  [Arxiv 2025](https://arxiv.org/pdf/2512.24338 "Arxiv")

  [CVPR 2026 Findings ](https://openaccess.thecvf.com/content/CVPR2026F/papers/Frija-Altarac_The_Mechanics_of_CNN_Filtering_with_Rectification_CVPRF_2026_paper.pdf "CVPR 2026 Findings")
  

## Repository Structure

### /utils/utils.py
- Basic tools for decomposing an image into symmetric and antisymmetric components.
- Miscellaneous tools for accessing CNN filters and measuring a filter’s dominant orientation.
- Utilities for measuring a single kernel’s orientation.

### /propagation_experiments
Experiments related to information propagation (repeated convolution with different kernels, different activation functions) .

### /dct_breakdown
Analysis of the spectral distribution of filters in CNNs.
