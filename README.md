# C3_3_AIML_Miniproject
AIML Miniproject: Loan approval prediction system

Loan Approval Prediction System
Project Overview
This project is a Machine Learning application designed to predict the approval status of loan applications. It analyzes various applicant details (such as income, education, and credit history) to classify the loan request as Approved or Rejected. The system includes an interactive user interface built with Gradio for real-time predictions.

Features
Data Processing: Handles missing values and performs feature encoding for categorical variables.

Exploratory Data Analysis (EDA): Visualizes data distributions and correlations using Matplotlib and Seaborn.

Machine Learning Pipeline: Utilizes a pipeline for preprocessing (scaling, encoding) and model training.

Predictive Model: The final deployed model is based on Logistic Regression (as indicated in the UI code).

Interactive UI: A user-friendly web interface created with Gradio that allows users to input applicant details and receive instant feedback with approval probability, risk level, and decision reasons.

Dataset
The project uses the loan prediction dataset.csv file. Key features analyzed include:

Demographics: Gender, Marital Status, Dependents.

Socio-economic: Education, Employment Status, Property Area.

Financial: Applicant Income, Co-applicant Income, Loan Amount, Loan Term, Credit History.

Technologies & Libraries Used
Python 3

Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn, plotly

Machine Learning: scikit-learn (Logistic Regression, Decision Tree, Random Forest)

Model Persistence: joblib

User Interface: gradio

Installation & Usage
Install Dependencies:

Bash

pip install pandas numpy matplotlib seaborn scikit-learn gradio joblib
Run the Notebook: Open C3_3_AIML_Miniproject.ipynb in Jupyter Notebook or Google Colab.

Launch the App: Execute the final cells to train the model and launch the Gradio interface. The app will generate a public or local URL for interaction.

Developers
Developed by Mitali, Khushi, and Sakshi Cummins College, 2025
