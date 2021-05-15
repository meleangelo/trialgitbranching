# trialgitbranching

a few notes on git workflow, for fun

# fork repo
to fork a repo just write

```
git clone meleangelo/trialgitbranching
```

# create new branch

```
git checkout -b feature/angelo/branchtest
```

# do work and  commit

change files and update, the commit using

```
git commit -a -m "message for commit"
```

# push changes to github branch

```
git push origin feature/angelo/branchtest
```

# to check log of changes done in branch and master

``` 
git log --oneline --decorate
```

or with graph
``` 
git log --oneline --decorate --graph --all
```
