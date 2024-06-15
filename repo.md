---
layout: default
title: Clone Repo
description: Ein Repository clonen
---

Herausfinden, wo das Repository zu finden ist.
github.com / gitlab.domain.xyz

Meistens:
Git-Server / Ordner / Repository .git

Beispiel: https://github.com/User/Repository.git

CMD-Befehl git
git clone <repo> [<dir>]

git clone <repo> C:\Temp\xyz
(Ohne Pfad-angabe wird das Repo in das Verzeichnis gecloned, in dem die CMD akutell ist (current-dir))

//
D:\Dev\test>git clone https://github.com/Feicht/git4goicke.git
Cloning into 'git4goicke'...
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 22 (delta 1), reused 14 (delta 1), pack-reused 0
Receiving objects: 100% (22/22), 4.54 KiB | 2.27 MiB/s, done.
Resolving deltas: 100% (1/1), done.
//

Falls ein anderer Branch verwendet werden soll:
git branch -r
(zeigt alle verfügbaren branches an)

//
D:\Dev\test\git4goicke>git branch -r
  origin/HEAD -> origin/main
  origin/main
  origin/test
//

um den branch zu wechseln:
git checkout <branch>
git checkout test

//
D:\Dev\test\git4goicke>git checkout test
branch 'test' set up to track 'origin/test'.
Switched to a new branch 'test'
//