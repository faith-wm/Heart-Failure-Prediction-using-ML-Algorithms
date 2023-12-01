# Predicting Heart Failure with Machine Learning Techniques
Objective: Develop machine learning models to determine the likelihood of heart failure in patients using various clinical indicators.


## Dataset
Dataset can be downloaded from: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

Data features
- Age -  years
- Sex - M:male, F:female
- ChestPainType - [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP - resting blood pressure (mmHg)
- Cholesterol - cholesterol (mm/dl)
- FastingBS - fasting blood sugar [1:fastingBS?120ng/dl, 0: otherwise]
- RestingECG - Normal, ST, LVH
- MaxHR - maximum heart rate
- ExerciseAngina - N:No, Y:yes
- Oldpeak - ST 
- ST_Slope - Up, Flat, Down
- HeartDisease (target) 0: normal,  1: heart disease

## Exploratory Data Analysis (EDA)
EDA involves using Pandas for data manipulation and Matplotlib and Seaborn for visualization.
  
  ## Models
- Logistic Regression
-  Decision Tree
-  Random Forest
-  K-Nearest Neighbors
-  LightGBM
-   XGBoost

  ## Evaluation metrics
  - ROC-AUC
  - Confusion matric
  
