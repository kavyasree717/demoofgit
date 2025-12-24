# this my demo of git and git hub

# step -1 we create new directory using "mkdir < dirname>"

# step - 2 we use command "cd <dirname>" to change the dir and work on it to add new files ,etc

# step -3 now we create a dir but to perform git operations we need git file in the created dir so we initialize the dir by using "git init", so the dir get initialize in the git  reconginze the folder as git repo

# step - 4 now after initialization of dir we now add required or files in created dir then we add files and code using command "git add <file names> " or to add all files we can use "git add ." it will include all the files we want push.

# step -5 without adding you cannot commit because before adding files are untracked files so those files cannot be commited so when we use command "git add " and add files , flies beacome tracked so they can commit now we use command "git commit -m "message for the change" " and commit the changes.


#  files --> untracked (no commit)
#  files --> add the tracked (files can commit)

# before push the code now the created dir is in vscode to link  this in git hub we use command "git remote add origin <link>" in <link> we have to keep repo you created  in git so it links the vs code git repo to repo you created in the git hub <link> url is actual location of the repo in git hub


#  by using command "git remote -v " we can know where repo is present.


# in this origin is repo alia's which is standard for all files to push in reposoritry


# next we use branch where we store all this repo or changes done by other members in group with differnt branch we check the  branch name by command "git branch" . for changing the name of branch we use command "git branch -M <name> "


# step - 6 for pushing everything in the vs code to git hub we use command "git push -u origin main"

# -u is upstream tracking which track changes in files  used let us push files in same repo without origin main for everytime we push  if we want push again the changes we use command "git push" and it push all files in same repo after the each change we have to add to git and commit it and then push it in repo.


work flow


git hub
   |
  repo
   |
  clone
    |
  changes
    |
  add 
    |
    commit
    |
    push     


    