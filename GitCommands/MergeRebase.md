# Merge and rebase

Create a new branch

```
git branch [new-branch-name]
```

Checkout a branch

```
git checkout [branch-name]
```

Merge a branch

```
git checkout [destination-branch]

git merge [source-branch]

git commit -m "[Commit message]"
```

Squash merge a branch

```
git checkout [destination-branch]

git merge --squash [source-branch]

git commit -m "[Commit message]"
```

Rebase a branch

```
git checkout [source-branch]

git rebase [destination-branch]

git checkout [destination-branch]

git rebase [source-branch]
```