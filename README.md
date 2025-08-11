Employee Salary Prediction Model 💼
📌 Project Overview
This project predicts whether an employee earns more than $50K annually based on demographic and professional attributes. It was developed as part of my AI Internship at Edunet Foundation and demonstrates the complete machine learning workflow — from data preprocessing to model deployment.

🎯 Objective
Build a predictive model using classification algorithms.

Evaluate performance and select the most accurate model.

Deploy the model in a Streamlit web application for interactive use.

📊 Dataset
Source: UCI Adult Census Dataset

Size: 48,842 rows × 15 columns

Key Features: Age, Work Class, Education, Marital Status, Occupation, Relationship, Race, Hours-per-week, etc.

🛠 Methodology
1. Data Preprocessing
Handled missing values and replaced unknown categories.

Encoded categorical variables using Label Encoding.

Removed irrelevant columns and handled outliers.

Applied StandardScaler for feature scaling.

2. Model Training & Evaluation
Algorithms Tested:

Logistic Regression

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Gradient Boosting

Best Model: Gradient Boosting Classifier

Accuracy: 86.37%

3. Deployment
Built a Streamlit web application to allow users to enter employee details and get instant predictions.

📦 Technologies Used
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Streamlit

🚀 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YourUsername/SalaryPredictionModel.git
Navigate to the project folder:

bash
Copy
Edit
cd SalaryPredictionModel
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
📂 Repository Structure
bash
Copy
Edit
SalaryPredictionModel/
│-- app.py               # Streamlit app
│-- salary_predictor.py  # Model training script
│-- requirements.txt     # Dependencies
│-- README.md             # Project documentation
│-- dataset.csv           # Dataset used
📈 Results
Model	Accuracy
Logistic Regression	82.76%
Random Forest	85.75%
KNN	82.43%
SVM	84.86%
Gradient Boosting	86.37%

