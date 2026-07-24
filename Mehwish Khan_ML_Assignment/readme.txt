# Project Title
Oral Cancer Risk Prediction

## Description
This project is an oral cancer risk prediction model built using machine learning. It uses patient-related demographic, lifestyle, clinical, and medical-history features to predict whether a person is likely to have oral cancer.

## ML Algorithm Used
- Random Forest Classifier

## Dataset Features
The dataset contains 24 features after removing the unnecessary `ID` column. Important features include:
- Country
- Age
- Gender
- Tobacco Use
- Alcohol Consumption
- HPV Infection
- Betel Quid Use
- Chronic Sun Exposure
- Poor Oral Hygiene
- Diet Fruits Vegetables Intake
- Family History of Cancer
- Compromised Immune System
- Oral Lesions
- Unexplained Bleeding
- Difficulty Swallowing
- White or Red Patches in Mouth
- Tumor Size cm
- Cancer Stage
- Treatment Type
- Survival Rate 5-Year
- Cost of Treatment USD
- Economic Burden Lost Workdays per Year
- Early Diagnosis
- Oral Cancer Diagnosis

## Visualization Explanation
The notebook includes data exploration and preprocessing visualizations to understand the dataset distribution and relationships between features. These visualizations help identify patterns in symptoms, risk factors, and target class behavior before training the model.

## Accuracy
The model accuracy on the test set:
- Accuracy: [1.0]

## How to Run
1. Download the notebook file and dataset.
2. Install the required Python packages using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
4. Run all cells step by step.
5. Check the final accuracy and prediction results in the output cells.

## Author
Mehwish Khan