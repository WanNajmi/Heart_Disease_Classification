# Heart_Disease_Classification

# <div align="center">Heart Disease Classification</div>
<div align="center"><img src="https://nationaljewish.org/getattachment/Health-Insights/smoking-and-tobacco-use/health/coronary-heart-disease-and-tobacco/Coronary-Arteries.jpg.aspx?width=428&height=244&ext=.jpg" width="80%"></div>

## Overview
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient consist of0 == no disease and 1 == disease.

## Dataset:
[Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

#### Dataset attributes:
There are thirteen features and one target as below:
- age : The person's age in years
- sex : The person's sex (1 = male, 0 = female)
- cp : The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
- trestbps : The person's resting blood pressure (mm Hg on admission to the hospital)
- chol : The person's cholesterol measurement in mg/dl
- fbs : The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
- restecg : Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
- thalach : The person's maximum heart rate achieved
- exang : Exercise induced angina (1 = yes; 0 = no)
- oldpeak : ST depression induced by exercise relative to rest
- slope : the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
- ca : The number of major vessels (0-3)
- thal : A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

## Data Exploration:

## Heart Disease Frequency based on Sex:
<img src = "https://github.com/WanNajmi/Heart_Disease_Classification/blob/main/output/sex.png" width = "80%" >

## Heart Disease Frequency based on Ages:
<img src = "https://github.com/WanNajmi/Heart_Disease_Classification/blob/main/output/age.png" width = "80%" >

## Heatmap correlation of Heart Disease dataset:
<img src = "https://github.com/WanNajmi/Heart_Disease_Classification/blob/main/output/heatmap.png" width = "80%" >

## Training vs Validation Accuracy: 
<img src = "https://github.com/WanNajmi/Heart_Disease_Classification/blob/main/output/accuracy.PNG" width = "40%" >

## Training vs Validation Loss: 
<img src = "https://github.com/WanNajmi/Heart_Disease_Classification/blob/main/output/loss.PNG" width = "40%" >
