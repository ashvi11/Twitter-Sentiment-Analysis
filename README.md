# Twitter-Sentiment-Analysis

Dataset Link: https://www.kaggle.com/kazanova/sentiment140

This dataset consists of over 1 million tweets. First, we performed various data analysis and data visualizations to gain useful insights like distribution of positive vs negative tweets, distribution of length of the tweets(number of characters), etc. Then we trained Machine Learning Models such as Logistic Regression and Naive Bayes on this Dataset to predict sentiment score.

We then used these already trained models to predict sentiment score of the tweets of a table in MYSQL Database(this is a different table from the above dataset). We populated the database table with the predicted sentiment score. 

We then performed data analysis on this table and ran queries to gain useful insights.

Tools, Technologies and Libraries: Python, Jupyter Notebook, MYSQL, MYSQL Workbench, pandas, scikit-learn, nltk, seaborn, matplotlib, pymysql
