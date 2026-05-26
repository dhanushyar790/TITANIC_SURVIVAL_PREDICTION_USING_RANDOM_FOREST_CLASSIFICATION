# 🚢 Titanic Survival Prediction

## 📖 Overview
This project predicts passenger survival on the Titanic dataset using a Random Forest Classifier.  
It demonstrates end-to-end machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and visualization.

---

# ⚙️ Workflow

## 1️⃣ Data Cleaning & Imputation
- Handled missing values using `SimpleImputer`
- Used:
  - `mean` strategy for numerical columns
  - `most_frequent` strategy for categorical columns

---

## 2️⃣ Feature Engineering
- Applied Label Encoding for categorical features
- Used Standard Scaling for numerical columns
- Performed outlier treatment using Winsorization

---

## 3️⃣ Model Training
Trained a `RandomForestClassifier` with tuned hyperparameters:

- `criterion = "entropy"`
- Optimized:
  - `n_estimators`
  - `max_depth`
  - `min_samples_split`
  - `min_samples_leaf`

---

## 4️⃣ Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

Generated visualizations:
- Correlation Heatmap
- Boxplots
- Random Forest Decision Tree Visualization

---

# 🛠️ Tech Stack

## Python Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Machine Learning
- Scikit-learn
  - Random Forest Classifier
  - Preprocessing
  - Metrics

## Statistics
- SciPy (Winsorization)

---

# 📊 Results
- Achieved strong classification accuracy
- Identified important survival-related features
- Built clear visualizations for better model interpretation

---

# 📈 Visualizations Included
- Boxplots
- Correlation Heatmap
- Confusion Matrix
- Random Forest Tree Plot

---

# 🚀 Conclusion
This project demonstrates how Random Forest can effectively solve classification problems through proper preprocessing, feature engineering, and hyperparameter tuning.
