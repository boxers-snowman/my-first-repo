# My first repo on Github!

## this is a repo made for users to learn how to initialize a repo in github
- if your page looks similar to this then you are good!

## there are some main github commands that you will be using which are listed below

to add files to the staging area in git you can do the follwing command

`git add .` the dot at the end of add means that you want to stage all files in the working directory. You can stage specific files by typing their name intead of the dot.

After adding the files to the staging area, now we can do what is called a commit. You can add commit messages and they will show up in github. We can do this by using the command

`git commit -m "commit message here"`

You can also combine the previous two commands with two && signs like so

`git add . && git commit -m "commit message here"`

finally we can push these changes to the repo and see them on github with the following command

`git push -u origin main` or `git push origin main` 

There are plenty of things you can do with git other than these commands but these are the most important. If you want to seek more information you can read the docs [here](https://git-scm.com/doc)
