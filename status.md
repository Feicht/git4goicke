---
layout: default
title: Git Status
description: Lokalen Status einsehen
---
# Git Status
Der Status zeigt immer den aktuellen Stand an und was als nächstes getan werden kann.
`git status`
<br>
#### Lokale Änderung ohne git add
Output: <br>
> D:\Dev\git4goicke>git status <br>
> On branch main <br>
> Your branch is up to date with 'origin/main'. <br>
> <br>
> Changes not staged for commit: <br>
>  (use "git add <file>..." to update what will be committed) <br>
>  (use "git restore <file>..." to discard changes in working directory) <br>
>        modified:   repo.md <br>
> <br>
> no changes added to commit (use "git add" and/or "git commit -a") <br>

#### Lokale Änderung mit git add, ohne git commit
Output: <br>
> D:\Dev\git4goicke>git status <br>
> On branch main <br>
> Your branch is up to date with 'origin/main'. <br>
> <br>
> Changes to be committed: <br>
>  (use "git restore --staged <file>..." to unstage) <br>
>        modified:   index.md