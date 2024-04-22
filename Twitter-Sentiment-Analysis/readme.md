# Twitter Sentiment Analysis 🐦💬

## 📚 Project Overview 

The project utilizes Natural Language Processing (NLP) techniques to extract insights from tweets. It involves data collection, preprocessing, feature engineering, model training and evaluation, and visualization.

**Key steps involved:**

* **Data Collection:** `snscrape` is used to gather tweets based on relevant hashtags.
* **Preprocessing:** Text data is cleaned and prepared by removing irrelevant characters, stop words, and applying stemming.
* **Data Balancing:** SMOTE is employed to address class imbalance and ensure equal representation of sentiment categories.
* **Feature Engineering:** Text data is transformed into numerical features using TF-IDF vectorizer.
* **Model Training and Evaluation:** Various machine learning algorithms are implemented and compared, including Naive Bayes, Decision Tree, Logistic Regression, KNN, and SVM. Cross-validation is used for evaluation and hyperparameter tuning is performed for optimization.
* **Visualization:** Visualizations are created to understand word frequency and class distribution.

## 🛠️ Technologies Used 

* **Python**
* **Libraries:** `snscrape`, `pandas`, `numpy`, `nltk`, `sklearn`, `imblearn`, `matplotlib`, `seaborn`

## 🚀 How to Run 

1. Clone the repository: `git clone https://github.com/anhxd/twitter-sentiment-analysis.git`
2. Navigate to the project directory: `cd twitter-sentiment-analysis`
3. Open and run the Jupyter Notebook: `jupyter notebook sentiment_analysis.ipynb`

## 🎉 Results and Conclusion 

The project successfully demonstrates the ability to classify Twitter sentiment with good accuracy. The SVM model achieved the highest performance, highlighting its effectiveness in handling text data and sentiment analysis tasks.

## 🤝 Contributing 

Feel free to fork the repository, contribute to the codebase, or suggest improvements. 
