# Tamil Nadu Women's Crime Analysis & Prediction

## Overview
This project analyzes crimes against women across various districts of Tamil Nadu and predicts future crime counts using Machine Learning. The goal is to identify high-risk districts, understand crime patterns, and support preventive safety measures.

## Objectives
- Analyze women's crime data in Tamil Nadu.
- Identify districts with high crime rates.
- Study rape-related crime patterns.
- Analyze victim age distribution.
- Predict future crime counts using Machine Learning.
- Classify areas into safety levels.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## Dataset Features
- Year
- District
- Area
- Crime Type
- Victim Age
- Time of Crime
- Urban/Rural Area
- Police Station
- Crime Count

## Machine Learning Model
### Random Forest Regressor

Random Forest Regressor was used to predict future crime counts based on district, crime type, victim age, location information, and other factors.

### Model Performance
- Algorithm: Random Forest Regressor
- R² Score: 91.41%



## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Feature Encoding
6. Train-Test Split
7. Model Training
8. Crime Prediction
9. Safety Level Classification



## Results & Analysis

### 1. Top Dangerous Districts

This chart highlights districts with the highest number of crimes against women.

**Observation:** Chennai reported the highest crime count, followed by Coimbatore and Madurai.

<img width="1352" height="672" alt="Screenshot 2026-06-16 205747" src="https://github.com/user-attachments/assets/12ef5329-dabb-46e7-be07-951a7f2dc683" />



### 2. Top Districts with Rape Cases

This visualization shows districts with the highest reported rape cases.

**Observation:** Coimbatore recorded the highest rape-related crime count, followed by Chennai and Trichy.

<img width="1402" height="682" alt="Screenshot 2026-06-16 205927" src="https://github.com/user-attachments/assets/6db9bc18-eb55-4028-8def-43e7feb0355c" />




### 3. Victim Age Distribution

The histogram shows the age distribution of victims.

**Observation:** Most victims fall within the 20–30 age group.

<img width="1275" height="725" alt="Screenshot 2026-06-16 210016" src="https://github.com/user-attachments/assets/681c1b22-8336-467e-8133-a51be878f34b" />



### 4. Crime Type Distribution

The pie chart represents the proportion of different crime categories.

**Observation:**
- Rape: 51.4%
- Assault: 20.9%
- Kidnapping: 20.4%
- Harassment: 7.4%

Rape accounts for the largest share of reported crimes.

<img width="1053" height="763" alt="Screenshot 2026-06-16 210212" src="https://github.com/user-attachments/assets/aed6f039-23a6-4b45-b523-b04ce1f9387b" />



### 5. District Wise Crime Analysis

This chart compares crime counts across Tamil Nadu districts.

**Observation:** Crime incidents are unevenly distributed, with Chennai showing significantly higher crime counts than other districts.

<img width="1345" height="581" alt="Screenshot 2026-06-16 210232" src="https://github.com/user-attachments/assets/5dc5eb8a-04ff-439b-a01e-d8a331efd1b7" />



### 6. Crime Prediction

The trained Random Forest model predicts future crime counts using historical crime data and district-level information.

#### Sample Input
- Year: 2027
- Victim Age: 24
- District: Encoded Value
- Crime Type: Encoded Value

#### Prediction Output
- Predicted Crime Count: 18.81
- Safety Level: High Danger
- 
<img width="1277" height="747" alt="Screenshot 2026-06-16 210355" src="https://github.com/user-attachments/assets/18731893-c67f-481c-9200-00ef9919fd5a" />


## Key Findings

- Chennai is the most crime-prone district in the dataset.
- Coimbatore has the highest number of rape cases.
- Women aged 20–30 are the most affected group.
- Rape contributes the largest percentage of crimes.
- Random Forest achieved high prediction accuracy with an R² score of 91.41%.



## Conclusion

This project successfully analyzes women's crime patterns in Tamil Nadu and predicts future crime trends using Machine Learning. The results can help identify vulnerable regions and support data-driven safety planning and preventive measures.


