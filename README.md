# Github-interaction
Interact with local Git and GitHub

You want to learn, how to interact Git and GitHub locally so that 
1. You can modify GitHub file on your computer 
2. Update your remote repository on GitHub throgh local git

Let's dive into learing......

(*Note:  Requirement: 
1. Knowledge of how to create account on any online platform
2. Installed git on computer (if not go through website link: https://git-scm.com/downloads
3. Introduction of git software commands (Command cheatsheet URL: https://github.github.com/training-kit/downloads/github-git-cheat-sheet/ ))                       

Steps you need to follow: 
1. Create account on GitHub (Fill information)
2. Create new repository
3. After successfuly creating new repository click "Clone or download" and copy URL
4. Go to your local computer git software and type following command
5. $ git clone <paste URL>
6. Git will ask you for GitHub's USERNAME and PASSWORD
7. Now we downloaded the clone repository on your local machine
8. Computer will automatically create directory and working tree to perform changes in file
9. $ cd <repository name>   : To add directory to perform changes
10. Now use your command on git to perform actions 
    ( For more information on commands check this URL: https://github.github.com/training-kit/downloads/github-git-cheat-sheet/ )
11. After you made changes repository on your local machine you need to update those on you GitHub remote repository
12. $ git push  : Use to merge changes on GitHub repository
13. Now you successfuly updated the GitHub remote repository
14. After that you made some changes on the remote repository on Github and you want to retrive those changes on your computer you
    can use next command
    $ git pull

Extra: To avoid password enter process...

1. Use credential helper to store cache for 15 minute  

$ git config --global credential.helper cache

$ git pull and it will ask you for userID and password one time after you don't need to type for 15 minutes

2. Adding your computer SSH -key to your GitHub account 
For more information see: https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh


.............................Congrats on your successfuly completion....................................

