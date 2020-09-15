# 1. Creation of repository, checkout, pushing, branching, committing
----------------------------------------------------------------
1. Create an empty local repository named Master, create a text file example.txt with the single line "initial master", push this repository to
a remote server
2. Checkout test into local repositories named DeveloperA and DeveloperB
3. For DeveloperA create a branch named common_branch, switch on it, push it to the remote server
4. For DeveloperB switch on common_branch locally
5. For DeveloperB in example.txt change "initial master" to "initial developer b", commit and push common_branch to the remote server
6. For DeveloperA in example.txt change "initial master" to "initial developer a", commit this locally

https://stackoverflow.com/questions/8198105/how-does-git-store-files#answer-8198276

# 2. Getting info on changes without checkout, rebase on master, resolving conflicts
-------------------------------------------------------------------------------
7. For Master in example.txt change "initial master" to "changed master", commit and push master to the remote server
8. For DeveloperB find out what changes are made in master without switching locally on master
9. For DeveloperA and DeveloperB make rebase of common_branch on master, resolve conflicts by putting "changed developer a"
and "changed developer b", respectively


# 3. Aborting of rebase: hard reset via Reflog, pushing after rebase
---------------------------------------------------------------
10. For DeveloperA return to the state immediately before rebase resetting on the commit in Reflog, after this make rebase anew
11. For DeveloperA push common_branch to the remote server, explain how to do this successfully
12. For DeveloperB rebase common_branch on remote common_branch, resolve conflicts, push the result to the remote server
13. For DeveloperA switch on the remote branch common_branch, what is wrong?
14. For DeveloperA find in Reflog the lost commit and switch on it, returning to the previous state for DeveloperA


# 4. Switching on remote branch instead of pulling, pulling, cherry-picking
-------------------------------------------------------------------------------------------------------------
15. For DeveloperA switch on the remote branch common_branch (with overriding local branch),
add a file nottocommit.txt, commit this file, push it
16. For DeveloperA change the text in example.txt to "changed developer a", make a commit, push the repository
17. For DeveloperB pull the remote repository (safe due to fast-forward)
18. For DeveloperB make new branch common_branch_b by taking what was locally before pull, switch on it,
perform cherry-picking of all commits excluding committing of nontocommit.txt
19. For DeveloperB push common_branch_b to the remote common_branch, switch on this remote common_branch (with
overriding local branch)


# 5. Why pull may be non-safe and should be made carefully
-----------------------------------------------------
20. What may be wrong, if DeveloperA make pull of common_branch this time? Get the changes made by DeveloperB in the remote repository locally not by pull

https://stackoverflow.com/questions/15316601/in-what-cases-could-git-pull-be-harmful

# 6. Renaming, moving and deleting of files in git, squashing to simplify the history
-------------------------------------------------------------------------------
21. For Master change the text in example.txt to "updated master", rename (via git!) example.txt to example2.txt,
push to the remote server
22. For Master create new folder Folder, add new empty file stub.txt in Folder, add stub.txt to the local repository, make a commit,
look at the log
23. For Master move (via git!) example2.txt to Folder, commit the result, look at the log
24. For Master delete (again via git!) Folder with example2.txt and stub.txt from the repository,
squash commits (starting from renaming of example.txt to example2.txt) into a single commit, push the result to the remote server


# 7. Merging, resolving conflicts in the case of merge
-------------------------------------------------
25. For DeveloperA change the text in example.txt to "updated developer a", push it to the remote server
26. For DeveloperA merge changes from master into common_branch, resolve conflicts by retaining
example.txt, push it to the remote server
27. For DeveloperB change example.txt to "updated developer b", commit the result locally, merge common_branch
with the remote branch common_branch, resolve conflicts so that the resulting example.txt contains two
lines: "updated developer a" and "updated developer b", but not commit the result

https://stackoverflow.com/questions/47089913/merge-commit-vs-normal-commit

# 8. Aborting of merge: hard reset, simplifying the history by mixed reset
-------------------------------------------
27. For DeveloperB abort merge by making hard reset to the state immediately before previous merge, make merge
from the previous item anew, commit the result without pushing, look at the log
28. For DeveloperB make a mixed reset to the state before merge, commit the result,
look at the log, push the result to the remote server

