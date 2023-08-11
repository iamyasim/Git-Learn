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
<<<<<<< HEAD
<<<<<<< HEAD
git revert <commit id> ( This command will revert back done in given commit)
This is not even a command.
=======
>>>>>>> parent of 67eaacf (Added revert command)
=======
>>>>>>> 4bf7ea4 (Revert "Added revert command")
