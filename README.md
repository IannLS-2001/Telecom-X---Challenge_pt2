# Telecom-X---Challenge_pt2
Customer Churn Analysis
Project Overview

This project analyzes customer churn (cancellation) data to identify the factors that most influence whether a customer leaves a service. The analysis includes data preprocessing, exploratory data analysis, model building, and evaluation. The goal is to provide actionable insights to improve customer retention strategies.

Features

Cleaned and preprocessed dataset with categorical variables encoded for machine learning.

Exploratory data analysis with visualizations to identify trends and correlations.

Built predictive models including:

Logistic Regression

Random Forest

Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.

Identified key factors influencing customer churn.

Recommended strategies to reduce churn based on model insights.

Installation

Clone this repository and install the required dependencies:

git clone <repository_url>
cd customer-churn-analysis
pip install -r requirements.txt


Dependencies:

Python 3.x

pandas

numpy

scikit-learn

seaborn

matplotlib

Usage

Load the dataset into the data/ folder.

Run the data preprocessing scripts to encode categorical variables and clean data.

Perform exploratory data analysis:

python eda.py


Train and evaluate models:

python modeling.py


Generate the report with insights and recommendations:

python report.py

Insights

Customers with short-term contracts or higher variability in spending are more likely to churn.

Certain services (like internet or add-ons) and payment methods influence cancellation.

Strategies such as promotions, loyalty programs, and proactive engagement can help reduce churn.

Project Structure
customer-churn-analysis/
│
├─ data/               # Dataset files
├─ notebooks/          # Jupyter notebooks for exploration
├─ scripts/            # Python scripts for preprocessing and modeling
├─ reports/            # Generated reports and visualizations
├─ requirements.txt    # Python dependencies
└─ README.md           # Project documentation

License

This project is licensed under the MIT License.

