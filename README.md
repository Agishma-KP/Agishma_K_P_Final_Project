# 🛒 Customer Behavior Prediction in E-Commerce

This project analyzes e-commerce customer sessions to predict whether a user will make a purchase. Using classification models and real-world behavioral data, it identifies key patterns that influence purchasing intent.

---

## 📌 Project Highlights

- **Goal**: Predict purchasing intent of online shoppers.
- **Dataset**: Real-world e-commerce session data (user behavior, session details, technical context).
- **Target**: `Revenue` (binary: purchase or not).

---

## 📊 Workflow Summary

1. **Data Cleaning & Preprocessing**  
   ➤ Handled missing values, encoded categorical features, scaled numerical data.

2. **Exploratory Data Analysis (EDA)**  
   ➤ Analyzed session duration, bounce rates, user types, and seasonality.  
   ➤ Visuals used: heatmaps, bar plots, distribution charts.

3. **Feature Engineering**  
   ➤ Feature selection via `mutual_info_classif` and `SelectKBest`.  
   ➤ Power transformation to normalize skewed data.

4. **Model Building**  
   ➤ Models used: Logistic Regression, Random Forest, Gradient Boosting, SVC, KNN, Naive Bayes.  
   ➤ Handled class imbalance using **SMOTE**.

5. **Evaluation**  
   ➤ Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.  
   ➤ Used Confusion Matrices and ROC Curves for visual evaluation.

6. **Hyperparameter Tuning**  
   ➤ Applied `RandomizedSearchCV` to optimize best models.

7. **Pipeline Construction & Testing**  
   ➤ Built a complete ML pipeline and validated it on unseen data.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Imbalanced-learn (for SMOTE)

---

## ▶️ How to Run

1. Clone or download the repo.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Agishma_K_P_Project.ipynb
   ```

## 👤 Author

**Agishma K P**

This project showcases practical ML workflow skills from raw data to production-ready model pipelines.
