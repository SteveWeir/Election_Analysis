# Election_Analysis

##  Election Audit Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv (can be found in 'Resources' folder in this repository)
- Software: Python 3.9, IntelliJ IDEA Community Edition 2020.3.1

## Election Audit Results
The results of the analysis of the election (which can also be viewed in the "election_analysis.txt" file in this repository) are as follows:
- There were 369,711 votes cast in this election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The voter turnout by county was calculated as follows:
    - Jefferson County had 10.5% of the voter turnout, at 38,855 votes
    - Denver County had 82.8% of the voter turnout, at 306,055 votes
    - Arapahoe County had 6.7% of the voter turnout, at 24,801 votes
- The county with the highest number of votes was:
    - Denver County, with 82.8% of the voter turnout (306,055 votes).
- The voting results for each candidate are as follows:
    - Charles Casper Stockham received 23.0% of the vote, at 85,213 votes.
    - Diana DeGette received 73.8% of the vote, at 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote, at 11,606 votes.
- The winner of the election was: 
    - Diana DeGette, who received 73.8% of the vote, at 272,892 votes.

## Election Audit Summary & Proposal for Continued Use
The python code (PyPoll__Challenge.py) that was written for this specific election audit may, with minor modifications, be re-purposed to audit the results of any election or poll. In-code references to the load file "election_results.csv" and the output file "election_analysis.csv" may be altered to reference different files of the client's choosing. Additionaly, variable names may be changed to store data of different varieties. For example, an analyst seeking to interpret the results of a poll regarding sales of different ice cream flavors could easily change the dictionary "candidate_votes{}" to "flavor_votes{}" and the list "candidate_options[]" to "flavor_options[]", and, provided they also ensured that the code referenced the correct column in their load file, read the results of their poll. Such changes would also imply the requirement that the formatting of the output .txt file within the python code would need to be augmented in order to properly display the results of a new election or poll. Despite these small required changes, the vote counting functions and mathematical operations within the code can be applied to analyze the results of any survey-style data set.
