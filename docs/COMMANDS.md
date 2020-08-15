# Basic git commands
## 1. git init
Initializes the current directory as a local git repository.
```
git init
```
## 2. git branch
Lists all the branches in your repository, and indicates which branch is currently checked out
 - Remember that a git repository allows you to create "snapshots" of your files (think of it as a file timeline)
 - The timing of the snapshots is determined by you
 - To create a snapshot, we must commit any changes to a branch in the repository
 - A branch must be checked out in order to commit changes to it
```
git branch
```
## 3. git checkout \<branchname\>
Used to checkout a branch (to first create the branch, use -b flag)
```
git checkout -b master
```
## 4. git status
Lists the changed files in the repository
 - Now that we have a local repository with a master branch, we can commit files to the currently checked out branch (in our case, the master branch is checked out)
 - Before we do that, let’s look at the files that have changed
```
git status
```
## 5. git add \<filename\>
 - Before we can commit changes, we must stage any files we want to commit
 - Files can be staged individually, or all at once using a wildcard (only files with changes will be staged)
```
git add *
```
  - Verify the status of the local repo
```
git status
```
 - Notice the changed files have been staged
## 6. git commit
Commits all staged changes to the currently checked out branch
```
git commit -m "initial commit"
```
  - Verify the status of the local repo
```
git status
```
## 7. git diff
Preview uncommitted file changes
 - Update the text file "Hello World!"
```
git diff
```
 - Enter the git commands to stage and commit all changes to the master branch of the local repo
```
git add *
git commit -m "enter greeting"
```
[Tutorial Home](https://github.com/jgrissom/GitTutorial/)
