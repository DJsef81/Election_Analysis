# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Caclulate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate recieved. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.
6. Which County had the largest number of votes?

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.0, Visual Studio Code, 1.49.3

## Summary 

[Click here for the election analysis](election_analysis.txt)

The analysis of the election show that:
- There were 369,711 votes cast in the election. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The Candidate results were: 
  - Charles Casper Stockham recieved 23% of the vote and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the vote and 272,892 number of votes. 
  - Raymon Anthony Doane recieved 3.1% of the vote with 11,606 number of votes.
- The winnner of the election was:
  - Diana DeGette, who recieved 73.8% of the vote and 272,892 number of votes. 
- The county with the largest number of votes was:
  - Denver, with 306,055 votes cast in the county, equal to 82.8% of the total votes cast. 
- The other two counties number of votes were
  - Jefferson, with 38,855 votes cast in the county, equal to 10.5% of the total votes cast.
  - Arapahoe, with 24,801 votes cast in the county, equal to 3.1% of the total votes cast. 

## Challenge Overview
Based on our findings in our summary, Dinan DeGette came out as the clear winner with almost 3/4ths of the total votes. In second place was Charles Casper Stockham with almost 1/4th of the total votes. In a distant third was Raymon Anthony Doane. Adding all our candidates vote percentages leaves us with a 99.9% total. While that's not a definite 100%, it's pretty close, and has no affect on the outcome. 

Of the three counties, Denver is by far the most represented in terms of sheer number of votes, probably because of its population size in comparison to the other two counties, but that is just an assumption. 

## Challenge Summary
Based on the findings after running and analyzing the output of our script, I am confident in proposing to the Election Commission that they utilize this script, albiet, with some minor alterations, for future election analyses. This is under the assumption that future audits exectued by the Election Commission would collect and store their data the same as they did in the election_results.csv file.

"# Add a variable to load a file from a path."
"file_to_load = os.path.join("../Resources/election_results.csv")"
"# Add a variable to save the file to a path."
"file_to_save = os.path.join("analysis", "election_analysis.txt")"
