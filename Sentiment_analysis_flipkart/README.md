# Sentiment Analysis of Real-time Flipkart Product Reviews

## Project Overview

This project focuses on analyzing customer reviews of Flipkart products and classifying them as Positive or Negative using Natural Language Processing (NLP) and Machine Learning techniques.

The project uses TF-IDF feature extraction and multiple machine learning models such as Logistic Regression, Naive Bayes, Random Forest, SVM, and XGBoost to perform sentiment classification.

A Streamlit web application is also developed for real-time sentiment prediction of user-provided reviews.

## Dataset Information

The dataset contains customer reviews for the product:

**YONEX MAVIS 350 Nylon Shuttle**

The dataset includes:
- Review Text
- Ratings
- Reviewer Name
- Review Title
- Up Votes
- Down Votes
- Place of Review
- Month

Total Reviews: **8518**

----
## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- XGBoost
- Streamlit
- Google Colab
- VS Code

-----

## Workflow

1. Data Loading and Analysis
2. Data Cleaning and Preprocessing
3. Text Normalization using Lemmatization
4. TF-IDF Feature Extraction
5. Model Training
6. Model Evaluation using F1-Score
7. Hyperparameter Tuning
8. Streamlit App Development
9. Deployment Preparation

----

## Model Performance

| Model | F1 Score |
|---|---|
| Logistic Regression | 0.9573 |
| Naive Bayes | 0.9493 |
| Random Forest | 0.9570 |
| SVM | 0.9621 |
| Tuned SVM | 0.9621 |
| XGBoost | 0.9556 |

----
## How to Run the Project

### Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Streamlit App

```bash
python -m streamlit run app/app.py
```

----
## Future Improvements

- Implement Deep Learning models such as LSTM and BERT
- Add multilingual sentiment analysis
- Deploy using AWS EC2
- Improve UI design
- Add sentiment visualization dashboards

----

## Conclusion

This project successfully performs sentiment analysis on Flipkart product reviews using NLP and Machine Learning techniques. Among all the models tested, SVM achieved the best performance with an F1-score of 0.9621.