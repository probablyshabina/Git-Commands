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

git commit -m "commit message line 1" //commit the files that has been changed

git remote //returns the remote repositories that have been linked to the current local project
git remote add name-of-repo repository-url //links project with remote repository
git remote -v //return the links
git remote show origin

git push name-of-repo branch-of-repo -u //sync with remote repo
ex: git push origin master -u


<!---->

<!--FILE-->
create .gitignore and include the file that should not be tracked
<!---->