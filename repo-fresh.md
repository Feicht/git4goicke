---
layout: default
title: Repo aktualisieren
description: Ein Repo aktualisieren
---
Um den aktuellen Stand vom Server zu aktualisieren:<br>
`git pull`<br>
<br>
Sollten sich lokale Änderung bestehen, welche überschrieben werden sollen:<br>
`git fetch -all`<br>
`git reset --hard origin/main`<br>
`git pull`<br>
<br>
Um lokale Änderungen zu behalten und dennoch aktualisierungen vom Server zu holen:<br>
`git stash`<br>
`git pull`<br>
`git stash pop`
<br><br><br>
[![Home](./assets/img/home.png)Home](https://git.fullme.sh/)<br><br>
[![Grundkonfiguration Git](./assets/img/gear.png)Nächste Seite: Git Status](./status.html)