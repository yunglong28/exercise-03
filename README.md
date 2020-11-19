# Exercise 3

This exercise is about git. We will create and resolve merge conflicts.

## Step 1

Please clone this repository onto your local computer. On the command line, you would enter: `git clone https://github.com/idh-cologne-tools-ressourcen-infra/exercise-03`, and create a new branch using your UzK username as a name.

## Step 2
The file `suitcase.txt` contains items to be packed into a suitcase (you might now this children's game where you have to remember everything that has been mentioned before. This exercise is loosely inspired by it). Please add an item that you pack into your suitcase, *at the end of the list*. Commit your changes.

## Step 3

Switch to the main branch, pull changes from the remote repository (if there are any) and merge the changes from your branch into the main branch (command line: `git checkout main`, followed by `git pull` and `git merge MYBRANCHNAME`). This will likely result in a merge commit, which you need to resolve now. Commit your changes.

Push your changes to the remote repository. If this results in more conflicts, you'll need to pull the new stuff from the server, resolve conflicts, and push again.

