# Merging branches / Handling conflicts
To merge a branch into the currently checked out branch, use:
**git merge \<branchname\>**
## 1. Merge the spanish branch into the master branch
 - Examine the file hello.txt on master branch
```
git checkout master
git merge spanish
```
 - Examine the file hello.txt on master branch
## 2. Create a conflict
 - With the master branch checked out, modify the file hello.txt
 - Update the text on line 1: "Hello World, git is fun!"
 - Stage and commit all changes
```
git add *
git commit -m "update english greeting"
```
 - Checkout the spanish branch
```
git checkout spanish
```
 - Modify the file hello.txt
 - Update the text on line 2: "Hola mundo, git es divertido!"
 - Stage and commit all changes
```
git add *
git commit -m "update spanish greeting"
```
## 3. Merge the conlict
 - Checkout the master branch and merge the spanish branch into the master branch
```
git checkout master
git merge spanish
```
 - In the file editor, choose the resolution that makes the most sense (Accept Both Changes)
 - Stage and commit all changes
```
git add *
git commit -m "merge conflict resolved"
```
[Tutorial Home](https://github.com/jgrissom/GitTutorial/)
