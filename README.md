# git-learn

## Merging

### Main types of merges:
1. Fast-forward merge
2. Merge commit
3. Squash merge
4. Rebase

1. Fast-forward merge
  - Fast-forward is the default way the git will attempt a merge.
  - Moves the base/master branch label to the tip of the feature branch.
  - Possible only if no other commits have been made to base/master branch since the feature branch was created.
  - If any commit is made to the base/master branch, Git will not allow to perform a fast-forward merge.
  
2. Merge commits
  - Combines the work of the tips of the feature and base/master branches and places the result in a single merge commit.
  - Merge commits have multiple parents.
  - These type of merges where multiple commits work is combined may result in merge conflicts.
  

  
