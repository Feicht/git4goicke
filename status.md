---
layout: default
title: Git Status
description: Lokalen Status einsehen
---
# Git Status
Der Status zeigt immer den aktuellen Stand an und was als nächstes getan werden kann.<br>
`git status`
<br>
#### Alles ist aktuell
<!-- Output: <br>
> Already up to date. -->

<br>

![Output Git Status Alles gut](./assets/img/status-outp_good.jpg)
<br>
#### Lokale Änderung ohne git add
<!-- Output: <br>
> D:\Dev\git4goicke>git status <br>
> On branch main <br>
> Your branch is up to date with 'origin/main'. <br>
> <br>
> Changes not staged for commit: <br>
>  (use "git add <file>..." to update what will be committed) <br>
>  (use "git restore <file>..." to discard changes in working directory) <br>
>        modified:   repo.md <br>
> <br>
> no changes added to commit (use "git add" and/or "git commit -a") <br> -->

<br>

![Output Git Status Local Changes without Add](./assets/img/status-outp_wadd.jpg)
<br>
#### Lokale Änderung mit git add, ohne git commit
<!-- Output: <br>
> D:\Dev\git4goicke>git status <br>
> On branch main <br>
> Your branch is up to date with 'origin/main'. <br>
> <br>
> Changes to be committed: <br>
>  (use "git restore --staged <file>..." to unstage) <br>
>        modified:   index.md -->

<br>
![Output Git Status after Add without Commit](./assets/img/status-outp_wcom.jpg)
<br>
#### Lokale Änderung mit git add, mit git commit, ohne git push
<!-- Output: <br>
> D:\Dev\git4goicke>git status
> On branch main
> Your branch is ahead of 'origin/main' by 2 commits.
>  (use "git push" to publish your local commits)
>
> nothing to commit, working tree clean -->

<br>

![Output Git Status Ohne Push](./assets/img/status-outp_wpush.jpg)