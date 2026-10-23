# Decision Making & Machine Learning Algorithms

This repository contains academic projects exploring different machine learning algorithms and probabilistic approaches to decision-making using Python.

The implementations focus on understanding the underlying mathematical concepts and applying them to classification and clustering problems.

## Projects

### 1. Bayesian Belief Network – Mushroom Classification

An exploration of Bayesian reasoning and probabilistic classification using the Mushroom dataset.

**Key Concepts:**

* Bayesian Probability
* Prior Probability
* Conditional Probability
* Posterior Probability
* Probabilistic Classification
* Probability Distribution Visualization

The implementation uses observed mushroom characteristics to estimate the probability of edibility.

### 2. Decision Tree – Diabetes Classification

A Decision Tree implementation built around entropy and information gain.

**Key Concepts:**

* Entropy
* Information Gain
* Recursive Tree Construction
* Feature Selection
* Classification and Prediction

The model uses the Diabetes dataset to explore how decision trees split data based on feature values and make classification decisions.

### 3. K-Means Clustering – Customer Segmentation

An implementation of K-Means clustering using the Mall Customers dataset.

**Key Concepts:**

* Unsupervised Learning
* Centroid Initialization
* Euclidean Distance
* Cluster Assignment
* Centroid Recalculation
* Iterative Clustering

The project groups customers based on Annual Income and Spending Score to explore customer segmentation.

### 4. Naive Bayes – Iris Classification

A Gaussian Naive Bayes implementation developed using Python, Pandas, and NumPy.

**Key Concepts:**

* Bayes' Theorem
* Prior Probability
* Mean and Variance
* Gaussian Probability Density
* Posterior Probability
* Log Probability
* Classification

The model uses the Iris dataset to classify flowers into three species:

* Setosa
* Versicolor
* Virginica

The implementation includes custom training, prediction, and train-test splitting functions.

### 5. Support Vector Machine (SVM)

An exploration of Support Vector Machines with a focus on optimization and classification.

**Key Concepts:**

* Hyperplane
* Maximum Margin
* Support Vectors
* Hinge Loss
* Regularization
* Stochastic Gradient Descent
* Feature Selection
* Feature Scaling

The implementation explores SVM optimization using NumPy and includes preprocessing techniques such as correlation-based feature removal and Min-Max normalization.

## Technologies & Libraries

* **Python** – Main programming language
* **NumPy** – Numerical computations and mathematical operations
* **Pandas** – Data loading, manipulation, and analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Scikit-learn** – Data preprocessing, scaling, and evaluation
* **Statsmodels** – Statistical modeling and feature analysis

## Datasets

The projects use the following datasets:

| Dataset        | Application                           |
| -------------- | ------------------------------------- |
| Mushrooms      | Bayesian probabilistic classification |
| Diabetes       | Decision Tree classification          |
| Mall Customers | Customer segmentation with K-Means    |
| Iris           | Gaussian Naive Bayes classification   |
| Breast Cancer  | Support Vector Machine classification |

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/elsen111/decision-making.git
cd decision-making
```

### 2. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the individual notebooks inside their respective directories and execute the cells to explore the implementations.

## Repository Structure

```text
decision-making/
│
├── Bayesian belief network/
│   └── Bayesian Belief Network (mushrooms).ipynb
│
├── Decision tree/
│   └── Decision tree (Diabetes).ipynb
│
├── K-Means/
│   └── K-Means (Mall_Customers.csv).ipynb
│
├── Naive Bayes/
│   └── Naive Bayes (Iris).ipynb
│
├── SVM/
│   └── SVM.ipynb
│
└── README.md
```

## Learning Objectives

* Understand supervised and unsupervised learning approaches.
* Explore probabilistic reasoning and Bayesian classification.
* Implement fundamental machine learning algorithms.
* Understand entropy and information gain in decision trees.
* Apply clustering techniques to customer segmentation.
* Explore optimization techniques used in Support Vector Machines.
* Practice data manipulation and numerical computation using Pandas and NumPy.

## Project Context

Academic projects developed to study machine learning algorithms, probabilistic models, optimization techniques, and data-driven decision-making through practical Python implementations.
