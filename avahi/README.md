# chippro-docker avahi
Very small little image used for allowing Bonjour to work from your C.H.I.P Pro (and possiable other ARM devices). By default the hostname will be used.

Run instructions:

1. add or update files in the 'services' directory, sftp & ssh are shown my default
2. `docker run --volume /var/run/dbus:/var/run/dbus --net host lymbada/chippro:avahi_latest`
3. searh on your machine for an answer
   1. try 'Bonjour Browser'

