# Election-Analysis
## Project Overview
The objective of this project is to complete an election audit given from a Colorado Board of Elections of a local election. 

Tasks include:

1. Calculate the total number of votes
2. Create a list of candidates that received votes
3. Calculate the number of vote each candidate received
4. Calculate the percentage of votes each candidate received
5. Announce the winner based on the popular vote 

## Resources
- Data Source: election_results.csv 
- Software: Python 3.7.6, Visual Studio Code 1.63.2

## Summary
From the analysis we can show that:
- There were 369,711 votes cast
- The Candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote with 85,213 votes 
  - Diana DeGette received 73.8% of the vote with 272,892 votes 
  - Raymon Anthony Doane received 3.1% percent of the vote with 11,606 votes 
- The winner of the election was:
  - Diana DeGette with 73.8 percent of the vote



## Challenge Overview 

Analyze the county election data in addition to the candidate and general election data

## Challenge Results

- County vote totals:

![](https://github.com/alexlieberman22/ElectionAnalysis/blob/main/Analysis/County_data.PNG)
  
- County with the largest number of votes:
  - Denver with 306,055 votes

## Challenge Summary

This code has the capability to read and analyze data from other elections. Any number of candidates and counties can be stored in dictionaries and presented in a txt file. This would however require the same exact format as in the election_data.txt file. With a different format of txt file or additional election data from each voter, the code can be modified to read whichever column is important and/or show additional data on top of counties and candidates (such as voter age, gender, ethnicity etc.). The same code structure for candidates and counties can be added onto the code to accommodate other data fields.
