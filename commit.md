---
layout: default
title: Git Commit
description: Lokale Änderungen an Repo veröffentlichen
---
## File hinzufügen
Dateien "Stagen" (zur Veröffentlichung hinzufügen) <br>
`git add <file>`
<br>
<br>

## File commit
Datei in einem Commit hinzufügen (eine Sammlung an Änderungen) <br>
`git commit -m "<Nachricht für den Commit>"`
<br>
Beispiel: <br>
`git commit -m "Das ist ein Test"`
<br>
Output: <br>
> [main a987158] add <br>
> 1 file changed, 3 insertions(+), 1 deletion(-)

<br>

![Output Git Commit](./assets/img/git-commit.jpg)

## Push
Commit (Sammlung an Änderungen) an Repository senden <br>
`git push`
<br>

![Output Git Push](./assets/img/git-push.jpg) 