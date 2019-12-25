Steps for auth:

1.  passwd -c user.passwd USERNAME
2.  docker create secret joplin.user.passwd userpasswd # it says joplin but its webdav. I just use this for Joplin
3.  run docker-compose.yaml
