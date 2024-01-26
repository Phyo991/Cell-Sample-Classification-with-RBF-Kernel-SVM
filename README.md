# Cell-Sample-Classification-with-RBF-Kernel-SVM

## Overview

This project is part of the Machine Learning with Pythonoffered by IBM. It focuses on the classification of human cell samples as benign or malignant using the Radial Basis Function (RBF) Kernel Support Vector Machine (SVM) algorithm. The dataset used in this project is publicly available from the UCI Machine Learning Repository and contains several hundred human cell sample records. Each record contains values representing various cell characteristics.

## Dataset

- The dataset is publicly available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)).
- It includes the following fields:
  - ID: Unique identifier
  - Clump: Clump thickness
  - UnifSize: Uniformity of cell size
  - UnifShape: Uniformity of cell shape
  - MargAdh: Marginal adhesion
  - SingEpiSize: Single epithelial cell size
  - BareNuc: Bare nuclei
  - BlandChrom: Bland chromatin
  - NormNucl: Normal nucleoli
  - Mit: Mitoses
  - Class: Benign (2) or malignant (4)

## Methodology

- Radial Basis Function (RBF) Kernel SVM is used for modeling, a powerful algorithm for high-dimensional data.
- The dataset is preprocessed to handle missing values and normalize the features.
- The model is trained and tested on the dataset for cell sample classification.

## Evaluation Metrics

The model's performance is evaluated using the following metrics:

1. **Confusion Matrix**: Provides insights into the number of true positives, true negatives, false positives, and false negatives.

2. **F1 Score**: A measure of the model's accuracy that considers both precision and recall. It's especially useful when dealing with imbalanced datasets.

3. **Jaccard Score**: Measures the similarity between the predicted and actual labels. It is a measure of the intersection over union (IoU) between sets.

## How to Use (as instructed in the Coursera Course)

1. Clone or download this repository to your local machine.

2. Follow the code provided in the Coursera course materials to replicate the RBF Kernel SVM classification and evaluation on your own dataset or the provided dataset.

3. Ensure you meet any additional requirements or instructions provided by the course instructors regarding the usage and submission of the project.

## Dependencies

- Python 3.x
- Libraries used are specified in the course materials, including scikit-learn for SVM implementation.

## License

This project is subject to the terms and conditions of the Coursera course. Please refer to the course materials for licensing information.

## Contact

For any course-related questions or support, please refer to the course discussion forums on Coursera.
