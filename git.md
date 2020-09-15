# Git 
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

## Gir flow
    When we are using git flow, we create a repository firstly, add collaborators and start the project. Basically, we have a remote repository and several local repositories which are cloned from the remote repository or another remote repository which is forked from the original one. We use git add and git commit commands to submit the change on the codes and documents. 

    Here is a typical example: we create and checkout a new branch from the master branch. Then we add and commit the changes to the local git. After that, we can push them to the remote repository. We can also push them to the forked repository, and then raise a pull request to the original repository. If the repository has been updated by others, we could also pull the changes to the local repository easily.
    
    We can check the status of the git by using git status, which shows us the workspace of the git. We can also use git rm to  remove files from the remote repository and remove command to remove branches. We can get information of the commits by using git show.

## Git Terms
* Repository - A repository to store the files and git history
* Clone – A git clone is a git command that allows a user to clone a repository into a new directory that which they choose
* Fork - Fork is an operation to track a repository without being a collaborator. We can fork a repository, make changes to the forked one and raise pull requests to the original repository.
* Branch – It is a branch that is based on the original branch that allows a user to develop something without affecting the master branch.
* Commit - Git commit is the command to submit the changes which is added to the git workspace.
* Merge – A git merge is a command that lets a user take lines of code they developed in a git branch and assimilate them into a single branch. It will combine many commits into one.
* Checkout - By using git checkout, we can switch to a branch we named.
* Push – a git push updates the remote repository along with any commit that have been made locally to a branch
* Pull - There are two kinds of pull: we can pull the remote branch/repository to our local git and update the changes made by others. We can also raise pull requests in a forked repository.
* Remote Add – It adds a new remote for the repository.

* Remote Remove – TBD it removes a remote, any and all remote-tracked branches and configuration settings are updated to reflect the changes.
* Remote  Show – gives information about the remote.
* Status - Git status is showing the status of the workspace, the files which are added and committed or not.
* Master Branch – the main branch of a repository. Likened to a trunk of the tree.

