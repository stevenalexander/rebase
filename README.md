# REBASE


Example of rebase usage

![Alt text](./master/rebase.gif)

```
# checkout new branch off master
git checkout -b example

# Show log with 3 commits for a feature
git log --pretty=oneline

# Start rebase in interactive mode
git rebase -i HEAD~3
# edit to change first two feature commits option to squash then wq to save and quit
# edit the commit to pretend you did it all in one neat commit like a pro!

# Show log with 1 lovely commit for a feature
git log --pretty=oneline
```