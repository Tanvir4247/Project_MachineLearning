# Personality Classification using Machine Learning

## Introduction
This project aims to classify personalities using machine learning techniques. The Myers-Briggs Type Indicator (MBTI) categorizes individuals into one of 16 personality types based on four dichotomies: Introversion (I) – Extroversion (E), Intuition (N) – Sensing (S), Thinking (T) – Feeling (F), and Judging (J) – Perceiving (P). By employing natural language processing and machine learning algorithms, this project seeks to predict an individual's personality type based on textual data.
![Personality Image](https://drive.google.com/file/d/1AeS-gUN2wg4omQf1T91qC3AU8A8A3vBW/view?usp=sharing)

## Data Collection
The dataset used for this project is obtained from Kaggle, containing textual information associated with individuals' personalities as per the MBTI framework.

## Data Preprocessing
Data preprocessing involves converting the raw text data into a format suitable for machine learning models. This includes:
- Tokenization: Breaking down the text into individual words or tokens.
- Count Vectorization: Converting the text into a matrix of token counts, where each row represents a document and each column represents a token's frequency in that document.
- Limiting Features: To manage computational complexity and reduce noise, we limit the number of features to 4000 using CountVectorizer.

## Model Used
Several machine learning models were employed for personality classification:
- XGBoost
- XGBoost with Latent Dirichlet Allocation (LDA)
- Support Vector Classifier (SVC)
- Logistic Regression
- Decision Tree
- Random Forest
- K Nearest Neighbors
- Naive Bayes

## Results
The model performances, measured in terms of accuracy, are as follows:
- XGBoost: 0.695352
- XGBoost with LDA: 0.694170
- SVC: 0.648483
- Logistic Regression: 0.601229
- Decision Tree: 0.541299
- Random Forest: 0.536688
- K Nearest Neighbors: 0.422589
- Naive Bayes: 0.215905

## Conclusion
The results indicate that XGBoost and XGBoost with LDA outperform other models in predicting personality types based on textual data. This project demonstrates the feasibility of using machine learning techniques for personality classification, which can have applications in various fields such as psychology, human resources, and social media analysis. Further optimization and exploration of feature engineering techniques could potentially enhance model performance.
