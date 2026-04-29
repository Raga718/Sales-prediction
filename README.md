📊 Sales Prediction using Linear Regression

📌 Overview

This project builds a Machine Learning model to predict product sales based on advertising spend across different channels.

Using Linear Regression, we analyze how marketing investments influence sales and generate predictions.

📁 Dataset
File: sales dataset.csv
Features:
TV – Advertising spend on TV
Radio – Advertising spend on Radio
Newspaper – Advertising spend on Newspaper
Target:
Sales – Product sales


⚙️ Project Workflow
1. Data Preprocessing
Loaded dataset using pandas
Removed unnecessary column (Unnamed: 0)
Checked for missing values
2. Exploratory Data Analysis (EDA)
Pairplot using seaborn
Correlation heatmap
3. Feature Selection
Input (X): TV, Radio, Newspaper
Output (y): Sales
4. Train-Test Split
80% training, 20% testing
5. Data Scaling
StandardScaler applied
6. Model Building
Linear Regression using scikit-learn
📈 Key Insights
TV advertising has the strongest impact on sales
Radio also contributes significantly
Newspaper has lower influence
🛠️ Tech Stack
Python
pandas, numpy
matplotlib, seaborn
scikit-learn
