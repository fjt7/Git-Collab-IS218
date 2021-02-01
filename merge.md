![Merging](https://res.cloudinary.com/practicaldev/image/fetch/s--MEKaM3dY--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/430Q2w473e2R/Image%25202018-04-30%2520at%25201.07.58%2520PM.png)
## What is a merge in Github?

Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.

## How to merge branches?
```$ git merge```

To merge commits into the master branch, let's now switch over to the master branch.

```$ git checkout master```

## Note
Git will not allow you to merge until all changes in your current branch have been committed.

To resolve the issue:

```git checkout -b new-branch-name```

```git add . ```

```git commit -m "<your commit message>"```

## Sources:
* https://www.atlassian.com/git/tutorials/using-branches/git-merge#:~:text=Merging%20is%20Git's%20way%20of,merge%20into%20the%20current%20branch.
* https://backlog.com/git-tutorial/branching/merge/