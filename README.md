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
Instead of always writing "git push origin main", we write "git push -u origin main" i.e. setting origin. Once one does that, one only needs to write "git push" 