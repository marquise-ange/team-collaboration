3. Creating a Git Repository

A Git repository is a folder where Git tracks changes made to a project. Creating a repository allows developers to save different versions of their work and manage changes over time.

Creating a Git Repository Locally

To create a Git repository, first open the terminal and navigate to your project folder:

cd project-folder

Then initialize Git:

git init

The git init command creates a hidden .git directory inside the project folder. This directory contains the information Git needs to track the project's history.

To check whether Git is working correctly, use:

git status

Git will show the current state of the files in the repository.

Example
mkdir my-project
cd my-project
git init

After running git init, the folder becomes a Git repository.