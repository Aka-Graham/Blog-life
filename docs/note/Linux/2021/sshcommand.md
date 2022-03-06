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

