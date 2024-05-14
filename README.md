# Predictive Analysis of Heart Attack Risks Using RapidMiner
The predictive analysis of heart attack likelihood is a pivotal stride towards proactive healthcare management, facilitating early interventions and potentially saving lives. Utilizing historical medical data to develop predictive models is an emergent paradigm that leverages machine learning and data analytics tools to derive insights and support clinical decision-making.

## PROBLEM DESCRIPTION 

The core objective of this project is to develop a robust predictive model using the dataset available at Kaggle which encapsulates key indicators pertinent to heart attack risks. The model aims to accurately predict the likelihood of heart attack occurrences based on a variety of medical and demographic factors. The analytical tool of choice for this endeavor is RapidMiner, known for its efficacy in handling complex data analytics tasks. 

### DATA SOURCE AND COMPOSITION

This project's dataset came from the website Kaggle, which has a number of datasets. This specific dataset contains demographic and medical data that may be useful in estimating the risk of a heart attack.

#### VARIABLES AND FEATURES
Numerous numerical and categorical variables are included in the dataset, including:
Age, sex, and income provide socioeconomic and age-related context through demographic information.
- Medical History: Vital health indicators such as blood pressure, heart rate, diabetes, cholesterol levels, and family history of heart disease.
- Lifestyle Factors: Information on the following lifestyle factors that might affect heart health: smoking, obesity, physical activity, number of hours spent sedentary each day, number of hours slept each day.
Regional and environmental health patterns may be correlated with geographic data, which includes information about the country, continent, and hemisphere.

##### EXPLORATORY DATA ANALYSIS(EDA)
Before going to exploratory data analysis (EDA), We need to download the latest version of the RapidMiner in our system.

###### CHECKING FOR MISSING VALUES 
There are no missing values in the dataset.

###### HISTOGRAM OF THE AGE COLUMN:
 The frequency distribution of the age distribution inside a heart attack prediction dataset. This histogram displays the number of observations by age group. The number of observations varies greatly by age group, with frequencies ranging from 20 to 90 years old.

 <img width="458" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/739ebf85-345d-400c-921e-e6160d0b964a">

####### DIET V/S HEART ATTACK RISK 
<img width="497" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/016db3fe-691d-4a1d-bbc5-5734242e500c">

##### MACHINE LEARNING MODEL:

<img width="468" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/c8e83fc5-f192-48ea-bdaf-69c097d90c11">
<img width="468" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/17b6250e-54db-4899-847a-e2b6cd465f09">

###### RESULTS:

<img width="468" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/a517887f-616b-491e-9062-fcba2cd29486">

<img width="468" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/d83d5df2-bac9-40e1-be05-f530eab2a566">

<img width="468" alt="image" src="https://github.com/VijayKumarMahto/Analysis-of-Heart-Attack-Risks-/assets/98145692/b2d9637d-a3db-4bf8-87cf-55ed73b19216">


###### MODEL ACCURACY:
The KNN model predicts heart attack risk accurately 62.39% of the time throughout the dataset, with an accuracy of 62.39%. The accuracy measure's confidence interval is suggested by the provided margin of error (+/- 1.57%), which implies that the real accuracy of the model may vary significantly within this range.

###### CLASS ACCURACY AND MEMORY:
The precision of the model in forecasting the genuine risk of a heart attack (true 'T') is 58.64%. This indicates that 58.64% of the time, the model is right when it indicates a patient is at risk. With a higher precision of 71.96%, the real 'F' stands for no heart attack risk prediction. For the positive class (patients at risk), the class recall, or sensitivity, is 40.08%. , indicating that the model is able to identify 40.08% of all actual positive cases in the dataset.


###### FINDINGS FROM THE APPLICATION OF DATA MINING :
The data visualization indicated that there was a greater risk of heart attack in men as opposed to women. This was seen in both heart attack risk groups ('0' for no risk and '1' for at risk), with a much larger percentage of men in the 'at risk' group.
People with a reasonably equal distribution of stress levels were shown to be at risk for heart attacks, regardless of their level of stress. This implied that the risk of a heart attack is influenced by stress.
In every diet category, there were more men than women who were at risk of having a heart attack. This difference was most noticeable when it came to those who were classified as following a "Healthy" diet.
With an accuracy of 62.39%, the KNN model demonstrated its capacity to classify the risk of a heart attack using the provided information. The accuracy in identifying the likelihood of a heart attack was 58.64%, while the accuracy in identifying the absence of risk was 71.96%. The model's sensitivity to identifying true positive cases was demonstrated by the recall for positive cases (patients at risk), which was 40.08%.
