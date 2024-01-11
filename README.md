# CSC 340 Spring 2024 Individual Assignment 1

This assignment is to make sure you are comfortable using Git. At the end, you will have created your own branch off of a main branch, made your own edits, pushed those edits back to the origin. \
You will have sent a pull request to have your changes merged with the main branch. Be sure to add your GitHub username to the assignment "Give Me Your Github Username" located on this Canvas course. \
You will receive an invitation to participate in the project via email once I have added you as a collaborator to the GitHub repo. That's when you know you will have permission to push your changes to the GitHub server.
## Step One: In your OneDrive location, navigate to your workspace for CSC340 projects. 
Do not go into any previously created repositories!

## Step Two: Right-Click on an empty space and start a Git Bash terminal/Git GUI dialog. 
MacOS users can just start a regular terminal.

## Step Three: Clone this repository to your local machine.
https://github.com/csc340-sp24/assignment-1.git

## Step Four: Change directory into the the repository you just cloned. 
cd assignment-1


Look for the blue text that says (main)/(master)

## Step Five: Create your own branch.
git checkout -b [ BRANCH NAME ]


where [ BRANCH NAME ] is your first initial and last name, e.g. John Doe would be jdoe

## Step Six: Open the file AboutMe.txt and in a text editor.
Add your name, underline it using dashes. Write a short paragraph about yourself. 

Do not use a word processing program.
This will add formatting characters that can break the readability of a plain text file. Use a text editor such as Notepad++ or SublimeText. The file type should remain as .txt, not .rtf, or .pdf, or .doc, or .docx.\
Note: This file is public. Do not add any information that you would not want someone to read who might happen upon it.

## Step Seven: Add the edited file to the staging area.
git add AboutMe.txt

## Step Eight: Commit your changes to the repository.
git commit -m 'a short description of why you are making this commit'

## Step Nine: Pull from the main branch into your branch.
More edits may have been to the document from other users in the time it took you to clone the file and update it.\
To resolve any potential conflicts and make sure your document is up-to-date, pull from Main again.

git pull origin main

Note, if there are any updates or merge conflicts that have to be resolved, Go to Step six. Edit the file and remove the extra text inserted by the merge conflict.

## Step Ten: Publish your branch to origin.
git push origin [ BRANCH NAME ]

## Step Ten: Log into GitHub and create a Pull Request
https://github.com/csc340-sp24/assignment-1


Make sure the compare branch is your own branch, and the base branch is main.

## Final Step: Submit a link to the pull request that you created.
Your work will get approved and merged so that your changes show up on the main branch.
