# springboard-6.3-branching-exercise

Part I
Answer the following questions:

1. What git command creates a branch? 
git checkout -b

2. What is the difference between a fast-forward and recursive merge?
Fast-forward merge is readily able to append commits of the new branch to the main branch because there were no conflicting changes on the main branch.

3. What git command changes to another branch?
git checkout

4. What git command deletes a branch?
git branch -d name_of_branch

5. How do merge conflicts happen?
Merge conflicts happen when changes were made on the main branch while different changes were made on the branch to be merged. The author must then choose between the two changes to decide which gets written to the main branch.


Part II
Practice with fast forward and recursive merges! Make a branch and add and commit onto it and merge it back into master.

Try to create your own merge conflict by modifying the same file on two separate commits on two separate branches.
