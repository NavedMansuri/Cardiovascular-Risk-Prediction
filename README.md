# Cardiovascular-Risk-Prediction
![images (1)](https://user-images.githubusercontent.com/75332345/208301232-8c469b44-524d-4460-8454-3b8e8d2ea818.png)


# Project Summary 
Several health conditions, your lifestyle, and your age and family history can increase your risk for heart disease. These are called risk factors. About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Some risk factors for heart disease cannot be controlled, such as your age or family history. But you can take steps to lower your risk by changing the factors you can control.

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.

The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 3,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.


# Data discription
Demographic:

Sex: male or female("M" or "F")

Age: Age of the patients (Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

Education: The level of education of the patient (categorical values - 1,2,3,4)

Behavioral:

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
Medical( history):

BP Meds: whether or not the patient was on blood pressure medication (Nominal)
Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)
Tot Chol: total cholesterol level (Continuous)
Sys BP: systolic blood pressure (Continuous)
Dia BP: diastolic blood pressure (Continuous)
BMI: Body Mass Index (Continuous)
Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
Glucose: glucose level (Continuous) Predict variable (desired target)
10-year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)
Objective: Building the classification model which best predict whether the patient has a 10-year risk of future coronary heart disease (CHD).
