---
layout: post
title: ADB over WiFi
---
Android Debugging Bridge — adb.   
Вы можете включить adb по WiFi с помощью команд в терминале вашего устройства:  
``` bash  
su
setprop service.adb.tcp.port 5555
stop adbd
start adbd
```
