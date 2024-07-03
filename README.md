# Diabetes Prediction Project

This project aims to diagnostically predict whether or not a patient has diabetes based on certain diagnostic measurements. The dataset used is from the National Institute of Diabetes and Digestive and Kidney Diseases.

## Dataset

The dataset contains diagnostic measurements of female patients who are at least 21 years old. It includes the following features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

The target variable is a binary value indicating whether the patient has diabetes (1) or not (0).

## Project Structure

- `diabeties.csv`: The dataset file.
- `diabetes_prediction.py`: The main Python script for data analysis, model training, evaluation, and visualization.
- `README.md`: This readme file.

## Requirements

The following Python packages are required to run the project:
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install the required packages using the following command:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
