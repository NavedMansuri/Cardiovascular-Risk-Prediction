# Cardiovascular-Risk-Prediction

![AdobeStock_241906878_optimised](https://user-images.githubusercontent.com/75332345/209083547-591d8da2-8e82-453e-9ef7-eee3066f0e4b.jpg)



# Project Summary 
Several health conditions, your lifestyle, and your age and family history can increase your risk for heart disease. These are called risk factors. About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Some risk factors for heart disease cannot be controlled, such as your age or family history. But you can take steps to lower your risk by changing the factors you can control.

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.

The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 3,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.


# Data discription
Demographic:

* Sex: male or female("M" or "F")
* Age: Age of the patients (Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
* Education: The level of education of the patient (categorical values - 1,2,3,4)

Behavioral:

* is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
* Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

Medical( history):

* BP Meds: whether or not the patient was on blood pressure medication (Nominal)
* Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
* Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
* Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)
* Tot Chol: total cholesterol level (Continuous)
* Sys BP: systolic blood pressure (Continuous)
* Dia BP: diastolic blood pressure (Continuous)
* BMI: Body Mass Index (Continuous)
* Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
* Glucose: glucose level (Continuous) Predict variable (desired target)
* 10-year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

* Objective: Building the classification model which best predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

# EDA

* Dependent variable(Ten year CHD) is binary, its only consist two values 0 or 1.​
* Ten year CHD is imbalanced with 15% of risk CHD.
* Female are more compare to male's. ​
* Equally number of smockers.​
* Most people are education level 1.
* Very less number of people having past blood pressure and hark stoke.​
* 1000+ people having hypertension.​
* A few peoples suffering from diabetes.​
* Ages of 45 and 65 have the highest risk of acquiring heart disease​
* Cardiovascular heart disease affects slightly more men than women.​
* Cardiovascular heart disease affects nearly equal numbers of smokers and non-smokers.​

# ML Model

![ml classification ](https://user-images.githubusercontent.com/75332345/209082616-aebbfeb1-db14-4919-84bf-18d5ffbeb8ba.png)

# Conclusions

* we trained 5 Machine Learning models, and hyperparameter adjustment was utilised models to increase model performance.​

* The training dataset was oversampled using SMOTE to reduce bias on one outcome, missing values were handled, feature engineering, and feature selection were performed.​

* Cardiovascular heart disease affects a similar number of smokers and non-smokers.​

* Age, total cholesterol, systolic blood and diastolic blood pressure, BMI, heart rate, and glucose are the main factors in determining a person's 10-year chance of having cardiovascular heart disease.​

* The K Nearest Neighbour is proved to be best algorithms can be used for the risk prediction of Cardiovascular heart disease.​

* We chose the oversampling technique because the data provided to us had fewer records. But since there will be a lot of unbalanced and large amounts of health data, we can try to work on cost-sensitive learning, which, rather than changing the data records, only gives more weight to the minority and focuses on the individuals at high risk for heart disease.



