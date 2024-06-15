---
layout: default
title: Clone Repo
description: Ein Repository clonen
---
## Repo finden
Herausfinden, wo das Repository zu finden ist. <br>
github.com / gitlab.domain.xyz<br>
<br>
HTTPS:// Git-Server / Ordner / Repository .git<br>
<br>
Beispiel: https://github.com/User/Repository.git<br>
<br>
CMD-Befehl Git<br>
`git clone <repo> [<dir>]`<br>
Beispiel: <br>
`git clone <repo> C:\Temp\xyz`<br>
> Ohne Angabe des Pfades wird das Repo in das Verzeichnis kopiert, in das aktuelles Verzeichnis (der CMD (dir))

<br>
Output: <br>
> D:\Dev\test>git clone https://github.com/Feicht/git4goicke.git <br>
> Cloning into 'git4goicke'... <br>
> remote: Enumerating objects: 22, done. <br>
> remote: Counting objects: 100% (22/22), done. <br>
> remote: Compressing objects: 100% (12/12), done. <br>
> remote: Total 22 (delta 1), reused 14 (delta 1), pack-reused 0 <br>
> Receiving objects: 100% (22/22), 4.54 KiB | 2.27 MiB/s, done. <br>
> Resolving deltas: 100% (1/1), done. <br>