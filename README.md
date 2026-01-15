# AI Learning: SageMaker Model Training with XGBoost

## 🎯 What This Repository Is About

This repository is part of my journey into AI/ML, building on my cloud and infrastructure background. Here, I'm focusing on **training machine learning models using AWS SageMaker and the XGBoost algorithm**.

## 📚 The Learning Path

This is the second step in my AI learning series:

1. **[Data Preparation](https://github.com/VijayBheemineni/AI_Learning_DataPrep_SageMaker)** - Where I cleaned and prepared the `adult_data.csv` dataset
2. **Model Training** (this repo) - Where I train a binary classification model using XGBoost
3. **Model Deployment** (coming next) - Where I'll deploy the trained model for predictions

## 🔍 What I'm Learning

In this repository, I'm exploring:

- How to set up a SageMaker training environment
- Configuring the XGBoost algorithm for binary classification
- Understanding hyperparameters and their impact on model performance
- Training a model to predict income categories (`>=50K` or `<50K`)
- Evaluating model performance using validation and test datasets
- Working with model artifacts for future deployment

## 📂 What's Inside

- `vijay_train_and_create_model_xgboost.ipynb` - Jupyter Notebook with step-by-step model training code

## 🎓 The Use Case

I'm working with the Adult Census Income dataset to predict whether an individual's income is above or below $50K based on demographic and employment features. This is a classic **binary classification problem**, perfect for learning the fundamentals of supervised machine learning.

## 🛠️ Technologies Used

- **AWS SageMaker** - For managed model training infrastructure
- **XGBoost** - A powerful gradient boosting algorithm for structured data
- **Python** - For scripting and data manipulation
- **Jupyter Notebooks** - For interactive development and documentation

## 🚀 Getting Started

To run this notebook, you'll need:
- An AWS account with SageMaker access
- Prepared training, validation, and test datasets in S3 (from the data prep step)
- Basic understanding of Python and machine learning concepts

---

This is a hands-on learning project where I'm documenting my journey from cloud infrastructure into the world of AI and machine learning. Feel free to follow along!
