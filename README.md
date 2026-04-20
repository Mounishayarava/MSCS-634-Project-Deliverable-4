# MSCS-634-Project-Deliverable-4: Data Mining and Predictive Analytics

# Project Overview
This project applies multiple data mining and machine learning techniques to analyze customer churn behavior. The goal is to extract meaningful insights from customer data, build predictive models, and identify patterns that can help businesses reduce customer loss and improve engagement strategies.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression analysis
- Classification modeling
- Clustering analysis
- Association rule mining


# Dataset Description
The dataset used is the **Customer Churn Dataset (Churn Modelling)**.

It contains customer-related information such as:
- Demographics (Age, Gender, Geography)
- Financial details (Balance, Salary, Credit Score)
- Account activity (Tenure, Active Membership)
- Target variable: **Exited (0 = No churn, 1 = churn)**

This dataset was selected because it is well-suited for classification, clustering, and pattern discovery tasks.


# Project Workflow

## 1. Data Preprocessing
- Removed irrelevant columns (RowNumber, CustomerId, Surname)
- Handled missing values
- Encoded categorical variables using one-hot encoding
- Standardized numerical features using StandardScaler


## 2. Exploratory Data Analysis (EDA)
- Identified correlations between features
- Analyzed distribution of age, balance, and salary
- Detected patterns linked to customer churn


## 3. Feature Engineering
- Converted categorical variables into numerical format
- Created grouped features (age, balance, salary categories)
- Improved model interpretability


## 4. Machine Learning Models

####  Regression
- Linear Regression used for baseline analysis
- Evaluated using R² score

####  Classification
- Logistic Regression used to predict churn
- Achieved ~80–86% accuracy

####  Clustering
- K-Means clustering used to group customers into segments
- Identified 3 main customer clusters

####  Association Rule Mining
- Apriori algorithm used to identify relationships between customer attributes
- Extracted patterns related to churn behavior


## Key Findings
- Inactive members are significantly more likely to churn
- Customers with higher balances show distinct behavioral patterns
- Age and activity level are strong predictors of churn
- Customer segmentation reveals high-value and at-risk groups


# Ethical Considerations
This project considered the following ethical aspects:
- **Data Privacy:** No sensitive personal identifiers were used in modeling
- **Bias:** Potential bias in demographic features was acknowledged
- **Fairness:** Care was taken to avoid misleading interpretations of model predictions
- **Transparency:** Models were interpreted to ensure explainability


# Recommendations
- Improve engagement strategies for inactive customers
- Use predictive models to identify at-risk customers early
- Implement personalized retention strategies for high-value users


#T ools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- MLxtend (Apriori Algorithm)
- Jupyter Notebook


# Repository Structure
-Project Deliverable4
-README
