# School_District_Analysis

### Overview
The client has provided me with reading and math test scores for students at 15 district high schools, as well as information about budget, type, and size of each of the schools. I have been tasked with merging the data sets and then determining passing percentages for each test and overall based upon school, grade, type of school, size of school, and budget. After the initial analysis it was determined that there were ineligible test results from the 9th graders at Thomas High School due to cheating.  I was resposible to eliminate the test results and student counts from this population and rerun the analysis.

### Results

#### District Summary

##### Initial Analysis
![ia_district_summary](https://user-images.githubusercontent.com/86164867/127041715-a408eb04-3adc-4bf9-a2d7-8388429d936d.PNG)
##### THS 9th Grade Adjustment
![ths_9th_district_summary](https://user-images.githubusercontent.com/86164867/127041853-9019466f-40fd-4f97-af81-39cfaba71988.PNG)
##### Variance 
The average scores and percent passing have slightly dropped for all categories by replacing the reading and math scores for all 9th grade students at Thomas High School with NaN.  I did not, however, remove these students from the student count. This results in all of the the 9th grade THS student scores registering as 0 and pulling down the averages. If the students had also been removed from the count the average scores and passign percentages would have eith dropped by a smaller margin, stayed the same, or increased.

#### Per School Summary

##### Initial Analysis
![ia_by_school](https://user-images.githubusercontent.com/86164867/127042702-181addad-144b-4569-b6e4-507de06fe101.PNG)
##### THS 9th Grade Adjustment
![ths_9th_by_school](https://user-images.githubusercontent.com/86164867/127042847-b422cc99-dbea-4f3d-8e90-22d377930eb5.PNG)
##### Variance
The Thomas HS passing percentages were heavily affect by the adjustment, since roughly one quarter of the students recorded scores of 0 for both tests.

