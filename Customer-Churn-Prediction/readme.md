# Telecom Customer Churn Prediction 🧮 

<h2>📚 Project Overview </h2>

This project dives into the world of customer churn for a California telecommunications company using data from Q2 2022. We're talking information on 7,043 customers, covering demographics, location, subscription services, tenure, and churn status. The goal? To crack the code of customer churn and build a predictive model to identify those at risk of leaving. 🔍

<h2>🚀 Dataset Link </h2>

[https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics](https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics)

<h2>📊 Data Exploration and Visualization </h2>

* We're exploring features like age, number of dependents, tenure, monthly charges, and total charges.
* Visualizations like histograms, boxplots, and heatmaps help us analyze the data and spot any outliers.
* We're also investigating the relationships between features and customer churn. 

<h2>🧹 Data Preprocessing </h2>

* Unnecessary columns get the boot, including customer ID, total refunds, zip code, latitude, longitude, churn category, and churn reason.
* Missing values? We handle them with interpolation and dropping rows with remaining missing data.
* Categorical features like gender, marital status, payment method, contract type, internet type, and offer are encoded using label encoding and one-hot encoding techniques.
* Numerical features get scaled using MinMaxScaler for a performance boost.

<h2>🤖 Model Building and Evaluation </h2>

* We're comparing several machine learning models, including:
    * Random Forest Classifier 🌳
    * Logistic Regression 📈
    * Gaussian Naive Bayes 🧮
    * Decision Tree Classifier 🌳
    * XGBoost Classifier 🚀
* GridSearchCV helps us optimize hyperparameters for each model.
* XGBoost Classifier takes the crown with an accuracy of 80.86% on the test set. 🏆
* The confusion matrix and classification report help us evaluate the model's performance and understand its strengths and weaknesses.

<h2>📓 Model Overview </h2>

| Machine Learning Models Applied            | Accuracy |
| ----------------- | ------------------------------------------------------------------ |
| Random Forest | 78.11% |
| Logistic Regression | 78.28% |
| Naive Bayes Gaussian | 36.77% |
| Decision Tree | 77.29% |
| XGB_Classifier | 80.86% | 

<h2>🎉 Conclusions </h2>

* XGBoost Classifier is the champion for predicting customer churn in this dataset!
* The model's accuracy shows its potential for identifying at-risk customers, allowing the company to take action and keep them around.
* Further analysis can explore feature importance and the impact of specific factors on churn. 

<h2> 💻 Instructions to Run the Code </h2>

1. Clone the repository. 
2. Install the necessary libraries: `numpy`, `pandas`, `plotly`, `matplotlib`, `seaborn`, `sklearn`, and `xgboost`.
3. Download the dataset `telecom_customer_churn.csv` and place it in the project directory.
4. Run the Jupyter Notebook or Python script containing the code.







