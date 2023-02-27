# My first repo on Github!

## This is a repo made for users to learn how to initialize a repo in github
- If your page looks similar to this then you are good!

## There are some main github commands that you will be using which are listed below

To add files to the staging area in git you can do the follwing command

`git add .` the dot at the end of add means that you want to stage all files in the working directory. You can stage specific files by typing their name intead of the dot.

After adding the files to the staging area, now we can do what is called a commit. You can add commit messages and they will show up in github. We can do this by using the command

`git commit -m "commit message here"`

You can also combine the previous two commands with two && signs like so

`git add . && git commit -m "commit message here"` or combine the two like so `git commit -am "commit message here"`

### Before we do our first push, it is recommended that we create a personal access token, add our email to the git config, and store the credentials in the git config

For information on how to create your personal access token you can go [here for doucmentation](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) or [here](https://www.youtube.com/watch?v=ytSoabxSQ6E) for a video

To add our email to the git config we can do the following command in the terminal 

`git config --global user.email "your_email@example.com"` this saves your email into the git config

- note: on our intial push it is going to ask for your username and password, for this first push we are going to use the personal access token in place of our password. 

- additionally, we want to run the following command before we push because it will save the credentials to the git config `git config --global credential.helper store`


Finally we can push these changes to the repo and see them on github with the following command

`git push -u origin main` or `git push origin main` 

Upon pushing we are going to be asked for our credentials. Make sure you use the personal access token when it asks for your password. Because we used the `git config --global credential.helper store` it will remember our credentials from now on

There are plenty of things you can do with git other than these commands but these are the most important. If you want to seek more information you can read the docs [here](https://git-scm.com/doc)
