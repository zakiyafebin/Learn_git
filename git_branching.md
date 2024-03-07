# Git Branch
Create a branch for every task or issue you work on. This ensures that your work on the task or issue is isolated from your existing codebase. That makes it easier to work on multiple parts of the project simultaneously, or try out ideas without adversely affecting your main codebase.\
By defaualt you will be in main branch. The following command will help you to see which branch you are on
* git branch
* ![git branching](images/gitbranch.png)
* The circles are commits, and together form the Git project’s commit history.
* New Branch is a different version of the Git project. It contains commits from the main branch but also has commits that it does not have.


> ### Create a new branch
> git branch branch_name
> ### Swithch to new branch
>  git checkout branch_name
>  ### Together we can use in a single command as follows
>  git checkout -b branch_name

## Git Merge

When we are finished with the task or issue, we want to merge the code for that task or issue into our main codebase. \
To merge a brange to main 
* Commit current changes in that branch
* Then switch to main branch by 
* git checkout main
* git merge branch_name
 >- ## Merging branches to remote repository
 > git push --set-upstream origin branch_name
 > goto the UI open the pull request and merge the pull rquest

