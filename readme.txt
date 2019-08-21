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