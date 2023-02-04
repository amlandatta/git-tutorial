# Create a new repository and push existing project

This is a beginners guide!

## Pre-requisites
* You should have installed git client

  Confirm using `git --version`

  If not installed, download from [here](https://git-scm.com/downloads)

## Get started with new repository

1. Create a **new repository** in Github

- After you login to Github, select `Your Repositories > Click New`
- For this example I select `Public` repository.
    - Select `Public` if you want your content to be visible to all.
    - Select `Private` if you want to choose who can see and commit to the repository.
- Click `Create Repository`

2. Configure git

```
# view existing configurations
git config --list

# set your user name
git config --global user.name "Amlan Datta"
```

## Working with existing repository

3. You have an existing project. `cd <to-your-project-folder>`

  ```
  cd git-tutorial
  git init

  # to add selective files
  git add README.md
  # to add all files
  git add .
  git commit -m "Initial commit"
  
  # set default branch
  git branch -M main
  # set remote repository. You can find the https URL
  git remote add origin https://github.com/amlandatta/git-tutorial.git

  # Publish your content to Github
  git push -u origin main
  ```

4. Refer [Connecting to Github with SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

5. For daily use, useful steps continue [here](docs/DAILY_USE_GIT_COMMANDS.md)

6. Some GIT commands seems to be similar but are for different purpose. Check [here](docs/SIMILAR_BUT_DIFFERENT.md)