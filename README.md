# rentweb
Checking


Two Branches =>
1.Master : Contains the stable code
2.Unstable : Contains the unstable code. We wil make changes to this branch and push to it.

To see your branches: git branch -a
To change your branch: git checkout <branchname>
To pull a branch: git pull origin <branchname>

To add your files to the branchs
git add --all 
git status (This will display the files that have been affected by you.) 
git commit -m "Your Commit Message, keep it short" . 
git push -u origin <branchname> 


Please enter your credentials after it. 
if you face a commit error, please sync your directory with "git pull origin master" first and then do the push again.


App Hostd at heroku : https://rentweb.herokuapp.com/ 