# School-District-Analysis

## Overview of Project
Assisting chief data scientist Maria with analyzing school distict data. Data provided is in the resource folder as new full student data as a csv. The analysis will be on all standadized testing and will be providing visual insights and performace trends.

## Results
The data was cleaned and verified for null values and any duplicates within the data set. The analysis was to find any correlation of the standardized test results based on the school types(Public vs Charter) budget. The analysis shows the the average school budget for public schools was 38k more than charter schools. With having the school budget average we can now dive in and see how that may effect the school test score average.
![](Images/School%20Budget.png)

Charter schools have a better standardized average in both reading and math scores even with a lower school budget.
![](Images/Avg%20math%20score%20vs%20school%20type.png)
![](Images/avg%20reading%20score%20vs%20school%20type.png)

To give a further understanding on the difference in Charter vs Public schools I hae also included a grade break down from the 9th to 12th grade. This will give an understanding of the shortcoming of each school type and where we can improve.
![](Images/School%20type%20grades%20math%20and%20reading%20score.png)

As shown above the Charter schools has a spike in standardized scores during the 11th grade and out paces Public schools by 9% in math and 8% in reading scores. However the opposite would happen during the 12th grade and Public schools would out pace Charter schools by 4% in math and 3% in reading. 

## Analysis that may be useful
Including the the school type with the school name in the student count would help give a better understanding of how the budget is utilized.  

## Challenge Reflection.
During this module I utilized pandas functions to analyze the given data set. Some of the more familiar coding were mean(), min(), and max() which were easy to grasp and understand. Utilizing iloc and loc were easier once I understood that they both get a row and column but in a different way. I also grouped the school types by using groupby function. This challenge was fun however I need to work on spell checks when typing in the code that caused me alot of wasted time. 
