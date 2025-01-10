1
git init
echo file
git add .
git commit -m "msg"

2
git init
echo file
git add .
git commit 
git checkout -b nb
echo file 
git add .
git commit -m
git checkout main
git merge nb

3
git init
echo file
git add .
git commit -m msg
git checkout -b nb 
echo file 
git add .
git stash save
git checkout main 
git stash apply

4
git init
echo file 
git add .
git commit -m msg 
git clone url


5
git init
echo file 
git add .
git commit -m msg 
git branch -M main
git remote add origin url
git push -u origin
git checkout -b nb
git fetch origin
git rebase origin/main
git push origin nb

6
git init 
echo file
git add .
git commit -m msg 
git checkout -b nb 
echo file 
git add .
git commit -m msg 
git checkout main 
git merge nb -m msg

7
git tag v1.0 <commit-SHA>

8
git cherry-pick <start-commit>^..<end-commit>

9
git show <commit-SHA>
or
git log -n 1 <commit_SHA>

10
git log --author="name" --since="year-month-date" --until="year-month-date"

11
git log -n 5

12
git revert <commit-SHA>
