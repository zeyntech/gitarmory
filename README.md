# gitarmory


### Update Flow
1. List all the git branches in the repo \
  ```git branches -a```
1. Go to the git branch from which you need to branch out \
  ```git checkout source_branch_name```
1. Run git status command to ensure the clean state of the repo (nothing is pending/modofied/etc) \
  ```git status```
1. Create a new branch from the source branch \
  ```git checkout -b new_branch_name```
1. Add, modify and delete files as necessary
1. Run git status command to see the changes in the stage and commit areas \
  ```git status```
1. Add the modified files into the staging area \
  ```git add path/to/file```
1. Commit the staged files \
  ```git commit -m "message" ```\
      OR \
  ```
  git commit -m "
  multi
  line
  message"
  ```

### Create Pull Request (PR)
1. Run git status or git log commands to see the committed changes \
  ```git status``` \
  ```git log```
1. Check the details of remote repo and ensure they are correct
  ```git remote show remote_name```
1. Push the changes to the remote repo
  ```git push -u remote_name new_branch_name```
1. Create a Pull Request (PR) for your changes to be reviewed, approved and included into the repo

