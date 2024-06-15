---
layout: default
title: Clone Repo
description: Ein Repository clonen
---
Herausfinden, wo das Repository zu finden ist. <br>
github.com / gitlab.domain.xyz<br>
<br><br>
Meistens: <br>
Git-Server / Ordner / Repository .git<br>
<br>
Beispiel: https://github.com/User/Repository.git<br>
<br>
CMD-Befehl git<br>
`git clone <repo> [<dir>]`<br>
`git clone <repo> C:\Temp\xyz`<br>
> Ohne Pfad-angabe wird das Repo in das Verzeichnis gecloned, in dem die CMD akutell ist (current-dir)
<br>
Output:<br>
// <br>
D:\Dev\test>git clone https://github.com/Feicht/git4goicke.git <br>
Cloning into 'git4goicke'... <br>
remote: Enumerating objects: 22, done. <br>
remote: Counting objects: 100% (22/22), done. <br>
remote: Compressing objects: 100% (12/12), done. <br>
remote: Total 22 (delta 1), reused 14 (delta 1), pack-reused 0 <br>
Receiving objects: 100% (22/22), 4.54 KiB | 2.27 MiB/s, done. <br>
Resolving deltas: 100% (1/1), done. <br>
// <br>
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