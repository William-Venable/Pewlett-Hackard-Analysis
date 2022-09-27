# Pewlett-Hackard-Analysis

## Project Overview
At Pewlett-Hackard I was given two assignments to follow up on:
  1. Determine the number of retiring employees per title
  2. Identify employees who are eligible to participate in a mentorship program
This analysis will help prepare the manager for the "silver tsunami" as the current employees reach the retirement age.

## Results
Based on the results of our data, we can find four major points:
  - The list of employees and their different titles throughout the years
  - The list of employees and their current titles
  - The list of employee titles
  - The list of employees eligible for the mentorship
  
As the Pewlett-Hackard employees reach their retirment age, we are asked to pool those reaching that age into a list. Using our code below, we have accumulated a list of these employees. However, we can see that there are duplicates in the list which actually shows the different titles that these employees have had through the years, suggesting promotion.

![Retirement_Titles_Code](https://user-images.githubusercontent.com/110737061/192619383-f44dcd80-6c60-4a70-b3f4-7c34c51ffccb.png)
![Retirement_Titles_Data](https://user-images.githubusercontent.com/110737061/192619390-fe0ca40e-1e52-411f-b309-8b542ced0a3f.png)

To refine our list down so there are no duplicates, we've adjusted our code in order to get current and unique titles to each employee; the total number of employees reaching the retirement age is currently 72458.

![Unique_Titles_Data](https://user-images.githubusercontent.com/110737061/192619881-8010e8cf-25dd-4a2a-bec1-86ee3326b8a1.png)

Using our new unique title list, we can also get a count of the number of each unique title within the buisness.

![Retiring_Titles_Data](https://user-images.githubusercontent.com/110737061/192620073-bcebdc51-930e-4e44-a92f-2fbcda314fd8.png)

Now that we have refined our list of employees reaching retirement age, we can see who is eiligible for the mentorship. We have filtered our data to only show employees born within the year 1965 and the result was only 1549 eligible employees.

![Mentor_Eligibility_Data](https://user-images.githubusercontent.com/110737061/192620748-73e36a36-f96e-4b93-a996-1b0bb50e2d50.png)

If you are interested in looking at the complete lists of data collected, they are all pooled in the https://github.com/William-Venable/Pewlett-Hackard-Analysis/tree/main/Data folder.
