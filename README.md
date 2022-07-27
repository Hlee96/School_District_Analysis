# School_District_Analysis
## Overview of School District Analysis
THe purpose of this analysis is to analyze the data for the school district. Analysis that includes student grades, passing grade by subject, overall passing and the budget for each High School within the district. It provided insight for each school's performance within the district from 9th-12th grade, providing performance results. There was an academic dishonesty, making the analysis to be conducted twice to ensure integrity within the state-testing standards.
## Results
There was an academic dishonesty by the 9th graders from Thomas High School. It caused the analysis to be done twice to find the dishonesty and find how much effect it had on the student grade and performance for each school. 
Below is an image of prior to replacing Thomas High School 9th graders scores with nan
![Screenshot 2022-07-27 141032](https://user-images.githubusercontent.com/108282027/181353110-30e8b83f-c097-4b29-8146-412680acce9d.png)
Below is an image of after replacing Thomas High Shcool 9th graders with nan
![Thomas NAN](https://user-images.githubusercontent.com/108282027/181353223-fbd0eee6-ef11-453f-83fe-83d49ea87cb8.png)
It can be concluded that:
  - Overall passing percentage for Thomas High School is at 65%
  - Overall passing percentage for the district is at 64.9%
  - Thonmas High School is no longer in the top 5 schools
Effect on the school summary
  - Overall score for Thomas HIgh school.
  - Average scores have been decreased
  - Thomas High School overall passing score has dropped from 90 to 65
Below is an image of the original school summary
![Original School Summary](https://user-images.githubusercontent.com/108282027/181356556-8e4b9835-62d3-4337-b249-3407c8da80ef.png)
Below is an image of the refactored school summary
![Refactored School Summary](https://user-images.githubusercontent.com/108282027/181356601-0c2bce73-74fb-4eeb-bebd-5cb137fbc789.png)
Once the 9th graders math and reading scores have been replaced with nan values, it shows that Thomas High School 9th graders are struggling in comparison to other top performing schools. Thomas High School ranking dropped from being 2nd to the bottom tier for schools.
### Math & Reading score by grade
The only data that is changed is for Thomas High School, where the data within the column for 9th graders will show as nan. It won't effect any other school's math and reading score.  
### Spending
There is no effect on spending, since the dataframe only includes 10th-12th graders. 
#### Original
![Old Spending](https://user-images.githubusercontent.com/108282027/181391836-f10cda6f-fc38-4938-aa02-7065d0870c89.png)
#### Refactored
![Score By Spending](https://user-images.githubusercontent.com/108282027/181391605-e1dc1898-1e4a-405b-a676-dfc9fdea46db.png)
### Size
There is no effect on the size, since the dataframe only includes 10th-12th graders.
#### Original
![Old Size](https://user-images.githubusercontent.com/108282027/181391886-d92975e2-648b-43fe-aec1-2ec5659e031e.png)
#### Refactored
![Score By Size](https://user-images.githubusercontent.com/108282027/181391668-44445af2-e64d-4908-9161-b0960df59a88.png)
### School Type
There is no effect on the school type, since the dataframe only includes 10th-12th graders. 
#### Orginal
![Old Type](https://user-images.githubusercontent.com/108282027/181391981-e4fd6739-253c-445b-ab2c-4d0e6c9e0078.png)
#### Refactored
![Score By Type](https://user-images.githubusercontent.com/108282027/181391720-21e1fc09-30ca-4ae3-aa84-4b6d24250e68.png)
## Summary


