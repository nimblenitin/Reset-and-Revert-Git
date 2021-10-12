# Reset-and-Revert-Git

Reset - On the commit-level, resetting is a way to move the tip of a branch to a different commit. Revert - Reverting undoes a commit by creating a new commit.

Steps to perform-
- Rollback to a previous commit using the reset command
- Rollback to a previous commit using the revert command

```

1. Rolling back to a previous commit using the reset command for a repo with multiple commits-
$ git log --oneline 
$ git reset COMMIT_VALUE
COMMIT_VALUE is the commit id

2. Rolling back to a previous commit using the revert command for a repo with multiple commits-
$ git log --oneline 
$ git revert COMMIT_VALUE
COMMIT_VALUE is the commit id

3. Use the git log --oneline command to check the log of recent commits-
$ git log --oneline 

```
