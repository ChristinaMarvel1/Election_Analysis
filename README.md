# Election_Analysis
Election results printed to the command line and saved to a text file using Python
## Deliverable 1 Instructions
-  Using repetition statements, conditional statements with logical operators, and print statements, print out the candidate and county election results to the command line.
Initialize a county list, like the candidate_options list, that will hold the names of the counties.
Initialize a dictionary, like the candidate_votes dictionary, that will hold the county as the key and the votes cast for each county as the values.

-  Initialize an empty string, like winning_candidate, that will hold the county name for the county with the largest turnout.
Initialize a variable, like the winning_count variable, that will hold the number of votes of the county that had the largest turnout.

-  While reading the election results from each row inside the for loop, write a script that gets the county name from each row.

-  Write a decision statement with a logical operator to check if the county name acquired in Step 3 is in the county list you created in Step 1.
If the county is not in the list created in Step 1, add it to the list of county names like you did when adding a candidate to the candidate_options list.
Write a script that initializes the county vote to zero, like you did when you began to track the vote counts for the candidates.

!(https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/deliverable%201%20through%204.jpg)

-  Write a script that adds a vote to the county’s vote count as you are looping through all the rows, like you did for the candidate’s vote count.

-  Write a repetition statement to get the county from the county dictionary that was created in Step 1.
Initialize a variable to hold the county’s votes as they are retrieved from the county votes dictionary.
Write a script that calculates the county’s votes as a percentage of the total votes.
Write a print statement that prints the current county, its percentage of the total votes, and its total votes to the command line.
Write a decision statement that determines the county with the largest vote count and then adds that county and its vote count to the variables created in Step 2.

![(Resources/deliverable 6 through 8.jpg)](https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/deliverable%206%20through%208.jpg)


-  Write a print statement that prints out the county with the largest turnout.

-  Write a script that saves each county, the county’s total votes, and the county’s percentage of total votes to the election_results.txt file.
Write a script that saves the county with the largest turnout to the election_results.txt file.

# Written Analysis of the Election Audit

1. Overview of Election Audit: Explain the purpose of this election audit analysis.
    
    The purpose of this audit was to tally the election results across the three counties of Jefferson, Denver, and Arapahoe. After calculating the total votes, we calculated the votes for each county which helped us determine whiach had the largest county turnout, which candidate won which percentage of votes and who was the elected candidate. 

2. Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

![(Resources/text file from Interactive Window.jpg)](https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/text%20file%20from%20Interactive%20Window.jpg)


3.  How many votes were cast in this congressional election? 
    
    369,711 votes were cast.

4. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![ (Resources/county votes.jpg)   ](https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/county%20votes.jpg) 

5. Which county had the largest number of votes?

    Denver county had the largest number of votes.

6. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![[percentage votes] (Resources/percentage votes.jpg)](https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/percentage%20votes.jpg)

7. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![[winner] (Resources/percentage votes.jpg)   ](https://github.com/ChristinaMarvel1/Election_Analysis/blob/e075c295deae6774e7c84cfb56807c159c951ef3/Resources/winner.jpg) 

8. Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

    In this audit we used Python to pull summaries from the CSV file containing our data. With that we were able to calculate the 
candidate winner and what percentage of the vote they recieved. Since we pulled the county votes, we could do a query on the rest of the candidates and how they fared in each county. Then, we could see not only who won, per county, but also who won with the percentage of the votes in each county. This can help the losing candidate find out what counties they fared well in so for future elections, they will know where to focus their canvassing. It would also be good for the winner, Diana DeGette to know what counties she didn't fare as well in so those counties can be focused on for future elections. 
        
