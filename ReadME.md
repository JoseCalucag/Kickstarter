# Kickstarting with Excel

## Overview of Project
My client approached me to investigate if there is any correlation with Kickstarter-funded theatre campaigns to their launch dates and their funding goals. So, I was hoping to gather some conclusions and data points by leveraging Kickstarter data into tabular charts and visualizations; and be able to hypothesize actionable outcomes from them.

## Analysis and Challenges
I was able to get a dataset of Kickstarter-funded campaigns between 2014-2016 to which I filtered for ‘theatre’ campaigns. With this subset, I created two pivot tables by targeting specific areas for each: one looking at “Outcomes Based on Launch Date” and the other “Outcomes Based on Goals”. 

![Outcomes_vs_Goals](https://raw.githubusercontent.com/JoseCalucag/Kickstarter-Analysis/master/Resources/Outcomes_vs_Goals.png)
### Analysis of Outcomes Based on Launch Date
For the 'Outcomes Based on Launch Date' worksheet, I wanted to visualize the number of campaigns based on the month it was launched. So, I created a pivot table from using the 'Date Created Conversion' column on the Kickstarter worksheet and sorted them out by the month of the launch date. I further broke down the data by the outcome of the campaign and whether it was a 'successful', 'failed' or 'canceled' campaign. And based upon the created pivot table, I created a line chart to visualize the pivoted data.

![Theatre_Outcomes_vs_Launch](https://raw.githubusercontent.com/JoseCalucag/Kickstarter-Analysis/master/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
For the 'Outcomes based on Goals' worksheet, I was able to table campaign data by creating data ranges based on crowdfunded goal amounts then cross referencing each range on whether it was either success, a failure or canceled. Afterwards, I further expanded my analysis by finding the percentages of each total to the total amount of campaigns for each range. I then created a line chart that visualized the data range by their percentages.

### Challenges and Difficulties Encountered
When it comes to any data project, the main challenge is to know how to leverage the data to achieve a specific outcome. So, 

## Results
Based upon my findings, we can pinpoint talking points from these worksheets. First, from the Outcomes Based on Launch Date worksheet, we can see that the majority of the campaigns started in the Spring and throughout the Summer. Moreover, most of the campaigns that were successful were funded at the start of the theatre festival season in May and June. Secondly, from the Outcomes based on Goals, albeit most of the campaigns are under the 10K range, the most successful are mostly under 5K where 141 were under 1K while 188 where between 1K to 5K. To further illustrate, the succesful rate is at 73.5%. What we can hypothesize from this is that a lot of smaller productions (probably from local communities) probably had a good grassroots in their area during the winter-spring; and once festival season started, their was a buzz for some of these productions and got momentum to get funded.

## Possible Future Considerations
For future takes on this analysis, we can consider other avenues and data points to help broaden some concepts that we can take into making deliverables. 
- Instead of months, we can see the funded amounts for each year to see if there's any conclusions to take there, like why one year was better funded than the others. Or, the vice versa of why one year was the worst funded. What are the reasons for this?
- We could see if certain countries had more projects that others. With this knowledge, we can focus on these certain regions for  possibility of having more special events or theatre festivals for these regions to help with funding and staging these productions.
- We can see a donor's list to see if there are people that have donated to multiple campaigns that can be called upon for future campaigns.
- As the interest was to make line charts for this project, I think using stacked bar charts is more telling in certain situations. For instance, in 'Outcomes Based on Goals', stacked bars on data amounts could've shown more of a difference in each data range. 
