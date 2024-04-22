# Artificial Neural Networks for Fraud Detection in Supply Chain Analytics: A Study on MLPClassifier and Keras

## Introduction 
In recent years, the use of neural networks in supply chain analytics has gained considerable traction as organisations look for ways to improve their operations and make more informed decisions. One area where neural networks can have a significant impact is in the detection of fraud before shipments are processed. Fraudulent activities can cause significant financial losses, and early detection is essential for minimising any damage.
We present our study on the use of neural networks for detecting fraud in the supply chain. Two models were developed as part of this study: one using the MLPClassifier algorithm from the scikit-learn library, and another using a custom neural network built using the Keras library in Python. These models were developed using open-source libraries, including NumPy for numerical computation, Pandas for data manipulation, Seaborn for statistical data visualisation, matplotlib for plotting, and the machine learning frameworks SciKit Learn, Keras, and Tensorflow (backend). The scikit-learn library is a widely used machine learning library in Python, and the MLPClassifier algorithm from this library is a type of multi-layer perceptron classifier that has been shown to perform well on various classification tasks. The custom neural network, on the other hand, was designed to provide a deeper level of control over the architecture and training process, allowing for a more customised solution. The objective of our study is to identify potential fraudulent activities in the supply chain before shipments are processed, thus reducing the risk of financial loss for the organisation.
RConfusion Matrix (Accuracy 0.9787)
<h2>🚀Dataset link </h2>

[https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)



<h2>Key steps involved</h2>

* **Data Exploration:** Analyzing the dataset to understand its structure, identify missing values, and explore relationships between variables.
* **Data Cleaning & Preprocessing:** Handling missing values, encoding categorical variables, and creating new features for better model performance.
* **Data Visualization:** Utilizing visualizations like heatmaps and bar charts to gain insights into the data and identify potential areas of concern. 
* **Model Building:** Implementing and comparing different machine learning models, including MLPClassifier and a custom neural network, to predict fraudulent orders. 
* **Model Evaluation:** Assessing the performance of the models using metrics such as accuracy, F1 score, and confusion matrix.
* **Model Validation:** Validating the models on a separate validation set to ensure generalizability and avoid overfitting. 



## Tools Used:
- Python
- SciKit Learn
- Seaborn
- Pandas
- TensorFlow
- Keras
- Matplotlib
- Plotly
  

##  Key Findings

* Certain product categories and markets exhibit a higher tendency for losses, warranting further investigation.
* Transfer payments appear to be associated with a higher risk of suspected fraud compared to other payment types.
* Both MLPClassifier and the custom neural network achieved high accuracy (around 98%) in predicting fraudulent orders, demonstrating the effectiveness of machine learning for fraud detection in supply chain analytics. 



## Confusion Matrix
 
| Actual/Prediction  | 0 | 1 |        
| ------------- | ------------- |------------- |
|0  | 17532     |130  |
| 1  | 254       |  136  |
