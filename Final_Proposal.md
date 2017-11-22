---
  output:
  html_document: default
---

## Contributing Factors in Employee Turnover & How to Reduce It
#### (A Springboard Capstone Proposal) 
###### - For a made-up client, based on a simulated dataset in HR Analytics -
##### By Doan Tran
  
  ***
  
#### **The Problem**
  *What is the problem I want to solve?*
  
  The days of an employee working and staying at one company for their entire career have been long over. High turnover rates can be disruptive to operations and expensive due to retraining costs. Many employees terminate from their positions, even when they are well paid and highly satisfied. This project will examine the correlations of reasons employees staying at their company or leaving their jobs.

***
  
#### **The Client**
  *Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn’t have otherwise?*
  
  My client is Jack Bezos, the CEO of Aliba-Mazon, an online source for manufacturers who sell at wholesale, an online retailer of goods and products, and a delivery company promising 2 day shipping to its annual suscription member clients. Mr. Bezos would like to reduce the turnover rate at his company and retain his best employees. He will enable new benefits and incentives and enforce new policies to avoid factors that contribute to higher turnover.

***

#### **The Data**
*What data are you going to use for this? How will you acquire this data?*

The dataset for this project comes from Kaggle: <https://www.kaggle.com/ludobenistant/hr-analytics>

|Variable|Description|
|----|----|
|Satisfaction_Level| Average satisfaction score based on periodic employee survey completed (0 being lowest score and 1 being highest score)
|Last_evaluation| Average score of evaluation (0 being lowest score and 1 being highest score)
|number_project| Number of projects assigned to employee (will assume projects per month)
|Average_monthly_hours| Average of monthly hours that employee works
|Time_spend_company|Range is 2-10. (Will assume that units are in years.)
|Work_accident| Has the employee ever had an injury at work? Expressed in true (1) or false (0)
|Left| Has the employee termed from the company? If termed/yes, then expressed in true (1); else false (0)
|promotion_last_5years| Was the employee promoted in the last 5 years? Expressed in true (1) or false (0)
|Department| The last department that employee worked in
|Salary| Expressed in "low", "medium", or "high" range


#### **The Approach**
*In brief, outline your approach to solving this problem (knowing that this might
change later)*

My approach can be broken out into the following sections:

1. Data wrangling and cleaning
+ Take into account any missing values or outliers
+ Is there any "weird" or "non-fitting" data? 
+ Can I input any values into fields that 

2. Exploratory Data Analysis
+ Use a combination of inferential statistics and data visualization to identify trends between the different fields
+ Determine potentially significant variables
+ Identify trends and correlations between variables
3. Machine Learning
+ Dig deeper into the correlation between how the correlations can be used to retain the best employees and reduce turnover among all employees.
4. Data visualization and report out
+ Compile all relevant information into deliverables (listed below)

***

#### **Deliverables**
*What are your deliverables?*

My deliverables will consist of a report on my findings, a slide deck, and the corresponding R code used in analyzing the data. In addition, the aforementioned deliverables will be submitted and published on GitHub. A report and recommendations presentation will be given to CEO Jack Bezos.

