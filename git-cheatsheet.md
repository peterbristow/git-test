GIT CHEAT SHEET
===============

Cheat sheet for using git in different senarios.


Work with a new up-stream repo
------------------------------


- Make a new repo on Github
- Make/navigate to folder on local
- `git clone git_url`
- `git log --stat`
- `git checkout -b my_branch`
- Make required changes
- `git commit -a`  # opens the commit to add/amend a message. 
- `git checkout master`
- `git merge my_branch`  # merge my_branch into master.
- `git push origin master`  # push changes on master to github.

### Add a change directly to master (without using a new branch)

- Make required changes
- `git commit -a`  # opens the commit to add/amend a message. 
- `git push origin master`  # push changes on master to github.
