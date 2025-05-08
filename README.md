# **Predicting Molecular Solubility with Machine Learning**

This project demonstrates how to build and evaluate machine learning regression models using molecular descriptor data to predict aqueous solubility (`logS`) of chemical compounds.

## 🔍 Objective

To predict the solubility of molecules using their chemical structure features and compare the performance of two regression algorithms.

## 📁 Dataset

- Source: [Delaney solubility dataset](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv)
- Target variable: `logS` (log-scale solubility)
- Features: Molecular descriptors derived from chemical structure

## 🧪 Models Used

- **Linear Regression**
- **Random Forest Regression** (with `max_depth=2`)

## 📊 Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score (Training and Test)

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook

## 🧾 Results Summary

| Model              | Training MSE | Training R² | Test MSE | Test R² |
|-------------------|--------------|-------------|----------|---------|
| Linear Regression | *calculated* | *calculated*| *calc.*  | *calc.* |
| Random Forest     | *calculated* | *calculated*| *calc.*  | *calc.* |

> Replace *calculated* with actual results from the notebook when finalized.

## 🚀 How to Run

1. Clone this repository.
2. Open `Predicting-Molecular-Solubility.ipynb` in Jupyter Notebook or VSCode.
3. Run all cells to train and evaluate models.

## ✍️ Credits

This project was created as a beginner-friendly introduction to machine learning regression modeling. Huge thanks to [Data Professor](https://www.youtube.com/@DataProfessor) for his tutorial, enabling me to launch my first ever machine learning project!

