# Election_Analysis
Election results printed to the command line and saved to a text file using Python
## Deliverable 1 Instructions
1. Using repetition statements, conditional statements with logical operators, and print statements, print out the candidate and county election results to the command line.
Initialize a county list, like the candidate_options list, that will hold the names of the counties.
Initialize a dictionary, like the candidate_votes dictionary, that will hold the county as the key and the votes cast for each county as the values.

2. Initialize an empty string, like winning_candidate, that will hold the county name for the county with the largest turnout.
Initialize a variable, like the winning_count variable, that will hold the number of votes of the county that had the largest turnout.

3.While reading the election results from each row inside the for loop, write a script that gets the county name from each row.

4. Write a decision statement with a logical operator to check if the county name acquired in Step 3 is in the county list you created in Step 1.
If the county is not in the list created in Step 1, add it to the list of county names like you did when adding a candidate to the candidate_options list.
Write a script that initializes the county vote to zero, like you did when you began to track the vote counts for the candidates.

5. Write a script that adds a vote to the county’s vote count as you are looping through all the rows, like you did for the candidate’s vote count.

6. Write a repetition statement to get the county from the county dictionary that was created in Step 1.
Initialize a variable to hold the county’s votes as they are retrieved from the county votes dictionary.
Write a script that calculates the county’s votes as a percentage of the total votes.
Write a print statement that prints the current county, its percentage of the total votes, and its total votes to the command line.
Write a decision statement that determines the county with the largest vote count and then adds that county and its vote count to the variables created in Step 2.

7. Write a print statement that prints out the county with the largest turnout.

8. Write a script that saves each county, the county’s total votes, and the county’s percentage of total votes to the election_results.txt file.
Write a script that saves the county with the largest turnout to the election_results.txt file.

# Written Analysis of the Election Audit

1. erview of Election Audit: Explain the purpose of this election audit analysis.

2. ction-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

3.  many votes were cast in this congressional election?

4. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

5. Which county had the largest number of votes?

6. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

7. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

8. Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
