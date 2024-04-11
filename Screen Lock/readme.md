Doc: https://manpages.ubuntu.com/manpages/bionic/man5/weston.ini.5.html

https://superuser.com/questions/1084382/weston-screen-blanking

>From man pages for weston.ini, to disable screen locking, add next lines:
```
echo "
[core]
idle-time=0

[shell]
locking=false
" > $HOME/.config/weston.ini
```
