# version-control
1. git init is a command used to initialize a new Git repository in your project directory. It creates a hidden git folder, which tracks changes in your project.

2.Git add . 
This command adds files to the staging area, preparing them for a commit.

3.git commit
Commits the staged changes to the repository with a message. 

4.git push
Uploads local commits to a remote repository (e.g., GitHub).

5.git pull
Fetches and merges changes from a remote repository to your local branch.
example: git pull origin main  "Pull the latest changes from main branch"

6.git clone
Creates a copy of a remote repository on your local machine.
example: git clone <repository-url>

7. git merge
Combines changes from one branch into another.

8.git branch
Lists, creates, or deletes branches.
Branches allow you to work on features without affecting the main project.

9.git checkout (Switching Branches)
Moves between branches.
example:
git checkout <branch-name>  # Switch to a different branch
git checkout -b <new-branch>  # Create and switch to a new branch

10. git status
Shows the status of your working directory (which files are modified, staged, or untracked).
Useful before committing to check what’s change

11. git log
Shows the commit history.
You can see previous commits, their authors, and timestamps.

12. git reset
Undo last commit (permanently removes changes).

13.git stash → Temporarily save changes without committing.

14. git rebase → Reapply commits on top of another branch.

