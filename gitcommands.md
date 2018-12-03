## Git commands

```
# add all new files in git 
git add -A

# commit changes 
git commit -m "your message"

# add and commit simultaneously
git add -A && git commit -m "your message"

# create and switched to newly created branch
git checkout -b branchName

# merge in master with other branch
git checkout master		# must stay in the branch where you merge in 
git merge branchName
# remove the file from the stage.
git rm --cached file.txt

# switch to the specific commit's changed file 
git checkout hashcode filename
```