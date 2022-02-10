# Git Workshop

## Remotes

## Multi branch feature + showcase of PR flow

```
-  base
--  feature/base-2
---  feature/base-3
```

## Interactive rebase

```
-  manual-rebase
```

input

```
1
2b
todo temp commit
2a
todo temp commit
3
2c
```

desired history

```
1
2
3
```

## reflog

```
- reflog-base
-- feature/reflog-feat-1
```

## rebase over a not up to date branch

rebasing over a branch that has changes on remote but not localy

```
- rebase-2
-- feature/rebase-2-feat
```

pulling not updated branch w/ a local change

```
- rebase-3
stash: rebase-3
```

## stashing

```
stash: 'stash-change'
```
