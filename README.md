                                                                  Git important commands
                                                                  

Preface : This document is intended to the audience who wish to use Git into their project. It comprises of basic commands being used.

Pre-requisite : Should hava basic understanding or version control system such as SVN etc.

(Note : commands are not in specific order)
1) git remote -v - show details of remote url to which your repository is connected with.
2) git remote add origin <url.git> - makes the current location or folder in attached state with the git repository.
3) git status - make this command your most trusted friend as whenever you get stuck any where while processing commands in git this will help you determinig the state you are in. 
4) git log - to see all the log(s) like commit message, hash generated etc. You can use many attribute with it to beautify you findings as :-
a) git log --oneline
b) git log --oneline --graph
5) git fetch - this command helps you to update your local repository from the origin or the remote master repository, it will also update the information about any new branches created.
6) git checkout - checkout all the changes made to the master or the default branch after doing fetch.
7) git checkout <branch-name> - to checkout the local repository changes being taken from remote repo made to a particular branch.
8) git pull - directly pull all the changes from the remote repository to your local repository + branch you are working on.
9) git clone - an alternative to git fetch + git checkout, it clones the remote repo to your local folder or on the location.
10) git commit - to commit you local code changes to the local repo or branch. After this command an insert dialog will open up to write some (sensible) details about the commit you are doing.
11) git commit -m "<some one line message>" - to do an one line commit.
12) git push - to push the local repository changes to the remote repo.
13) git diff - to check all the differences between the code you are having at your end w.r.t to the code in the local repo.
14) git branch - to list out all the branches.
15) git branch <branch-name> - create a new branch with the specified branch name
16) git branch -d <branch-name> - deletes the specific branch (safely)
17) git branch -D <branch-name> - forcefully deletes the specific branch.
(Pay more attention to -d, -D a letter can do wonders and also can make you cry!)
18) git branch -m <branch-name> - force delete the specified branch even if it has unmerged changes.
19) git checkout <branch-name> - to switch between two branches.
20) git checkout -b <branch-name> - to create and checkout the branch.
21) git merge <branch> - merge one branch to another branch.
22) git reset --hard <commit or hash> - make your current branch point to <previous hash>
23) git clean -f - will remove untracked files.
24) git add . - to add all the files into staging area, before commit.
(mind the gap between a dot(.) !)
25) git add <some file name> - to add the specific file into the staging area before commit.
26) git stash - to remove you changes (You will use this a lot, if you are regularly trying some thing new in you code :))
27) git stash pop - to pop the latest stash you have done.
28) git push origin --delete <branch_name>
	to remotely delete a branch
29) git remote update origin –prune – To update the information from remote repo into local git you are working on.
30) git remote set-url origin <url> – To update the url of git server
