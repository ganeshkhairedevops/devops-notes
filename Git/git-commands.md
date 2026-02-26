# Git Commands Reference with Explanation


## git init
Initialize a new Git repository.

Example:
```bash
git init
```
---

## git add
Stage changes before committing.

Example:
```bash
git add file.txt
git add .
```
---

## git commit
Save staged changes to repository history.

Example:
```bash
git commit -m "Add new feature"
```
---

## git branch
List or create branches.

Example:
```bash
git branch
git branch feature-login
```
---

## git switch
Switch branches.

Example:
```bash
git switch main
or
git checkout main
```
---

## git merge
Merge another branch into current branch.

Example:
```bash
git merge feature-login
```
---

## git reset --soft
Move HEAD but keep changes staged.

Example:
```bash
git reset --soft HEAD~1
```
---

## git revert
Create a new commit that undoes previous commit.

Example:
```bash
git revert <commit-hash>
```
---

## git reflog
Show history of HEAD movements.

Example:
```bash
git reflog
```

## git stash
Temporarily save changes that are not ready to be committed.
Example:
```bash
git stash
```
## git stash pop
Apply stashed changes and remove from stash list.
Example:
```bash
git stash pop
```
## git stash list
List all stashed changes.
Example:
```bash
git stash list
```
## git stash apply
Apply stashed changes without removing from stash list.
Example:
```bash
git stash apply
```
## git stash drop
Remove a specific stash from the stash list.
Example:
```bash
git stash drop stash@{0}
```
## git stash clear
Remove all stashes from the stash list.
Example:
```bash
git stash clear
```
## git stash show
Show the changes in a specific stash.
Example:
```bash
git stash show stash@{0}
```
## git cherry-pick
Apply the changes from a specific commit to the current branch.
Example:
```bash
git cherry-pick <commit-hash>
```
## git log
Show commit history.
Example:
```bash
git log
```
## git log --oneline
Show commit history in a compact format.
Example:
```bash
git log --oneline
```

