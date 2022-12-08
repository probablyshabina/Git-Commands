<!--COMMANDS-->
git --version //retuens the installed version if installed 
git config --list //to find the current author name and email
git config --global user.name //author name for all the repositories
git config --global user.email //author email for all the repos
git config --local user.email //author email for the current repo

git init // initialize an empty repository with the folder name
git add . //stages all the files that has been changed to commit
git add README.md //stages the specifc file that has been changed to commit
git reset . //unstages the all the files that has been staged to commit
git reset README.md //unstages the specific file that has been staged to commit

git status //returns the commit status of the files in the repo
<!---->

<!--FILE-->
create .gitignore and include the file that should not be tracked
<!---->