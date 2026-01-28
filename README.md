Project Overview
This project involves a comprehensive analysis of the UCI Census Income Dataset (containing over 48,000 records). The goal is to identify key socio-economic drivers—such as education, occupation, and age—that influence an individual's earning potential and to build a predictive model to classify individuals into income brackets (>50K or ≤50K).

Key Features
Data Cleaning & Imputation: Handled missing values using Mode Imputation to maintain dataset integrity.

Exploratory Data Analysis (EDA): Leveraged Seaborn and Matplotlib to visualize correlations between demographic features and wealth distribution.

Feature Engineering: Implemented Label Encoding to transform categorical variables for machine learning compatibility.

Machine Learning Modeling: Developed and compared multiple classification algorithms to achieve high prediction accuracy.

Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

Environment: Jupyter Notebook

Analysis Insights
The project explored how various social factors impact economic outcomes:

Education: Higher education levels showed a strong positive correlation with the >50K income bracket.

Occupation: Roles such as "Exec-managerial" and "Prof-specialty" were identified as high-probability indicators for higher income.

Demographics: Age and work-class distribution provided significant context for earning trends.

Model Performance
The classification models were evaluated based on accuracy: | Algorithm | Accuracy | | :--- | :--- | | Logistic Regression | 83% | | Decision Tree Classifier | 82% | | Principal Component Analysis (PCA) | 81% | | Linear Discriminant Analysis (LDA) | 76% |
