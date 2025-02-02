Description:
● Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.
Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common 
event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

● People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes,
hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.


Domain: Healthcare
Domain Analysis:
There are 13 columns in the lables dataset, where the patient_id column is a unique and random identifier and all features are described in the section below.
slope_of_peak_exercise_st_segment (type: int):
         the slope of the peak exercise ST segment, an electrocardiography read out indicating quality of blood flow to the heart
thal (type: categorical):
         results of thallium stress test measuring blood flow to the heart, with possible values normal, fixed_defect, reversible_defect
resting_blood_pressure (type: int):
        resting blood pressure
chest_pain_type (type: int):
       chest pain type (4 values)
num_major_vessels (type: int):
      number of major vessels (0-3) colored by flourosopy          
fasting_blood_sugar_gt_120_mg_per_dl (type: binary):
    fasting blood sugar > 120 mg/dl
resting_ekg_results (type: int):
    resting electrocardiographic results (values 0,1,2)
serum_cholesterol_mg_per_dl (type: int):
  serum cholestoral in mg/dl
oldpeak_eq_st_depression (type: float):
   oldpeak = ST depression induced by exercise relative to rest, a measure of abnormality in electrocardiograms
sex (type: binary):
   0: female, 1: male
age (type: int):
   age in years
Exploration of dataset
The attributes of the dataset utilized (risk factors of heart attack) are discussed below:

Age (age):
This is a highly crucial risk factor for the occurrence of heart attacks because the risk of getting heart attacks can double as age increases. In adults, the fatty streaks indicative of coronary artery disease starts to develop and it is proven that more than 80% cases of heart attacks due to coronary heart disease are in patients aged 65 or above.

Sex (sex):
It has been proven that there is a higher risk of heart attack in men compared to women aged 50 or less.17 After the menopause in women, there is a debate of equal risk of heart attack in both men and women. The disease of diabetes in women increases the risk of a heart attack.

Chest pain (cp):
This happens when the muscle of the heart doesn’t get enough blood with oxygen and is called angina. The feeling of squeezing or high pressure builds up in the chest and an uncomfortable feeling in shoulder, jaw, back, or neck can also develop along with the feeling of indigestion in angina. The pain can be felt in the hands. Different types of Angina include stable angina, pectoris, unstable angina, prinzmetal angina, and microvascular angina.

Blood pressure ():
Arteries can be affected by high blood pressure. This can occur because of different reasons like imbalanced cholesterol, high sugar, obesity etc. which can enhance the risks.

Cholesterol (chol):
Arteries again can get affected due to imbalanced or bad cholesterol. It narrows the arteries especially the low-density lipo-protein cholesterol. Another cause is the blood fat i.e., triglycerides with high levels of cholesterol which can also enhance the risk of heart attacks. So, it is advisable to maintain good cholesterol to lower the risk of a heart attack.

Fasting blood sugar (fbs):
High blood sugar can become a cause of a heart attack. It may happen due to lower hormone production by the pancreas or no response to insulin in the body.

Resting Electrocardiographic (restecg):
For medium to high risk of heart attack, the present scenario is not sufficient to understand the screening disadvantages. For those having less risk of disease, the screening harmful effects including a rash or irritation on skin can balance up with exercise.

Heart rate (thalach):
The increase in the heart rate with the enhanced risk of heart disease is being parallelized with risk increment with blood pressure enhancement.23It is proven in research25that if the heart rate increases by 10 bpm, then the chances of cardiac death increase by 20%. This is also the same with the enhancement in the blood pressure of 10 mm Hg.

Angina (exng):
The discomfort from Angina which is an Exercise-induced makes the person feel gripped, squeezed and tight which can carry from mild toserious. The pain is usually felt in the chest’s center and it can spread up in the shoulders, back, jaw, arm or neck. Angina plays a crucial role in identifying coronary disease which makes it worthwhile to consider it a separate category for analysis.

Thalium Stress Test (thal):
Duration of the segment is very important because it needs to be checked that after peak stress, the recovery is happening constantly or not with a positive treadmill test. The abnormal values come under the downslope of depression with less than or equal to 1 mm with 60 to 80 ms. The equivocal tests i.e., with up-sloping segments are also there in the exercise.

Aim of the project :
                    * our aim is to predict the binary class heart_disease_present, which represents whether or not a patient has heart disease.
                    •	0 represents no heart disease present
                    •	1 represents heart disease present
