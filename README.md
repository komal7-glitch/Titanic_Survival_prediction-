# Titanic_Survival_prediction-
🚢 Titanic Survival Prediction
This project is a classic example of binary classification using machine learning. It predicts whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, fare, and more.

📂 Dataset
Source: Kaggle - Titanic: Machine Learning from Disaster

File Used: Titanic-Dataset.csv

🔧 Technologies Used
Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Streamlit (for deployment)

📊 Steps Followed
1. Data Preprocessing
Handled missing values in Age, Cabin, and Embarked.

Converted categorical variables (Sex, Embarked, Pclass) into numerical format using encoding.

Feature scaling applied to numerical features.

2. Exploratory Data Analysis (EDA)
Visualized survival rate by gender, class, and age.

Identified strong predictors of survival such as:

Gender (Sex)

Passenger class (Pclass)

Age

3. Model Building
Used various ML algorithms:

Logistic Regression

Random Forest

Support Vector Machine

Evaluated models based on:

Accuracy

Confusion Matrix

Classification Report

4. Model Evaluation
Best Performing Model: Random Forest (example)

Accuracy: ~85% (based on evaluation)

Cross-validation: Applied for performance stability

🚀 Streamlit Deployment
How to Run the App Locally
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run titanic_app.py
Enter passenger details and get survival prediction in real-time.

📌 Key Findings
Females had a higher survival rate.

First-class passengers were more likely to survive.

Children (under age 10) had better chances of survival.

💡 Recommendations
Ensure complete and clean data for higher model accuracy.

Use ensemble models for better generalization.

Improve model interpretability using SHAP or LIME.

👨‍💻 Author
Komal yadav
📧 Email: ky4207479@gmail.com


