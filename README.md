# Git commands
### Simple list of git commands

Create a local repository.
```
git init
```

Add readme file.
```
git add README.md
```

Create a new commit containing the current contents.
```
git commit -m "commit description"
```

Assign remote directory your repository is stored at.
```
git remote add origin https://github.com/[username]/[rep]
```

Pushes the commits to the remote master branch.
```
git push -u origin master
```

Make local the same of remote origin/master.
```
git fetch origin && git reset --hard origin/master && git clean -f -d
```

Switch to a different branch
```
git checkout [branch name]
```

Delete local branch (-D to force the deletion)
```
git branch -d  [branch name]
```

Delete remote branch (you can use --delete or -d)
```
git push origin --delete [branch name]
```
OR
```
git push origin :[branch name]
```

Other
```
https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-your-personal-account/managing-multiple-accounts
```
