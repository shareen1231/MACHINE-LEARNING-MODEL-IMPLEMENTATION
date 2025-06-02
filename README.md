# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: SHAREEN KUMAR J

INTERN ID : CT04DL684

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

#DESCRIPTION

This Python script implements sentiment analysis using machine learning models to classify user reviews as positive or negative. It leverages the pandas library for data manipulation, scikit-learn for machine learning models, and CountVectorizer for transforming text into numerical features. The dataset used is a tab-separated values (TSV) file named opinions.tsv, which contains two columns: Sentiment (binary labels: 0 for negative, 1 for positive) and Review (textual data). The script begins by reading the dataset into a pandas DataFrame and splitting it into training and testing sets using an 80-20 ratio. The CountVectorizer is applied to convert text into numerical feature representations, ignoring English stopwords and filtering out rare and overly common words. The text data is then transformed into document-term matrices (DTM) for training and testing.

The script evaluates four different classification models: Naïve Bayes (MultinomialNB), Logistic Regression, Support Vector Machine (LinearSVC), and K-Nearest Neighbors (KNN). Each model is trained on the training data, and its accuracy is measured on the test set using accuracy_score and a confusion matrix to analyze prediction errors. Among the models, Logistic Regression is identified as the best-performing model based on accuracy. Additionally, the script provides Naïve Bayes-based analysis, extracting feature counts for positive and negative reviews, determining the number of positive and negative tokens, and allowing users to check sentiment weights for specific words. It also identifies false negatives (actual positive but predicted negative) and false positives (actual negative but predicted positive) for further error analysis.

The final part of the script allows users to input a custom review for sentiment analysis. A new CountVectorizer is fitted on the complete dataset, and a Logistic Regression model is retrained using the full data. The user provides a review, which is vectorized and classified as positive or negative based on the trained model. This interactive functionality enhances the practicality of the sentiment analysis tool. Overall, the script effectively demonstrates natural language processing (NLP) techniques and machine learning classifiers to analyze textual sentiment, offering both automated classification and interpretability through token analysis and model evaluation.

#OUTPUT

![Image](https://github.com/user-attachments/assets/dc317127-cb4c-4533-81b0-a39a75befe4d)
