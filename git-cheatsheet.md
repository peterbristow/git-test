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
- `git add file_name`
- `git commit -m "Commit message ..."`
- `git checkout master`
- `git merge --log --stat --no-commit my_branch`
- `git commit -a`
- `git checkout my_branch`
- `git log --stat`
