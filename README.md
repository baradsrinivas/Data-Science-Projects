Project - Mobile App efficacy.

Overview: This Project is to study the customers behaviour of using mobile application. a poorly designed application is unlikely to result in increased revenue and may hurt the business.
          This case study is done for a hotel chain "Smith Hotels" with properties including full-service hotels and resorts is considering whether to push a newly built app to its
          customers.
          
Objective : The objective of this case study is to get a deeper understanding of the impact of the mobile app will have on customers purchase behaviour.

Experiment : Company had conducted a live test to few of its loyalty customers to test the behaviour and recorded the same. 


                                                                    Experiment Design

Control Group : 

Number of customers: 2000
Before: At the beginning of the experiment, the spending behavior of all the customers in the control group was recorded for one-year	Before: At the beginning of the experiment, the spending behavior of all the customers in the treatment group was recorded for one-year

Treatment Group: 
Number of customers: 2000 
Treatment: No changes were introduced to the control group	Treatment: A mail was sent to all the customers in the treatment group with a link to download the beta version app. 
After: The control group was tracked for another year, and their spending behaviors were recorded.	After: All the customers in the treatment group started using the app, and their spending behavior was recorded for another year.

The project document contains Python file which consists of following aspects.
     - Data preparation and Wrangling
     - Exploratory Data Analysis 
            - Univariate Analysis 
            - Multivariate Analysis
    - Statistical Analysis 
         - After-Only design
              To determine the treatment effect of customers’ adoption of the app on their spending with the hotel chain, construct a pivot table of average Spending broken up by Adopt                and Post. What is the difference between the treatment and control groups’ spending in the Post =1 period? This is the treatment effect, assuming the experiment is of an 
              Is the above treatment effect statistically significant? Perform the necessary hypothesis test and construct a 95% confidence interval for the difference. Take the level                 of significance as 0.05

        - Before-After design
              Constructed a new DataFrame, where for each customer, you have a new variable, which is the difference in spending between the Post = 1 and Post=0 periods.
              Computed the average difference between those with Adopt = 1 and those with Adopt = 0 in both the Post = 1 and Post = 0 periods. Call these differences Difference1 (i,e,                 the average difference in spending between Post = 1 and Post = 0 periods for customers with Adopt = 1),  and Difference0 (i,e, the average difference in spending between                 Post = 1 and Post = 0 periods for customers with Adopt = 0). Compute the difference between these two differences as Difference1 – Difference0. This is the treatment                     effect in the Before-After design. 
              Is the above treatment effect statistically significant? Similar to the previous step, perform the necessary hypothesis test and construct a 95% confidence interval for                  the difference in differences.Take the level of significance as 0.05
     
Executive Summary : Concluded based on the Analysis which can be found in the executive summary file.
