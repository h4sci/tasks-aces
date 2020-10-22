Merge conflicts solved by:
- create branch for everyone
- discuss merge options
- inserting spaces and lines while merging

Merge conflict terminal:

When trying to push:
To https://github.com/h4sci/tasks-aces.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/h4sci/tasks-aces.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


When pulling:
 git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.

When trying to merge:
git merge 
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
