# Kickstarting with Excel
## Contents of Respository
Two spreadsheets and two .png files
Kickstarter_Challenge.xlsx contains the deliverables for the project
data-1-1-3-StarterBook.xlsx contains the activities listed in the module (in case there are sheets missing from the other file that need to be reviewed)
## Overview of Project
The purpose of this exercise was to determine how Louise's campaign faired in comparison to other Kickstarter campaigns based on launch date and fundraising goals.
## Analysis and Challenges
Two different analyses were performed. The first was to determine the outcomes based on Launch Date. A new columnn had to be created to further filter the data 'by year' as opposed to 'by date'. I faced an issue while creating this column because the formula Years() did not want to populate all for every row. I had to mnanually drag the formula down. A pivot table was created to visualize how many theater campaigns were successful, failed, or canceled month to month. Please see Theater_Outcomes_vs_Launch.png for the plot.
The second analysis performed was a separate sheet to determine the outcomes based on goals. For set monetary ranges, the data from "Kickstarter" was pulled to count the successful, failed, and canceled play campaigns. From that data, one could then determine the total projects in those monetary ranges and for those set outcome descriptions. Then percentages were calculated for each outcome. No challenges were faced while creating this sheet. Please see Outcomes_vs_Goals.png for the plot.
## Results
### Conclusions for Outcomes Based on Launch Date
Based on the Theater Outcomes vs Launch plot, one can conclude that launching a Kickstarter in May contributed to the most successfull campaigns. Also, if a campaign is launched in December there is about 50% chance the campaign will fail. This is more than likely due to the holidays and people are spending their money on their families.
### Conclusions for Outcomes Based on Goals
The Outcomes Based on Goals plot does not have any obvious trends. The very small goals were typically successful and the very large goals typically failed. With that said, there were high dollar goals that were still over 60% successful. This particular data would need further analysis to determine the cause. Were there fewer backers thatvjust contributed most of the funds? When were those specific campagins launched? Were those plays more popular and well known?
### Limitations and Recommendations
The questions posed in the previous section show some limitations of the analysis so far. There would need to be more analysis done to make better conclusions and recommendations for Louise. Another column could be made to put the goal amount into buckets, like what was done on the "Outcomes Based on Goals" tab to then add that as a filter into the Outcomes Based on Launch Date pivot table. That could tell us a much better story of the data. 
