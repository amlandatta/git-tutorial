
## Create a new repository and push existing project ##

**Pre-requisites**
  * You should have installed git client

    Confirm using `git --version`

    If not installed, download from [here](https://git-scm.com/downloads)


1. Create a **new repository** in Github

  - After you login to Github, select `Your Repositories > Click New`
  - For this example I select `Public` repository.
    - Select `Public` if you want your content to be visible to all.
    - Select `Private` if you want to choose who can see and commit to the repository.
  - Click `Create Repository`

2. You have an existing project. `cd <to-your-project-folder>`

  ```
  cd git-tutorial
  git init

  # to add selective files
  git add README.md
  # to add all files
  git add .
  git commit -m "first commit"

  # set remote repository. You can find the https URL
  git remote add origin https://github.com/amlandatta/git-tutorial.git

  # Publish your content to Github
  git push -u origin master
  ```
