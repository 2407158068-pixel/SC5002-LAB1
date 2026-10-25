# SC5002 Artificial Intelligence Fundamentals & Applications

## Lab Assignment

This repository contains the completed Google Colab notebook for the SC5002 Lab Assignment.

## Part 2: Applied Machine Learning

The practical component uses the California Housing dataset to compare Linear Regression and Ridge Regression models.

### Tasks
- **Task 2.1:** Load and analyze the California Housing dataset and apply StandardScaler.
- **Task 2.2:** Train Linear Regression and Ridge Regression models with different alpha values (0.1, 10, and 1000) and evaluate them using 5-fold cross-validation.
- **Task 2.3:** Compare model performance using a bar chart and analyze the effect of regularization.

## Results

| Model | Alpha | Mean 5-Fold CV R² |
|---|---:|---:|
| Linear Regression | - | 0.6457 |
| Ridge Regression | 0.1 | 0.6457 |
| Ridge Regression | 10 | 0.6443 |
| Ridge Regression | 1000 | 0.3574 |

The results show that weak regularization produced performance similar to Linear Regression, while excessive regularization at alpha = 1000 significantly reduced the R² score.

## Files

- `SC5002_Lab_Assignment.ipynb` – Completed Google Colab notebook containing the dataset setup, model training, cross-validation, and visualization.
- `README.md` – Overview of the project and experimental results.

## Tools and Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
