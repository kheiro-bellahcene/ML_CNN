# TP1 - Linear & Polynomial Regression

This notebook explores basic concepts of regression in Machine Learning, particularly Linear Regression and Polynomial Regression. The project involves data generation, model fitting, and visualization using Python libraries such as NumPy and Matplotlib.

> ⚠️ This is just a **practice lab** for experimenting with GitHub. More advanced and polished projects (CNN, LLM, etc.) are coming soon!

## 📌 Objectives

- Understand and implement **Linear Regression** using the normal equation.
- Extend to **Polynomial Regression** (degree 2).
- Analyze the models' behavior in the presence of **outliers**.
- Visualize results and compare performances.

## 🧪 Dataset

- **Synthetic** data generated using NumPy.
- 2000 data points for training.
- 20 outlier points are added for robustness analysis.

## 🛠️ Methods

### 1. Linear Regression

- Features are augmented with a bias term.
- Parameters are estimated using the closed-form solution:

  ![theta formula](https://latex.codecogs.com/png.image?\dpi{120}&space;\theta%20=%20(X^T%20X)^{-1}%20X^T%20y)

### 2. Polynomial Regression (Degree 2)

- The feature space is expanded with quadratic terms.
- The same closed-form solution is used.

### 3. Robustness Test

- 20 random outliers are added far from the original data.
- Models are retrained to observe their sensitivity.

## 📈 Visualization

- Scatter plots of data and outliers.
- Regression lines for both models.
- Comparison of model fitting with and without outliers.

## 🧰 Tools Used

- Python 3.x
- NumPy
- Matplotlib

## 📂 File Structure

```
📁 ML_Practice_Labs/
│
├── TP1_ML_BELLAHCENE_Kheir_Eddine_SAM.ipynb     # Linear & Polynomial Regression
├── README.md
│
├── cnn/                                         # (To be added) Convolutional Neural Networks
│   └── tp_cnn_image_classification.ipynb
│
├── llm/                                         # (To be added) Large Language Models
│   └── llm_prompt_engineering.ipynb
```

## 👤 Author

**Kheir Eddine Bellahcene**

---

## 🚀 Note

This repo is just a warm-up. Stay tuned — better and cooler projects are on the way!


