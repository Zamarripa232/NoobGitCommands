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
If any changes were made on the remote master branch, this will integrate all the changes with your local repository. This also makes sure you start the day with a clean copy of whatever it is you happen to be doing.
### $ git fetch origin
If working with other people, this will tell you if any changes have been made but will not integrate them immediately.
### $ git pull origin master
yoloswag all those changes into your copy.
### $ git branch <newbranchname>
Creates a new branch, which is a good idea to do all the damn time whenever you try something diff, add new stuff, whatevers. Even bug fixing. Create a new branch.
### $ git checkout <newbranchname>  
Switches you to that other branch so you are no longer working directly on the safe and functional master branch, for example. All commits and changes are recorded on the checked out branch and kept separate so you can play around as much as you want.
### $ git checkout master
Switches back to the master branch so that you can...
### $ git merge <newbranchname>
This will merge all the cool new additions you've made under newbranch into the master branch
