# Machine Learning Coursework: Classification, Clustering, and Sentiment Analysis
## What it does
This project covers three core machine learning tasks in one pipeline. It builds classification models to predict categories, clustering models to group similar data points, and a sentiment analysis model to judge the tone of text.

## Why I built it
This was a coursework assignment for my MSc in Artificial Intelligence at the University of Salford.

## Tools used
Python, Scikit-Learn, GridSearchCV, PCA, Naive Bayes.

## How to run it
1. Clone this repository and install the dependencies.

2. Place your dataset in the input folder.

3. Run the classification script to train Logistic Regression and Random Forest models with GridSearchCV tuning.

4. Run the clustering script to apply K-Means and Agglomerative Clustering, then view the PCA visualisation.

5. Run the sentiment analysis script to test the Naive Bayes sentiment model.

## Results
The Logistic Regression and Random Forest classifiers reached 90 percent accuracy after GridSearchCV tuning. The K-Means and Agglomerative Clustering models achieved a silhouette score of 0.35, visualised using PCA. The Naive Bayes model was used to classify sentiment across the text data.
