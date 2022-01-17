# School-District-Analysis

## Overview of School District Analysis
Maria, the chief data scientist for a city's school district is analyzing school and student data from across her district in regards to standardized testing scores data for the year. She is tasked with analysis, reporting, and presentation of this data to the district's school board to deliver insights in the schools' performance trends and patterns based on a variety of factors such as budget, school size, test scores per student, and more. These insights will inform discussion and strategic decisions at the school and district levels. Maria has asked for help analyzing the data on student/school funding and standardized test scores. With access to every student's math and reading scores, as well as all other school we have assisted Maria in compiling the data and delivering the statistical analyses and proper data organization for proper presentation to the district school board. As all data & information is protected under the Family Educational Rights and Privacy Act of 1974 (or FERPA), data specifics and information on students and some school details are confidential.

In this project, we've aggregated the data into various data frames and series to present the school board with test score results by school, grade, budget, and school size, in order to help inform them on strategic decisions for schools in the district moving forward based on current education trends.

While the aggregation and analysis had been completed once with all of the data provided, Maria had afterwards announced that the school board may have suspected some trace(s) of academic dishonsty coming from Thomas High School's 9th-grade class. As such a second aggregation and analysis was done refactoring the statistical models and data frames to replace all of the Thomas High School's 9th grade test score data with Temporary null values to provide the school district with still accurate and representative data, despite this issue.

## Results

### District Summary Affects
With the exclusion of Thomas High School's 9th-grade class, the district summary's % Passing statistics for all schools had changed slightly. These changes in results are primarily due to the exclusion of scores from 461 9th Grade Thomas High School Students. As such the scores shifted downwards by a factor of ~1-2% per category. This is due to how relatively small the omissions to the Thomas High School Data was in regards to the 39,000+ total test score data points for all schools across the districts
-% Passing Math across the district had changed from an original 75% to 73.9%
-% Passing Reading across the district had changed from an original 86% to 84.7%
-% Overall Passing across the district had changed from an original 65% to 64.1%


### School Summary Affects
Because the only change that took place between the two aggregations and analyses was in regards to Thomas High School, the only school's statistics affected within the School Summary data was Thomas High School's statistics. Thomas High School's % Passing statistics had changed significantly.
-% Passing Math scores for Thomas High School went from an original 66.91% to 93.18%%
-% Passing Reading scores for Thomas High School went from an original 69.66%% to 97.02%%
-% Overall Passing scores for Thomas High School went from an original 65.08% to 90.63%%

With these statistically significant differences in % Passing, we can start to see a possibility of Thomas High School falsely reporting lower % Passing rates for their 9th-grade students in an attempt to convince the district school board that they may need more funding to help subsidize beneficial educational efforts.


### Thomas High School Relative to Other Schools
With this correction in data, Thomas High School remained in the top five test scores ranking schools in the district (#2!)

### Changes to Aggregated Statistics
Math and Reading scores by grade were generally unaffected save the new "nan" value for Thomas High School's 9th-grade scores for both reading and math.

Changes to scoring statistics based on school spending seemed to only change negligibly if at all

Changes to scoring statistics based on school size seemed to only change negligibly if at all

Changes to scoring statistics based on school type seemed to only change negligibly if at all

## Summary
The biggest changes to the data after replacing the Thomas High School 9th grade values are as follows:
(1) 139.26% increase in average passing math scores for Thomas High School
(2) 139.28% increase in average passing reading scores for Thomas High School
(3) 139.26% increase in average overall passing test scores for Thomas High School
(4) The district's overall % of passing test scores shifted from 65% to 64.1% with the omission of the 461 Thomas High School 9th grade students (represented in the individual & aggregate data as null values - "NaN")


## Conclusion
-The changes to data in regards to Thomas High School did not affect other schools data.
-Aggregate data, however, was skewed marginally due to the effect of the 461 now null entries from Thomas High School's 9th-grade class
-Thomas High School Data had changed considerably and showed trends of much higher actual test scoring from the students at Thomas High School.

-There may have been a mis-inputting or purposeful forgery of test score data from Thomas High School in regards to their 9th-grade class test scores. Regardless, with the omissions of that outlier data, accurate trends and data on the educational successes of each school within the school district based on a myriad of factors such as individual school, budget/funding, school size, and more has been successfully delivered to Maria and presented to the school board.
