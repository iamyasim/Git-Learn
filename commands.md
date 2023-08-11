git init
git clone "repo-url"
git add "filename"
git commit -m "comment"
git config --global user.name "username"
git config --global user.email "emailaddress"
git config--list (to list out users in git)
git status (to check status of code file)
git log (it tells which commit is done by which user)
git show <commit id> (to see code of perticular commit)
git remote add origin <url of repo> (to create a link between local and remote repo)
git push -u origin master (to push code from local repo to remote repo in master branch)
git revert <commit id which you want to revert> ( This command will revert back done in given commit)
git reset <commit id where you want to go back after reset>(This command deletes the commit and also deletes the history of commits)
git checkout master
git merge dev ( this will merge dev branch into checkedout master branch with dev branches commit history)
git merge dev --squash (This will merge but will not add commit history of dev)
git merge dev --squash HEAD~2 (This will merge but will only add 2 commits history of dev)
firt command from dev
second
third
fourth