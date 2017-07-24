A quick GitHub Demo to show the students at SMU

![gh-logo](https://user-images.githubusercontent.com/15793521/28505229-7317ae18-6fe7-11e7-8665-ae3539a72266.png)


what is GitHub?
-----------

see [Wikipedia](https://en.wikipedia.org/wiki/GitHub)

> GitHub is a web-based Git or version control repository and Internet hosting service. It is mostly used for code. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.


CREATE
-----------

* Clone an existing repository.  
**$ git clone ssh-key**  
* Create a new local repository.  
**$ git init** 

LOCAL
----------- 

* Check the changes in your working directory.  
**$ git status**  
* Check changes to tracked files.  
**$ git diff** 
* Add all changes to the next commit.  
**$ git add .**  
* Commit previously staged changes.  
**$ git commit -m "reminder text"**
* Push local changes to remote(Github).  
**$ git push [remote] [branch]** 
* Downloads all remote changes without merging.  
**$ git fetch**  
* Merge branch into current branch 
**$ git merge [branch]**
* Does a git fetch followed by a git pull.  
**$ git pull remote branch** 
  
BRANCHES
-----------

* List all existing branches.  
**$ git branch**
* Make new branch    
**$ git branch [branch name]**   
* Switch to different branch    
**$ git checkout [branch]** 
* Delete a local branch    
**$ git branch -d [branch]** 
   
UNDO
-----------

* Stash all uncommitted changes and revert back to previous commit.  
**$ git stash**  
* Apply all stashed changes to current branch.  
**$ git stash apply** 
* Discard all local changes in your working directory.  
**$ git checkout [HEAD ID]** 



ADD COLLABORATORS
-----------

**STEPS**
1. Go to repository settings
2. Click on Collaborators on the left hand side
3. Add collaborator via username, full name,or email


PULL REQUEST
-----------

**STEPS**
1. Go to repository 
2. Click on Pull request
3. Click on New pull request button
4. Change compare barnch to the barnch you want pulled
5. Click on Create pull request
6. Describe your pull request to repository admin
7. Submit pull request


Git Concepts  
-----------

[Git Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)  
[HEAD, master, origin](https://stackoverflow.com/questions/8196544/what-are-the-git-concepts-of-head-master-origin)

