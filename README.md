# git-command

git init

git git config --global user.name "Your name here"

git config --global user.email "your_email@example.com"

git status

git add .

git commit -m "commit name here"

git log --oneline

git diff

git show

git diff --stage

git rm <file name>

git reset HEAD <file name>

git checkout <file number / master>

git clear



============ssh key generate=========================

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

eval $(ssh-agent -s)

ssh-add ~/.ssh/id_rsa

clip < ~/.ssh/id_rsa.pub






=============remote origin connect http===================

git remote add origin <file source (https://github.com/Samir1919/test.git)>

git push -u origin master

=============remote origin connect ssh===================

git remote add origin <file source (git@github.com:Samir1919/test.git)>

git push -u origin master



...........................................................................





git clone <file address> <if u need new name for project type here>

git fetch

git pull

git checkout -b <branch name>

git merge <branch name> 

git branch

git branch -D <branch name>

git push




git stash

git stash pop

git stash apply

git stash list

git stash pop <stash number>

Dropped <stash number>


git clean -f


touch .gitignore 
for details (https://www.atlassian.com/git/tutorials/saving-changes/gitignore)
