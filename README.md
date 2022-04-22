# SC1015 Mini-Project (AY21/22 Semester 2)
This project is done in partial completion of the module SC1015 Introduction to Data Science & Artificial Intelligence.

This is done by **SC8 Team 04** which consists of:
1. Choo Jin Cheng (U2121190C)
2. Chua Min Min (U2121126G)
3. Poh Shi Qian (U2122452J)

Date completed: XX April 2022

---
## Real-life Problem
### Stroke can often be caused by unhealthy lifestyle and other health problems. Are there any unconventional causes?
According to the World Stroke Organisation (n.d.), stroke is a "leading cause of death and disability globally". In 2019 alone, there were 6.6 million people who died stroke of varying severity (American Heart Association, 2021).

While age and chronic health conditions like heart diseases are commonly known to increase the chances of a person getting a stroke, there might be unconventional factors leading to a healthy person getting a stroke. Hence, this project aims to uncover, if any, correlations between unconventional factors like marital status and a person's chance of getting a stroke.
<br><br><br>
## Data Science Question
### Do unconventional features help to better predict whether a person will have / already has a stroke?
This is a Classification problem. Our goal is to find out if there is any unconventional feature that makes one more likely to get a stroke.

---
## Dataset
This dataset is extracted from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). It has the following fields:

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
<br>*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
<br><br>

### Unconventional variables
* ever_married
* work_type
* Residence_type

---
## What did we do in this project?
1. Exploratory Data Analysis on the features (graphs, calculations, correlation checks)
> * Plotting of graphs<br>
> * Statistical summaries<br>
> * Simple calculations<br>
> * Correlation checks<br>
2. Data Cleaning and Preparation (removal, replacement, encoding)
3. Post-cleaning Work (correlation checks, feature selection)
4. Machine Learning (k-Nearest Neighbors, XGBoost, Artificial Neural Network, Naive Bayes)
5. Conclusion (answering our question)
<br><br><br>
## New things we tried!
1. **Chi-square test** - this is for categorical features correlation check
2. **One-hot encoding** - this is for categorical features that are non-binary
3. **SelectKBest feature selection** - this is to provide insights on variable importance
4. **Synthetic Minority Over-sampling Technique (SMOTE)** - this is to compensate for our heavily imbalanced data
5. **k-Nearest Neighbors** - model
6. **XGBoost** - model
7. **Artificial Neural Network** - model
8. **Naive Bayes** - model

---
## Conclusion

<br><br><br>
## References:
* American Heart Association (2021). *2021 Heart Disease & Stroke Statistical Update Fact Sheet Global Burden of Disease*. Professional Heart Daily. https://professional.heart.org/-/media/PHD-Files-2/Science-News/2/2021-Heart-and-Stroke-Stat-Update/2021_Stat_Update_factsheet_Global_Burden_of_Disease.pdf
* Bariatric Department at Lafayette General Medical Center (2019). *How Obesity Affects Stroke Risk*. Ochsner Lafayette General. https://ochsnerlg.org/about-us/news/how-obesity-affects-stroke-risk
* WebMD (2021). *Top 10 Causes of Strokes - Risk Factors and How You Can Lower Your Risks*. WebMD. https://www.webmd.com/stroke/guide/stroke-causes-risks
* World Stroke Organization (n.d.). *Learn about stroke*. World Stroke Orgnization. https://www.world-stroke.org/world-stroke-day-campaign/why-stroke-matters/learn-about-stroke
* Wyller T. B. (1999). Stroke and gender. *The journal of gender-specific medicine : JGSM : the official journal of the Partnership for Women's Health at Columbia*, 2(3), 41–45.
