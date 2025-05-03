# housing-price-prediction
House Price Prediction Using Linear Regression
This project demonstrates a complete end-to-end machine learning workflow to predict house prices using the Boston Housing dataset. It covers data cleaning, exploratory data analysis (EDA), feature selection using Recursive Feature Elimination (RFE), and building a regression model using Scikit-learn's Linear Regression.

Technologies Used
Python 🐍

Pandas & NumPy

Seaborn & Matplotlib

Scikit-learn

Jupyter Notebook

 Key Steps
Data Loading
Load the Boston Housing dataset using Scikit-learn.

Data Cleaning

Handle missing values

Remove duplicates (if any)

Exploratory Data Analysis (EDA)

Correlation matrix

Visual inspection of feature relationships

Feature Selection with RFE

Use Recursive Feature Elimination (RFE) with Linear Regression to select top 6 features.

Model Building

Train a Linear Regression model

Evaluate performance with MSE and R²

Prediction & Visualization

Compare actual vs predicted prices using scatter plot.

Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Create and activate a virtual environment (optional):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook

Results
R² Score: ~0.73

Top 6 Features (via RFE): Example – RM, LSTAT, PTRATIO, etc.

Learning Outcomes
Hands-on understanding of linear regression

Importance of feature selection in model performance

End-to-end data science workflow
