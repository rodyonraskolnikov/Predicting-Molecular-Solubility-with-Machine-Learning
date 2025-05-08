# **Predicting Molecular Solubility with Machine Learning**

This project demonstrates how to build and evaluate machine learning regression models using molecular descriptor data to predict aqueous solubility (`logS`) of chemical compounds.

## 🔍 Objective

The goal of this project is to develop and compare machine learning models to predict the aqueous solubility (logS) of chemical compounds based on their molecular descriptors. Using a publicly available dataset from [Delaney Solubility Dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)
, I explored how chemical structure information can be used to model solubility behavior—a key property in drug design and materials science.

By applying both Linear Regression and Random Forest Regression, I assessed the performance of each model and interpreted their ability to generalize to unseen molecular data. This project showcases end-to-end ML workflows including:

- Data loading and cleaning

- Feature/target separation

- Model training and prediction

- Evaluation using MSE and R² Score

- Model comparison for insight into performance tradeoffs

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

