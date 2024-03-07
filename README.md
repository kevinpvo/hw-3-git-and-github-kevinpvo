Commit 0: Initial Commit
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
- Commit 4: Update README.md [branch bug-fix]
```
> git add README.md
> git commit -m "Commit 4: Update README.md branch bug-fix]"
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