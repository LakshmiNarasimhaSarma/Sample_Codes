git version - it wil check what version of git is installed on the machine

git config --global user.name "Kalyan Sarma" // give your user name

git config --global user.email "Kalyansarma142@gmail.com" // give your email id 

mkdir hello-from-git // it will create directory

cd hello-from-git // change directory - it will take you to the folder which you want.

git init // Initialize a repository

create file and add some data inside the file 

git status // it will check the status

git add . // It will add files to the stating area 

git log // it will check the logs

git commit -m "Adding Hello world"  // git commit command will commit the changes

git branch -M main
git remote add origin git@github.com:KalyanSarma/Sample_code.git
git push -u origin main

git diff // it will show the differences of the files

Git Commands

git version - it wil check what version of git is installed on the machine

git config --global user.name "Kalyan Sarma" // give your user name

git config --global user.email "Kalyansarma142@gmail.com" // give your email id 

mkdir hello-from-git // it will create directory

cd hello-from-git // change directory - it will take you to the folder which you want.

git init // Initialize a repository

create file and add some data inside the file 

git status // it will check the status

git add . // It will add files to the stating area 

git log // it will check the logs

git commit -m "Adding Hello world"  // git commit command will commit the changes

git branch -M main
git remote add origin git@github.com:KalyanSarma/Sample_code.git
git push -u origin main

git diff // it will show the differences of the files


Branches & Merge :

Branch : It allows you to work on different parts of your repository ( codebase) in isolation from others.

Merge : Merging in git combines changes from different branches.

# creating a branch

To create a branch in git, you use the git branch command followed by branch name 

git branch <branch_name>

# switching branches

git checkout <branch_name>  Or git switch <branch_name>

# creating and switching the branch in one step

git checkout -b <branch_name>

# merging Branches

Once you made the changes in feature branch and are ready to merge those changes back to the main branch, you use the git merge command

git checkout master/main // first switch to master

git merge <branch_name> //feature branch name // branch name that you want to merge to main branch

# Deleting a Branch

Once branch has been merged and you no longed need it, you can delete it using -d option with git branch

git branch -d feature/new-feature

# Listing Branches

To see list of all branches in your repo, use :

To list down your local repository branches : git branch

To list down the remote repository branches : git branch -r

If you want to list down all the branches irrespective of local or remote ----> git branch --all

# cloning the repo

git clone <repo_url>

# Fetching

Git fetch command downloads from a remote repository to your local repo

It updates your remote tracking branches to reflect changes made in the remote repo, but it does not merge those changes in your current branch

git fetch

git merge origin/main

# pull command

git pull

if you don't want to use the git fetch and git merge command we can use single command which is git pull

git pull command is combination of git fetch and git merge

It updates your current branch with latest changes from the remote rep.
















