# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to help Louise fund her play "Fever". Louise would like to see how well kickstarters work and would like us to narrow it down. The data shows all kickstarters in multiple different categories, we need to filter it to only the ones that relate to her. We are looking at kickstarters dated from 2009 to 2017 to help Louise figure out when and how to fund her play. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To start the analysis all kickstarters were filtered by Theater into a pivot table. The data was then filtered by outcomes: successful, failed, or canceled. The graph below was created using those filters and shows how the kickstarters do based on the month of the year. ![Outcomes based on launch date](https://user-images.githubusercontent.com/94948877/147180767-51e8cfaf-825f-4156-909d-d3d30aa5b6f6.png)

### Analysis of Outcomes Based on Goals
This data set was created based on the goals that were set by the kickstarters. This was filtered down by Theater along with the subcategory "plays" to get a more accurate data set for Louise since she is specifically funding a play. This is also looking at only outcomes that were successful, failed, or canceled because we do not want to see the live kickstarters. The following graph was created using this data set. ![Outcomes based on Goal](https://user-images.githubusercontent.com/94948877/147280706-2d515783-a07f-4ec8-a820-45cfc665c27d.png)


### Challenges and Difficulties Encountered
This data set did have dates for when they were launched but they were in Unix Timestamp which was not readable. This required me to create another column with the converted time to be able to sort the data by the date they were launched. Using excel functions I was able to do this easily. This was needed so we could see when the best time of the year would be to launch a Kickstarter. 



## Results


Kickstarters that were launched in May had a much higher success rate than any other month, but it also shows that the most successful time to launch a Kickstarter seems to be the summer months. The successful compared to failed is much higher in May also which means there is a higher chance of the Kickstarter succeeding. The data does not show much correlation between date launched and cancelled. 

From this data it looks like most kickstarters that were successful had a goal less than $15,000. There is also some correlation between $35,000 to $45,000 that shows most of those kickstarters were successful also. We would probably need to do further analysis on this to figure out what caused this. 

With how much data there is in this set we could filter it down by genre of play to help Louise figure out if there is correlation on that. This data set does not show genre though so we cannot see what the comparisons are between genres of plays and how successful they are. Another limitation would be on the outcomes based on launch date because we did not filter that by plays. On that graph all the subcategories under theater are being compared. I'm not sure if this is really a limitation on the data set because I am able to add in a filter by subcategory, but the module just did not have us do that. Another useful table and graph we could create would be to find how long each Kickstarter was run to see how long we should keep the Kickstarter active and compare that to the outcomes. 


