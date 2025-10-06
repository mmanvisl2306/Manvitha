Cloning a repository (git clone): This command copies a project from GitHub to your computer so you can work on it locally. It downloads all files, commit history, and branches of the project, making it ready for you to work on.
Example: git clone https://github.com/mmanvisl2306/Manvitha.git

Checking status (git status): This shows the current state of your project. It tells you which files have been changed, which files are staged and ready to be committed, and which branch you are currently working on. This is useful to keep track of your changes before committing.
Example: git status

Creating and switching branches (git branch, git checkout -b): Branches are a way to work on new features or fixes without affecting the main project. They help in keeping work organised and make collaboration easier.

Create a branch: git branch feature1

Switch to a branch: git checkout feature1

Create and switch in one step: git checkout -b new-feature

Pulling the latest code (git pull): This updates your local copy of the project with the newest changes from GitHub. It ensures you are working with the latest version and reduces the chances of merge conflicts later.
Example: git pull origin main

Committing and pushing changes (git add, git commit, git push): These commands let you save your work and upload it to GitHub so others can see your changes.

Stage changes: git add  : adds all modified files to the staging area.

Save changes with a message: git commit -m "message" : records changes with a description so you can track what was done.

Upload changes to GitHub: git push origin branch-name: sends your committed changes to the remote repository so they are available online.
