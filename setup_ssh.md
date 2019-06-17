## Connection closed by **.**.**.** port 22

There is a white list of users in file `/ect/ssh.global.user.allowed`

Add your username.

## Refused user **** for service sshd

`/etc/ssh/sshd_config`

Add `AllowUsers otherusers`


