# School_District_Analysis

## Overview of Project
To get a proper ananlysis of the school district grades, while removing the nineth-grade reading and math scores.
	

## Results
The results for our School District dataframe after removing the 9th Grade grades for "Thomas High School" are explained below:

- How is the district summary affected?
	* By removing 9th grade, grades we can see that not much gets affected in the District Summary. at most you can tell that
		the "overall %" was affected by 0.1% (from 65.1% to 64.9%) while "passing math & reading %" stayed the same only the decimals changed. Please note the image 	attached of the District Summary chart
		
	* [District_summary_changes](Resources/District_summary_changes.PNG)
		
- How is the school summary affected?
	* The school summarry is only affected in the "Thomas High School" row. we can see that removing the 9th grader grades
		- The "overall passing" dropped form 91% to 65%
		- the "% passing reading" dropped form 97% to 67%
		- the "% passing reading" dropped form 93% to 83%

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	* Thomas High School performance remained the same in relative to other schools.
		-looking at the image in the question above we can see that the average reading and math scores stayed relatively the same.

		
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade:
	* Math and reading scores were not affected as removing 9th graders did not change the data.
		- we can see by the comparison made on the math and reading scores from the previous and current dataframes dont change
		besides not having the 9th grade data.
	* Scores by school spending
		- Based of the data the Scores by school spending do not seem to change.
	* Scores by school size
		-Based of the data the Scores by school size do not seem to change.
	* Scores by school type
		-Based of the data the Scores by school type do not seem to change.

	
## Summary
- In conclusion we see that by removing 9th grade data, we primary affected the School Summary as this is where it factors in
	total count of 9th graders at Thomas High School (461). 
- If we tried to remove a larger data set, say the value of 10th - 12th grade scores (1174) we may get a more visible 
	change in our analysis.
   
