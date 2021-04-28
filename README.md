# Written Analysis of the Results
## Overview of Project

  The kickstarter challenge is a group of data sets that judge the success or failure of various media projects, the two specific data sets created are both revolved around theatre. Theatre Outcomes Based on Launch Date specifically tracks the theatre projects that are most successful or most likely to fail. Outcomes Based on Goals marks the percentage chance of a theatre project succeeding, failing, or being canceled based on the range of monetary goals. 
## Analysis and Challenges

### Analysis of Theatre Outcomes based on Launch Date

  Outcomes based on Launch date were provided through the filtering of theatre from the parent category into its own specific subcategory, then organized based on date and amount of success and failures. Running the collected data into a pivot table gives a clear and accurate representation of the projects that succeeded, failed, or canceled. 
  
![Anylysisscreenshot](https://user-images.githubusercontent.com/82983000/116432873-f3ebdd00-a816-11eb-925d-590641c8e15c.png)

### Challenges 
  
  The one challenge that came up afterwards manifested in the fact that the theatre category involved both plays and musicals, whereas the data set required only plays and did not find a distinction between the two in the data category. This was addressed by utilizing a simple formula using the COUNTIFS function while selecting the column of subcategories and filtering out the word *plays*, which separates it from musicals and other forms of theatre production. 
  
###  Analysis of Outcomes Based on Goals

  
