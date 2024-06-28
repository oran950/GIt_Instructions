# Git Workflow Guide <br>
## Welcome to the Git Workflow Guide! This repository is designed to help you master the essential Git commands and workflows for managing your projects efficiently. Whether you're new to version control or looking to refine your skills, this guide provides a clear and concise overview of the steps required to set up a Git repository, manage branches, and collaborate with others using GitHub.

## In this guide, you'll learn how to:

## Initialize a Git repository: Get started with version control in your project.
## Track changes: Add, commit, and view the history of your files.
## Navigate versions: Checkout previous commits to see or revert changes.
## Collaborate with GitHub: Push your code to a remote repository, create branches, and manage pull requests.
## By following these steps, you'll be able to streamline your workflow, keep your projects organized, and collaborate more effectively with your team. Let's dive in and explore the powerful capabilities of Git and GitHub!


## If you are using Windows, download and install Git Bash. For Linux or Mac, Git is typically pre-installed.

# Create a new directory for your project and navigate into it
mkdir gitproject <br>
cd gitproject

# Initialize a Git repository
git init

# Create necessary files
touch index.html app.css

# Add files to the staging area
git add index.html app.css      # Add specific files <br>
 git add .                       # Add all files

# Commit changes
git commit -m "Add HTML and CSS files"

# View commit history
git log

# Checkout a previous commit (replace <commit_hash> with the actual hash)
git checkout <commit_hash>

# Connect the local repository to GitHub (replace with your actual repository URL)
git remote add origin https://github.com/your_repo/your_file

# Push local changes to GitHub
git push -u origin master

# Create and switch to a new branch
git checkout -b new_branch

# Push the new branch to GitHub
git push origin new_branch

# Open a pull request on GitHub and have it approved and merged

# Sync local repository with GitHub
git pull origin master



