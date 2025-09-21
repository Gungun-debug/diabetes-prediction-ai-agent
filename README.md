# Diabetes Prediction AI Agent

## Project Overview
This project is an AI Agent that predicts whether a patient is diabetic or not based on medical features. It uses a Logistic Regression model trained on the **Pima Indians Diabetes Dataset**.

## Dataset
- **Name**: diabetes.csv  
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**: Outcome (1 = Diabetic, 0 = Not Diabetic)

## Model
- **Algorithm**: Logistic Regression
- **Evaluation**: Accuracy measured on test dataset

## How it Works
1. User inputs medical details for a patient.
2. The AI Agent processes the input and predicts the **Outcome**.
3. Outputs “Diabetic” or “Not Diabetic”.

## Sample Predictions
- Input: [6, 148, 72, 35, 0, 33.6, 0.627, 50] --> Predicted Outcome: Diabetic  
- Input: [0, 85, 66, 29, 0, 26.6, 0.351, 31] --> Predicted Outcome: Not Diabetic

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

## How to Run
1. Clone the repository.
2. Open the Jupyter Notebook `Data_Analysis_Project.ipynb`.
3. Run all cells.
4. Enter patient details to get predictions.
