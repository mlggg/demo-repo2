#Demo 2

Text

This Demo is to upload file from local machine to Github

Step by Step Guide

1. run `git init` in the directory of the folder
2. run `git status` to track status
3. run `git add . ` to add changes in the working directory 
4. run `git status` to check whether successfully added
5. run `git commit -m "Title" -m "Description"` to add the title and description tlo the change
Note that the changes so far only done locally, to make it live you will need to create a new repository on Github
6. Go to Github create a new repository, copy the link e.g. https://github.com/mlggg/demo-repo2.git
7. run `git remote add origin https://github.com/mlggg/demo-repo2.git` -> remote means somewhere else but not on this computer, refering to Github
8. Check using `git remote -v`,it will show any remote repository connected to this repo
9. run `git push origin master` to upload to Github

To set an upstream `git push -u origin master`, in the future just run `git push`

The -u option automatically sets that upstream for you, linking your repo to a central one. That way, in the future, Git "knows" where you want to push to and where you want to pull from, so you can use git pull or git push without arguments.