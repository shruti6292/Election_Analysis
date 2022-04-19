# Election_Analysis

## Project overview

### A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election. I have to finish the tasks as below:
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
1. data Source : election_results.csv
2. Software : Python 3.10
3. Visual Studio Code 1.63.2

## Summary

### The analysis of the election shows that:
1. There were "369,711" votes cast in the election.
2. The candidates were:
   - a). Charles Casper Stockham
   - b). Diana DeGette
   - c). Raymon Anthony Doane
   
The Candidate results were:
  - a).Candidate 1 received 23.0 % of the vote and 85213 number of votes.
  - b).Candidate 2 received 73.8 % of the vote and 272892 number of votes.
  - c).Candidate 3 received 3.1 % of the vote and 11606 number of votes.
  
The winner of the election was:
  - Candidate b).Diana DeGette , who received 73.8 % of the vote and 272892 number of votes.
  
  ## Challenge Overview
  After doing analysis and submitting election audit results to the election commisiion, they requested some additional data to complete the audit. I have to finish the additional tasks as below:
  - 1.The voter turnout for each county
  - 2.The percentage of votes from each county out of the total count
  - 3.The county with the highest turnout
    
  ## Challenge Summary
  For the additinal data for audit, we have to read counties from the given data source and extract the number of counties first.
  Then by using repetition statements like for loops, conditional statements with logical operators like if and greater than and using f strings in print statements, we were able to format the results in the way as wanted by the election commisssion. 
Lot of formatting has to be done to get the exact format of the results.

## The additional analysis of the election shows that:
1. There were "369,711" votes cast in the election.
2. The counties were:
   - a). Jefferson
   - b). Denver
   - c). Arapohoe
   
The County voter's turnout was:
  - a).Jefferson county 38,855 votes which makes 10.5% of total votes.
  - b).Denver county 306,055 votes which makes 82.8% of total votes.
  - c).Arapohoe county 24,801 votes which makes 6.7% of total votes.
  
The highest turnout county was:
  - County b).Denver county 306,055 votes which makes 82.8% of total votes.
 
 ## Election Audit Summary
 This analysis could be used to any other type of elections in Colorado Board of education. We have program to know all the candidates, the counties and voter turnout. One modification we can do from the given data source is to show the county of each candidates in the results. By doing that one can find the corelation between voters turnout per county and the winning candidate.
 We can modify this script for town mayorial race as well as for the board of directors election in public schools.
