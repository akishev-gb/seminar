# Репозиторий для пул реквестов

## Work with pull request!

> We go to open account we are interested in on github, and enter the button 'fork', then a repository opens on our github page.

> On desktop created catalog, and clone the repositories

* *git clone repository address* - **clone the repository address**

* *git branch new_branch* - **created a new branch**

> Working in new branch, added and commit chenges

* *git push* - **pushes changes to local repository**

> Then in your github account appears button *pull request*, enter the button.

##  Local repository

* *git remote -v* - **list remote repositories associated with local**

* *git remote remove origin* - **remove remote repository binding abbr. origin**

* *git remote add origin https://github.com:nicothin/test.git* - **add a remote repository (abbreviated as origin) with the specified URL**

* *git remote rm origin* - **remove remote repository affinity**

* *git remote show origin* - **get data about remote repository with abbreviated name origin**

* *git fetch origin* - **fetch all branches from the remote repository (abbreviated as origin), but don't merge with your own branches**

* *git fetch origin master* - **same, but only the specified branch is downloaded**

* *git checkout --track origin/github_branch* - **create a local branch github_branch (take data from a remote repository with an abbreviated name origin, branch github_branch) and switch to it**

* *git push origin master* - **push to the remote repository (abbreviated as origin) the data of your master branch**

* *git pull origin* - **pull changes from remote repository (all branches)**

* *git pull origin master* - **pull changes from the remote repository (only the specified branch)**






