12. Git Pull
What is Git Pull?

git pull is used to download changes from a remote GitHub repository and automatically integrate them into your current local branch.

It is commonly used before starting work so that your local project has the latest changes from your team.

Syntax
git pull origin branch-name
Example
git pull origin main

This downloads the latest changes from the main branch on GitHub and merges them into your current branch.

Use Case

Use git pull when:

Your teammate has pushed new changes to GitHub.
You want to update your local project.
You want to get the latest version before making new changes.
Important
git pull

is essentially a combination of:

git fetch
git merge
Commit Message
Add documentation for Git pull