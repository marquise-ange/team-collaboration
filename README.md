6. Commits

A commit is a saved snapshot of changes in a Git repository.

Commits allow developers to keep a history of what was changed and when it was changed.

Creating a Commit

First, check your changes:

git status

Stage the changes:

git add .

Then create a commit:

git commit -m "Add Git workflow documentation"

The -m option allows you to provide a message describing the changes.

Good Commit Messages

A good commit message should be short and describe what was changed.

Examples:

git commit -m "Add Git repository documentation"
git commit -m "Explain Git working areas"
git commit -m "Add branch documentation"
Viewing Commit History

To see previous commits:

git log

A shorter version is:

git log --oneline

Example:

d6d2bfb Git Installation and Configuration
97089cf First commit

Each commit has a unique identifier called a commit hash.