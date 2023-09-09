# Fake-News-Detection-Using-Machine-Learning-Techniques
This project aims to detect fake news articles using various machine learning algorithms, including Logistic Regression, Decision Tree, Gradient Boosting Classifier (GBC), and Random Forest Classifier (RFC). Fake news detection is a critical task in today's information age, as it helps in identifying and mitigating the spread of false information.

## Dataset
The dataset used in this project consists of labeled news articles, where each article is labeled as either "fake" or "real." The dataset is available in the data/ directory and is split into a training set and a testing set.

## Data Preprocessing
Data preprocessing is a crucial step in preparing the dataset for model training. It includes tasks such as text cleaning, tokenization, vectorization, and feature extraction. 

## Machine Learning Models
We employ the following machine learning algorithms for fake news detection:

**Logistic Regression**: A linear classifier that models the probability of an article being fake or real.

**Decision Tree:** A tree-based model that splits the dataset based on feature values to make predictions.

**Gradient Boosting Classifier (GBC):** An ensemble model that combines multiple weak learners (decision trees) to improve predictive performance.

**Random Forest Classifier (RFC): ** Another ensemble model that uses multiple decision trees to enhance accuracy and reduce overfitting.

## Evaluation Metrics
We evaluate the performance of each model using various metrics, including accuracy, precision, recall, F1-score, and confusion matrices. These metrics help us assess the model's ability to correctly classify fake and real news articles.
