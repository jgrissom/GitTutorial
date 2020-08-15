# Push to remote repository
## 1. Create a remote repository
 - Login to github.com
 - Add a repository (GitDemo)
 - Copy the url of the remote repo to the clipbloard
## 2. Connect the local repo to the remote
```
git remote add origin https://github.com/<owner>/GitDemo.git
```
 - To list all remote repos connected to the local repo:
```
git remote -v
```
## 3. Push master branch to the remote repository
```
git push origin master
```
- View repository on github.com
- Examine commits
## 4. Push spanish branch to remote repository
```
git push origin spanish
```
- View repository on github.com
- Examine branches / commits

[Tutorial Home](https://github.com/jgrissom/GitTutorial/)
