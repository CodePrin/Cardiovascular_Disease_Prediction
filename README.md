# Cardiovascular_Disease_Prediction
In this project, the dataset of ardio_tain.csv is being cleaned and analysed. This dataset is collected from medical examination of various patients to predict the occurrence of cardiovascular disease. It includes information such as age, gender, height, weight, blood pressure and other related information of patient.
Data analysis and visualization with the help of python will be performed to get insight from this data.

![HeartbeatCirculatoryGIF](https://github.com/CodePrin/Cardiovascular_Disease_Prediction/assets/89415614/40ad80b3-0510-44e1-bf1b-d3b7cb99ffcc)


## Table Of Content
* Problem Statement
* Tools
* Files
* Data Features
* Results
* Dataset Information


## Problem Statement
In the course of medical examination, most of the patients were detected with cardiovascular disease. You have to find out the precise medical reasons and insights of having cardiovascular disease by analysing the various features of this dataset.


## Tools 
Used Python 3.11.1 for this project and below given packages:
* Numpy
* Pandas
* Matplotlib
* Seaborn


## Files
This repository contains four files other than README.md file, which are as follows:

* **CardiovascularDiseasePrediction.ipynb:** It is a Jupyter Notebook file containing all the python code, documentation and visualization.  
* **cardio_train.csv:** Dataset file in csv format.
* **CardiovascularDisease_Dataset.zip:** Zip file to extract the main dataset file.
* **requirements:** It is a text file containing all the packages installed during the project.


## Dataset Features
**There are 3 types of input features of this dataset:**
* Objective: Factual information.
* Examination: Results of medical examination.
* Subjective: Information given by the patient.

**All the features of this dataset are as  follows:**
* Age | Objective Feature | age | int (days)
* Height | Objective Feature | height | int (cm) |
* Weight | Objective Feature | weight | float (kg) |
* Gender | Objective Feature | gender | categorical code |
* Systolic blood pressure | Examination Feature | ap_hi | int |
* Diastolic blood pressure | Examination Feature | ap_lo | int |
* Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
* Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
* Smoking | Subjective Feature | smoke | binary |
* Alcohol intake | Subjective Feature | alco | binary |
* Physical activity | Subjective Feature | active | binary |
* Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

 **All the values of the dataset were collected at the moment of medical examination.**


 ## Results
* The age of the patient of this dataset lies inclusively between the age-group of 30 to 65. 
* The age value of patients above 35 is very large and below 35 is very small.
* With the increase in age, the problem of occurring cardiovascular disease is very high. The possibilities are highest above the age of 56.
* Most of the patients in the dataset are women. 65% are women and 35% are men.
* Men are taller than women.
* Weight of men is more than women.
* Most often the systolic blood pressure is high in men above 120, than women.
* Most often the diastolic blood pressure is high in men above 80, than women.
* In the dataset, mostly the height of the patients are in normal range and have no special effect on the occurrence of cardiovascular disease.
* The patients having more weight will have higher chances of having cardiovascular disease.
* The blood pressure increases with age. The patients between the age of 30 to 65 years have an increasing diastolic pressure ranging between 70 to 80 mm Hg and increasing systolic pressure ranging between 110 to 135 mm Hg. 
* In this dataset, approximately 75.5% of patients have normal, 13.4% have above normal and 11.2% have well above normal level of cholesterol.
* Cholesterol level increases with age and most of the patients have normal cholesterol level. The level of cholesterol of patients is above normal mostly at the age of 54 years and well above normal at the age of 60 years. When there is too much cholesterol in the blood, it builds up in the walls of the arteries, causing a process called atherosclerosis, a form of heart disease. The arteries become narrowed and bloodflow to the heart muscle is slowed down or blocked. This can cause chest pain (angina) or a heart attack. That's why high cholesterol level in adults can cause a serious problem.
* High number of patients having normal cholesterol level will have a moderate chance of having cardiovascular disease. But the small number of patients who have a above normal and a well above normal level of cholesterol will have a higher chance of having cardiovascular diesease.
* In this dataset, approximately 85.4% of patients have normal, 7.5% have above normal and 7.2% have well above normal level of glucose.
* Glucose level of most of the patients are normal. The glucose level of patients increases to go above normal and well above normal mostly at the age of 50 years. High blood sugar levels can damage blood vessels and the nerves that control the heart over time, leading to an increased risk of heart diseases.
* In this dataset, approximately 91.2% are non-smoker whereas 8.8% are smokers.
* The patients who don't smoke will have a higher chance of having cardiovascular disease than those who smoke. This could be only possible if the patients who don't smoke are exposed to passive smoking or the environment in which the patient is living or working is polluted (mostly metropolitan cities and industrial areas).
* In this dataset, approximately 94.7% of patient do not intake alcohol whereas 5.3% intake alcohol.
* Most of the patients don't drink alcohol and with increase in age most of the adults don't prefer to drink it.
* It is important to note that some of the patients in this dataset could be alcohol abstainers who previously drank excessively and had undermined their health. After they quit, they call themselves as non-alcoholic and categorized as non-drinkers, which in turn lead to more sick people in the non-drinkers category. That's why, the patients who don't drink alcohol will have higher chance of having cardiovascular disease than those who drink alcohol.
* In this dataset, approximately 80.4% of patient performs regular physical activity whereas 19.6% do not perform regular physical activity.
* Most of the patients are physically active.
* Non-active patients have higher chances of having cardiovascular disease whereas active patients have lower chances of having cardiovascular disease. But the dataset of 'Having cardiovascular disease' of active patients is higher than non-active patients because of the extreme strength-based laborious worklife conditions of the physically active patients. It means that the active patients mostly do high strength-based physical labour without any proper nutrition or guidance. This is also a fact, that this data could be examined from weight-lifters, wrestlers, fighters and atheletes because of their high-strength based work but there is one more fact associated, that these people mostly train themselves with proper guidance, routine and nutrition which decreases there chance of having cardiovascular disease. So that's why the patient of this dataset cannot be concluded as weight-lifters, wrestlers, fighters and atheletes. By observing this analysis, we can assume that this dataset is collected from manual labours because these labours do a lot of strength-based work without proper nutrition and health checkups.
* In this dataset, approximately 51% of patients do not have cardiovascular disease whereas 49% of patients suffers from cardiovascular disease.


## Dataset Information
This "Cardiovascular Disease" dataset was posted on Kaggle by Svetlana Ulianova.
Download link for this dataset is given below:
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset


