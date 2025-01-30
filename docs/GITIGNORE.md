# Gitignore
A gitignore file tells git which files to ignore from the project (any changes to these files will not be tracked) - https://git-scm.com/docs/gitignore
## 1. Add a new text file "hello.xxx"
 - Add the text "This file should be ignored"
 - Examine changes
```
git status
```
## 2. Add a .gitignore file
 - Add the text "hello.xxx" to the .gitignore file
 - Examine changes
```
git status
```
 - Stage and commit all changes
```
git add *
git commit -m "create .gitignore"
```
- Push changes to remote repo
```
git push origin main
```
- Examine github.com (the file "hello.xxx" is ignored)
## 3. Add a new text file "goodbye.xxx"
 - Add the text "Goodbye"
 - Examine changes
```
git status
```
## 4. Modify .gitignore
 - Replace "hello.xxx" with "*.xxx"
 - Examine changes
```
git status
```
 - Stage and commit all changes
```
git add *
git commit -m "update .gitignore"
```
- Push changes to remote repo
```
git push origin main
```
- Examine github.com (all files with ".xxx" extension are ignored)

[Tutorial Home](https://github.com/jgrissom/GitTutorial/)
