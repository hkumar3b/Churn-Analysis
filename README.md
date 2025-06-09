# 🏦 Predicting Customer Churn with Machine Learning and Power BI

## 📊 Overview
This project focuses on understanding and predicting customer churn for a bank using machine learning techniques, complemented by a Power BI dashboard for interactive data visualization.  
Customer churn, or attrition, significantly impacts profitability. This analysis aims to identify key factors contributing to churn and build predictive models to aid customer retention strategies.

---

## ❓ Problem Statement
Customer churn is a critical issue for businesses, especially in subscription-based industries like banking.  
Acquiring new customers is often more expensive than retaining existing ones. Therefore, analyzing and predicting churn is essential for:

- Identifying service-related problems
- Making informed strategic decisions
- Improving customer satisfaction and retention

---

## 🎯 Project Objective
The primary goal of this project is to:

- Perform an extensive **Exploratory Data Analysis (EDA)** to visualize and understand the underlying factors that drive customer churn.
- Develop various **machine learning models** to predict whether a customer is likely to churn.
- Optimize the models using **recall** as the key performance metric, prioritizing the correct identification of churn-prone customers.
  
---

## 🔍 Methodology
The project follows a structured approach encompassing the following steps:

- **Exploratory Data Analysis (EDA)**: Analyze and visualize factors contributing to customer churn.
- **Data Preprocessing**:
  - Feature Selection  
  - Encoding Categorical Features  
  - Feature Scaling  
  - Addressing class imbalance using **SMOTE**
- **Machine Learning Model Building**: Develop classification models.
- **Model Tuning**: Optimize model parameters for better performance.
- **Model Evaluation**: Evaluate using appropriate metrics, focusing on **recall**.

---

## 🛠️ Technologies and Libraries

- **Programming Language**: Python  
- **Data Manipulation**: Pandas  
- **Numerical Operations**: NumPy  
- **Data Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn (Logistic Regression, SVM, Random Forest, Gradient Boosting), XGBoost, LightGBM  
- **Handling Class Imbalance**: Imblearn (SMOTE)  
- **Business Intelligence**: Power BI (for dashboard creation)

---

## 📈 Key Findings and Results

- **Feature Importance**:  
  - `Age` is the most significant feature, with older customers more likely to churn.  
  - Customers with a higher number of products also had a higher likelihood of churning.

- **Model Performance**:  
  - The machine learning models achieved a **recall of approximately 78%**, successfully detecting nearly 80% of likely churn cases.

- **Business Impact**:  
  - These insights can help banks tailor their services to retain high-risk customers and improve overall satisfaction.

---

## 📊 Power BI Dashboard
An interactive **Power BI dashboard** has been developed for:

- Visual exploration of customer churn data
- Displaying insights from the ML models
- Easy accessibility for business stakeholders

---

## 🚀 Future Development

- Explore additional features or acquire more diverse data sources to enhance model accuracy.  
- Investigate more advanced machine learning or ensemble techniques to improve recall and overall performance.

---

