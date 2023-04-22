# Git
Some useful instructions of git bash on Windows 10

## Terms
|Terms|Description|
|-----|-----------|
|Workspace|when editing local files, it happens on Workspace|
|Index/Stage|any change needs to be added to index in order to commit|
|Repository|after *add*, changes can be committed to local repository|
|Remote|after *commit*, changes can be pushed to remote repository|

## Instructions
### 0. set up
After installed git, we have to configure some setting
- set user info
`git config --global user.name "name"`
`git config --global user.email "email@email"`
- check configuration
`git config --list`

### 1. build or clone a repository
- build a git repository based on current direction  
`git init`  

- build a new direction and a initialize it as a new repository  
`git init project-name`  

- clone a repository  
`git clone url`  

### 2. add and commit
- show changes in Workspace  
`git status`
- show differences between Index and Workspace  
`git diff`
- add all of the changes into Index  
`git add .`
- commit all of the changes in the Index into local repository with a comment  
`git commit -m 'comment'`

### 3. remote operation
- check remote repository
`git remote`
- add remote repository
`git remote add`
- update local repository as remote (recommend to do this before every time before starting work)  
`git pull [local-name] [branch-name]`
- update remote repository as local (after *commit*)  
`git push [remote-name] [branch-name]`

### 4. branch operation
- create branch
`git branch [name]`
- check branch
`git branch`
- switch branch
`git checkout`
- merge branch
`git merge [name]`

### 5. Others
If you have added some file, e.g. `.idea/` to your `.gitignore`, but git still track those files. You should remove them from cache.  
```
git rm -r --cached .idea
```
