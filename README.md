# test
A test repo for branching and pulling

## Some general commands.
git branch -> shows all branches (-v for more detail on them)

git checkout / git switch -> switches between branches

git branch -d *[name]* -> deletes a selected branch

## Branch Creation
### 1. Create a new branch
git branch *[name]* -> creates a new branch with a given name

### 2. Switch into branch
git switch *[name]*

### 3. Update during first push (FIRST PUSH ONLY)
git push -u origin *[name]* -> will update a branch which is local to remote
*push normally after initial push*

## Merging Branch Command
### 1. Switch into MAIN branch
git switch main

### 2. Merge a selected branch
git merge *[name]*
