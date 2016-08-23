## 'Merge' a commit into the current branch

```
git cherry-pick [commitHash]
```

Grabs a commit by its hash and merges it into the current branch

## Change last (local) commit

```
git commit --ammend [any other options]
```

'Edits' the last local (not pushed) commit. To only change the message use the `-m` option.
