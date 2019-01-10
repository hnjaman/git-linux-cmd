## Git commands

```
# add or track all new files in git 
git add -A

# commit changes 
git commit -m "your message"

# update a commit
git commit -a --amend -m "your message"

# add and commit simultaneously
git add -A && git commit -m "your message"

# Already tracked files
git commit -a -m "your message"

# create and switched to newly created branch
git checkout -b branchName

# merge in master with other branch
git checkout master		# must stay in the branch where you merge in 
git merge branchName
# remove the file from the stage.
git rm --cached file.txt

# switch to the specific commit's changed file 
```
git checkout hashcode filename
```

# Branch show
```
git branch	// show branches 
git branch -a	// show all branch
git branch -r	// show remote branch
```
# Commit hierarchy 
```
git log --all --graph
```
