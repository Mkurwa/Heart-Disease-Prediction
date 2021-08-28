# Heart-Disease-Prediction

This project focuses on predicting heart disease based on attributes such as blood pressure, cholesterol levels, heart rate, and other characteristic attributes. Patients are classified as to whether they have coronary artery disease or not.

This dataset contains patient data concerning heart disease diagnosis that was collected at several locations around the world. There are 76 attributes, including age, sex, resting blood pressure, cholestoral levels, echocardiogram data, exercise habits, and many others. To data, all published studies using this data focus on a subset of 14 attributes. This project also uses these 14 features. More specifically, this project uses the data collected at the Cleveland Clinic Foundation.

This project uses some common Python libraries, such as pandas, numpy, matplotlib and seaborn. Furthermore, for the machine learning side of this project, sklearn and keras is used.

## Attribute Information:

Only 14 attributes used:

* (age): age in years
* (sex): sex (1 = male; 0 = female)
* (cp): chest pain type -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic
* (trestbps): trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* (chol): serum cholestoral in mg/dl
* (fbs): fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* (restecg): restecg: resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
* (thalach): thalach: maximum heart rate achieved
(exang): exercise induced angina (1 = yes; 0 = no)
* (oldpeak): oldpeak = ST depression induced by exercise relative to rest
* (slope): slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping
* (ca): ca: number of major vessels (0-3) colored by flourosopy
* (thal): thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* (num) (the predicted attribute): num: diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)
