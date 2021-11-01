# Election_Analysis

## Project Overview
The purpose of this project is to assist Seth and Tom with an election in Colorado. A congressional election was just recently held and the raw data stored in a csv file. Our job is to take this raw data and summarize it. This will include breaking down the votes into counties, and candidates, and we will determine the share of the vote in each. Ultimately, we will determine the winner and the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.0, Visual Studio Code, 1.61.2

## Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The counties were:
  - Jefferson
  - Denver
  - Arapahoe
- The county results were:
  - Jefferson had 10.5% of the vote share and 38,855 total votes.
  - Denver had 82.8% of the vote share and 306,055 total votes.
  - Arapahoe had 6.7% of the vote share and 24,801 total votes.
- Denver had the largest number of votes of the 3 counties.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote share and 85,213 total votes.
  - Diana DeGette received 73.8% of the vote share and 272,892 total votes.
  - Raymon Anthony Doane received 3.1% of the vote share and 11,606 total votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote share and 272,892 total votes.

![txt_file_results](https://user-images.githubusercontent.com/91795475/139605246-e198ab31-9774-4231-81a4-011b12ed53ec.PNG)

## Election-Audit Summary
The script we wrote for this election could be used in a multitude of ways. Theoretically this script can be used for any election, with some modifications. Since we made the candidate and county variables dictionaries and lists, we can use the same variables if there are more candidates/counties. The main thing we would have to change is the inputs from a different csv or other file. Specifically, the row function we used to read the candidates and counties would at the very least likely have a new value for the index to get the information we want. This modified script could be used for virtually any election from the local to the national level. Examples include a mayoral election or an election for a congressional district. We would need a few more modifications for the election of president of the united states to account for the electoral college, but we could still use the code to determine which candidates win which states. Then we would just have to add electoral votes for each won state and we could determine the winner. This code can alos be modified to more than just political elections. A company who votes in members or votes in leaders can use this script as well. We could even go further with different applications. While it would require many changes or revisions, the basis of the script could be used for any number of competitions with a binary outcome. While the text would be mostly rewritten, much of the rest of the script could stay close to the same for say a script that determines the standings of teams in a sports league. Calculating the number of wins would be very similar to calculating the total votes each candidate got,
