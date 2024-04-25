# Parameter-Optimazation

Completed By: Aryan Gupta
--
Roll No. 102103140
---

## Result Table

![Result Table](Result_Table.png)

## Result Graph

![Result Graph](Result_Graph.png)

## Overview

This report offers a comprehensive analysis of the [Dry Bean Dataset](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset) (UCI ML Repository ID: 602).

## Methodology

1. **Data Loading**: The Dry Bean Dataset is loaded using the UCI ML Repository API.
2. **Data Preprocessing**: The dataset is split into features (X) and target (y). A train-test split is performed for model evaluation.
3. **Model Selection**: A Nu-Support Vector Classifier (NuSVC) with Bayesian Optimization is employed to optimize hyperparameters.
4. **Model Evaluation**: The model's accuracy is evaluated using cross-validation and convergence plots.
5. **Result Analysis**: The best hyperparameters and accuracy obtained are analyzed.

## Dataset Description

The Dry Bean Dataset comprises various attributes of dry beans, including geometric, shape, and texture attributes, used for bean classification.

### Features

The dataset includes the following features:

- **Area**
- **Perimeter**
- **MajorAxisLength**
- **MinorAxisLength**
- **AspectRatio**
- **Eccentricity**
- **ConvexArea**
- **EquivDiameter**
- **Extent**
- **Solidity**
- **Roundness**
- **Compactness**
- **ShapeFactor1**
- **ShapeFactor2**
- **ShapeFactor3**
- **ShapeFactor4**

### Target

The target variable represents the class of the dry bean.


---
