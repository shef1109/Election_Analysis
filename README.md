# Election_Analysis 


## Project Overview

A Colorado Board of Elections employee requested your help in completing an election audit of a recent local congressional election. The following tasks are to be included in the completed election audit.

	1. Calculate the total number of votes cast. 
	2. Get a complete list of candidates who received votes. 
	3. Calculate the total number of votes each candidate received. 
	4. Calculate the percentage of votes each candidate won. 
	5. Determine the winner of the election based on popular vote. 
	
## Challenge Overview

The employees, Seth and Tom, have submitted the *first draft* of our election audit results to the election commission. However, the election commission would like more information to finalize the audit. They are requesting us to determine the following data to add to our *final election audit*:

	1. The voter turnout for each county
	2. The percentage of votes from each county out of the total count
	3. The county with the highest turnout

## Resources

**Data Source:** election_results.csv

**Software:** Python 3.7.6, Visual Studio Code 1.72.2

## Summary

### Audit Results
![Election_Results](/Resources/Election_Results.png)

The analysis of the election results (as provided in the image above) show that:
* There were 369,711 votes cast in the election.

* The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane

* The county vote results were:
	- Jefferson county received **10.5%** of the votes and _85,213_ number of votes.
	- Denver county received **82.8%** of the votes	and _306,055_ number of votes.
	- Arapahoe county received **6.7%** of the votes and _24,801_ number of votes.

This data confirms that Denver county has the largest number of votes during this election.

* The candidate results were:
	- Charles Casper Stockham received **_23.0%_** of the vote and _85,213_ number of votes.
	- Diana DeGette received **_73.8%_** of the vote and _272,892_ number of votes.
	- Raymon Anthony Doane received **_3.1%_** of the vote and _11,606_ number of votes.
  
 * The **winner** of the election was:

    **Diana DeGette**, who received **73.8%** of the total votes and **272,892** number of votes.
	
### Audit Summary
Currently, our script is able to effectively find votes counts, percentage of votes won by each county, provide a candidate breakdown by percentage of votes and number of votes, and determine who the winner of the election was. Therefore, using a similar code we wrote to find the candidate breakdown, we can also figure out what the percentages of each county voted for each candidate. We can do something like this by adding another *if* statement that will give us a breakdown showing what counties voted for who. This can be used for any future election because it gives us a more detailed breakdown of counties, or further modify and even expand to entire states, to provide us with more data for election audits.
