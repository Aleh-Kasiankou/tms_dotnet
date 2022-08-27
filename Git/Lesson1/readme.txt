Here is what has been studied/done during the first GIT lesson and home assignment:

Website with Git basic theory and exercises: https://learngitbranching.js.org/
Official Git Documentation: https://git-scm.com/docs 

Basic commands:

##### Start with Git #####

#git init [initializes new local git repository ] 
{https://git-scm.com/docs/git-init}

-b <name> [allows setting a non-standard name for the main branch]



##### Track changes with Git#####

#git add <filename / . > [adds the changed files to index. Dot symbol adds all the changed files to index] 
{https://git-scm.com/docs/git-add}

-i [enables interactive mode for adding files to index]


#git rm [removes file from index and/or from working directory] {https://git-scm.com/docs/git-rm}
--cached [only removes files from index]

#git commit [commits all the indexed changes to the current branch] {https://git-scm.com/docs/git-commit}

-m [adds a commit message]
-–amend [merge the last commit and the current one]



##### Branching #####

#git branch <name> [creates a branch with name <name>]{https://git-scm.com/docs/git-branch}

-d [deletes a branch]
-f <targetlocation> [puts the existing branch to the <targetlocation>]
-u <upstream> / --set-upstream-to=<upstream> [sets upstream remote branch]

#git checkout <branchname/ commit hash / HEAD^ / HEAD~2>  [move HEAD to the selected branch/position]
{https://git-scm.com/docs/git-checkout}
-b [create a new branch and checkout to it]

## Navigation:
^ parent
^2 second parent
~2 grandparent
^2~2 grandparent of second parent



##### Merging changes from two branches #####
#git merge <branch to merge> [Merges <branch to merge> into current branch]
{https://git-scm.com/docs/git-merge}

#git rebase <target> [moves all new commits to the <target> and overrides the git tree] 
{https://git-scm.com/docs/git-rebase}

-i [allows interactively select what commits to rebase]

#git cherry-pick <commit1> <commit2> [copies the selected commits to the current tree]
{https://git-scm.com/docs/git-cherry-pick}



##### Reverting commits #####
#git reset <target commit> !!!Only local. [Removes all commits after target] 
{https://git-scm.com/docs/git-reset}

#git revert <target commit> [creates commit with changes neutralizing selected commits] 
{https://git-scm.com/docs/git-revert}



##### Stashing changes ##### 
#git stash {https://git-scm.com/docs/git-stash} // to add more info



##### Working with remote repositories #####
#git clone
#git push
#git fetch
#git pull –rebase

Note:
Push | fetch | pull support the following syntax:
command origin <source:target> [where origin is remote repo]


##### Navigating through the tree #####
git log <commit> info about all commits before target one
git describe - displays nearest tag
Git tag <name> <commit> to put tag




Git Clients:
GitHub Desktop
Source tree
GitKraken
Git Extensions +++

Home Assignment:
 Resolve merge conflict | Done
Test a few Git Clients | Selected *Git Extensions*
Finish all the exercises  learngitbranching.js.org | Done
 