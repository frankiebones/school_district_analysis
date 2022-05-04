# Overview
## We were tasked with locating trends in school performance to better allocate budgets.  
We compared results across grades **9 - 12** for math and reading scores, the number of students who passed each subject with a grade of **70 or higher** as well as the combined total of those who passed both math & reading.  

We then used the provided data to further analyze those results based on a number of factors for each school.  
These factors included:  
-the school size  
-the school type (whether District or Charter)  
-their overall spending  
-their average spending per student  

****
***Please note:*** We were forced to remove all of the **9th grade** scores for **Thomas High School** due to evidence of academic dishonesty.
****
# Results

In terms of the district summary there is little to no change between the altered grades and that which had the grades removed completely.  

We do however see a change when comparing the school summaries, most noticably in the average of students who passed math or reading.   

*Adjusted:*  
<img width="1100" alt="THS_summary_dataframe" src="https://user-images.githubusercontent.com/15967377/166817271-848ecd20-b86b-4cf5-b12d-3b5cd4212f4f.png">
*Original:*  
![THS_1](https://user-images.githubusercontent.com/15967377/166817578-7bc1e9c1-bb49-4b69-9ba8-7b4c41297543.PNG)  

This led to:
- a decrease of approximately 28.4% in percentage of those who passed overall
- lowering their ranking of Charter schools from 2nd to last
***
We can see that **Charter** schools far surpass the overall passing percentage when compared to **District** schools.  

![school_type_summary_df](https://user-images.githubusercontent.com/15967377/166818223-1e474428-ad89-4575-8ead-2676f1bb80d8.PNG)  

As school size increased the overall passing percentage decreased, while we do not know the class sizes of each school, one might infer that a larger school size would increase the chances of larger class sizes which could in turn lead to less attention per student by the faculty.  

![school_size_summary_df](https://user-images.githubusercontent.com/15967377/166815549-2b78a88f-3bdf-4381-a0c0-5491edc5d696.PNG)  

There is also a decrease in overall passing percentage as the amount spent per student rises. Without further data as to how the budgets are allocated it would be hard to determine why this is.  

![spending_per_student_summary_df](https://user-images.githubusercontent.com/15967377/166815448-a05e61e3-25eb-4815-9b47-164c1df61849.PNG)


We have informed Maria that we would be happy to continue further analysis as to what budgetary adjustments could be made to increase the overall passing percentage of these schools but until we have the data as to how the money is being spent (amenities, teacher salary, school supplies, etc...) we cannot make any additional suggestions.

In my opinion this data pipeline needs improvement as the amount of suffixes/prefixes that were included is too large. My guess is someone used a template for a survey that included all the suffix/prefix options in a drop down menu and the students just couldn't help themselves. This could also have led to the tampering that caused the 9th grade scores at Thomas High School to be removed thereby leading to their lowered ranking among the other schools. 

It would be wise for the schools to review how they collect and store data to ensure it requires less cleaning and is more secure to avoid tampering.
