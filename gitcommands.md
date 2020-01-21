# git committing 

add all new files in git 
```
git add -A
# or 
git add .
```
commit changes 
```
git commit -m "your message"
```
amend or update a commit
```
git commit -a --amend -m "your message"
```

add and commit simultaneously
```
git add -A && git commit -m "your message"
```

Already tracked files
```
git commit -a -m "your message"
```
show all commit hierarchy 
```
git log --all --graph
```
show last 5 commit
```
git log -5
```
show last 5 commit as oneline 
```
git log -5
```

switch to the specific commit version of a file 
```
git checkout commitId filename
```

remove file from the stage.
```
git rm --cached file.txt
```

# git branching

create a new branch from existing branch
````
git checkout newBranch existingBranch
````
create and switched to newly created branch from existing branch by single command
```
git checkout -b newBranch existingBranch
```

show all branch
```
git branch	// show branches 
git branch -a	// show all branch
git branch -r	// show remote branch
```

delete a branch 
```
git branch -D branchName
```

# git merging
merge in master branch from other branch
```
# first have to switch to the master branch 
git checkout master
git merge otherBranch
```

cherry-pick or merge a specific commit
````
# copy the commitId from any branch you want to merge by 
git log

# move to the branch where merging will do
git checkout branchName

# cherry-pick by that commitId
git cherry-pick commitId
````

# git pulling
get update with all remote branches without merging with changes 
````
git fetch -a 
````

get update with remote branches and merging with changes
````
git pull
````

# git pushing 
push new commit to remote server
````
git push
````

push newly created local branch to remote as origin
````
git push --set-upstream origin localBranchName
````