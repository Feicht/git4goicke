---
layout: default
title: Branch
description: Ein Brauch wählen
---
## Branch auswählen (optional)
<br>
Falls ein anderer Branch verwendet werden soll: <br>
`git branch -r`<br>
> zeigt alle verfügbaren branches an

<br>
Output:<br>
// <br>
D:\Dev\test\git4goicke>git branch -r <br>
  origin/HEAD -> origin/main <br>
  origin/main <br>
  origin/test <br>
// <br>
## Branch wechseln (optional)
<br>
um den branch zu wechseln: <br>
`git checkout <branch>`<br>
`git checkout test`<br>
<br>
Output:<br>
// <br>
D:\Dev\test\git4goicke>git checkout test <br>
branch 'test' set up to track 'origin/test'. <br>
Switched to a new branch 'test' <br>
//