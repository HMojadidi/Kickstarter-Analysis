# Kickstarting with Excel
I will manipulate the given Excel data in order to reach possible conclusions based on those data readings.

## Overview of Project
After successfully reaching her fundraising goal, Louise wants to know how different campaigns fared in relation to their launch dates and fundraising goals. I will follow this with a written report on my findings.

### Purpose
The purpose of this Excel project is to create:

*   Deliverable 1:  Outcomes Based on Launch Date Chart
*   Deliverable 2:  Outcomes Based on Goals Chart
*   Deliverable 3:  A written analysis of the results (READE.md)


## Analysis and Challenges

*   Deliverable 1: In order to manipulate the data, it is important to pinpoint the relevant variables so as to produce conclusions. I first created a "Years" column to extract the years from the lauch dates. Previously, I had extracted all dates from the timestamps in which the original date had came in. Afterwards, in the Pivot table setting I used the filter on Parent Category set to 'Theater' since we are specifically looking at theater campaigns only for this task. The Pivot table helped calculate the aggregate number of successful, failed and canceled campaigns. I produced a line graph which gave a better visual for the data trends. I found this task to be particulary easy.

* Deliverable 2: This deliverable required more work, especially that it involved ensuring the proper syntax for a quite lengthy COUNTIFS function. After many tries, I was able to perfect it so that it would give the desired data for the number of succcesful, failed and canceled plays withing specific numeric ranges. It furthermore required calculating the total sum and percentages for each of the 3 outcome categories. I also produced a line graph which showed the outcome percentages for a numeric scale. The visual production  was rather easy for me.

### Challenges and Difficulties Encountered

*   For Deliverable 1, I did not encounter any difficulty and thought of the assignment as quite straightforward. I initially struggled to be able to save the chart as a .png but thankfully was able to do so in the end. 

*   However, I did face some difficulty with Deliverable 2. The biggest challenge was getting the COUNTIF syntax correct. After much trial and error, I was thankfully able to resolve it. 

### Analysis of Outcomes Based on Launch Date

For 'Outcomes Based on Launch Date', we can see that campaigns lauched between May and June have most successfully met their fundraising goals. Those campaigns which failed did so rather consistently throughouth the years within narrower number variations as compared to the successful ones. This can lead one to conclude that the failure of the failed campaigns had less to do with timing and were ruled more by perhaps other factor(s). As for the canceled campaigns, launch dates didn't seem to fluctuate that much ether as they seem to fail regardless of the month of the year. There wasn't any conclusive data available for failed campaigns lauched in October in this data set.  

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95712234/156226643-940741a4-56c9-4892-9340-96226a3647f8.png)


### Analysis of Outcomes Based on Goals

For 'Outcomes Based on Goals', based on the findings we can see that the most number of successful campagins fall in the lower numeric ranges of $5000 and less. There is a decline between the $5000 and $30000 range. We can see a slight incline in the $30000 and $45000 only to drop again in the higher numbers, most likely indicating outliers. For the failed campaigns, the numbers were highest in the $5000 and below range. The percentage of successful campaigns decreased as the budget increased. Similarly the percentage of failed campaigns increased as the budget increased. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95712234/156226826-e3a72b7c-c663-4b61-a9da-8836ffd16f2a.png)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the 'Outcomes based on Launch Date', one can first conclude that the most successful campaigns were launched in May, June and July with smallest success numbers in the December time. Secondly, the number of failed launch outcomes was rather spread out throughout the year with less fluctuation seen when compared to the successful launch timings. The canceled campaigns were fairly consistent throughout the year regardless of launch dates.


- What can you conclude about the Outcomes based on Goals?

The data clearly shows successful campaigns fair better in the lower budget goals and there are fewer successful ones in the higher budget goals. Altough there are many failed campaigns in the lower budgets, there seem to be more failed ones in the higher budget goals as compared to the successful ones. 

![Descriptive Statistics](https://user-images.githubusercontent.com/95712234/156230314-88fe1f5f-2eb2-46d2-98f7-bc2ead2df610.png)



- What are some limitations of this dataset?

The dataset does not indicate reasons for cancelations based on launch date nor budget goals.

- What are some other possible tables and/or graphs that we could create?

I would be interested to remove remote outliers and see how that effects the distribution of line graph. It's easier to see it in a box plot but I feel it would significantly alter a line graph.
