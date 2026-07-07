# Email Spam Detection using Machine Learning

## Project Overview

This project develops a machine learning model to classify SMS messages as either **spam** or **ham (legitimate)** using Natural Language Processing (NLP). The dataset undergoes preprocessing, feature extraction using Term Frequency–Inverse Document Frequency (TF-IDF), and classification using supervised learning algorithms.

## Objectives

- Perform data cleaning and preprocessing
- Explore the dataset using Exploratory Data Analysis (EDA)
- Engineer useful features such as message length
- Convert text into numerical features using TF-IDF
- Train and compare multiple machine learning classifiers
- Evaluate model performance using classification metrics and ROC curves

## Dataset

The project uses the **SMS Spam Collection Dataset**, containing over 5,000 labeled SMS messages categorized as either **spam** or **ham**.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

## Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Text Preprocessing
6. TF-IDF Feature Extraction
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison

## Machine Learning Models

- Multinomial Naive Bayes
- Logistic Regression

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Area Under the Curve (AUC)

## Results

Both classifiers achieved excellent performance, with ROC AUC scores above **0.98**. Among the evaluated models, **Multinomial Naive Bayes** produced the best overall performance, achieving higher accuracy, recall, and F1-score, making it the preferred model for this SMS spam detection task.

## Conclusion

This project demonstrates that Natural Language Processing techniques combined with machine learning can effectively distinguish spam messages from legitimate messages. By applying text preprocessing, TF-IDF vectorization, and classification algorithms, highly accurate spam detection models can be developed for practical use in email and messaging systems.
