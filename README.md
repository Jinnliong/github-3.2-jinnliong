# github-3.2-jinnliong

# SCPT Cloud Infrastructure Engineering Cohort 4
## _Assignment 3.2 by Chin Jinn Liong_

## Explain what is GitHub Authentication and how what methods available to be implemented?

GitHub Authentication verifies users' identities before granting access to resources, protecting code and infrastructure. It enhances security, reduces risks, improves auditability, and complies with regulations. Methods include:

1. Username and password (basic, least secure).
2. Two-factor authentication (2FA) for added security.
3. Personal access tokens (PATs) for API/command line access.
4. Single sign-on (SSO) for simplified user management.
5. SSH keys for secure remote access.

Recommendations:
- Always use 2FA with username and password.
- Consider PATs and SSH keys with restricted permissions.
- Explore SSO for larger teams.

Additional notes for cloud infrastructure engineers:
- Secure cloud access similarly.
- Implement least privilege access control.
- Regularly review and update security practices.

Robust authentication is crucial for secure and resilient cloud infrastructure.


## 15 github commands and their usages

Here are 15 essential GitHub commands along with their usage:

1. git clone:

Usage: Clones a remote repository to your local machine.
Example: git clone https://github.com/user/repo.git

2. git init:

Usage: Creates a new Git repository in the current directory.
Example: git init

3. git status:

Usage: Shows the status of changes in the working directory and staging area.
Example: git status

4. git add:

Usage: Adds files or changes to the staging area for committing.
Example: git add file1.txt file2.txt

5. git commit:

Usage: Commits staged changes to the local repository.
Example: git commit -m "Add new feature"

6. git push:

Usage: Pushes local commits to a remote repository.
Example: git push origin master

7. git pull:

Usage: Fetches and merges remote changes into the current branch.
Example: git pull origin master

8. git branch:

Usage: Manages branches in the repository.
Examples:
git branch: Lists all branches
git branch new-branch: Creates a new branch
git checkout branch-name: Switches to a different branch

9. git merge:

Usage: Merges one branch into another.
Example: git merge feature-branch

10. git diff:

Usage: Shows differences between files or commits.
Examples:
git diff: Shows unstaged changes
git diff --staged: Shows staged changes
git diff master feature-branch: Compares two branches

11. git log:

Usage: View commit history of the repository.
Example: git log

12. git reset:

Usage: Undoes changes to files or commits.
Examples:
git reset HEAD file.txt: Unstages a file
git reset --hard HEAD~1: Resets to the previous commit

13. git stash:

Usage: Temporarily shelves changes to apply later.
Example: git stash

14. git remote:

Usage: Manages remote repositories.
Examples:
git remote -v: Lists remote repositories
git remote add origin https://github.com/user/repo.git: Adds a remote

15. git checkout:

Usage: Switches between branches or restores files from a previous commit.
Examples:
git checkout branch-name: Switches to a branch
git checkout -- file.txt: Reverts a file to its previous state


## 4 Commom Github commands essential to real-world projects and why.

Here are 4 GitHub commands that I believe are essential in real-world projects and why:

1. git status:

Why it's crucial:
Provides a clear overview of the current state of your working directory, staging area, and repository.
Helps you track untracked files, modified files, and staged changes, ensuring you know exactly what's going on before committing or pushing.
Prevents accidental commits or pushes of unwanted changes.

2. git commit:

Why it's crucial:
Creates snapshots of your project's progress, enabling you to revert to specific states if needed.
Records changes with meaningful messages that describe the purpose of the changes, making collaboration and future understanding easier.
Forms the backbone of version control, allowing you to track the evolution of your project and easily compare different versions.

3. git push:

Why it's crucial:
Shares your local changes with remote repositories, enabling collaboration with other team members.
Ensures your work is backed up and accessible to others, even if your local machine experiences issues.
Triggers continuous integration and deployment pipelines, automating testing and release processes.

4. git pull:

Why it's crucial:
Fetches and integrates changes made by other team members into your local repository.
Keeps your local codebase up-to-date with the latest developments, preventing conflicts and ensuring you're working with the most recent version.
Facilitates collaboration and avoids merge conflicts by frequently incorporating remote changes.
Additional notes:

While these 4 commands form a core workflow, other commands like git branch, git merge, git diff, git log, and git reset are often used in real projects as well, depending on specific needs and workflows.


## License

MIT