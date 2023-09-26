# To Do List Project
Was created from local Windows. 
Steps used in making this from local to remote repository:
1. Created new folder in local system(a).
2. Checked hidden files. No '.git' found. Made this folder into new Git repository by using command 'git init'.
3. Created relevant files (index.html, README.md etc).
4. Checked status. Made all the untracked files tracked using 'git add .'
5. Commited the files using ' git commit -m "some msg" '.
6. Create a new repository(b) in GitHub where you will be tranferring this folder's data to it.
7. Establish a connection between your local Git repository(a) and a remote repository(b) using ' git remote add origin <--link of this new created repository on Github--> '.
8. Verifying whether the remote is properly set by command 'git remote -v'.
9. Check branch using 'git branch'. To rename branch - 'git branch -M main(or any branch name)'.
10. Push changes to the main(or any branch name) branch, use the command 'git push origin main(or any branch name)'. This step updates the Github repository.

# Some Shortcuts
Instead of always writing "git push origin main", we write "git push -u origin main" i.e. setting origin/ git set-upstream allows you to set the default remote branch for your current local branch. Once one does that, one only needs to write "git push" (Local --> GitHub).

When there is such a change in which only a single file is modified and no new(/untracked) is created, there commit and add can be done together using 'git commit -am "some msg'

# Branch Command
1. To navigate : git checkout <-branch name->
2. To create new branch : git checkout -b <-new branch name->
3. To delete branch : git branch -d <-branch name->

# Merging Branches
Create new branch. Do some changes in it. Use command "git push --set-upstream origin feature" to set upstream branch in this new branch (in order to use shortcuts such as "git push" etc).

To join two branches (two ways):
1. Using Git : (a)To compare two branches - git diff <-branch name-> 
               (b)to merge two branches - git merge <-branch name->
               
# 
When changes are done in remote repository using pull request, to reflect those changes in local repository too (Local <-- GitHub), we use "git pull origin main"