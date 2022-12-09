# Heart Disease Prediction
![HeartDiseaseFactors-1345978894-770x533-1-650x428](https://user-images.githubusercontent.com/83806097/206735868-9d9d30d1-c135-4919-b2ec-24c471834c9f.jpg)

# Problem Statement
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict a possible heart disease.
## Data Description
The dataset we’ve consisted of records of Heart Disease. It  has various columns which describe the factors related with the heart disease such as the age, Chest Pain Type, Resting BP,  Cholesterol, Max HR, Exercise Angina etc. This study reviewed the literature and used the following 12 variables as explanatory variables:
- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]
## Approach Pipeline
- Data Exploration
- Data Preprocessing
- Model Prediction
# Project Files Description
- [Zep project on heart disease.ipynb](https://github.com/AnkitaD1998/Heart-Disease-Prediction/blob/main/Zep%20project%20on%20heart%20disease.ipynb) - Includes Exploratory Data Analysis and all algorithms which are used in this project.
- [Heart Disease Prediction.pdf](https://github.com/AnkitaD1998/Heart-Disease-Prediction/blob/main/Heart%20Disease%20Prediction.pdf) - Includes pdf of the presentation of the project.
- [Heart Disease Prediction Report](https://github.com/AnkitaD1998/Heart-Disease-Prediction/blob/main/HEAT%20DISEASE%20PREDICTION%20REPORT.pdf) -  Includes report of the analysis.
# Algorithms
1. K Nearest Neighbor classifier (KNN)
2. Logistic Regression classifier
3. Decision Tree classifier
4. Random Forest classifier
5. Support Vector Machine (SVM) classifier
6. Gradient Boosting classifier
7. XG Boosting classifier
# Conclusion
I have applied seven different types of classification algorithm on my given dataset to know which algorithm good fit for our dataset & gives us the best accuracy. Before applying Cross validation and hyperparameter tuning Gradient Boosting shows highest test accuracy score of 0.870, F1 score is 0.887 and Accuracy is 0.868, but after applying Cross validation and hyperparameter tuning on the Gradient Boosting algorithm it gives test accuracy score of 0.864, F1 score is 0.88 and Accuracy is 0.861 which is almost same than before. As we know that Cross validation and hyperparameter tuning certainly reduces chances of overfitting and also increases performance of model. So we can conclude that before tuning our model worked well so here no needed to apply tuning as such.
