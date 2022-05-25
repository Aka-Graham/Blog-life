
---
title: ssh 配置
date: 2022-05-25
tags:
- linux

categories:
- linux
---

chmod 600 authorized_keys
chmod 700 ~/.ssh
ssh 配置
```


RSAAuthentication yes
PubkeyAuthentication yes
PasswordAuthentication no
```
```
sshd -t
```

