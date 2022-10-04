# devops-00-git-basics-final

Initialize Git on the current folder

```
git init
```

Set the user name for the current repository to "fake-user"

```
git config user.name "fake-user"
```


Check the status of the Git
```
git status
```
Commit the changes to the current repository with the message "docs : adding answers"
```
git commit -m "docs : adding answers"
```

Commit the updated files directly, skipping the staging environment with following message "test : adding missing tests"
```
git commit -a -m "test : adding missing tests"
```
View the history of commits for the repository
```
git log
```
Show the possible options for the status command in command line
```
git status -help
```

Update the current branch from its origin using a single command
```
git pull origin
```

push the current branch to its default remote origin
```
git push origin
```

## Those are commands, you will certainly use one day on a daily basis.
