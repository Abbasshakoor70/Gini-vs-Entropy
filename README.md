# Gini-vs-Entropy

# Decision Tree Classifier Comparison

This project compares the performance of Decision Tree Classifiers using two criteria:
- **Gini Impurity**
- **Entropy**

The classifiers are applied to the **Breast Cancer Dataset** from `scikit-learn` to evaluate their accuracy and tree depth.

## Project Overview

- Load and preprocess the dataset.
- Train Decision Tree classifiers with Gini and Entropy criteria.
- Evaluate the models on test data.
- Visualize the decision trees and compare performance.

## Dataset

The dataset used is the `Breast Cancer Wisconsin Diagnostic` dataset, loaded using:
```python
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()
```

## Installation

To run this project, install the required packages using:
```bash
pip install -r requirements.txt
```
### Required Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. **Run the Notebook:**  
   Open the Jupyter Notebook `ml_9_code.ipynb` and execute all cells to reproduce the results.

2. **Visualize Results:**  
   - Decision tree plots for Gini and Entropy criteria.
   - Bar plot comparing model accuracy.

## Model Evaluation

The models are evaluated using:
- **Accuracy Score:** Measures prediction accuracy.
- **Tree Depth:** Compares complexity of decision trees.

## Visualization

- Decision trees plotted for the first 3 levels.
- Accuracy comparison displayed with a bar plot.

## Results

The results highlight the differences in model performance using Gini and Entropy criteria.

## License

This project is licensed under the MIT License.
