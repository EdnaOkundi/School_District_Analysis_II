# School_District_Analysis_II

Overview
A school district asked for a snapshot of several key metrics by each school campus and by the district level. 
The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. 
However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. 
The school board asked for the data to be removed and analyzed again for a comparison.

Process
Open Jupyter Notebook files from local directories using a development environment.
Read an external CSV file into a DataFrame.
Format a DataFrame column.
Determine data types of row values in a DataFrame.
Retrieve data from specific columns of a DataFrame.
Merge, filter, slice, and sort a DataFrame.
Apply the groupby() function to a DataFrame.
Use multiple methods to perform a function on a DataFrame.
Perform mathematical calculations on columns of a DataFrame or Series.

Results
How is the district summary affected?
The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, 
passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, 
which was not turned into null data.The adjusted analysis showed that removing less than 500 test scores had a nominal impact on the
almost 40,000 student data set. The change was less than a 1% difference and the numbers would still round to the same whole number.

How is the school summary affected?
In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board 
as being too high. After calculating the total number of 10th - 12th grade students as the new denominator, 
the rest of the testing data was adjusted accordingly.Results showed that removing the 9th grade students from the data set had a 
huge impact by dropping from 91% to 65% for the overall passing rate.In the original analysis, 
Thomas High School ranked 2nd in the district raising red flags with the school board.After adjusting the 9th grade data, 
it ranked in the exact middle of 15 campuses at 8th from the bottom.

Adjusted Averages using the Math and Reading Scores:
In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. 
Now the scores have been replaced with null values and shows up in Python programming as NaN. 
Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes.
There was very little spending impact by changing the 9th grade scores.

Scores by school size:
Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes.
There was very little impact by campus size due to changing the 9th grade scores.

Summary

-The overall passing rate for Thomas High School changed dramatically from 91% to 65%.
-Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.
-Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School
-In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.
-The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.

Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes