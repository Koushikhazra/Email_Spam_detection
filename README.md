# Email Spam Detection with Machine Learning

This repository contains a Python project that implements an email spam detection system using machine learning techniques. The dataset used is `spam.csv`, which contains labeled email messages.

## Project Structure

- `Email_Spam_Detection_with_Machine_Learning.ipynb` - Jupyter notebook detailing the entire workflow: data preprocessing, exploration, visualization, model training, evaluation, and deployment.
- `spam.csv` - Raw dataset used for training and testing the spam classifier.

## Key Features

1. Data preprocessing and cleaning (dropping unnecessary columns, handling duplicates, etc.).
2. Exploratory data analysis with visualizations (pie charts, word clouds, etc.).
3. Text feature extraction using `CountVectorizer`.
4. Machine learning model implementation using Multinomial Naive Bayes in a scikit-learn pipeline.
5. Evaluation metrics such as accuracy, precision, recall, F1-score, ROC AUC, and confusion matrices.
6. A simple function (`detect_spam`) to classify new email text as spam or ham.

## Usage

1. Open the notebook and run the cells sequentially to reproduce the analysis.
2. Modify the `detect_spam` function to load a persisted version of the trained model if saving is added.
3. Train and test the model on the provided dataset or use your own labeled email data.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- wordcloud

 
