# Heart Disease Prediction Project

## Introduction
This project aims to predict the 10-year risk of coronary heart disease (CHD) using logistic regression. The dataset used for this project is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.

## Problem Statement
The World Health Organization estimates that millions of deaths occur worldwide every year due to heart diseases, with half of the deaths in developed countries being due to cardiovascular diseases. Early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high-risk patients and reduce complications. This project intends to pinpoint the most relevant/risk factors of heart disease and predict the overall risk using logistic regression.

## Solution
Logistic regression is employed as the classification technique to predict whether a patient has a 10-year risk of future coronary heart disease (CHD).

## Dataset Information
The dataset contains over 4,000 records and 15 attributes. It includes demographic risk factors such as sex, age, and education, as well as behavioral risk factors like smoking, medical history risk factors, and physical examination results.
## Framingham Heart Study Dataset

The Framingham Heart Study dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. It includes over 4,000 records and 15 attributes.

### Demographic Risk Factors
1. **sex**: Male or Female.
2. **age**: Age of the patient.
3. **education**: Levels coded as follows:
   - 1: Some high school
   - 2: High school diploma or GED
   - 3: Some college or vocational school
   - 4: College degree

### Behavioral Risk Factors Associated with Smoking
1. **currentSmoker**: Whether or not the patient is a current smoker.
2. **cigsPerDay**: The number of cigarettes that the person smoked on average in one day.

### Medical History Risk Factors
1. **BPMeds**: Whether or not the patient was on blood pressure medication.
2. **prevalentStroke**: Whether or not the patient had previously had a stroke.
3. **prevalentHyp**: Whether or not the patient was hypertensive.
4. **diabetes**: Whether or not the patient had diabetes.

### Risk Factors from the First Physical Examination of the Patient
1. **totChol**: Total cholesterol level.
2. **sysBP**: Systolic blood pressure.
3. **diaBP**: Diastolic blood pressure.
4. **BMI**: Body Mass Index.
5. **heartRate**: Heart rate.
6. **glucose**: Glucose level.

### Target Variable
- **TenYearCHD**: 10-year risk of coronary heart disease (CHD).

The dataset is available in the repository.

## Libraries Used
- Pandas: For data manipulation
- Matplotlib: For data visualization
- Seaborn: For data visualization
- Scikit-Learn: For data modeling

## Contents
1. Importing the required libraries.
2. Importing and reading the dataset.
3. Exploratory Data Analysis (EDA).
4. Data Preprocessing.
5. Data Visualization.
6. Correlation Matrix.
7. Pairplot.
8. Countplots.
9. Data Modeling.
10. Separating the data into features and target variable.
11. Splitting the data into training and test sets.
12. Modeling/Training the data.
13. Predicting the data.
14. Calculating the prediction scores.
15. Getting the model's accuracy.
16. Classification Report.
17. Confusion Matrix.

## Usage
- Clone this repository.
- Install the required libraries using `pip install -r requirements.txt`.
- Run the Jupyter Notebook or Python script.

