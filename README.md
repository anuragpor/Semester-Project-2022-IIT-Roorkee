# Proximal Support Vector Machine

## Overview

This project introduces Proximal Support Vector Machine (PSVM), a novel approach for classifying points based on their proximity to parallel hyperplanes, unlike the conventional Support Vector Machine (SVM), which divides points into two distinct half-spaces.

### Objectives

- **Objective Function Formulation:** 
  Formulated the objective function of PSVM, enabling the classification of points based on their proximity to one of two parallel hyperplanes.

- **Optimized Runtime using Sherman Morrison Formula:**
  Implemented the PSVM Algorithm in Python and optimized runtime using the Sherman Morrison Formula. This optimization significantly reduced matrix complexity from (mxn) to (nxn), where (m = training points, n = features).

- **Achieved Rapid Computation:**
  Demonstrated the ability to achieve rapid computation even with large datasets. PSVM efficiently handles the inversion of a matrix of the order of the input space dimension, typically around 100 or less, even with 1,000,000 data points for classification.

### Performance Comparison

Comparison of PSVM and SVM Test Set Correctness:

- **Pulsar Star Dataset (5003x8) with RBF Kernel:** 
  - PSVM Accuracy: 98.05%
  - SVM Accuracy: 97.29%

- **Credit Card Dataset (284807x31) with Linear Kernel:** 
  - PSVM Accuracy: 94.57%
  - SVM Accuracy: 96.12%

### Technology Used

Tech: PYTHON, ML.

### PowerPoint Presentation

Link to the PowerPoint presentation of the project: [Link to PowerPoint Presentation](https://github.com/anuragpor/Semester-Project-2022-IIT-Roorkee/blob/main/19312004_Anurag_Porwal_MAN-300.pptx)
