# School_District_Analysis

## Project Overview
Maria, the city’s school district chief data scientist, analyzes information from a wide-ranging variety of sources, and in numerous formats. For this project, I will assist Maria with preparing the standardized test data for analysis, reporting, and presentation by aggregating the data to showcase the district’s school performances, trends, and patterns. All of which will provide the school board and superintendent with the valuable insights necessary to have informed discussions and make strategic decisions regarding the schools’ budgets and priorities.
During the course of the analysis, it was discovered that a discrepancy involving Thomas High School’s ninth grade students would render their math and reading scores unusable. Once Thomas High School’s ninth graders’ scores were removed, Maria requested the following deliverables:
-	A high-level snapshot of the district's key metrics, presented in a table format
-	An overview of the key metrics for each school, presented in a table format
-	Tables presenting each of the following metrics:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

## Resources:
- Data Source: clean_students_complete.csv, missing_grades.csv, schools_complete.csv, students_complete.csv
- Software: Anaconda, 2022.10, Jupiter 1.0.0, Pandas 1.4.4

## Results:
Th effect of replacing Thomas High’s school’s ninth-grade scores on the listed metrics are the following:
-	Removing the math and reading scores of Thomas High School’s ninth grade students caused a less than one percent decrease in the district’s average math and reading scores, as well as the percentage passing math and reading scores, and lastly the percentage overall passing score.
-	Excluding Thomas High’s school’s ninth graders’ scores from the school summary affected it in that Thomas High School’s percentage passing scores in math and reading—individually, as well as overall--were significantly higher than previously recorded.
-	Replacing the ninth graders’ math and reading scores did not affect Thomas High School’s performance relative to the other schools. Thomas high school still ranked as the second-best high school in the district.
-	Math and reading scores by grade: All Thomas High’s school’s ninth graders’ scores were excluded from the data.
-	Scores by school spending: The spending ranges remained the same although Thomas High’s school’s recalculated scores very slightly lower.
-	Scores by school size: Just as the scores-by-school-spending metric, Thomas High’s school’s scores by school size ranges remained the same despite the recalculation.
-	Scores by school type: Although removing Thomas high school’s ninth grade students’ scores insignificantly lowered the charter schools’ grades across the board, charter schools still notably outperformed district schools.

## Summary
In summary, although replacing Thomas High School’s ninth grade reading and math scores with NaNs made no significant difference in the update analysis. It is important that the changes in values are pointed out.

District Summary df Before THS Edit:

![alt text](Resources/District%20Summary%20df%20Before%20THS%20Edit.png)


District Summary df After THS Edit:

![alt text](Resources/District%20Summary%20df%20After%20THS%20Edit.png)

The changes resulted in deviations from the original analysis’ average math scores, average Reading scores, passing math percentages, passing reading percentages, and overall percentages for: the district (see images above)., the school-spending, school-size, and school-type metrics, as well as Thomas High School’s individually calculated metrics.
