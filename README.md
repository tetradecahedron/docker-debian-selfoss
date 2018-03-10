[Selfoss RSS reader](https://selfoss.aditu.de/)

Remove (leave container in timezone UTC) or edit files/etc/cont-init.d/11-timezone to your preference

To keep data persistent mount ´/var/www/html´ ex:
[...]-v ./appdata/webapp:/var/www/html[...]

Set userid and groupid of container with environment vars
PUID=<uid(userid)>
PGID=<gid(groupid)>