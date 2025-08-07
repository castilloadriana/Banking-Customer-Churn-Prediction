# 🏦 Bank Customer Churn Prediction

This project uses machine learning to predict **customer churn** in the banking sector based on a Kaggle dataset of **10,000 users** from **Germany, France, and Spain**. It includes features like **Credit Score, Age, Tenure, Balance, Number of Products, Estimated Salary**, and more. The target variable is **`Exited`** (1 = churned, 0 = stayed), helping banks identify which customers are likely to leave.


---

## 📌 Project Overview

We explored three models (Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest) to determine the most effective at predicting churn. After evaluation, Random Forest emerged as the most accurate model with a test accuracy of 0.88, demonstrating a strong ability to detect patterns of customer departure. Key findings showed that age was the most influential feature, with older customers more likely to churn. Other important factors included balance, estimated salary, and credit score, while geography had minimal impact. Unexpectedly, customers using four products were more prone to churn, suggesting that higher product engagement does not always equate to loyalty. Gender had little effect on predictions, indicating demographic and product usage factors were stronger churn indicators than location or basic financial metrics.

### 🔍 Key Highlights

- Feature preprocessing included **encoding categorical variables** and **scaling** (where needed).
- Conducted **feature importance analysis** to better understand model decision-making.
- Created a smaller, custom dataset to probe model behavior manually.

---

## 🧠 Tech Stack

- **Python 3**
- **Pandas**, **NumPy**
- **scikit-learn** for machine learning

---

## 📂 Repository Structure
-  **churn_model.py:** Main ML pipeline (training, evaluation)
-  **churn_analysis_essay.pdf:** Project summary and reflections
-  **README.md** : You are here
