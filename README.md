# Salary Prediction Project using Machine Learning

This repository contains a comprehensive salary prediction project built using Python and Scikit-Learn. The goal of this project is to analyze and predict employee salaries based on various professional and demographic features by evaluating multiple machine learning approaches.

---

## 🎯 Model Evaluation & Experimentation

The project evaluates the dataset under **3 different conditions/models** to compare how feature selection and algorithm choice impact overall accuracy ($R^2$ Score):

### 📊 Section 1: Data Preprocessing & Baseline Model (All Features)
* **Algorithm:** Multiple Linear Regression
* **Description:** Trained using the complete encoded dataset, utilizing all available features (e.g., experience, skills count, location, company size).
* **Performance ($R^2$ Score):** **0.963 (96.3% Accuracy)** ⭐ *Best Performing Model*

### 🔬 Section 2: Experimentation - Manual Feature Selection
* **Algorithm:** Multiple Linear Regression
* **Description:** Features were manually trimmed to analyze the impact of specific variables. Key columns like `skills_count` were excluded.
* **Performance ($R^2$ Score):** **0.777 (77.7% Accuracy)**

### 🌳 Section 3: Alternative Model - Decision Tree Regressor
* **Algorithm:** Decision Tree Regressor (`max_depth=5`)
* **Description:** A non-linear tree-based approach implemented to observe how hierarchical rules fit the salary pattern.
* **Performance ($R^2$ Score):** **0.532 (53.2% Accuracy)**

---

## 📈 Visualizations
The project includes **Actual vs. Predicted Salary Scatter Plots** for the models. The baseline Multiple Linear Regression model demonstrates an exceptionally close alignment with the perfect prediction line, proving its strong predictive capability compared to the Decision Tree approach.

---

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Environment:** Jupyter Notebook / JupyterLab
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/Repository-Name.git](https://github.com/your-username/Repository-Name.git)
