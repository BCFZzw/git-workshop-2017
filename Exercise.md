This is the first exercise!
===========================

This exercise shows how to use a merge to reconcile history.

Notice that this branch is diverges from the master branch.
Commit 59fd5a4 is the common ancestor.
Your goal is to merge this branch into the master branch.

To do so, checkout the master branch and use `git merge exercise-1` to merge
this branch.

This will prompt you for a message for the merge commit, whose parents will be
both `master` and `exercise-1`.
The usual semantics of committing apply here, so since HEAD is attached to
`master` and a new commit is created, `master` will be bumped forward to the
new commit.
