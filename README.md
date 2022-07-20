# Election Audit Analysis

## Project Overview
A Colorado election commission requests an election audit and analysis of a local congressional election. The expected results should include:
- Total votes
- Total county votes and percentage by county
- County with the highest voter turnout
- Candidate votes and percentage of total votes
- Winner of the election with total and percentage of votes

### Resources
- Data source: election_results.csv
- Software: Python 3.9.12; Visual Studio Code 1.69.0

### Election-Audit Results:
The project requirements exceute a Python program that reads the election data set, compiles the requested information, and prints the results to a text file and a terminal screen. 

1. Total votes cast in the congressional election
  - There were 369,711 total votes cast in the congressional election. 
     
2. Breakdown of the number of votes and percentage of total votes for each county in the precint.
  - Three counties had voter returns in the data file provided; they were Jefferson, Denver and Arapahoe. Of the 369,711 votes cast, 10.5% (38,855) were from Jefferson; 82.8% (306,055) were from Denver; and 6.7% (24,801) were from Arapahoe. 


3. Which county had the largest number of votes?
  - The county with the largest voter turnout was in Denver County with a turnout rate of 82.8%. 

4. The total number of votes and percentage each candidate received.
  - There were three candidates in the election audit. The results by candidate are provided as they appear in the text file and on the terminal screen.
    - Charles Casper Stockham received 23.0%, or 85,213 votes
    - Diana DeGette received 73.8%, or 272,892 votes
    - Raymon Anthony Doane received 3.1%, or 11,606 votes

5. Identify the winner of the election, their vote count and percentage of total votes.
  - The winner of the election audit was Diana DeGette, with 73.8% (272,892) of the vote. 

### Text File Results
An image of the text file is provided to demonstrate the requested output results to a text file.
 
  ![img](https://github.com/DannyJohnson-Hi/Election_Analysis/blob/main/FinalResults.png)
 
 
### Election-Audit Summary
The election commission may wish to consider some additional functionality to the related Python program used to develop the attached audit. For example, it might be beneficial to discover the winning candidate by county. By adding an additional "if" statement to the current code, the number of candidates per county could be calculated, providing more specifc data into the voting patterns within a given county. It would also be interesting to find voter turnout by race/ethnic group. We would need to add a row to the .csv file, calculate the total votes and percentage to the total amount of votes. This would allow each candidate to get a vision of their voter fanbase.


The provided Python script audit is adaptable and can be used on a much wider scale. The data provided for this audit includes three counties in the state, but the audit program can be modified/adjusted to a much larger data set, and could be expanded to all counties in Colorado. I propose the election committee utilize this simple analysis tool as the state-wide solution for congressional election audits. This program is simplistic in design, but very powerful in the range of data that can be returned.

