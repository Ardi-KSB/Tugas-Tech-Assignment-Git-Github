1. What does git clean do? git clean to removes files that have not been staged yet
2. What do the -d and -f flags for git clean do? Remove untracked directories in addition to untracked files. If an untracked directory is managed by a different Git repository, it is not removed by default. Use -f option twice if you really want to remove such a directory.
3. What git command creates a branch? git checkout -b
4. What is the difference between a fast-forward and recursive merge? fast forwards can only happen if there have not been commits on the original branch while the new branch is being worked on
5. What git command changes to another branch? git checkout
6. How do you remove modified or deleted files from the working directory? git checkout
7. What git command deletes a branch? git branch -D
8. What does the git diff command do? shows you a difference between two different commits
9. How do you remove files from the staging area? git reset HEAD name_of_file or git rm --cached name_of_file
10. How do merge conflicts happen? When Git can not determine what file or folder to choose when merging since there have been different commits with changes to the same file