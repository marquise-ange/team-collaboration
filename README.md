 7. Branches

A branch is an independent line of development in a Git repository.

Branches allow different developers to work on different parts of a project without immediately changing the main branch.

The default branch is commonly called:

main

For collaborative work, team members can create their own branches.

For example:

main
├── 1
└── 2


In this example:

* 1 represents the first developer's branch.
* 2 represents the second developer's branch.
* main is the shared main branch.

 Creating a Branch

To create a new branch, use:
git branch branch-name

For example:
git branch 1


To create a branch and switch to it at the same time, use:
git switch -c 1


Viewing Branches

To see the branches in your local repository, use:
git branch


The * indicates the branch you are currently using.

Example:
* 1
  main
  2


In this example, the * shows that the user is currently working on branch 1.
