# CNN Exploration

This project explores **Convolutional Neural Networks (CNNs)** for tabular data classification, using the mushroom dataset from the [Kaggle Playground Series S4E8](https://www.kaggle.com/competitions/playground-series-s4e8/overview).  
It also integrates **automated EDA** through `ydata-profiling` to accelerate insights and preprocessing decisions.

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Performed EDA:
  - Checked data types, null percentages, and unique counts.
  - Visualized distributions of numerical features using seaborn.
  - Studied categorical correlations with **dython associations**.

### 2. Data Preprocessing
- Dropped features with excessive missing values.
- Imputed missing values with `SimpleImputer`.
- Encoded categorical variables using `OrdinalEncoder`.
- Train-test split for supervised learning setup.

### 3. Model Development
- Implemented a **Convolutional Neural Network (CNN)** to experiment with deep learning on structured tabular data.
- Reshaped categorical features into a format suitable for CNN input.
- Tuned layers, activations, and dropout for model training.

### 4. Evaluation
- Evaluated the CNN using standard classification metrics.
- Compared results with baseline models to understand CNN effectiveness.

---

## Key Learnings
- First hands-on exploration of **CNNs for tabular data**.
- Leveraging **EDA automation** with ydata profiling can speed up preprocessing.
- Handling categorical-heavy datasets requires careful encoding and feature preparation.

---

