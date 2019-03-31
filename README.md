# NoobGitCommands
Simple git command cheat sheet for the everday beginner who is likely their only contributor and doesn't need to get too deep.

# Project Start
### $ git init
Initializes the directory as a repository.
### $ git clone <remote-url>
Creates a local clone of whatever repository is at the URL.

# While Working
### $ git status
See if any files have been changed but not staged to be committed.
### $ git add .
Adds all files to the staging area. Replace "." with the filename to add only a specific file.
### $ git commit -m "This is an update"
Commit to updating the staged files on the repository, always leave a note with -m.
### $ git status
Check the status again to verify only the staged files were committed and everything is as planned.
### $ git push origin master
Pushes the changes to origin and the branch named "master"

# Status Checks
### $ git status
Shows what is staged to be committed with git add and committed to the changes with git commit. Do this before add/commit and after to verify your sanity.
### $ git log
List of commits in chronological order with their long jumbly names.

# Next Day and Onward
### $ git pull origin master
