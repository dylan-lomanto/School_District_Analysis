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

#### Top and Bottom Schools

##### Initial Analysis Top
![ia_top_schools](https://user-images.githubusercontent.com/86164867/127043289-f667481a-0ae1-437b-bb6a-f840a374f3eb.PNG)
##### Initial Analysis Bottom
![ia_bottom_schools](https://user-images.githubusercontent.com/86164867/127043399-401ae81c-d697-409d-8db0-9b01c630b460.PNG)
##### THS 9th Grade Adjustment Top
![ths_9th_top](https://user-images.githubusercontent.com/86164867/127043535-a83f45eb-e275-4b82-a0f8-2969c68dc0f8.PNG)
##### THS 9th Grade Adjustment Bottom
![ths_9th-bottom](https://user-images.githubusercontent.com/86164867/127045435-84c06204-c6ee-4cd1-b09f-d213b9d6da94.PNG)
##### Variance
There is slight variance between the passing percetages for Thomas HS in the initial and adjusted analysis. This difference is small because we eliminated the THS 9th graders from the count by creating the variable thomas_10_to_12 before getting the averages.

#### By Grade Summary

##### Initial Analysis
Math Scores:
![ia_by_grade](https://user-images.githubusercontent.com/86164867/127047662-10f9093a-b5e2-4864-8f0f-edcabe7dd038.PNG)
Reading Scores:
![ia reading by grade](https://user-images.githubusercontent.com/86164867/127048410-5ab85bca-b421-4dae-8b8c-5bbaee118d43.PNG)
##### THS 9th Grade Adjustment
Math Scores:
![9th math](https://user-images.githubusercontent.com/86164867/127048531-c6bb95ab-a2b6-413d-83b1-f17beb9b4301.PNG)
Reading Scores:
![9th reading](https://user-images.githubusercontent.com/86164867/127048590-5009e9a5-c3c5-4a9e-8bad-a286e58117c6.PNG)
##### Variance
Thomas High School registered NaN values for 9th grade reading and math scores in the adjusted analysis due to the 9th grade scores being thrown out.

#### By Spending Summary

##### Initial Analysis
![ia by spending correct](https://user-images.githubusercontent.com/86164867/127049899-d8af0de2-bb93-487c-b13f-a0c4acfa5d05.PNG)
##### THS 9th Grade Adjustment
![9th by spending](https://user-images.githubusercontent.com/86164867/127049608-5c0b2c29-5a31-4511-be57-a73e398d5ad8.PNG)
##### Variance
There is minimal variance between the two analyses because the elimination of the 9th grade scores and student counts from Thomas HS does not have an effect visible to within one decimal point. The variance would have been larger if the student count had not been altered to remove the 9th graders.


#### By Size Summary

##### Initial Analysis
![ia by size](https://user-images.githubusercontent.com/86164867/127056762-f95b1f15-43ab-4caa-9c89-ed25784cfd02.PNG)
##### THS 9th Grade Adjustment
![9th by size](https://user-images.githubusercontent.com/86164867/127056957-030a7d55-5c4f-438b-804c-974da6639849.PNG)
##### Variance
Similarly to the spending summary, there is not visible variance since the elimination of the THS 9th grade scores and students counts does not alter the averages significantly enough to be visible with a single decimal point.

#### By Type Summary

##### Initial Analysis
![ia by type](https://user-images.githubusercontent.com/86164867/127057219-78cc581f-c82e-47b3-bb91-4f5cec5df283.PNG)
##### THS 9th Grade Adjustment
![9th by type](https://user-images.githubusercontent.com/86164867/127057286-e549e629-e09c-4ab3-a55d-1e9a4e50112d.PNG)
##### Variance
Similarly to the spending and size summaries, there is not visible variance since the elimination of the THS 9th grade scores and students counts does not alter the averages significantly enough to be visible with a single decimal point.










