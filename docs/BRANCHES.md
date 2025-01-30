# Repository branches
Remember, to create and checkout a new branch use:
**git checkout -b \<branchname\>**
## 1. Create a new branch
```
git checkout -b spanish
```
## 2. List all branches (the currently checked out branch is indicated)
```
git branch
```
## 3. Modify the file hello.txt
 - Add the following text on line 2: "Hola Mundo!"
 - Examine changes
```
git status
git diff
```
## 4. Stage and Commit all changes
```
git add *
git commit -m "add spanish greeting"
```
## 5. Checkout the main branch
```
git checkout main
```
 - Examine the file hello.txt
## 6. Checkout the spanish branch
```
git checkout spanish
```
 - Examine the file hello.txt
 
[Tutorial Home](https://github.com/jgrissom/GitTutorial/)
