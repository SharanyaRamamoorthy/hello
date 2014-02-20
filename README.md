
$ mkdir ~/hello
# Creates a directory for your project called "world" in your user directory

$ cd ~/hello
# Changes the current working directory to your newly created directory

$ git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/hello/.git/

$ touch README
# Creates a file called "README" in your hello directory



$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"




$ git remote add origin https://github.com/username/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the "master" branch to GitHub
