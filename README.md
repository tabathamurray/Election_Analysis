# Detailed Instructions From Your Instructor Team

The objective of this challenge is for you to gather additional information by using repetition and decision statements with membership and logical operators, print the data to the command line, and save data to an output file, and write a report on the election analysis.

## Deliverable 1: The Election Results Printed to the Command Line

For the first deliverable, we are asking you to use your knowledge of `for loops`, `if` statements with membership and logical operators, and write print statements using `f-strings` to print the candidate and county election results to the command line.

We have provided you with a [PyPoll Challenge starter code](./Resources/Starter_code/PyPoll_challenge_starter_code.py) that includes the solution for the election results for Module 3, and has commented steps in the starter code file where you will need to add the code to complete this part of the challenge.

## Deliverable 2: The Election Results Saved to a Text File

For the second deliverable, we are asking you to use your knowledge of writing data to file to add the winning candidate results and the county election results to the `election_analysis.txt` text file (see [election_analysis.txt](./Analysis/election_analysis.txt)) for view of finished text file you are trying to create.

In the [PyPoll Challenge starter code](./Resources/Starter_code/PyPoll_challenge_starter_code.py) we have provided commented steps in the starter code file where you will need to add the code to complete this part of the challenge.

## Delivering Results: Written Analysis of the Election Audit

The goal of the writing assignment is for you to present your findings in a logical manner. As a reminder, you should use appropriate grammar and structure when writing.

For the written analysis, you should use the repository README.md to write your report. The report will contain three sections: an overview of the election audit, election audit results, and election audit summary.

**Overview of Election Audit:** Explain the purpose of this analysis. 

The purpose of this analysis is to review a cvs file containing election data and provide a concise election results using the following learned from this week: lists, dictionaries, decision statements, appending lists, calculating percentages, and printing results to a text file.

**Election Audit Results:** Using a bulleted list, address the following election outcomes. Use images of examples of your code if necessary to support your evidence.

- How many total votes were cast in this congressional election?

369,711

- Provide a breakdown of number of votes and percentage of total votes for each county each in the precinct.

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

- Which county had the largest number of votes?

Denver

- Provide a breakdown of the number votes and percentage of total votes each candidate received.

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their total number of votes and percentage of total votes?

Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

**Election Audit Summary:** In a summary statement provide a business proposal to the election commission on how this script can be used for any election with some modifications. Give at least two examples of how this script can be modified to meet business requirements to convince the election commission to use this script for future elections.

This script can easily be used for another upcoming election. The script concisely analyzes 369,711 votes to provide the largest county turnout, exact count for each candidate, and the winner. The script can be modified to show the smallest county turnout. This number can be useful when trying to see need to up their turnouts. You can also add additional counties to the csv file, and you would obtain the results you are looking for.

**Hint:** In the statement, we would like you to use some critical thinking. Here are a few examples that will meet this requirement:

* Refactor the election script by using functions.  Although we haven't covered writing functions (D.R.Y) in this module, the Day 2 Required lesson plan does have an activity.

* Adding a condition-controlled loop (`while loop`) to ask the user the name of the input file and output file to save the data, if give many files.

* Adding a repetition statement (`for loop`) to loop through many input files and using the file name as a parameter for a function.

The README.md document should be in the home directory of their repository. All links should be working, and images and code should be formatted and displayed where appropriate.

## Grading Rubric

The [PyPoll Grading Rubric](./Resources/PyPoll_Grading_Rubric.pdf) is provided for you to use when grading the you' submissions.
