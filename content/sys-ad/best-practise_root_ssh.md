+++
title= "SSH using root@machine"
date= "2019-09-19T16:58:58-05:00"
Description= "how to disable root login on SSH"
Tags= ["article"]
Categories= ["article"]
+++

##### Disable root login on SSH
To take control on a distant computer on Linux, many system offers a default login by root admin user.
Technically you need to know user name and user account password to connect.
Therefore anyone willing to connect would just have to guess a password.

---
what if root access is removed without creating other users?
Then server access is lost and would require an intervention to reinstall the system.
[b]YE BE WARNED![/b]

---
How to disable it:
```
emacs /etc/ssh/sshd_config
```
```
PermitRootLogin yes
```
change to (or comment with #)
```
PermitRootLogin no
```
CTRL X, CTRL C to overwrite and return to shell.


Morevore one could also change port from 22 to something looking random.