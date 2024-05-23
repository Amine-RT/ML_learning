# Toy Example for Supervised Learning: Mixed Linear and Non-linear Regression

This repository contains a Jupyter notebook that demonstrates an approach to building a regression model that handles both linear and non-linear relationships. This tutorial is part of a Machine Learning and Data Science course at Imperial College London.

## Introduction

Understanding the underlying patterns in data through supervised learning is essential in many fields. This tutorial walks through a toy example analyzing a model containing both linear and non-linear features, aimed at developing a robust predictive model for scenarios with both predictable trends and erratic fluctuations.

## Features

- **Hybrid Regression Model**: Combines linear regression with non-linear modeling to capture complex data interactions.
- **Sparsity and Regularization**: Implements techniques to manage model complexity and prevent overfitting.
- **Practical Examples**: Includes simulation of datasets and step-by-step model building.

## Getting Started

### Prerequisites

Ensure you have Python installed on your machine, along with the following packages:
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib scipy scikit-learn
```

### Installation

Clone this repository to your local machine to get started with the notebook:

```bash
git clone https://github.com/Amine-RT/ML_learning.git
cd ML_learning
cd Learning
```

### Running the Notebook

Open the Jupyter Notebook in your preferred environment, such as JupyterLab, Jupyter Notebook, or VS Code:

```bash
jupyter notebook
```

Navigate to the notebook file and open it to run the cells.

## Notebook Summary

- **Section 1**: Introduces the concept of hybrid regression and sets up the model structure.
- **Section 2**: Guides through setting up the environment and preparing the data.
- **Section 3**: Discusses the simulation of the datasets and the initial data preparation steps.
- **Section 4**: Explains the loss function tailored for handling both sparsity and complexity in the model.
- **Section 5**: Details the coding and implementation of the `CustomNonLinearEstimator`, including its application on simulated datasets.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or extensions to the notebook. For major changes, please open an issue first to discuss what you would like to change.
Feel free to fork this repository and submit pull requests with improvements or extensions to the notebook. For major changes, please open an issue first to discuss what you would like to change.


## Next steps
- Cross-validation for the choice of the hyperparameters
- use of Gaussian Process instead of the spline


## Acknowledgments

- Thanks to Prof. O. Deniz Akyildiz and Imperial College London for guidance and resources.

---