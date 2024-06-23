# Data Professional Survey Dashboard


## Problem Statement

This interactive dashboard helps us understand about the individuals working in the data field and how do they find it working  in this industry, we take their opinions about various aspects about  this industry and what are the skills they are using for their profession,their salaries,location and their level of satisfaction in different aspects.

This project helps us to get an overview of the field we work or aspire to work in and therefore might be helpful in navigating our career.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : First start by deleting the unwanted columns based on the dashboard elements you have decided to project,then clean the columns that will be required to be used since salary is in an irregular range format split the columns in a way to seperate the numbers and replace alphabhabets or symbols (i.e k,-) with null to get minimum and maximum of the slalry range and create a custom column and calculate the average Salary using the  function.
([#"Q3 - Current Yearly Salary (in USD) - Copy.1"]+[#"Q3 - Current Yearly Salary (in USD) - Copy.2"])/2)
- Step 5 : Commence further data cleaning and transformations in power query like cleaning the data in required columns for example :the job title had too many jobs related to other fields and therefore many jobs that simply classify as ithers use the split columns to seperate the "other" word and delete the uneceesary columnn formed
![Poweer query cleaning](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/2d04ff00-016b-4a8c-a381-23c4dca10c25)

- Step 6 :Once the data has been cleaned check the column data types and match the correct data type and also I like to rename the columns with suitable names that help in making the dashboard and help understand the data more easily.
- Step 7 :Start by first inserting a text box and sizing it preperly to add the title of the dashboard.

- Step 8 : Then Add two card visuals one to depict the count of particpants and also the participants of the field selected in other visualizations.The second card depicting the average of participants.
![Cards](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/c869fb82-2272-4bc4-9283-c93ac86f9024)

- Step 9 : A stacked bar chart is added to the visualization with the job title as legends that represents the current job title of the survey participants.
![Jobs Stacked Bar chart](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/679541b5-f247-4d1c-b15a-b7209278ec66)  

- Step 10 : Then followed by a stacked column chart to represent the programming language used by the professionals
![Language Stacked Column Chart](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/2490d729-e5a8-459f-aa7e-969ab9144cb6)

- Step 11 : A donut chart is added to represent the gender of the survey particpants.
![Gender Donut Chart](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/0c8814fa-fc4e-4714-8857-d4ab1b618acb)
  


- Step 12 : Now add a tree map to navigate the country of origin of the participants.
![Countries treemap](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/20797bbb-2b8a-444c-b782-cb7004aa8bbd)

- Step 13 : We finish our visualizations by adding to gauge visuals one depicting the satisfactory levels in work life balance on a scale of 1 to 10. And the other gauge visual showing satisfactory level with the current salary.
![Satisfactory Gauges](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/3ed1469a-d06e-4ac2-81ad-8699307b121c)





 
 # Report Snapshot (Power BI DESKTOP)

 
![Power BI Dashboard](https://github.com/rahulshivanshbagwar/Data_Survey-_PowerBI_Dashboard/assets/173008519/6bd3a8f9-ee3b-4ed7-b57a-d6b735824147)


# Insights

A single page report was created on Power BI Desktop 

Following inferences can be drawn from the dashboard:

### Country with the most Number of Participant = United States Of America

### Average Age of Participants =29.87

### Job title that has the most salary= Data Scientist
### Most used programming language =Python 
### Average Satisfactory level of the particpantswith their work life balance= 5.74/10
### Average Satisfactory level of the particpantswith their salaries = 4.27/10
### Gender Composition of the Participants= 49.2% Male and 50.8% Female 
