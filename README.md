README
MIT license
🎓 College Admission Chance Predictor
The College Admission Chance Predictor is a machine learning project that estimates the probability of a student’s admission into graduate programs based on their academic profile.

📊 Dataset
The dataset includes historical admission records with the following features:

GRE Score (out of 340)
TOEFL Score (out of 120)
University Rating (1–5)
SOP Strength (1–5)
LOR Strength (1–5)
CGPA (out of 10)
Research Experience (0 = No, 1 = Yes)
Target variable:

Chance of Admit (in percentage).
🧠 Methodology
Data Preprocessing

Dropped irrelevant columns.
Normalized features using MinMaxScaler.
Split dataset into training and testing sets.
Model Training

Used Linear Regression for prediction.
Evaluated using R² score and RMSE.
Deployment

Trained model saved with Pickle (lr.pkl).
Built a Streamlit app for user interaction.
🌐 Features
Enter GRE, TOEFL, CGPA, SOP, LOR, University Rating, and Research experience.
Predicts admission probability (%) instantly.
Interactive and easy-to-use web interface.
🚀 Tech Stack
Python – Pandas, NumPy, Scikit-learn
Streamlit – Frontend & deployment
Jupyter Notebook – Model training & analysis
⚙ Installation
Clone the repository:
