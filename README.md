# Election_Analysis

## Project Overview

#### The purpose of this challenge is to complete the election audit of a recent local election and project the following results:
1) Total number of votes that were cast
2) Vote distribution by county
3) List of candidates who received the votes and the total votes each received
4) Percentage of votes each candidate won
5) Winner of the election

## Resources used

* Data file: election_results.csv
* Software: Python 3.7.6, Visual Studio Code 1.60.2

## Results

#### Total votes of the election are saved as election_results.txt file. The results of the analysis are as seen below:

1) Total number of votes: 369,711

2) County results
     * Jefferson: 10.5% (38,855)
     * Denver: 82.8% (306,055)
     * Arapahoe: 6.7% (24,801)

3) Candidate results with percentage
     * Charles Casper Stockham: 23.0% (85,213)
     * Diana DeGette: 73.8% (272,892)
     * Raymon Anthony Doane: 3.1% (11,606)

4) Final winner
     * Winner: Diana DeGette
     * Winning Vote Count: 272,892
     * Winning Percentage: 73.8%

## Summary of analysis

#### This script can be used to determine total votes cast in any local election. It firther breaks down the information into total votes by county and by candidate, and also finally outputs the winner name and by how many votes and percentage they won. A database containing ballot ID, county and candidate selection will be sufficient to provide these results.

#### A practical use of this script can be applied in universities and colleges to determine election of student councils and different student organizations. This script can also be used at state level by using different sets of databases to extract desirable information and output and determine state elections.
