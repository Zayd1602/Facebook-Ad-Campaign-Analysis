<h1>Facebook Ad Campaign Analysis using Power BI <img width=125 align=right src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white"></h1>
   
Regularly analyzing the advertisement metrics helps us determine if we are getting a positive return on investment from our advertisement campaigns. 

In this project we will learn how does the advertisements effect people with different age range, gender and date of the month the advertisement campaign is run. We will see various interactive visuals of the data obtained from the data provided by facebook for the advertisement campaigns run by some company.

These visuals can help the marketers to target the audiences which are more susceptible to buy or take a look at the product offered by the company. It will significantly reduce the time taken by the medical professional to determine the patients’ problems. Analyzing the advertisement campaigns can not only reach more audiences, but also save a lot of money on those advertisements by targeting the interested audience.

The huge volume of data is used to make decision which is more accurate than intuition. Thus, the trends, patterns, and outliers even within large data sets can be identified fast.
   
## Problem Statement

Create a Dashboard using Facebook leads and campaigns data from a kaggle data set and analyze camapaigns with best recommmended changes to improve conversion rates across products

## Solution

Power BI is an interactive data visualization software that is responsible for creating, striking, engaging, and meaningful data visualizations that can help to break down even the most complex and convoluted problems into manageable component parts, giving businesses a new level of insight into how to change/modify their approach their target  while succeeding with their strategic goals.

## Description

Here, I’ve created a Dashboard for the dataset and recommended some measures to improve conversion rates. 

We can see that the Dashboard has three Plots, Key influencers and two slicers.

<details><summary><b>Approved Conversion, Amount Spent and Clicks by Age Range and Campaign Name Plot</b></summary> 

<img align=right width=330 src="https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Approved-Conversion-Amount-SPent-and-Clicks-by-Age-Range-and-Campaign-Range-Plot.png">
   
In this visual, we see a Line and clustered column chart which shows us the Age-Range vs. Approved Conversion plot with the lines representing the Amount-Spent and Clicks based on the Age-Range.
</details>

<details><summary><b>Total Conversion, Approved Conversion and Clicks by Day Plot</b></summary> 

<img align=right width=330 src="https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Total-Conversion-Approved-Conversion-and-Clicks-by-Day-Plot.png">
   
In this visual, we can see a Line chart which shows us the Day vs. Total-Conversion and Approved-Conversion plot with the Clicks being the secondary value. 
</details> 


<details><summary><b>Total Conversion Approved Conversion and Impressions by Day Plot</b></summary> 

<img align=right width=330 src="https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Total-Conversion-Approved-Conversion-and-Impressions-by-Day-Plot.png">

In this visual, we can see a Line chart which shows us the Day vs. Total-Conversion and Approved-Conversion plot with the Impressions being the secondary value. 
</details> 

<details><summary><b>Key Influencers</b></summary> 
<img align=right src='https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Key-Influencers.png'/>
   
   1. The key influencers tab displays the key factors affecting the value selected.
   2. On the other side there is a scatter plot showing the distribution of the selected factor.
   3. We can see a ring around each influencer’s bubble, which represents the approximate percentage of data that influencer contains. The more of the bubble the ring circles, the more data it contains.
   4. We can select different factors to observe their effect on Approved Conversion.   
</details>
   
- The visualizations are filtered between Campaign Names and Gender.
- Slicers are a way of filtering. They narrow the portion of the dataset that is shown in the other report visualizations. 
  So, I’ve made two slicers one for filtering from the different campaigns, i.e. C-1, C-2 and C-3, and another for filtering from different gender or both.

<div align=center>
   
| <img align=center src='https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Campaign-Name-Slicer.png'/> | <img align=center src='https://github.com/Zayd1602/Facebook-Ad-Campaign-Analysis/blob/main/Gender-Slicer.png'/> |
| --- | --- |

</div>
   
## Conclusion

- From the plots it is clear that the younger audience are more susceptible to buy the product shown in the advertisement. So, the amount allocated to display advertisements should be more focussed on targeting the younger audience to get more conversions.

- It can be seen that for the female audience, the advertisement campaigns are more effective during the starting days of the campaign and on the weekends (26-27 Aug 2017 are Saturday and Sunday respectively). The female audience are more susceptible to show their interest in the product during the days as discussed.

- For the male audience, the advertisement campaigns are more effective during the weekdays. The male audience are more susceptible to show their interest in the product during the days as discussed.

- So, for a better reach and conversions, the advertisements should be intensive during the early days of the campaign and on the weekends for females and on weekdays for males. Hence, the amount spent on the campaigns for female and male audience should be spent on the particular days as discussed to get more conversions.

- Also, the number of impressions on a day is directly proportional to the number of conversions on that day.


<div align = center> 
<!-- <img width=800 src="https://github.com/Zayd1602/FRT-Project-using-PowerBI/blob/main/Overall-visual.gif"> -->
</div>

<br>**Demo Video URL:** [https://youtu.be/QpFf__Gq4xQ](https://youtu.be/Ih6YxZ5ZXyM)</br>

## About the dataset

The following are the features we'll use to predict our target variable (approved conversion).
The data used in this project is from an anonymous organisation’s social media ad campaign.
There are 15 attributes:
<details><summary><b>Click to know more </b></summary>   

1. **ad_id**: an unique ID for each ad.

2. **reporting_start**: the start of the reporting of the advertisement's reach.

3. **reporting_end**: the start of the reporting of the advertisement's reach.

4. **campaign_id**: an ID associated with each ad campaign of XYZ company.

5. **fb_campaign_id**: an ID associated with how Facebook tracks each campaign.

6. **age**: age of the person to whom the ad is shown.

7. **gender**: gender of the person to whim the add is shown

8. **interest(1,2,3)**: a code specifying the category to which the person’s interest belongs (interests are as mentioned in the person’s Facebook public profile).

9. **impressions**: the number of times the ad was shown.

10. **clicks**: number of clicks on for that ad.

11. **spent**: Amount paid by company xyz to Facebook, to show that ad.

12. **total_conversion**: Total number of people who enquired about the product after seeing the ad.

13. **approved_conversion**: Total number of people who bought the product after seeing the ad.

</details>

  >Note: Names of the columns were changed while transforming the data in Power BI.

## Sources

- Dataset: [https://www.kaggle.com/madislemsalu/facebook-ad-campaign](https://www.kaggle.com/madislemsalu/facebook-ad-campaign) Kaggle 

- Dataset factors explanation: [https://www.kaggle.com/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/data](https://www.kaggle.com/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/data)
Kaggle

<!--  - Vector art - [https://www.freepik.com/vectors/people](https://www.freepik.com/vectors/people)
(People vector created by katemangostar - www.freepik.com) -->
