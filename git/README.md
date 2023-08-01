`
For your practice, make your change here: 
`

# Resources

- [GIT official website](https://git-scm.com/)
- [GIT full tutorial](https://www.tutorialspoint.com/git/git_basic_concepts.htm)
- [Sourcetree - A popular tool to visualize GIT](https://www.sourcetreeapp.com/)

# Follow below steps to start with GIT

## A. Install & config GIT on your OS
1. Create your account on https://github.com/ (This is the most popular online storage of repositories)
1. Install GIT on your OS(operating system): https://git-scm.com/downloads
1. Search for "GIT CMD" in Start menu, open it
1. (Setting your GIT username/email in the global config)[https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git]
1. Adding [an alias](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) to check our visualized git tree in CMD, using below command: 
`git config --global alias.tree "log --oneline --decorate --all --graph"`
1. Check all of our global GIT config using this command `git config --global -l`

## B. Start working on our learning-repository
1. Create a directory on your OS (ex: C:\Npthao\Repository), this will be the place to store our learning repostiory (and other repositories if any)
1. In GIT CMD, we move to the directory created at step 2 by the command `cd the-absolutepath-to-directory` (ex: "cd C:\Npthao\Repository")
1. Cloning the "learn2gether" repository to our directory using command "git clone https://github.com/thaoNG0612/learn2gether.git"
   Now, we can update our progress/resource independently but still neat and clear using GIT
1. In GIT CMD, move to our repository using command `cd learn2gether`
1. Using command `git tree` to check for the current GIT tree (commit history) of this repository 


## C. Tasks 

1. Finish the GIT tutorial in Resources segment. You will have a general idea about GIT, below are actions that commonly used (feel free to practice on our learning repo)
   - clone a repo to local environment 
   - create a new brach
   - switch among branches
   - review changes 
   - commit changes/push changes to remote repository
   - merge changes from a branch to current branch
   - move HEAD 
   - reset / hard reset (try to understand the different)
   - fetch changes from remote repository
   - pull lastest changes from remote repo to local repo


2. Try to read & understand the GIT tree of `learn2gether` repo 
3. Make below changes on our repo:
  - From the lastest commit, create your own branch (using `git branch` command to check what branch you're at)
  - Make 3 seperated commits on your new branch (using `git tree` to observe GIT commit history, try to understand local tree _in green_ & remote tree _in red_): 
    - Add 2 new files in folder `learn2gether\git`
    - Make some change in this README file
    - Remove 1 file you just created
  - Merge your new branch to `master`



