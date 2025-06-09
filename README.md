Predicting Customer Churn with Machine Learning and Power BI
Overview
This project focuses on understanding and predicting customer churn for a bank using machine learning techniques, complemented by a Power BI dashboard for interactive data visualization. Customer churn, or attrition, significantly impacts profitability, and this analysis aims to identify key factors contributing to it and build predictive models to aid customer retention strategies.

Problem Statement
Customer churn is a critical issue for businesses, especially in subscription-based industries like banking. Acquiring new customers is often more expensive than retaining existing ones. Therefore, analyzing and predicting churn is essential for identifying service problems and making informed strategic decisions to improve customer satisfaction and retention.

Project Objective
The primary goal of this project is to perform an extensive Exploratory Data Analysis (EDA) to visualize and understand the underlying factors that drive customer churn. Subsequently, various machine learning models are developed to predict whether a customer is likely to churn. The models are optimized using recall as the key performance metric, prioritizing the correct identification of customers who will churn, which is crucial for the bank.

Data Source
The dataset used for this project is sourced from Kaggle: predicting-churn-for-bank-customers.

Methodology
The project follows a structured approach encompassing:

Exploratory Data Analysis (EDA): Initial analysis and visualization of factors contributing to customer churn.
Data Preprocessing: This includes Feature Selection, Encoding Categorical Features, Feature Scaling, and addressing class imbalance using SMOTE.
Machine Learning Model Building: Development of various classification models.
Model Tuning: Optimization of model parameters for improved performance.
Model Evaluation: Assessment of model performance using appropriate metrics like recall.
Technologies and Libraries
Programming Language: Python
Data Manipulation: Pandas
Numerical Operations: NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn (for models like Logistic Regression, Support Vector Machines, Random Forests, Gradient Boosting), XGBoost, LightGBM.
Handling Class Imbalance: Imblearn (SMOTE)
Business Intelligence: Power BI (for dashboard creation)
Key Findings and Results
Feature Importance: Age was identified as the most significant feature in predicting churn, with older customers being more likely to churn. The number of products a customer has also showed a strong correlation, where more products increased the likelihood of churn.
Model Performance: The machine learning models built achieved a recall of approximately 78%, indicating their ability to successfully detect nearly 80% of customers likely to churn.
Business Impact: These findings can help the bank adapt and improve its services to increase satisfaction and retention among high-risk customers.
Power BI Dashboard
A Power BI dashboard has been developed to provide interactive visualizations of the customer churn analysis. This dashboard allows for easy exploration of the data and insights gained from the machine learning models, making it accessible for business stakeholders.

Future Development
Exploring additional features or acquiring more data could further enhance the predictive performance of the models.
Investigating other advanced machine learning techniques or ensemble methods to improve accuracy and recall.
How to Run
Clone this repository to your local machine.
Navigate to the Predicting_Customer_Churn_with_Machine_Learning.ipynb notebook.
Ensure all required Python libraries (listed above) are installed. You can install them using pip install -r requirements.txt (assuming you create a requirements.txt file from the notebook's imports).
Run the Jupyter Notebook cells sequentially to reproduce the analysis and model building.
Access the Power BI dashboard file (if included in the repository) to view the interactive visualizations.
Conclusion
This project demonstrates a robust approach to predicting customer churn, providing actionable insights for banks to enhance customer retention through data-driven strategies and predictive modeling.
