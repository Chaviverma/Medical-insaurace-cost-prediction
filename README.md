# Medical-insaurace-cost-prediction
Medical Insurance Cost Prediction is a machine learning project that predicts health insurance charges based on personal factors such as age, gender, BMI, number of children, smoking habits, and region. By analyzing these inputs, the model helps estimate the expected premium, giving users an idea of their potential medical insurance costs.





📌 About

This project predicts medical insurance charges using machine learning techniques.
It takes user details such as age, gender, BMI, number of children, smoking status, and region as input, and estimates the expected insurance premium.
The goal is to help individuals and insurance providers get a quick idea of healthcare costs based on lifestyle and demographic factors.



📊 Dataset

The dataset used is the popular Medical Cost Personal Dataset.

Features include:

age → Age of the individual

sex → Male/Female

bmi → Body Mass Index

children → Number of dependents

smoker → Smoking status (yes/no)

region → Residential area (northeast, northwest, southeast, southwest)

charges → Medical insurance cost (target variable)




⚙️ Features of the Project

Machine learning models (Linear Regression, Random Forest, Gradient Boosting, etc.)

Interactive Streamlit web app for predictions

User-friendly UI with sliders, dropdowns, and prediction results

Categorization of premium into Low, Medium, High ranges





🚀 How to Run

Clone this repository

git clone https://github.com/Chaviverma/insurance-cost-prediction.git
cd insurance-cost-prediction


Install dependencies

pip install -r requirements.txt


Run the Streamlit app

streamlit run app.py


Enter details in the app and get instant insurance cost predictions 💰





📌 Tech Stack

Python

Pandas, NumPy (Data processing)

Scikit-learn (Machine Learning)

Streamlit (Web app deployment)
