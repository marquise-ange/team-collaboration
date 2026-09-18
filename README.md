 7. Branches


 
​
19
 
Syntax
20
 
git pull origin branch-name
21
 
Example
22
 
git pull origin main
23
 
​
24
 
This downloads the latest changes from the main branch on GitHub and merges them into your current branch.
25
 
​
26
 
Use Case
27
 
​
28
 
Use git pull when:
29
 
​
30
 
Your teammate has pushed new changes to GitHub.
31
 
You want to update your local project.
32
 
You want to get the latest version before making new changes.
33
 
Important
34
 
git pull


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
