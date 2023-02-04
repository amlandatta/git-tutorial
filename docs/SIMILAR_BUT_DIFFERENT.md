# Similar commands with differences

# `git fetch` vs `git pull`

`git fetch` and `git pull` are similar in that they both download data from 
a remote repository.
* `git fetch` only downloads the data to your 
local repository and doesn't automatically merge it with your current branch.
* `git pull` automatically integrates the data into your 
current branch. 

In general, `git fetch` is used to preview changes before deciding whether 
to merge them, while `git pull` is used to actively incorporate updates into your local repository.


* # `git checkout` vs `git switch`

`git checkout` and `git switch` are similar in that they both allow you to 
switch between branches in Git. 
* `git checkout` is the traditional and more 
commonly used command for this purpose. 
* `git switch` was introduced in Git 
version 2.23 as a more user-friendly alternative to `git checkout`. 

Both commands have the same basic functionality and can be used 
interchangeably, with `git switch` offering some additional options and improved branch switching experience.


* # `git add` vs `git commit`

`git add` and `git commit` are two separate but related Git commands. 
* `git add` is used to stage changes to be committed to the repository. It stages 
changes to individual files or entire directories and prepares them for the 
next commit. 
* `git commit`, on the other hand, records the staged changes to 
the repository's history. A commit is like a snapshot of your project's 
state at a particular point in time, and it helps you to revert to previous 
versions if necessary. 

In short, `git add` stages changes and `git commit` permanently records them in the repository's history.
