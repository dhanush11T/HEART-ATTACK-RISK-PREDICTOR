# Heart Attack Risk Predictor
<img width="1800" alt="Screenshot 2024-08-28 at 11 43 21 AM" src="https://github.com/user-attachments/assets/c3c04bf8-2f1b-444d-b4c5-f5daaefd32e5">
<img width="1800" alt="Screenshot 2024-08-28 at 11 43 35 AM" src="https://github.com/user-attachments/assets/01f5f9db-e9d2-4b4e-a557-0b994997b3c3">
<img width="1800" alt="Screenshot 2024-08-28 at 11 43 27 AM" src="https://github.com/user-attachments/assets/cf8bba2b-c8ff-4349-ad18-cd985fa430a5">
<img width="1800" alt="Screenshot 2024-08-28 at 11 43 13 AM" src="https://github.com/user-attachments/assets/5675250f-ccd2-49c2-ae7d-4d0cfbb5e2b1">
<img width="1800" alt="Screenshot 2024-08-28 at 11 42 59 AM" src="https://github.com/user-attachments/assets/10f7ca96-a302-4053-be40-5d62b8ba3e95">
<img width="1794" alt="Screenshot 2024-08-28 at 11 42 33 AM" src="https://github.com/user-attachments/assets/76977ac1-acde-4b77-b81b-ffc96e1b422d">

#### RESULTS  ####
![Screenshot (140)](https://github.com/user-attachments/assets/fe5fb11c-c9b5-42d3-979c-ec0a2cbd8682)
![Screenshot (141)](https://github.com/user-attachments/assets/b0c0b953-f29a-41fa-b6d4-440f66d4677a)



## Overview
The **Heart Attack Risk Predictor** is a web application that leverages a machine learning model to predict the likelihood of a heart attack based on various health metrics. Users can sign up, log in, and input their health data into a form. The application processes this data and returns a prediction on the user's risk level.

## Features
- **User Authentication**: Sign up and login functionality to securely access the prediction tool.
- **Health Metrics Form**: A form where users input specific health-related parameters.
- **Risk Prediction**: The app uses a trained Decision Tree model to predict the likelihood of a heart attack based on the user's inputs.

## Input Parameters
The prediction model uses the following input parameters:

- **AGE**: Age in years.
- **SEX**: Gender (1 = male; 0 = female).
- **CP (Chest Pain Type)**:
  - Value 0: Typical angina (most serious)
  - Value 1: Atypical angina
  - Value 2: Non-anginal pain
  - Value 3: Asymptomatic (least serious)
- **TRESTBPS**: Resting blood pressure (in mm Hg).
- **CHOL**: Serum cholesterol in mg/dl.
- **FBS (Fasting Blood Sugar > 120 mg/dl)**: (1 = true; 0 = false)
  - Less than 100 mg/dL: Normal
  - 100 to 120 mg/dL: Prediabetes
  - 125 mg/dL or higher: Diabetes
- **RESTECG (Resting Electrocardiographic Results)**:
  - Value 0: Normal
  - Value 1: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
- **THALACH**: Maximum heart rate achieved.
- **EXANG**: Exercise induced angina (1 = yes; 0 = no).
- **OLDPEAK**: ST depression induced by exercise relative to rest.
- **SLOPE (The slope of the peak exercise ST segment)**:
  - Value 0: Upsloping
  - Value 1: Flat
  - Value 2: Downsloping
- **CA**: Number of major vessels (0-3) colored by fluoroscopy.
- **THAL**: 
  - Value 0: Normal
  - Value 1: Fixed defect
  - Value 2: Reversible defect

## How It Works
1. **Sign Up**: Users create an account by providing a username, email, and password.
2. **Log In**: Registered users log in to access the heart attack risk prediction tool.
3. **Input Data**: Users fill out a form with the required health metrics.
4. **Prediction**: The machine learning model processes the input data and provides a prediction indicating the likelihood of a heart attack.
5. **Result**: The prediction result is displayed on the screen.

## Technology Stack
- **Frontend**: React.js for building the user interface.
- **Backend**: Node.js and Express for handling user authentication and serving the machine learning model.
- **Machine Learning Model**: A Decision Tree model trained in Python using scikit-learn.
- **Database**: MongoDB for storing user credentials and prediction logs.

## Installation
To set up the project locally, follow these steps:

## 
git clone https://github.com/your-username/heart-attack-predictor.git and install modules accordingly and run it 

## 
The application will be available at `http://localhost:3000`.

## Usage
1. Sign up or log in to access the prediction tool.
2. Fill in the form with your health data.
3. Submit the form to receive a prediction on your heart attack risk.

