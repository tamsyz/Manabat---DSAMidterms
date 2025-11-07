<!-- # How to Set up Git and GitHub

Manabat, Zoe S.
BSCPE 1-1

## Git set up
1. Go to the official site https://git-scm.com/
2. Download and install Git for your operating system.
3. Set your username.
4. Set your email address that is used to author commits on GitHub and on your computer.

## GitHub set up
### Create a GitHub Account
1. Sign up for a free account and verify your email address.
### Create a new repository
2. Click the “+” icon in the upper-right corner of the page.
3. Select “New repository.”
4. Enter a repository name and description.
5. Choose Public or Private, then click Create repository.
### Copy your repository link
7.  After creating your repository, copy the HTTPS or SSH link provided.
### Connect your local project to GitHub
8. Open your terminal or Git Bash in your project folder.
9. Initialize Git if you haven’t already: git init
10. git remote add origin https://github.com/username/repo-name.git
### Add and commit files
11. Add your project files to the staging area: git add
12. Commit your changes: git commit -m "first commit"
### Push files to GitHub
13. git push -u origin main
### Verify your repository
14. Go back to your GitHub repository page.
15. Refresh the page to see your uploaded files.

### Other Useful Commands
1. git clone <URL>: Copies a remote repo to your computer
2. git pull: Updates your local repo with the latest changes from GitHub
3. git log: Shows commit history
4. git diff: Shows changes made since last commit
5. git checkout -b <branch>: Creates and switches to new branch