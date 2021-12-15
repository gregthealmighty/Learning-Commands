# Learning-Commands
learning gitbash commands
![image](https://user-images.githubusercontent.com/89087300/146108177-362ea4d2-1be7-4e96-b43a-28bf1672ee00.png)

Git Bash commands or git commands:

# 1. git --version

   To know the version of Git.

# 2. git init

   To create a Local repository

    Initialized empty Git repository in ..../RepositoryName/.git/

# 3. git bash.exe 

    It is like git cmd(Command Prompt)

# 4. git status

   To know unstaged/Untracked files/ Workspace files/ Staged files/Modified files

# 5. git add app1.txt

   Used to add individual files in Stage Area

# 6. git add . 

   Here . dot means all files.

   Used to add all files in Stage Area.

# 7. git rm --cached -r . --cached

    Remove files in Staged Area to keep in Workspace.

# 8. git rm --cached one.txt

    Remove file in Staged Area to keep in Workspace.

# 9. git commit -m "your message"

     Here -m is a message

     Commit selected files into Local Repository.

# 10. git config --global user.email " Your Email"

     Your Git Credentials(these Details Stored in control panel>Users and Accounts> credential Manager>Windows Credentials)

# 11. git config --global user.name " Your User Name"

     Your Git Credentials(these Details Stored in control panel>Users and Accounts> credential Manager>Windows Credentials)

# 12. git remote add origin https://github.com/UserName/RepositoryName.git

     Create Remote Repository add above.

# 13. git push -u origin main

     Local Repository files Stored in a remote repository.

     Send files from Local Repository to Remote Repository.

 # 14. git push 

     Second push onwards use like git push

     Send files from Local Repository to Remote Repository.

# 15. git pull

     Fetch files from Remote to Local Repository.

# 16. git restore one.txt

     Here one.txt is a file name with an extension used to Undo/Remove Modifications in files.

     To cancel workspace file changes or to avoid changes.

# 17 git commit 

      For long String commit message then appears terminal press I for insert mode enter commit message :wq for saving and exit press Esc.

# 18. git pull origin main

The first-time git pull origin main<branch name> used to retrieve files from Remote repository to Local Repository+Workspace folder.

# 19. git checkout

Used for check out any branch up to date or not.

or Changing from one branch to another branch.

# 20. git diff

 To see files modified code or

changes made on a file or

To check the changes in the working area and the staged area.

  __21. git diff --staged

To see files modified code or

changes made on a file or

Displays the differences between files in two commits or

To check the changes in the staged area and the Local repository area.

__22. git diff head

To see files modified code or

changes made on a file or

Displays the differences between files in two commits or

To check the changes in the working area and the Local repository area.

Note History in remote repository to see modifications in files every commit and history used to compare first commit and second commit.

__23. cls clear the cmd command line

__24. git branch

Note Point: branch-related all commands work after adding remote URL in the local repository.

To see the correct working branch name green color or To see the all available branches black color.

__25. git branch branch_name

Used to create a new branch

__26. git checkout branch_name

Switch to branch branch_name

__27. git checkout -b branch_name

To create a new branch, switch to that new branch.

__28. git switch branch_name

Switch to branch branch_name

__29. git switch -c branch_name

To create a new branch, switch to that new branch.

__30. Caused because of: git pull origin master

The first-time git pull origin main<branch name> used to retrieve files from Remote repository to Local Repository+Workspace folder.

Error: refusing to merge unrelated histories

Solution: git pull origin master --allow-unrelated-histories
__31. how to Git copy changes from one branch to another
git checkout BranchB
git merge BranchA
git push origin BranchB
32. git branch -d Branch_Name


