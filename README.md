4. Git Working Areas

Git uses different working areas to manage changes before they become part of the project's history.

The three main working areas are:

Working Directory
Staging Area
Repository
1. Working Directory

The working directory is where you create, edit, and delete files.

For example, if you create a file called:

index.html

and write some code in it, the changes are initially in the working directory.

Git can detect these changes using:

git status
2. Staging Area

The staging area contains changes that you have selected to include in the next commit.

To move a file to the staging area:

git add index.html

To stage all changed files:

git add .
3. Repository

The repository stores the committed history of the project.

After staging your changes, you create a commit:

git commit -m "Add index page"

The basic movement of changes is:

Working Directory
       ↓
   git add
       ↓
Staging Area
       ↓
  git commit
       ↓
   Repository