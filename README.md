# Heart-disease-predictor
A machine learning model created with scikit-learn library, with the logistic regression model, to identify if the poatient has heart disease or not.
The parameters that are used to train the model are:

age: patient's age in years

sex: The person’s sex (1 = male, 0 = female)

cp: chest pain type ( 0: asymptomatic, 1: atypical angina, 2: non-anginal pain, 3: typical angina )

trestbps: The patient’s resting blood pressure (mm Hg)

chol: The patient’s cholesterol mg/dl

fbs: The patient’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

restecg: resting electrocardiographic results
— 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria
— 1: normal
— 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)

thalach: The patient’s maximum heart rate achieved

exang: Exercise induced angina (1 = yes; 0 = no)

oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the ECG plot)

slope: the slope of the peak exercise ST segment — 0: downsloping; 1: flat; 2: upsloping

ca: The number of major vessels (0–3)

thal: A blood disorder called thalassemia Value 0: NULL (dropped from the dataset previously
- 1: fixed defect (no blood flow in some part of the heart)
- 2: normal blood flow
- 3: reversible defect (a blood flow is observed but it is not normal)
  
target: Heart disease (1 = yes, 0 = no) (This is the actual output)
