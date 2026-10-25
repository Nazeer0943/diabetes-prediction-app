# Diabetes Prediction App

## Project Overview

This project is a practice machine-learning application developed to learn how to deploy a classification model using Streamlit, GitHub, and Streamlit Community Cloud.

The application accepts user inputs, including age, gender, symptoms, and other characteristics, and passes them to a trained Random Forest classifier to generate a predicted class.

**Note:** This application is for educational purposes only and is not intended for medical diagnosis or treatment decisions.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Streamlit
- GitHub
- Streamlit Community Cloud

## Project Files

- `app.py` — Streamlit application and prediction form.
- `diabetes_model.joblib` — Saved Random Forest model.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.

## How to Run Locally

1. Clone this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start the application:

   ```bash
   streamlit run app.py
   ```

## Model Information

The practice model was trained using 16 input features. Its target column, `class`, contains two labels: `0` and `1`.

The meanings of these labels should be verified against the original dataset before interpreting predictions.

## Deployment

The application is deployed using Streamlit Community Cloud and is connected to this GitHub repository.

## Disclaimer

This project demonstrates a machine-learning deployment workflow. Its predictions are experimental and should not be used as medical advice.
