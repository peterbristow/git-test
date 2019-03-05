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


Add git to existing local project and push to a new Github repo
---------------------------------------------------------------
- Make a new repo on Github
- `git init`  # Run while inside the project root
- `git commit -a`  # Add and commit the files
- `git remote add origin git@github.com:peterbristow/name_of_repo.git`
- `git push -u origin master`  # Push to Github
