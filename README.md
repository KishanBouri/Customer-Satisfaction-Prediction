#  Customer Satisfaction Prediction

##  Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning to analyze customer support tickets and predict satisfaction ratings. It also explains predictions using SHAP.

---

##   Objectives
The objective of this project is to build an intelligent system that predicts customer satisfaction based on support ticket data by integrating structured data analysis with natural language processing (NLP) techniques. The goal is to uncover hidden insights from customer complaints using sentiment analysis and topic modeling, and to enhance trust in the model through explainable machine learning (SHAP). This approach not only forecasts customer satisfaction ratings but also explains the why behind each prediction, helping businesses improve customer experience, prioritize support operations, and reduce churn.

- Sentiment analysis of customer tickets
- Topic modeling using LDA
- Satisfaction prediction using RandomForest
- Explainable ML with SHAP

---

##  Project Structure
Customer-Satisfaction-Prediction/
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 01_sentiment_analysis.ipynb
│ ├── 02_topic_modeling.ipynb
│ ├── 03_model_training_explain.ipynb
│ └── 04_final_report.ipynb
├── reports/
│ └── final_report.pdf
├── outputs/
├── README.md
└── requirements.txt


---

##  Key Insights
- Tickets with negative sentiment often lead to low ratings.
- Certain topics (e.g., "payment issues", "delay complaints") consistently lead to poor ratings.
- SHAP shows **First Response Time**, **Sentiment Score**, and **Dominant Topic** are top predictors

---

## Final Output
- Predictive model with explainable results.
- Dashboard-ready data for further deployment.
- PDF report summarizing findings.

Author
Your Name: KISHAN KUMAR BOURI
GitHub: https://github.com/KishanBouri/Customer-Satisfaction-Prediction
Email: kishanbouri584@gmail.com

