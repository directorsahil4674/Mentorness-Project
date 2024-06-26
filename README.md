
# Animated Movie Data Analysis

This project is based on analyzing the movie data which is grouped and discussed based on the different KPIs and Metrics. 

# The Dashboard link: 

### Dashboard Link: https://app.powerbi.com/groups/5906dde9-b47d-4be9-b95c-e3bb444d5d96/reports/09bd541a-b93e-4566-a350-0305b0d571e2/ReportSection?experience=power-bi
## Problem Statement

This Dashboard discusses about the animated movie. We are intended to find the customer preferences based on genres and metrics realted to it. Additionally we are subjected to find the revenue generated by each genre based on the metrics such as vote counts, genres, year of release. 

## KPIs Identified 
The whole project is defined under to major KPIs 
- Audience Preferences 
- Revenue Analysis
Metrics which is a based line of the analysis under the KPIs are 
- vote count by Audience 
- Year 
- Movie genre
- Adult preference (If any)
- Last year vs Current Year Revenue made 

### Steps followed 

- Step 1 : Loaded data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so I selected "column profiling based on entire dataset".
- Step 4 : Added the columns related to the datetime filed by segregating it through 'add column field'. columns such as Month number, Month name.
- Step 5 : Reterived the data back to the report view. Rearranged the columns, identified and applied calculated columns and DAX measures. 
- Step 6 : DAX measures were applied to calculate and apply the identified filters. 
- Step 7 : Nonetheless, all the KPIs were identified using the card and grouped under using the effective charts demonstrating the details of the KPIs. 

# Snapshot of Audience Analysis by Preferences Dashboard (Power BI Service)

![Screenshot 2024-04-12 103000](https://github.com/directorsahil4674/Mentorness-Project/assets/147431382/149eea41-7833-418a-abbb-c747024381d2)

# Snapshot of Attrition by Employee Trunover (Power BI Service)

![Screenshot 2024-04-12 103025](https://github.com/directorsahil4674/Mentorness-Project/assets/147431382/691a57cd-4bde-4c57-bf97-f756b0af1978)

# Some potential insights I got from my analysis listed below:
Insight from Audience Prefereces: 

- The analysis starts from the year 2000 till 2023. 
- The drastic change in audience preference can be seen based on more vote counts, genre preferences based on popularity, and the count of the genre in which the movie is made.  
- The genre can be seen mainly based on family, comedy, adventure and fantasy. 
- Based on the analysis, the audience’s interest increased more from the start of the new decade to the film era. 
- Genres such as Family have 3,877 sum averages in the vote count and popularity of 17,345.12, which changes in the following years; however, it marks the first position. 
- Following it, Adventure with 3,078, comedy with 2,683 and Fantasy with 2,205, respectively. 
- Although action has lately become popular from the year 2016-2017 and marked the 5th position of interest among people. 

Insight from Revenue analyzed: 

- The revenue calculated is a total of $3.30 billion, which includes the years starting from 1918 up until 2023. 
- The key metrics are analyzed based on the runtime and revenue compared to last year's revenue and thus can be modified based on the filters
- The data of Tree Map will change if different visual filters will be applied.
- It is interesting to see in all the years, the United States positions itself as the top 1 country by revenue generated. 
- As we have discussed previously, genres such as Family position themselves to be most voted by people who hold a revenue of nearly $84,468,176,983.00, comedy with $62,159,429,424.00
- Lets dive into more practical scenario by seeing the actual dashboard on Power BI. 
