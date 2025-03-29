**Project :** Hospital Rating Classification :

**Overview :** The Centers for Medicare and Medicaid Services(CMS) is an US Agency of Department of Health and Human Services.
This includes insurance programs such as Medicare, Medicaid, and the Children’s Health Insurance Program (CHIP). 
CMS also plays an important role in collecting and analyzing data with the goal of improving efficiency and equity
in the healthcare system. In the current project, you will be analyzing CMS data on hospital quality. 
CMS rates hospitals in US on a scale of 1-5 with objective of making it easier for patients and consumers to compare the quality of services offerd by hospitals.
CMS conducts survey's each year and keep on updating the ratings to reflect the current services being delivered by each hospitals.

**Objective of this project**
This project is focused on developing an approach to calculate hospital ratings and using it to identify areas of improvement for hospitals.

Here's a quick overview of the columns available in the data set.
**Hospital Demographic Information**: This includes Provider ID (or, in other words, the Hospital ID), Hospital Name, Zip, Area, State, etc.
**Hospital overall rating:** Overall rating of the hospital. By default, CMS rates hospitals on ratings 1-5.
**Hospital Quality Information:** These are the columns that describe the scores received by hospitals based on different quality measures. 

These quality measures as defined by CMS (as per the year when the data was collected) are as follows:
   - Morality
   - Safety of Care
   - Readmission
   - patience Experience
   - Effectiveness of care
   - Timeliness of care
   - efficienct use of medical imaging
Qualitative measures have been quantified in 2 ways:
   - measure national comparison
   - Sub measure level information

                                                **Following tasks have been performed in python file.**

1. Understanding of data - includes basic check of quality of data and columns to understand key variables or important columns.
 Understanding of how the hospital rating is distributed etc..

2. Built Machine Learning Models by applying some key steps before building the models. 
       - Logistic regression
       - Decision Tree Classification
       - Knn Classification
       - Hyper parameter tuning using GridSearh CV
       - Built Neural Network
       - calculated the misclassification costs post model performances.
     
   

