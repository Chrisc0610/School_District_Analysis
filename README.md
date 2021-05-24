# School_District_Analysis

## Overview of Project
To get a proper ananlysis of the school district grades, while removing the nineth-grade reading and math scores.
	

## Results
The results for our School District dataframe after removing the 9th Grade grades for "Thomas High School" are explained below:

- How is the district summary affected?
	* By removing 9th grade, grades we can see that not much gets affected in the District Summary. at most you can tell that
		the "overall %" was affected by 
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
	* Scores by school spending
	* Scores by school size
	* Scores by school type

	
## Summary
I beleive that this script may be used not only for auditing this congressional board for Colorado but for any State, Country or any voting pool.
Based on our outcomes from the Colorado audit we can see that with this script, we are able to parse through an immense amount of data in a matter 
of seconds. Not only are we able to get the percentage outcomes for each candidate, but what if half way through the race another candidate decides to 
run for office? Well by simply adding the information to our current CSV file the script will automatically add the new candidate names and counties 
to our outcome. Refer to the image below, notice that 3 new candidates from 3 separate counties have joined this election. The script went ahead and 
added the calculations for the votes.

Futhermore, with the past election there were rumors that the election was rigged and that every vote should be counted. Well with this script
we can assure that all ballots will be accounted for. The most simple way to do this is by simply adding a new variable to load data from. By looking at
the example below we can see that our list of candidates for smaller while our list for counties got much bigger. This is a sample of how the script would run 
with a different data set. 


Please note if you were to do it on a country level, the "county" variable would be switched to "states".
   