5. Basic Git Workflow

The basic Git workflow is the process developers use to save and manage changes in a project.

The common workflow is:

Edit files
    ↓
git status
    ↓
git add
    ↓
git commit
    ↓
git push


Step 1: Edit Files

Create or modify files in your project.

Step 2: Check the Status

Use: git status

This shows which files have been modified, added, or deleted.

Step 3: Stage Changes

Use: git add .

 This stages all changes for the next commit.

Step 4: Commit Changes

Use: git commit -m "Describe the changes"

A commit saves a snapshot of the staged changes in Git's history.

Step 5: Push Changes

If the repository is connected to GitHub, use:

git push origin branch-name

For example: git push origin flora

This sends your local commits to the flora branch on GitHub.