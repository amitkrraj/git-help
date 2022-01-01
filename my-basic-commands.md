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


////////////////////////////
…or create a new repository on the command line

1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/amitkrraj/hello.git
6. git push -u origin main


/////////////////////////
…or push an existing repository from the command line

1. git remote add origin https://github.com/amitkrraj/hello.git
2. git branch -M main
3. git push -u origin main

