# Credit-Risk-Analysis-NLP

<div align="center">



## 📊 Overview

This project combines traditional credit risk analysis with modern NLP techniques to create a comprehensive loan default prediction system. By analyzing both structured financial data and unstructured customer reviews, we provide deeper insights into credit risk assessment.

### 🎯 Project Objectives

- 🔍 **Risk Identification**: Analyze key factors driving loan defaults
- 💭 **Sentiment Analysis**: Extract insights from customer feedback
- 🤖 **ML Modeling**: Develop precise default prediction models
- 📈 **Business Intelligence**: Generate actionable insights

## 🗃️ Key Features

### Dataset Components
```
📁 Data Structure
├── 📊 Loan Data
│   ├── Customer Demographics
│   ├── Loan Details
│   └── Repayment Status
├── 📝 Customer Reviews
│   ├── Textual Feedback
│   └── Timestamp Information
└── 🎯 Derived Metrics
    ├── Sentiment Scores
    └── Risk Indicators
```

### 🔍 Sample Features
- Customer Profile: ID, Age, Loan Type
- Financial Metrics: Loan Amount, Payment History
- Sentiment Indicators: Review Text, Sentiment Scores

## 🛠️ Technologies

### Core Stack
```python
# Data Processing & Analysis
import pandas as pd
import numpy as np
import scikit-learn

# NLP & Text Analysis
import nltk
import textblob

# Visualization
import seaborn as sns
import matplotlib.pyplot as plt
```

### ML Algorithms
- 📊 Logistic Regression
- 🌲 Random Forest Classifier
- 🚀 XGBoost

## 📋 Implementation Steps

1. **Data Preprocessing** 🧹
   - Handled missing values
   - Removed outliers
   - Normalized numerical features
   - Preprocessed text data

2. **Sentiment Analysis** 💭
   ```python
   # Sample sentiment analysis workflow
   from textblob import TextBlob
   
   def analyze_sentiment(text):
       return TextBlob(text).sentiment.polarity
   ```

3. **Feature Engineering** ⚙️
   - Created interaction features
   - Engineered time-based variables
   - Generated text-based features

4. **Model Development** 🤖
   - Split data (train/test)
   - Trained multiple models
   - Performed cross-validation
   - Optimized hyperparameters

## 📈 Results & Insights

### Model Performance
```
📊 Random Forest Classifier
├── AUC-ROC Score: 0.86
├── Accuracy: 84%
├── Precision: 82%
└── Recall: 79%
```

### Key Findings
1. 📈 Higher default rates in unsecured loans
2. 🎯 Strong correlation between sentiment and default risk
3. 💡 Age and loan amount are critical predictors

### Visualizations
<div align="center">
<img src="![image](https://github.com/user-attachments/assets/d6287172-2359-4c1a-b670-0130450af701)
" alt="Default Rate Analysis">
</div>



## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


<div align="center">

📍 Developed with ❤️ by Isfaque Ansari

</div>
