
## Customer Segmentation & Spending Prediction using Machine Learning
##  Project Overview
This project is based on Machine Learning techniques to analyze customer behavior.  
It includes both **Clustering** and **Regression** approaches.

- Clustering is used to group customers based on similar patterns.
- Regression is used to predict customer spending score.

---

##  Objectives
- Segment customers into different groups using K-Means clustering
- Predict customer spending score using regression
- Understand customer behavior for business decision-making

---

##  Dataset
Dataset used: Mall Customer Segmentation Data  
Source: Kaggle  

Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Data Preprocessing
- Checked for missing values
- Converted categorical data (Gender) into numeric
- Selected relevant features for modeling

---

##  Machine Learning Models

### 🔹 Clustering
- Algorithm: K-Means
- Used to group customers into segments
- Evaluation Metric: Silhouette Score

### 🔹 Regression
- Algorithm: Linear Regression
- Target Variable: Spending Score
- Evaluation Metrics:
  - R² Score
  - RMSE

---

##  Results

### Clustering:
- Customers divided into 5 segments
- Silhouette Score: (your output here)

### Regression:
- Model performance evaluated using R² score
- R² Score: (your output here)
- RMSE: (your output here)

---

##  Conclusion
- Customers were successfully segmented based on income and spending behavior
- Regression model predicted spending score with reasonable accuracy
- This analysis can help businesses in targeted marketing

---

##  Future Improvements
- Use advanced models like Random Forest or XGBoost
- Add more features for better prediction
- Deploy using Streamlit for visualization
