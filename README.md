# Diabetes Prediction Model

## Project Overview
This project uses a machine learning model to predict the likelihood of a patient having diabetes based on key health metrics, such as glucose levels, blood pressure, and BMI. The data used is from the Pima Indians Diabetes Database, a well-known dataset for diabetes research and machine learning applications.

The project explores the features of the dataset, performs data preprocessing, and trains a decision tree classifier to achieve accurate predictions. Currently, the model achieves an accuracy of over 80%.

## Features
- **Pregnancies:** Number of times the patient has been pregnant.
- **Glucose:** Blood glucose level after 2 hours in an oral glucose tolerance test.
- **Blood Pressure:** Diastolic blood pressure (mm Hg).
- **Skin Thickness:** Triceps skinfold thickness (mm).
- **Insulin:** Blood insulin level after 2 hours.
- **BMI:** Body mass index.
- **Diabetes Pedigree Function:** A function that estimates the likelihood of diabetes based on family history.
- **Age:** Patient’s age in years.

## Requirements
- Python 3.7+
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

Install dependencies using

`pip install pandas matplotlib seaborn scikit-learn
`

## Usage
Visit notebook for a comprehensive guide.

## Extending the project
A logical extension of this project is to create an API so others can input patient data and receive predictions. This API will allow healthcare providers or applications to easily consume the model's predictions.

#### Sample workflow
- API endpoint: `/predict` that accepts JSON data
- Prediction: Passes the data to the model and returns the diabetes prediction
- Response: Returns a JSON response indicating either the probability of a patient having diabetes or a binary prediction (has diabetes or does not have diabetes)

## License
This project is open-source under the MIT License.