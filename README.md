# rentweb

Two Branches =>
1. Master : Contains the stable code
2. Unstable : Contains the unstable code. We wil make changes to this branch and push to it.

To see your branches: git branch -a
To change your branch: git checkout <branchname>
To pull a branch: git pull origin <branchname>

To add your files to the branchs
1. git add --all 
2. git status (This will display the files that have been affected by you.) 
3. git commit -m "Your Commit Message, keep it short" . 
4. git push -u origin <branchname> 


Please enter your credentials after it. 
if you face a commit error, please sync your directory with "git pull origin master" first and then do the push again.

Github Link: https://github.com/Ayantaker/rentweb/tree/unstable
Stable App Hosted at heroku : https://rentweb.herokuapp.com/ 
Unstable App Hosted at : https://rentwebunstable.herokuapp.com/