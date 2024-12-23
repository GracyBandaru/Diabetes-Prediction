# Diabetes Prediction Web App

## Description
This project is a Streamlit-based web application that predicts the likelihood of diabetes based on user-provided health parameters. Using a pre-trained machine learning model, the app evaluates input data and provides a diagnosis of either 'Diabetic' or 'Non-Diabetic'.

---

## Features
- Easy-to-use web interface for inputting health parameters.
- Real-time diabetes prediction using a pre-trained model.
- Handles invalid input gracefully with error messages.

---

## Tech Stack
- Python
- Streamlit
- NumPy
- Pickle (for loading the pre-trained model)

---

## Usage

### 1. Install Dependencies
Ensure you have Python installed. Then, install the required libraries:
```bash
pip install streamlit numpy
```

### 2. Run the Application
Start the Streamlit server by running the script:
```bash
streamlit run app.py
```

### 3. Input Fields
The app requires the following health parameters:
- **Pregnancies**: Number of pregnancies.
- **Glucose**: Glucose level.
- **Blood Pressure**: Blood pressure value.
- **Skin Thickness**: Skin thickness value.
- **Insulin**: Insulin level.
- **BMI**: Body Mass Index.
- **Diabetes Pedigree Function**: A function that estimates diabetes likelihood based on family history.
- **Age**: Age of the individual.

### 4. View Results
- After inputting the parameters, click the 'Predict' button.
- The app will display whether the individual is 'Diabetic' or 'Non-Diabetic'.

---

## Example
Input sample values such as:
- Pregnancies: `2`
- Glucose: `150`
- Blood Pressure: `80`
- Skin Thickness: `25`
- Insulin: `100`
- BMI: `28.5`
- Diabetes Pedigree Function: `0.5`
- Age: `30`

Click 'Predict' to get the result.

---