![Git tree movements vizualized](https://bitbucket.org/repo/Ag9LKzq/images/3166920292-qRAte.jpg)

# 9. Problems with pushing, stashing
------------------------
29. For DeveloperA change example.txt to "modified developer a", commit the result and push it to the remote server without fetching before pushing, explain why push cannot be done even with "Known changes" checked?
30. For DeveloperA make a mixed reset to the state before merging with master, commit the result anew, fetch, then push the result to the remote server, what may be wrong with the changes made by DeveloperB? 
31. For DeveloperB push the result with "Known changes" checked anew to restore the state of the remote branch,
for DeveloperA make mixed reset up to the commit common for DeveloperA and DeveloperB, stash changes,
pull results with fast-forward only, pop stash and make example.txt contain two lines: "modified developer a"
and "updated developer b"


# 10. Rebase: resolving conflicts in the case of deleted files, why squash is useful for resolving conflicts, ways to do squash
-----------------------------------------------------------------------------------------------------------
32. For DeveloperB change example.txt to "modified developer b", commit it, push to the remote server
33. For DeveloperB rebase common_branch on master, resolve conflicts with master by not deleting example.txt
34. Suppose the previous step was improper, for DeveloperB switch on the remote common_branch with overriding
35. For DeveloperB rebase again common_branch on master, resolve conflicts by taking the version of master
(i.e. deleting of example.txt), why we have multiple conflicts? how the number of conflicts may be made
less by squashing? 
36. For DeveloperB abort rebase, squash all the commits ahead of master into a single commit, make rebase anew
37. Suppose the number of files to be squashed is too big, for DeveloperB switch again on the remote common_branch with
overriding, this time make squash via mixed reset, make rebase anew


# 11. Picking of necessary commits via rebase
-------------------------------------------
38. For DeveloperA make rebase on master by picking only the last commit and changing the contents of example.txt
to two lines: "modified developer a" and "modified developer b", resolve conflicts by leaving example.txt
(this is the way of repairing branches alternative to cherry-picking in the case we need to drop wrong commits
ahead of master)


# 12. How to delete remote branches, pruning
--------------------------------------------------------
39. For DeveloperB push common_branch_b to the remote server, for DeveloperA make fetch
40. For DeveloperB delete common_branch_b from the remote server, how to delete common_branch_b from the
list of remote repositories for DeveloperA (prune old branches)?


# 13. Soft reset vs mixed reset
-----------------------------
41. For Master create an empty file example_added.txt, add it, commit to the local repository,
then make soft reset to the revision before committing, look at the state of the file
42. For Master commit example_added.txt anew, then make mixed reset to the revision before committing,
look at the state of the file, what is the difference with the previous state?
43. For Master make mixed reset to the commit preceding deletion of example.txt, explain why example.txt did not appeared in the local folder, recover example.txt by making revert

https://habr.com/post/203282/
https://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified

# 14. Making tags, switching on tags, committing after making tags, detached commits
------------------------------------------------------------------------------
44. For DeveloperB add an empty file nottagged.txt, commit it to the local repository, then mark the commit preceding adding of nottagged.txt by a tag, switch the local branch on this tag, realize that the state of files fully correspond to the desired one
45. For DeveloperB add an empty file tagged.txt, commit it to the local repository, then switch to master. What may
be with the commit containing tagged.txt (detached commit)? Make a new branch common_branch_tagged pointing to this commit not to lose it
46. For DeveloperB delete the created tag using "Browse References"


# 15. Usage of git.ignore
----------------------
47. For DeveloperB make file example.tmp and make git ignore it


# 16. Configuration of git
------------------------
48. Make globally via configuration that pull makes only fast-forward merges, this is done by adding the following lines in global .gitconfig:
```
[pull]
	ff = only
```

https://stackoverflow.com/questions/35296680/how-to-configure-git-pull-ff-only-and-git-merge-no-ff

# 17. Using Git from IntelliJ IDEA
--------------------------------
50. Perform all the steps from Section 2 in IntelliJ IDEA, please mind that references given by IntelliJ IDEA in the list from the field "Onto" correspond to heads of local branches, not remote ones. To be sure that you rebase on
a remote branch, you should edit this field manually, for instance, use /refs/remotes/origin/master for remote master

https://git-scm.com/book/en/v2/Git-Internals-Git-References

https://stackoverflow.com/questions/29914052/i-cant-understand-the-behaviour-of-git-rebase-onto
