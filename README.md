# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you jthe follwing tasks to complete the election audit of a recent local congressional election

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Stuido Code, 1.61.0

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The Candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

 ## Challenge Overview
 The objective of this Module overall was to review and audit the election results for a theoretical Colorado congressional election, provided as a comma-separated value (CSV) file, to confirm the total number of votes cast, the candidates who received votes, their total votes, their percent of the overall votes, and the top vote-getter. 
 
 In the challenge phase of this Module, the goal was to provide additional analysis of the .csv file to determine the per-county voter turnout, the percentage of voters from each county per the total vote count, as well as determining the county with the highest number of votes cast (Note: voter turnout, as the module references as an outcome, is frequently calculated as a rate of total votes cast divided by eligible voters or total potential voters, and not just a simple count of votes cast per election).

 ## Challenge Summary and Results
The following is an image output of the executed terminal command from the PyPoll_Challenge.py file:
- [XXX]
The follwing is an image output of the elections_analysis.txt file:
- [YYY]

The following outcomes were found from the Challenge analysis:
- A total of 369,711 votes were case in the congressional election.
- The per-county breakdown of vote counts and percentage per county is as follows:
  - Jefferson county voters cast 38,855 votes, which was 10.5% of the overall congressional district votes cast.
  - Denver county voters cast 306,055 votes, which was 82.8% of the overall congressional district votes cast.
  - Arapahoe county voters cast 24,801 votes, which was 6.7% of the overall congressional district votes cast.
- Denver county provided the largest number of votes (306,055), eclipsing the Jefferson and Arapahoe county voters. I hope there is little to no gerrymandering involved.
- There were three candidates who received votes in the election, and a vote count and percent of votes for each candidate is as follows:
  - Charles Casper Stockham recived a total of 85,213 votes, which was  23.0% of the total vote count.
  - Diana DeGette recived a total of 272,892 votes, which was  73.8% of the total vote count.
  - Raymon Anthony Doanerecived a total of 11,606 votes, which was  3.1% of the total vote count.
-The overall winner of the popular vote, by a wide margin, was Diana DeGette, who captured 272,892 (73.8%!) of the district's votes. Were this not a district that appears to be in the geologically active Upper Colorado Basin, I'd call this a landslide. But given regional sensitivities, let's just call it a thorough a**-kicking for Ms. DeGette.

## Challenge Conclusion
In summary, the script in this challenge was able to provide a successful audit of the election results with confidence that the results were sound, and that votes per county can be reviewed compared to county voter registration records to ensure no funny business. In the future, this audit could be compared to a later congressional race in the distric to observe changes in voter preference, and possibly identify vote manipulation based on voting trends that lay outside accepted statistical models for voting preferences over time. In the future, additional improvements should be made to the script to better understand the per-county voting trends given the population dominance of Denver County. Not only would this information be informative to a decennial census-based redisctricing, but it would assist candidates in understanding the electorate and the variability of their votes from electio to election. Furthermore, python script could be further leveraged to perform statistical analysis on the results. This could be done at the district level, as well as the county level to help identify key differentiators in the district that lead to substantial voting trends.