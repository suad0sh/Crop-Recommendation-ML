# Crop Recommendation System using Machine Learning 🌾

This repository contains an end-to-end Machine Learning pipeline for crop recommendation based on soil and weather parameters.

## 📌 Features & Preprocessing
* **Missing Value Handling:** Imputed using Feature Median.
* **Outlier Removal:** Applied Interquartile Range (IQR) clipping.
* **Categorical Encoding:** Label Encoding applied to target crop labels.
* **Feature Scaling:** Standardized features using `StandardScaler`.

## 📊 Model Performance
| Model | Accuracy |
| :--- | :--- |
| **K-Nearest Neighbors (KNN)** | **100.00%** |
| **Random Forest** | **99.77%** |
| **Decision Tree** | **96.59%** |

## 📁 Repository Structure
* `Crop_recommendation_cleaned.csv` - Processed & cleaned dataset.
* `Notebook.ipynb` - Complete Jupyter/Colab notebook code.
* Visualizations for Feature Importances and Model Accuracies.# Crop-Recommendation-ML
