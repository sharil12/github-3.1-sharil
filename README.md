# github-3.1-sharil

Git and GitHub Commands
This guide covers some of the most commonly used Git and GitHub commands. For more detailed information, please refer to the official documentation:

Git: https://git-scm.com/doc
GitHub: https://docs.github.com/
Git Basics
1. Initializing a Repository:

git init: Creates a new Git repository in the current directory.
2. Adding and Committing Changes:

git add <file>: Adds the specified file to the staging area.
git add .: Adds all tracked files to the staging area.
git commit -m "<message>": Creates a commit with the specified message, recording the changes in the staging area.
3. Pushing and Pulling Changes:

git push origin <branch>: Pushes the current branch to the remote repository named "origin".
git pull origin <branch>: Pulls down changes from the remote repository and merges them into the current branch.
4. Branching and Merging:

git branch <branch-name>: Creates a new branch.
git checkout <branch-name>: Switches to the specified branch.
git merge <branch-name>: Merges the specified branch into the current branch.
GitHub Commands
1. Cloning a Repository:

git clone <url>: Downloads a copy of the repository from GitHub to your local system.
2. Creating a Pull Request:

Go to the repository on GitHub and click "New Pull Request".
Select the branch you want to merge and the base branch.
Add a descriptive title and message explaining your changes.
Review the changes and submit the pull request.
3. Creating an Issue:

Go to the repository on GitHub and click "Issues".
Click "New Issue".
Add a descriptive title and explain the issue you are experiencing.
You can also attach screenshots, logs, or other relevant files.
4. Reviewing and Commenting on Code:

On a pull request or issue page, you can click on lines of code to add comments or suggestions.
You can also start a discussion thread to ask questions or provide feedback.
5. Managing Collaborators:

Go to the repository settings on GitHub.
Under "Collaborators", you can add or remove people who have access to the repository.
Additional Commands:

These commands are less common but can still be useful:

git status: Shows the current status of the working directory and staging area.
git log: Shows the history of commits for the current branch.
git diff: Shows the differences between the working directory and the staging area, or between the staging area and the last commit.
git revert <commit>: Reverts the specified commit.
git tag: Creates a tag on a specific commit.