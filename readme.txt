This is the readme file for ITMO-444. 

I will be using this file to go through the git it tutorial
and make changes to the file and repo when necessary.

This is the second set of commits. 
Below will include a list of useful commands in case I forget 
in the near future.

Anyyyyways:

mkdir hello-world   --> this makes a directory
cd hello-world      --> this teleports you into the directory
git init            --> this tells git to track the folder
git status          --> "whats going on???"
ls                  --> list items in folder (linux does it better >_<)

git diff            --> view changes made to the file(s)
git add <FILENAME>  --> add a file's changes to be commited
git add <.>         --> add all the files with changes
git commit -m "MSG" --> commit the changes (save button) with description

git config --global user.username <USERNAME> --> this here adds my GitHub username to the Git config
git config --global user.username --> the command alone w/o the field lets you dblchk what is set in the config

origin              --> the primary remote 
.gitignore          --> list of files for git to not track (passwords)

git remote add origin <GITHUB_URL> --> add a remote named 'origin' to repo

git remote add <REMOTENAME> <URL>      --> add remote connections
git remote set-url <REMOTE NAME> <URL> --> set a url to a remote
git pull <REMOTENAME> <BRANCHNAME>     --> this pulls in changes
git remote -view                       --> this views remote addresses
git push <REMOTENAME> <BRANCH>         --> this pushes changes to somewhere

forking --> creating a copy of a repo to my own space
forks begins as remote repos 

getting forked repos onto the local space requires that I clone it

step 1) fork the repo via github site
step 2) clone the repo onto my local space via terminal

git clone <URLFROMGITHUB>      // make sure I'm not inside another git repo
git remote -v                  // checks to see if the address is already set up
git remote add upstream <LINK> // this adds a remote connection in case the original repo gets edits


git checkout -b <BRANCHNAME>   --> create + switch to branch in one line
git branch <BRANCHNAME>        --> create a new branch 
git checkout <BRANCHNAME>      --> switch to specified branch
git branch                     --> list all branches
git branch -m <NEWBRANCHNAME>  --> rename the branch currently on

git pull <REMOTENAME> <REMOTEBRANCH> --> pull in changes from remote branch
git fetch --dry-run                  --> see changes to the remote before pull in

git merge <BRANCHNAME>                     --> merge a branch into current branch
git branch -d <BRANCHNAME>                 --> delete a branch
git push <REMOTENAME> --delete <BRANCHNAME --> delete a remote branch
git push <REMOTENAME> <BRANCHNAME>         --> pull from remote
