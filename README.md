# Election_Analysis

## Overview of Election-Audit:

This program reads through a CSV file to gather many metrics that ulitmately calculates the winner of the election. The data is spread across three different counties and three different candidates. Outcomes of the file include: total votes, breakdown of votes by county and candidate with percentages, and the winning candidate.

## Election-Audit Results:

* Total number of votes cast: 369,711
* Vote breakdown by county
    * Jefferson: 38,855 votes, 10.5%
    * Denver: 306,055 votes, 82.8%
    * Arapahoe: 24,801 votes, 6.7%

* County with the largest number of votes: Denver  
* Vote breakdown by candidate:
    * Charles Casper Stockham:  85,213 votes, 23.0%
    * Diana DeGette: 272,892 votes, 73.8%
    * Raymon Anthony Doane: 11,606 votes, 3.1%
* Winning candidate:<br />
Diana DeGetter<br />
Votes: 272,892<br />
Percentage: 73.8%

## Election-Audit Summary
How the program works:
This program reads CSV files and converts them into a  txt. file. The CSV headers must be formatted as followed to run with this program

Ballot ID, County, Candidate 

If the the CSV file is formatted differently, then the python program can be reconfigured in line 49 and 52.

The path between python program is built to pull from a folder "Resources" and the file "election_results.csv and push to a folder "analysis" and the file "election_analysis.txt.
(These are found on line 9 and 11, respectively) 

For further use, files and pathway must be formatted in the same manner or python program can be altered to load and save the correct data.
