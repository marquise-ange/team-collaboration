Branching & Merging

Branches let teammates work on different features without interfering with each other.

Create and switch to a new branch
bash
git branch feature-navbar        # create branch
git checkout feature-navbar      # switch to it
# or in one step:
git checkout -b feature-navbar
List branches
bash
git branch
Merge a branch into main
bash
git checkout main
git merge feature-navbar
Delete a branch (after merging)
bash
git branch -d feature-navbar

Use case: Teammate A works on feature-login, Teammate B works on feature-navbar. Each pushes their own branch, then merges into main via a Pull Request once reviewed.