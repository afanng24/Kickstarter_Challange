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

  Outcomes Based on Goals marks the percentage success, failure, and cancelation of plays over the dataset based on the monetary goals of individual play productions. The difference between the two datasets is that this one specifically tracks plays whereas the other includes musicals and other theatre productions. This analysis also only marks the percentage success and failure and not over a period of time like Theatre Outcomes Based on Launch Date. The simplicity of using the COUNTIFS function allowed the data to be organized rather easily and filtered across every column without the use of a piviot table. 
  
![goals](https://user-images.githubusercontent.com/82983000/116436234-319e3500-a81a-11eb-96b7-260f2212137d.png)

### Challenges

  Layering the various COUNTIFS functions proved to be the most tedious challenge of the entire project, however, making sure the appropriate punctuation is in the right place of the formula solved that issue. The commas, quotation marks, and parenthesis can be difficult to remember especially for people who do not frequent the COUNTIFS function but making sure they are in the right places guarantees the success of the function. 
  
  
## Results 

### Results of Theatre Outcomes based on Launch Date




