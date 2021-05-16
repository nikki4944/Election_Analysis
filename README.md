# election_analysis
Module 3 Challenge

## Overview of Election Audit
In this deliverable, we were tasked with performing a vote audit to certify a Congressional election for a district spanning three counties. The data was compiled from votes cast which were then counted by hand, machine, and computer.

In this analysis, I used Python and Visual Studio Code to write a code determining how many ballots were cast and the winning candidate. This code also breaks the data down to determine how many ballots, and the percentage of total ballots, were cast in each county in the district as well as how many votes, and the percentage of total votes, each candidate in the election received.

## Election Audit Results
Using the following code, I determined the total number votes cast in the election, the number of candidates on the ballot, and the amount of ballots cast in each county in the district.

<img width="924" alt="County and Candidate Vote Totals" src="https://user-images.githubusercontent.com/82982901/118411467-b97d9f00-b662-11eb-831e-1c0723881104.png">

This code provided the vote county breakdown by candidate and county to be:
* 369,711 total votes were cast in the election
* For the three counties in the district:
    - Jefferson County contributed 38,855 votes
    - Denver County contributed 306,055 votes 
    - Arapahoe County contributed 24,801 votes 
* For the three candidates on the ballot:
    - Chasles Casper Stockham received 85,213 votes
    - Diana DeGette received 272,892 votes
    - Raymon Anthony Doane received 11,606 votes

After determining the total number of votes received in the election and total number of votes contributed by each county, I wrote additional code to calculate the percentage of total votes by county.

<img width="792" alt="County Vote Percentage" src="https://user-images.githubusercontent.com/82982901/118411933-2c881500-b665-11eb-8fda-2d78c6687fa8.png">

Based on this calculation, Denver County contributed the largest percentage of the total vote:
* Jefferson County- 10.5%
* Denver County- 82.8%
* Arapahoe County- 6.7%

Using a similar code, I was able to calculate the percentage of votes received by each candidate and determine the winner of the election.

<img width="708" alt="Candidate Vote Percentage" src="https://user-images.githubusercontent.com/82982901/118412041-cfd92a00-b665-11eb-8250-532c7cd71d85.png">

The winner of the election was Diana DeGette with each candidate receiving the following percentages:
* Charles Casper Stockhame 23.0%
* Diana DeGette 73.8%
* Raymon Anthony Doane 3.1%

Finally, I wrote code which printed these results to the command line and saved them to a text file for delivery to the election commission.

<img width="319" alt="Command Line Results" src="https://user-images.githubusercontent.com/82982901/118412108-2fcfd080-b666-11eb-9199-ea02afadefbd.png">

## Election Audit Summary
The code written for auditing the results of this Congressional disctrict election could easily be modified to analyze the results of state-wide races. If a larger data set was provided which included district information, the code could be adapated to provide the results, in the same format provided in the text file, for other Congressional districts. Additionally, if the data set also included the race information, such as governor or senate or congressional district, the code could also be modified to provide those results as well.
