# Indian Liver Patient Prediction

This project involves building a machine learning model to predict whether a patient is likely to have liver disease based on clinical data. The dataset used is the **Indian Liver Patient Dataset (ILPD)**, which contains medical records of patients including features such as age, gender, bilirubin levels, and liver enzyme levels.

## Dataset

The dataset consists of 583 patient records and includes the following features:

- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphotase
- Alamine Aminotransferase (SGPT)
- Aspartate Aminotransferase (SGOT)
- Total Proteins
- Albumin
- Albumin and Globulin Ratio
- Selector (target variable indicating liver disease presence)

## Objective

To create a classification model that can predict the likelihood of a patient having liver disease using medical attributes.

## Approach

The notebook follows a structured machine learning pipeline:

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical data
   - Splitting dataset into train and test sets
   - Scaling features

2. **Model Training**:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier

3. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

## Results

The models were evaluated on test data, and the accuracy scores were as follows:

- **Logistic Regression**: ~74.5%
- **Decision Tree**: ~74.5%
- **Random Forest**: ~78.7%

The **Random Forest Classifier** showed the best performance among all with an accuracy of approximately **78.7%**.

![image](https://github.com/user-attachments/assets/3668bc90-29b9-4d20-be4c-c18343292cbb)
![image](https://github.com/user-attachments/assets/3c168434-418e-417e-8dc8-df9adbd788d0)
![image](https://github.com/user-attachments/assets/2b77912f-316b-432e-ae7d-5e1b69bf35f2)
![image](https://github.com/user-attachments/assets/8f220255-c117-4001-b246-736965f22f81)
![image](https://github.com/user-attachments/assets/8b2377fd-109b-4bc9-b5c6-1659bb9d8f7b)





