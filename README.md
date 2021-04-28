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

From the pivot table and the corresponding data chart, one can see that the majority of productions increase during April with a peak in May and a steady decrease throughout the  rest of the year. The April to May timeframe just so happens to be when most theatre productions are successful but also when many fail as well. October sees a shift in percentage failure with only 65 productions being successful and 50 failing, thus the fall time is the most likely time a production is to fail and the beginning of summer is when a production is most likely to succeed. 

![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82983000/116438244-454a9b00-a81c-11eb-9daa-3618132ce0c3.png)

### Results of Outcomes based on Goals 

This dataset which only measures the percentage success and failure of plays makes it obvious that smaller productions with a goal of less that $5000 have a higher chance to succeed with a notable outlier in the 9 plays between the $35,000 to $45,000 mark being almost just as successful. The data set also only measures plays and not musicals, it is also interesting to note that while canceled plays are included there are no seem to be none that are canceled as opposed to musicals which are canceled more frequently. It is also important to note that a great majority of plays are under the $15,000 goal range so most are actually successful. An additional table or graph that shows the total number of successful plays over failed plays would be crucial to understanding the bigger picture. 


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82983000/116439363-75df0480-a81d-11eb-9b38-4f456e18f5ea.png)



