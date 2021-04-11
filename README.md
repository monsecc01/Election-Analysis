# Election-Analysis
Analysis of election results with Python

## Resources
Data Source: [election_results.csv](https://github.com/monsecc01/Election-Analysis/blob/9bea6ec438ec9c0f408b33f3377d84d3235eaafa/election_results.csv)

Software: Python 3.9, Visual Studio Code 1.55.1

## Overview of Election Audit:
In this project we will help Tom, an employee of the Colorado Board of Elections, complete an election audit analysis for a recent congressional election in a Colorado precinct. Through analysis of election results, we will provide the election commission the following data:
1.	Total number of votes cast
2.	A complete list of candidates who received votes
3.	Total number of votes each candidate received
4.	Percentage of votes each candidate won
5.	The winner of the election based on popular vote
6.	Voter turnout for each county
7.	Percentage of votes for each county
8.	Identification of county with highest voter turnout 

## Election-Audit Results: 
*	Number of votes cast in this congressional election
    * Total Votes: 369,711
*	A breakdown of the number of votes and the percentage of total votes for each county in the precinct
    * Jefferson:10.5% (38,855)
    * Denver:82.8% (306,055)
    * Arapahoe:6.7% (24,801)
*	County with the largest number of votes
    * County with Largest Turnout: Denver with 306,055 votes
* A breakdown of the number of votes and the percentage of the total votes each candidate received
    * Charles Casper Stockham: 23.0% (85,213)
    * Diana DeGette: 73.8% (272,892)
    * Raymon Anthony Doane: 3.1% (11,606)
*	The candidate who won the election, their vote count, and their percentage of the total votes
    * Winner: Diana DeGette
    * Winning Vote Count: 272,892
    * Winning Percentage: 73.8%

![Election Results](https://user-images.githubusercontent.com/81447450/114289601-f12f7080-9a3e-11eb-9b36-2cfb525b11c0.png)
   
## Election-Audit Summary: 
If the Colorado Board of Elections intends on analyzing election data in the future, we propose the use of this script. As long as the election results csv file has data for Ballot ID, County, and Candidate, the script will be functional for other elections. Modifications to names for file paths and the election results file may be required to run the script without errors if they are different.

![path code](https://user-images.githubusercontent.com/81447450/114289640-3fdd0a80-9a3f-11eb-916b-3e9ac2db9824.png)

Furthermore, this script could be used for additional analysis of the current election results. One example would be candidate votes by county to understand how candidates performed in different counties. If additional data were added to the election results, like age, race, or gender, we could further analyze vote counts by various categories. However, it is recommended to import the Pandas package to facilitate data analysis. 
