# Kickstarting with Excel

## Overview of Project
In this Project, we created a Pivot table and graph showing the Theather Outcomes vs. launch using the Plays subcategory. We were able to find trends, such as what months did best and which did worst.
### Purpose
The purpose of this activity was to create a pivot table and graphs using the data included in the Kickstarter sheet. We also classified the data by goal amount. With this, we got more detailed information on which campaigns were successful or not
## Analysis and Challenges
The hardest challenge that I faced was getting the following formula to work correctly =COUNTIFS(Kickstarter!D:D,">=1000",Kickstarter!D:D,"<=4999",Kickstarter!F:F, "successful",Kickstarter!Q:Q, "plays"). It took a lot of trial and error to get this working properly. The hint helped, but it wasn't the same. My last challenge was the fact that 0 Play Kickstarters were canceled. This got me thinking that I had done something wrong. I had to good back to the Kickstarter sheet to get it and used the filters to confirm this. 

### Analysis of Outcomes Based on Launch Date 
Kickstarters that are launched in May and June are successful. Kickstarters, launched in December, are less successful. Maybe because people are spending their money on gifts?

### Analysis of Outcomes Based on Goals
Based on the goals, we can see that Kickstarters from 0 to 19999 have a better chance of being successful than those exceeding that amount. 


### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Kickstarters that are launched in May and June are successful. Kickstarters, launched in December, are less successful. Maybe because people are spending their money on gifts?


- What can you conclude about the Outcomes based on Goals?
Surprisingly Kickstarters in the range of 1000 to 4999 do almost as good as the kickstarters that are less Than 1000

- What are some limitations of this dataset? On this dataset we didnt have any canceled plays. we couldnt calculate how canceled play would affect the data

- What are some other possible tables and/or graphs that we could create?
we could create graphs or tables for other forms of theather/plays subcategory. We could also create graphs that shows us what type of play (topic/theme) did worst overall etc.