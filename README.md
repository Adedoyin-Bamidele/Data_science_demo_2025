# Data_science_demo_2025
A portfolio project.

# Diabetes Prediction with PyTorch + Optuna

This project builds a neural-network classifier to predict the likelihood of diabetes using a public Kaggle dataset.  
It uses **Optuna** for hyperparameter optimization and **PyTorch** for model development.

---

## 📌 Project Overview

The goal is to:
1. Load and preprocess the Diabetes Prediction Dataset.
2. Build a configurable PyTorch neural network.
3. Use **Optuna** to search for the best hyperparameters.
4. Retrain the final model with optimal parameters.
5. Evaluate the model on a test set.
6. Save the trained model for future inference.

---

## 📂 Dataset

Dataset used: **Diabetes Prediction Dataset**  
Source: Kaggle — `iammustafatz/diabetes-prediction-dataset`

Downloaded using:

```python
import kagglehub
path = kagglehub.dataset_download("iammustafatz/diabetes-prediction-dataset")

