# Day to day use commands

When working on a Git repository maintained by a globally distributed team, 
it's important to keep in mind that concurrent changes with multiple pushes 
may occur. 

To avoid conflicts, it's recommended to regularly pull the latest 
changes from the remote repository, review and merge them into your local 
repository, and make sure to communicate with other contributors to avoid 
conflicting changes.

## Contribute to existing remote branch

Clone the remote repository to your local workstation.
Now you want to make changes and contribute to an existing remote branch.

```
git clone git@github.com:amlandatta/git-tutorial.git
  
git checkout -b origin/<remote-branch-name>
```
  
* After you implement changes to your local repository 
```
# to stage all changes to be committed to the repository  
git add .
# to carefully select files you want to commit to the repository. Prefer this option over above
git add <filename>

# to record the staged changes to the repository's history  
git commit -m "<Commit comments>"

# push changes to the remote repository  
git push origin <your-branch-name>```
```

## Work on new local branch and then push to remote branch

But you want to work on a different feature. Hence, you create a local branch and then push later when ready.

```
git clone git@github.com:amlandatta/git-tutorial.git

# create a local branch from remote 'main' branch
git checkout origin/main -b <local-branch-name>

git add <filename>

# to record the staged changes to the repository's history  
git commit -m "<Commit comments>"

# push changes to the remote repository  
git push origin <local-branch-name>
```

## TIPS: If integrated with JIRA

```
git commit -m "<JIRA number>: Change description"
```
