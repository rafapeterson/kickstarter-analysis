# Kickstarting with Excel

## Overview of Project
This project was analysis of a sampling of Kickstarter campaigns.

### Purpose
The purpose of this project was to compare the success of the client’s Kickstarter campaign to produce a new play against other similar campaigns. This was analyzed in relation to their launch dates & funding goals. A large sample of data that expanded outside of the Theater category was also reviewed, but focus was placed on Theater/Plays.

## Analysis and Challenges
In order to determine if the goal of a successful Kickstarter would be attainable, a historical sampling of different Kickstarter projects were analyzed. In this review, focus was placed on the country of origin, category of Kickstarter (specifically looking at theater/plays), and whether the Kickstarter succeeded, failed, was cancelled, or was still live.

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/13009587/133311114-cd1eab9d-f1e6-4b14-a8b0-16d29ff468e6.png)

In order to review the outcomes based on launch date, the year was pulled from the date created, then a pivot table was generated to categorize the outcomes (successful, failed, and canceled) and organize the data based on months, which provided some seasonal context behind the outcomes. Then, a chart was created to graphically demonstrate the trends within the data. ![Screenshot of outcomes by launch date](https://user-images.githubusercontent.com/13009587/133311144-0aeb4127-5c53-4bbb-b6a8-37a76356fe42.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/13009587/133311166-447b306e-ee7d-49c6-9a7f-9e9d62b6a524.png)

For the analysis of outcomes based on the goals, the data was filtered out of the “plays” subcategory based on which campaigns were successful, failed, or were canceled. From there, the percentages were calculated in order to then create a chart to illustrate the information gathered.
![Screenshotof outcomes based on goal](https://user-images.githubusercontent.com/13009587/133311179-acf897c8-aba3-4d1b-b6b3-f32b11405300.png)

### Challenges and Difficulties Encountered
<br/>In terms of challenges and difficulties, the data was consistent and easy to review. Barring some outlying data that prevented a smooth gradation in the review of “amount pledged,” the data told a story that wasn’t difficult to interpret.
<p>One potential challenge that could surface from this current data set would be if the client wanted the goals and pledged amounts in a consistent currency, because in order to provide a precise answer, historical conversion data would need to be pulled & have all the amounts converted into an agreed upon currency.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?</br>
  Based on the review of outcomes based on their launch dates, there is a strong correlation between the success of a campaign and when it launched. Campaigns started in May & June had a major surge in the count of successful outcomes, while October showed a trend of failed outcomes. Launching a Kickstarter campaign in late spring/early summer would provide the largest opportunity for success.<p>


- What can you conclude about the Outcomes based on Goals?<br/>
  In analyzing the outcome of multiple Kickstarter campaigns based on the goals that they’d set, there was a strong correlation between the size of the goal and their success. Goals that were less than $5000 were significantly more likely to succeed compared to those that were higher. <p>
To ensure the most likelihood of a successful campaign, seeking a lower goal amount is important. Also, keep in mind that a Kickstarter goal is only a goal. It is not unheard of for campaigns to exceed their goal amounts, so maintaining a conservative goal should be prioritized.<p>

- What are some limitations of this dataset?<br/>
  Some limitations of the dataset include only pulling data from Kickstarter. To complete an even more thorough analysis, data could have been pulled from other crowdfunding sources. Also, the amount of promotion on these campaigns was not specified. Without knowing what other marketing tactics were put in place to ensure the successful campaigns’ successes, it’s impossible to determine the weight promotion had on their success.<p>
- What are some other possible tables and/or graphs that we could create?
 <br/> Depending on the flexibility of the client, other tables comparing the success of different subcategories within the theater category could prove to be useful, if the client was considering other routes in the theater category. Also, one could potentially compare other fine arts campaigns with the plays subcategory to see the general popularity of theater/plays.
