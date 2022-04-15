1. git config --global user.name "amitkrraj"

2. git config --global user.email "amitkrraj.cse@gmail.com"

3. git init

4. git status

5. (I). git add file.txt
  (II). git add .
  
6. git commit -m "add file"

7. git push


*After git pull, to resolve problem use these commands
---Show current branch---
1. git branch --show-current


---Move to main branch---
1. git checkout 'main'

*What changes in a file ?
1. git diff
2. git log
3. git checkout id/address


////////////////////////////...
When you create a new repository on the command line

1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/amitkrraj/hello.git
6. git push -u origin main


/////////////////////////...
Push an existing repository from the command line

1. git remote add origin https://github.com/amitkrraj/hello.git
2. git branch -M main
3. git push -u origin main


/////////////////////////...
Branch in git

1. Create Branch  =>   
    $ git branch branch_name
1.1 simultaneously creates and checks out =>   
    $ git checkout -b branch-name
2. List Branch  =>  
    $ git branch --list  
     =>  or  =>  
    $ git branch  
3. Delete Branch  =>  
    $ git branch -d branch_name
     =>  or  =>  
    $ git branch -D branch_name
4. Delete a Remote Branch  =>  
    $ git push origin -delete branch_name
5. Switch Branch  =>  
    $ git checkout branch_name
6. Switch to master branch  =>  
    $ git branch -m master 
7. Rename Branch  =>  
    $ git branch -m old_branch_name new_branch_name
8. Merge Branch  =>  
    $ git merge branch_name 
