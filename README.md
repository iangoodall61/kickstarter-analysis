# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
## Overview of Project

### Louise was able to come close to reaching the fundraising goal for her Play Fever, and now would like to see how different campaigns fared in relation to their launch dates and their funding goals. I broke down the Kickstarter data in order to look at the outcomes based on both the launch date and goals in order to deliver her desired information. 

## Analysis and Challenges

### The analysis of the outcomes based on launch date began by adding an extra column to the data to pull out the beginning year in which each play was created. Then I was able to create a pivot table that counted the number of successful, failed, and canceled projects and broke it down by the months in which they were launched. I added a line graph to better visualize the results. 
![image](https://user-images.githubusercontent.com/107015694/174034163-c82763b4-71a4-4f5e-9bb4-b8af69894613.png)

### The analysis of the outcomes based on goals was completed by creating a new table to further map out the successful, failed, and canceled projects. I broke down the initial goal amount into different dollar amount ranges. I was then able to count the percentages for each of the successful, failed, and canceled projects after calculating the total number of projects within each goal amount. Using these percentages, I was able to create a line graph to visualize this information. 

### The first challenge I ran into was making sure I have the correct values in the correct spots in the pivot table. I had to manipulate the rows in order to get all the months to show as the row values. When I added in the date created conversion column to the rows it initially showed more information than I needed to I had to remove the extra added in columns under the rows. The second challenge I faced came when I was creating the outcomes based on goals chart. I needed to make sure I had the correct order for the countifs formula I used. Initially I had it backwards, so I had to swap the criteria ranges around, making sure to start with the goal amount range, then outcomes results, followed by the play subcategory.

## Results

- One conclusion I found after analyzing the launch dates is that an early summer launch date, around May, has the better chance for success. Another conclusion is that very few projects seem to get canceled no matter what month, so its worth taking a shot and launching a new project

- A conclusion I made after analyzing the outcomes based on goals is that as the goal amount for play increases past $5000 the more likely the play will fail, and she would have a better chance for success if her initial goal amount in below $1000.

- A limitation of our data is that we only looked at play outcomes, and we could dive deeper into what specific plays had the most success and provide more detail into the different storylines had the most success and what genre they fall under.  

- Another potential graph we could add would be to implement more descriptive analytics in order to create a box and whisker plot to see if there were any outliers that skewed our data. 
