---
layout: post
title: Grub install
---
```shell
grub-install /dev/sda
grub-mkconfig -o /boot/grub/grub.cfg
cp /boot/grub/locale/en\@quot.mo /boot/grub/locale/en.mo
```
