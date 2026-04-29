# Sales-prediction

📊 Sales Prediction using Linear Regression
🔍 Overview

This project builds a machine learning model to predict product sales based on advertising budgets across different channels:

TV
Radio
Newspaper

It uses Linear Regression to understand how marketing spend impacts sales.

📁 Dataset
File: sales dataset.csv
Features:
TV – Advertising spend on TV
Radio – Advertising spend on Radio
Newspaper – Advertising spend on Newspaper
Target:
Sales – Product sales

⚙️ Workflow
1. Data Preprocessing
Loaded dataset using pandas
Dropped unnecessary column (Unnamed: 0)
Checked for missing values
Converted all columns to integer type
2. Exploratory Data Analysis (EDA)
Used seaborn pairplot to visualize relationships
Generated correlation matrix to understand feature importance
3. Feature Selection
Input features (X): TV, Radio, Newspaper
Target (y): Sales
4. Train-Test Split
Split data into:
80% training
20% testing
5. Data Scaling
Applied StandardScaler for normalization
6. Model Building
Used Linear Regression (sklearn)
Trained model on scaled data

📈 Key Insight
Advertising channels (especially TV & Radio) show strong influence on sales.
Linear Regression helps quantify this relationship effectively.

🛠️ Tech Stack
Python
pandas, numpy
matplotlib, seaborn
scikit-learn

🚀 Outcome

A predictive model that estimates sales based on marketing spend, useful for:

Budget allocation
Marketing strategy optimization
