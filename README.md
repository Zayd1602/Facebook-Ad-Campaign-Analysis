<h1>Facebook Ad Campaign Analysis using Power BI </h1>
<!--   <img width=125 align=right src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white"></h1> -->
   
<!-- Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 17.9 million lives each year 
The effects of behavioural risk factors may show up in individuals. Identifying those at highest risk of CVDs and ensuring they receive appropriate treatment can prevent premature deaths. [(WHO)](https://www.who.int/health-topics/cardiovascular-diseases)
   
In this project we will learn how the disease affects different patients with respect to their sex or age. We will see various interactive visuals of the data obtained from the diagnosis of the patients and if they have the disease or not.

These visuals can help medical professionals to determine prescribing various medical treatments and treatment measures to the patients comparing their diagnosis data with our analysed data. It will significantly reduce the time taken by the medical professional to determine the patients’ problems.

The huge volume of data is used to make decision which is more accurate than intuition. The use of analytics in healthcare improves care by facilitating preventive care. Thus trends, patterns, and outliers even within large data sets can be identified fast. -->
   
## Problem Statement

Create a Dashboard using Facebook leads and campaigns data from a kaggle data set and analyze camapaigns with best recommmended changes to improve conversion rates across products

## Solution
<!-- 
<img align=right width=330 src="https://github.com/Zayd1602/Heart-Disease-Analysis-using-PowerBI/blob/main/Doctors-Vector-Art.jpg"> -->

Power BI is an interactive data visualization software that is responsible for creating, striking, engaging, and meaningful data visualizations that can help to break down even the most complex and convoluted problems into manageable component parts, giving businesses a new level of insight into how to change/modify their approach their target  while succeeding with their strategic goals.

<br></br>

## Description

Here, I’ve created a Dashboard for the dataset and recommended some measures to improve conversion rates. 

We can see that the visual has two tabs, namely – Key influencers and Top segments and two slicers.

<details><summary><b>Key Influencers</b></summary> 
<!-- <img align=right src='https://github.com/Zayd1602/Heart-Disease-Analysis-using-PowerBI/blob/main/Key-Influencers.png'/> -->
   
<!--    1. The key influencers tab displays the key factors affecting the value selected. In our case, the top factor that results in positive diagnosis of Heart Disease is Exercise Induced Angina. 
   2. On the other side there may be a column chart or a scatter plot showing the distribution of the selected factor.
   3. We can see a ring around each influencer’s bubble, which represents the approximate percentage of data that influencer contains. The more of the bubble the ring circles, the more data it contains.
   4. We can select different factors to observe their effect on the diagnosis of disease.

</details>
<details><summary><b>Top Segments</b></summary>   
<!-- <img align=right src='https://github.com/Zayd1602/Heart-Disease-Analysis-using-PowerBI/blob/main/Top-Segments.png'/> -->
   
   1. The top segments tab displays the top segments that are identified by Power BI from the dataset for the metric selected.
   2. It initially shows the overview of all the segments. These segments are ranked by the heart disease detected (True/False) and the number of patients (population size). The higher the bubble the more the percentage of disease detected (True/False). 
   3. The size of the bubble represents the number of patients within the segment.
   4. We can select a bubble which then displays the details of the segment. -->
   
</details>
   
<!-- - The visualizations are filtered between Disease Detected to be True or False.
- Slicers are a way of filtering. They narrow the portion of the dataset that is shown in the other report visualizations. 
  So, I’ve made two slicers one for filtering from the range of age, and another for filtering from different gender or both. -->

<div align=center>
<!--    
| <img align=center src='https://github.com/Zayd1602/Heart-Disease-Analysis-using-PowerBI/blob/main/Age-Slicer.png'/> | <img align=center src='https://github.com/Zayd1602/Heart-Disease-Analysis-using-PowerBI/blob/main/Gender-Slicer.png'/> |
| --- | --- | -->

</div>
   
## Conclusion
The advertisements should be intensive during the early days of the campaign, on the weekends for females and on weekdays for males. Hence, the amount spent on the campaigns for female and male audiences should be spent on the particular days as discussed to get more reach and conversions.
Also, the number of impressions on a day is directly proportional to the number of conversions on that day.


<div align = center> 
<!-- <img width=800 src="https://github.com/Zayd1602/FRT-Project-using-PowerBI/blob/main/Overall-visual.gif"> -->
</div>

<br>**Demo Video URL:** [https://youtu.be/QpFf__Gq4xQ](https://youtu.be/Ih6YxZ5ZXyM)</br>

## About the dataset

The following are the features we'll use to predict our target variable (heart disease or no heart disease).
There are 13 attributes:
<details><summary><b>Click to know more </b></summary>   
<!-- 
   1. **age**: age (in years)

2. **sex**: gender (1 = male; 0 = female)

3. **cp**: chest pain type
There are three criteria for classifying different types of angina (chest pain) under three categories (according to this NCBI paper: [https://pubmed.ncbi.nlm.nih.gov/20494662/](https://pubmed.ncbi.nlm.nih.gov/20494662/)
_Location_: Chest pain occurs around the substernal portion of the body
_Cause_: Pain is experienced after induction of emotional/physical stress
_Relief_: The pain goes away after taking nitroglycerine and/or a rest

   - **0**: normaltypical angina (all criteria present) 
   - **1**: atypical angina (two of three criteria satisfied)
   - **2**: non-anginal pain (less than one criteria satisfied)
   - **3**: asymptomatic (none of the criteria are satisfied)

4. **trestbps**: resting blood pressure (in mmHg, upon admission to the hospital)

5. **chol**: serum cholesterol in mg/dL

6. **fbs**: fasting blood sugar > 120 mg/dL (likely to be diabetic) 1 = true; 0 = false

7. **restecg**: resting electrocardiogram results
   - Value 0: normal
   - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) - more on the effects of these below
   - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8. **thalach**: maximum heart rate achieved

9. **exang**: exercise induced angina (1 = yes; 0 = no)

10. **oldpeak**: ST depression induced by exercise relative to rest (in mm, achieved by subtracting the lowest ST segment points during exercise and rest)

11. **slope**: the slope of the peak exercise ST segment, ST-T abnormalities are considered to be a crucial indicator for identifying presence of ischaemia (according to this research paper on NCBI: [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7027664/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7027664/)
    - 0: upsloping
    - 1: flat
    - 2: downsloping

12. **ca**: number of major vessels (0-4) colored by fluoroscopy. Major cardial vessels are as goes: aorta, superior vena cava, inferior vena cava, pulmonary artery (oxygen-poor blood --> lungs), pulmonary veins (oxygen-rich blood --> heart), and coronary arteries (supplies blood to heart tissue).
Radioactive dye is introduced to the body followed by x-ray imaging to detect any structural abnormalities present in the heart. The quantity of vessels colored is positively correlated with presence of heart disease.

13. **thal**: 0 = normal; 1 = fixed defect (heart tissue can't absorb thallium both under stress and in rest); 2 = reversible defect (heart tissue is unable to absorb thallium only under the exercise portion of the test)
Thallium testing is a method where the radioactive element thallium (Tl) is introduced to the body through an IV injection, followed by nuclear imaging of the heart with a gamma camera which reveals structural issues and abnormalities of the heart by showing whether if the isotope was absorbed by heart tissue under high (exercise) and low (rest) stress conditions.

14. **target**: 0 = no disease, 1 = disease -->

</details>

  >Note: Names of the columns were changed while transforming the data in Power BI.

<!-- ## Sources

 - Dataset - [https://drive.google.com/drive/folders/1M5z7z1NmWar7y1eFs67orfjqHL0iSViL](https://drive.google.com/drive/folders/1M5z7z1NmWar7y1eFs67orfjqHL0iSViL)
(iNeuron) 

 - Dataset factors explanation – [https://www.kaggle.com/onatto/predicting-heart-disease-a-detailed-guide](https://www.kaggle.com/onatto/predicting-heart-disease-a-detailed-guide)
(Kaggle)

 - Vector art - [https://www.freepik.com/vectors/people](https://www.freepik.com/vectors/people)
(People vector created by katemangostar - www.freepik.com) -->
