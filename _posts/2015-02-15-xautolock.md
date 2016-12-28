---
layout: post
title: xautolock
---
>Добавить в .xinitrc  
  
```shell
xautolock -time 7 -locker 'i3lock -i /img/lock.png -d' -nowlocker 'i3lock -i /img/lock.png -d'&
```
