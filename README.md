Project 1: Standardized Test Analysis
By Ryan Virgin
General Assembly
02/02/2023

Problem Statement

The ongoing usefulness of the SAT and ACT standardized tests as a predictor of college success is a matter of ongoing debate. The purpose of this analysis is to investigate the results of standardized testing and evaluate the relationship between collegiate standardized testing as part of a comprehensive college admissions process.

The findings from this analysis will provide insight into the validity of the SAT and ACT exams as a tool for college admissions and will inform the ongoing debate about their usag in the admissions process.

Conclusion

The ongoing usefulness of the SAT and ACT standardized tests as a predictor of college success is a matter of ongoing debate. The purpose of this analysis was to investigate the results of standardized testing and evaluate the relationship between collegiate standardized testing and success in college admissions.

The relationship between success on standardized tests, such as the ACT and SAT, and successful admission to top US Universities is clearly defined within the data. More prestigious institutions with lower acceptance rates accept students with higher total test scores and less pretigious institutions have a relative lower threshold for acceptance [fig. 6].

However, as SAT/ACT participation rate increases, the average score decreases noticably [fig. 3]. Further analysis would be required to determine the cause of this trend. Without further analysis, this trend would imply that the efficacy of the test to determine a  student's fitness for higher education would seem to be influenced by other factors outside of the student's aptitude.

This analysis provided insight into the validity of the SAT and ACT exams as a tool for college admissions success and an institution should be aware of these auxillary effects that could impact the institutions perception of college applicants. Additional data will need to be gathered to inform any changes to an institution's admission policies, as relatively few institutions have forgone the exams.

The findings of this analysis suggest that the SAT and ACT exams may provide beneficial data to help predict a student's success, they should not be relied upon as the sole indicator of a student's potential for success in college. The relationship between standardized test scores and student success is complex, and a comprehensive approach to college admissions, taking into account a range of factors beyond test scores, is necessary to make well-informed decisions. While these exams can provide valuable information, they should be considered as one part of a larger picture.



Data Dictionary

The two datasets selected for this project are:

* sat_2019.csv: 2019 SAT Scores in the United States by State
* sat_act_by_college.csv: SAT and ACT Scores by College

### 2019 SAT Scores in the United States by State
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|sat_2019.csv|list of US States| 
|participation_rate |float64|sat_2019.csv|Student's participation rate in the SAT by state| 
|read_write|int64|sat_2019.csv|The score attributed to the reading and writing component of the SAT|
|math |int64|sat_2019.csv|The score attributed to the math component of the SAT| 
|total |int64|sat_2019.csv|The combined score of the reading/writing and math components of the SAT| 


### SAT and ACT Scores by College

|Feature|Type|Dataset|Description|
|---|---|---|---|
|school|object|sat_act_by_college.csv|list of US colleges| 
|test_optional|object|sat_act_by_college.csv|Whether the test is required as part of the college's admissions| 
|num_applicants|int64|sat_act_by_college.csv|Number of applicants that applied to the specific college|
|accept_rate|float64|sat_act_by_college.csv|The rate at which students are accepted to the colleg | 
|sat_total_interquart|object|sat_act_by_college.csv|The interquartile total SAT score (25th-75th percentile)|
|act_total_interquart|object|sat_act_by_college.csv|The interquartile total ACT score (25th-75th percentile)| 
|sat_total_25|float64|sat_act_by_college.csv|The lower bound of the interquartile total SAT score (25th percentile)| 
|sat_total_75 |int64|sat_act_by_college.csv|The upper bound of the interquartile total SAT score (75th percentile)|
|act_total_25 |float64|sat_act_by_college.csv|The lower bound of the interquartile total ACT score (25th percentile)| 
|act_total_75|float64|sat_act_by_college.csv|The upper bound of the interquartile total SAT score (75th percentile)| 
