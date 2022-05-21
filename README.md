# Election_Analysis

## Overview of Election Audit

A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of counties represented.
3. Calculated the total voter turnout in each county.
4. Determine the county with the largest voter turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

I have been asked to assist in the confirmation and analysis of the election results using Python.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.62.2

## Election-Audit Results

The analysis of the election show that:
- There were 369,711 total votes cast in the election.
- The counties were:
    - Jefferson
    - Denver
    - Arapahoe
- The county results were:
    - Jefferson County represented 10.5% of the the votes and 38,855 of votes.
    - Denver County represented 82.8% of the votes and 306,055 of votes.
    - Arapahoe County represented 6.7% of the votes and 24,801 of votes.
- The county with the largest turnout was:
    - Denver County with 82.8% of the votes and 306,055 votes.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane receive 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary

In conclusion, we have been able to verify that the election results were correct, and have provided a full layout of results above.

This script was not only useful for this audit, but we can also utilize this script for future elections. For example:

1. If we have an election with more candidates, we can utilize the script as is - the loops are set up to add candidates and their votes to the list and dictionary if they are not already in the list.
2. If we do another election analysis and audit on a larger scale, we can update the "counties" information in the script to states or districts.

Now that this election audit script is built, it will be easy to adapt to any future elections.
