# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

1. Ensure that you are in the proper working directory for your project
1. Establish a connection with `git init` to ensure that changes are tracked on your local machine
1. Add files to the staging area with `git add <filename>`
1. Commit those files with `git commit -m "Message"; in this case it would be the "Initial commit"
1. Establish a new remote repository on [Github](github.com)
1. After you've established your remote repository, the next step is to push those files to the remote location using the following commands
```
git remote add origin git@github.com:USER_NAME/GIT_PROJECT.git
git branch -M main
git push -u origin main
```
    1. You can check your work to ensure that everything was uploaded properly to Github