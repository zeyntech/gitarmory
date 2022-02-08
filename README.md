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
1. Add, modify and delete files as necessary \
1. Run git status command to see the changes in the stage and commit areas \
  ```git status```
1. Add the modified files into the staging area \
  ```git add path/to/file```
1. Commit the staged files \
  ```git commit -m "message" ```


