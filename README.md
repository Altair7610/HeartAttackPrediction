# HeartAttackPrediction
Training repository within the "Machine learning for scientific data analysis" course

# Data
I`m gonna use [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset).
## Data description
* `age` - Age of the patient
* `sex` - Sex of the patient
* `cp` - Chest pain type
  * 0 = Typical Angina
  * 1 = Atypical Angina
  * 2 = Non-anginal Pain
  * 3 = Asymptomatic
* `trtbps` - Resting blood pressure (mm Hg)
* `chol` - Cholestoral fetched via BMI sensor (mg/dl)
* `fbs` - Fasting blood sugar (> 120 mg/dl)
  * 1 = True
  * 2 = False
* `restecg` - Resting electrocardiographic results
  * 0 = Normal
  * 1 = ST-T wave normality
  * 2 = Left ventricular hypertrophy
* `thalachh` - Maximum heart rate achieved
* `oldpeak` - Previous peak
* `slp` - Slope
* `caa` - Number of major vessels
* `thall` - Thalium Stress Test result (~0.3)
* `exng` - Exercise included angina
  * 1 = Yes
  * 0 = No
* __`output`__ - Target variable

# Main goal
Perform EDA and predict if a person is prone to a heart attack or not
