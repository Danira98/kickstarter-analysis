# **Kickstarting with Excel:** ***An Analysis of Kickstarter Campaigns.***

## Overview of Project

 In this project, we analyse the data from kickstarter campaigns provided by Louise to discover if there are trends in each industry as well as narrow down which campaings have been the most successful and what came in to play to help its success.

### Purpose

The purpose of this project is to find trends in each industry, focusing on the Theater industry specificallly,as well as narrow down which campaigns have been the most successful based on the countries, launch dates, the estimated goal and the pledged quantity obtained, and launch date.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

When the outcomes are analyzed based on launch date,we can see that in the industry of theater, it was the most succesful during the month of May followed closley by the months of June and July.

The following chart showcases the amount of succesful, failed and canceled plays during each month:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111034667/186757888-4e059a2b-9304-49b9-a58b-8e60b4473aa3.png)

<sub> Data collected from years 2009 to 2017<sub>

 If we compare it to the overall outcomes based on the launch date of all categories,we can see that theater carries a large wage in the categories of succesful and failed.
  
  ![Launch_Date_Outcomes_All](https://user-images.githubusercontent.com/111034667/186769352-d60d1804-1aa5-4169-b132-779d937be610.png)
  
  <sub> Pivot chart of outcomes based on launch date of all parent categories<sub>

### Analysis of Outcomes Based on Goals
 
When the outcomes are analyzed based on goals, still on the industry of theater and with the field of plays specifically, we can see that there were slighly more failed plays than succesful plays, with 0 canceled. The plays that were the most succesful were within the range of $0 to $4,999  with and average of 74.5% success, closely followed by the range $35,000 to $44,999, with an average of 67% success.
  
 The following chart exhibits the percentages of succesful,failed and canceled plays in each range:
  
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111034667/186760526-2348ae7d-1bda-48d0-a23c-7d086238b172.png)
  
<sub> Data collected from years 2009-2017<sub>
  
  
### Challenges and Difficulties Encountered
  
In this project, the difficulties I encountered were making sure the countifs equations were recollecting the correct amount of succesful, failed and canceled plays. For a while, I kept recieveing $0 for the ranges $25,000 and up because of a mispelled word. I was able to notice this error by filtering the Kickstarter data to the parameters I was using in the formula and comparing both numbers to ensure the numbers matched. In the end, being able to filter the original data to the parameters used in the countifs equation was the key to ensuring my calculations were correct, ensuring my graph was displaying the correct percentages for each category.

## Results

After analyzing the data and creating Pivot Tables as well as charts, from the analysis of outcomes based on Launch date,we can see that Lousie's play will be the most successful if it launches in the months of May, June, and July, and the amount of failed and successful plays are almost equal in the month of December.
 
The following charts exhibit the outcomes that the field that was the most succesful was theater, and it was most succesful in the United States: 
  
 ![Parent_Category_Outcome_All](https://user-images.githubusercontent.com/111034667/186770677-7577e330-d242-4b0b-a58c-0f8afacb5792.png)
  
  <sub> All Countries Included <sub>
    
 ![Parent_Category_Outcome_US](https://user-images.githubusercontent.com/111034667/186770766-1f51f1d5-6928-4cd5-84d0-8d723fee871f.png)
    
   <sub> United States Outcomes <sub>

With the analysis of outcomes based on goals, we can observe that there are a higher number of failed plays than successful. The goal ranges that were the most succesful were $0-$4,999 with a 74.5% of success and $35,00-$44,999 with a 67% of success. Hence, Louise could have a higher chance of success in her play if she stays within these ranges.
    
This data set is limited in terms of the years the data was collected from. Although we have a good range of years from 2009 to 2017, it might not be as helpful to Louise since the pandemic has impacted the entretainment industry the most. To get a more accurate result, it would be ideal to obtain data from the most recent years, possibly up to this year if data is avaliable and repeat the analysis to see if the outcomes found above are still relatively equal.
    
Although the analysis of the outcomes based on goals is useful to see which play reached its goal, it does not provide enough inside since there are multiple factors that come into play. For example, the amount of time the play stayed open for, the pledged vs goal amount, the average donation given, as well as the location of the play. Therefore, we would have to do additional analysis of these factors to see   which ones will contribute the most help to Louise's play success.







