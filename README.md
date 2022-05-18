# Notes on Git

## Commands:
Create a new repository:

  `git init [repository name]`

Setup global configs:

   `git config --global user.name "oleksandr.arzamastsev"`

   `git config --global user.email "sarzamastsev5@gmail.com"`

List global configs:

   `git config --global --list`

Add all files to the staging area:

   `git add .`

Add files to the staging area:
   
   `git add <f1> <f2>`

Display the current state of the repo:
   
   `git status`

Commit the staged changes:

   `git commit -m "message"`

View the history:

   `git log`

View the difference between the previous commit and the latest:

   `git --diff master~1 master -- [filename]`

## Additional info:
* All commits are uniquely identified by the SHA-1 hash value, which is a 160-bit (20-byte) 40-character hexadecimal string. They are used instead of the incremental ids due to the distributed nature of git. 
* Git is built on top of the object store- and it creates and stores a collection of objects during commits. Git objects are: commit, blob, tree, tag.

   