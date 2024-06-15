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
> [!Output]
> D:\Dev\git4goicke>git status
> On branch main
>Your branch is up to date with 'origin/main'.
>
>Changes not staged for commit:
>  (use "git add <file>..." to update what will be committed)
>  (use "git restore <file>..." to discard changes in working directory)
>        modified:   repo.md
>
> no changes added to commit (use "git add" and/or "git commit -a")
<br>
#### Lokale Änderung mit git add, ohne git commit
> [!Output]
> D:\Dev\git4goicke>git status
> On branch main
> Your branch is up to date with 'origin/main'.
>
> Changes to be committed:
>  (use "git restore --staged <file>..." to unstage)
>        modified:   index.md
