[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/5N0D6Mex)
# homework-3
Kevin Vo\
CSCI 5828 – Spring 2024\
Homework 3\
Team Members: Kevin Vo (I worked on this assignment by myself)\
2/21/2024

### Git Commands and Commits
- Commit 0: Initial Commit
```
 git init
 git add README.md
 git commit -m "Commit 0: Initial Commit [main branch]"
 git branch -M main
 git remote add origin https://github.com/kevinpvo/hw-3-git-and-github-kevinpvo.git
 git push -u origin main
```
- Commit 1: Edit README.md
```
 git add README.md
 git commit -m "Commit 1: edit README.md"
 git push -u origin main
```
- Commit 2: Edit README.md
```
❯ git add README.md
❯ git commit -m "Commit 2: edit README.md"
❯ git push -u origin main
```
- Commit 3: Edit README [branch bug-fix]
```
> git checkout 94bb8e9583540203ac9dba5f74f3ba927341baf3
> git branch bug-fix
> git checkout bug-fix
> git push -u origin bug-fix
> git add README.md
> git commit -m "Commit 3: Edit README.md [branch: bug-fix]"
> git push -u origin bug-fix
```
- Commit 4: Update README.md [branch: bug-fix]
```
> git add README.md
> git commit -m "Commit 4: Update README.md [branch: bug-fix]"
> git push -u origin bug-fix
```
- Commit 5: Merge main into bug-fix [branch: bug-fix]
```
> git merge main
**resolved merge conflicts**
> git add README.md
> git commit -m "Commit 5: merge main into bug-fix [branch: bug-fix]"
> git push -u origin bug-fix
```
- Commit 6: Update README.md [branch: bug-fix]
```
> git add README.md
> git commit -m "Commit 6: Update README.md [branch: bug-fix]"
> git push -u origin bug-fix
> git branch bug-fix-experimental
> git checkout bug-fix-experimental
> git push -u origin bug-fix-experimental
```

- Commit 7: Edit README [branch: experimental-bug-fix]
```
> git checkout 64a63cd87174d3f0fde2aac3ad17667820b7f893
> git branch experimental-bug-fix
> git checkout experimental-bug-fix
> git push -u origin experimental-bug-fix
> git add README.md
> git commit -m "Commit 7: Edit README [branch: experimental-bug-fix]"
> git push -u origin experimental-bug-fix
```
- Commit 8: Update README.md [branch: experimental-bug-fix]
```
> git add README.md
> git commit -m "Commit 8: Update README.md [branch: experimental-bug-fix]"
> git push -u origin experimental-bug-fix
```
- Commit 9: Update README.md [branch: experimental-bug-fix]
```
> git add README.md
> git commit -m "Commit 9: Update README.md [branch: experimental-bug-fix]"
> git push -u origin experimental-bug-fix
```
- Commit 10: Update README.md [on branch main]
```
> git checkout main
> git add README.md
> git commit -m "Commit 10: Update README.md [on branch main]"
> git push -u origin main
```
- Commit 11: Merge branch experimental-bug-fix into bug-fix [branch: bug-fix]
```
> git checkout bug-fix
> git merge experimental-bug-fix
**resolved merge conflicts**
> git add README.md
> git commit -m "Commit 11: Merge branch experimental-bug-fix into bug-fix [branch: bug-fix]"
> git push -u origin bug-fix
```
- Commit 12: Update README.md [branch: bug-fix]
```
> git add README.md
> git commit -m "Commit 12: Update README.md [branch: bug-fix]"
> git push -u origin bug-fix
```
- Commit 13: Merge branch 'bug-fix' into main
```
> git checkout main
> git merge bug-fix
**resolved merge conflicts**
> git add README.md
> git commit -m "Commit 13: Merge branch 'bug-fix' into main"
> git push -u origin main
```