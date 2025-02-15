# AI-Powered Medical Diagnosis System

## Project Overview
The **AI-Powered Medical Diagnosis System** is a machine learning-based application designed to assist in medical diagnoses. It utilizes various machine learning models like Support Vector Machine (SVM), Logistic Regression, and Random Forest to classify medical data and provide predictions based on input features. The application is designed to be user-friendly and is deployed using **Streamlit** for interactive web-based interfaces.

## Features
- **Data Preprocessing:** The system handles missing data, performs feature scaling, and splits the dataset into training and testing sets.
- **Model Training:** Utilizes machine learning models such as:
  - Support Vector Machine (SVM)
  - Logistic Regression
  - Random Forest
- **Model Evaluation:** Evaluates models based on accuracy, precision, recall, and F1-score.
- **User Interface:** Deployed with **Streamlit** to allow real-time interaction with the model for predictions.
- **Medical Dataset:** The system uses an anonymized dataset to train models for medical diagnosis.

## Installation

To run this project locally, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/Zai14/AI-Powered-Medical-Diagnosis-System.git
    ```
2. Navigate to the project directory:
 ```bash
cd AI-Powered-Medical-Diagnosis-System
pip install -r requirements.txt
streamlit run MDS.py
 ```
## Usage
1) Open the terminal and run the Streamlit command as shown above.
2) Open the browser and go to http://localhost:8501/ to access the web interface.
3) Upload your dataset or use the provided one.
4) Choose a machine learning model (SVM, Logistic Regression, or Random Forest) for prediction.
5) View results, including accuracy and classification report.
## Technologies Used
**Python:** Main programming language used for building the application.
**Scikit-learn:** Machine learning library for model training and evaluation.
**Pandas:** Used for data manipulation and analysis.
**NumPy:** Supports numerical computations.
**Streamlit:** Web framework used to deploy the application.
## Models Implemented
**Support Vector Machine (SVM):** A supervised machine learning algorithm that can be used for both classification and regression challenges.
**Logistic Regression:** A statistical model that uses a logistic function to model a binary dependent variable.
**Random Forest:** An ensemble method that fits multiple decision trees on various sub-samples of the dataset and uses averaging to improve prediction accuracy.
 
