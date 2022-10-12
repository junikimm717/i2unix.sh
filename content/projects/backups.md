---
title: "School Server"
date: 2022-10-11T20:03:45-04:00
unit: 7B
---

You may have noticed that your repository is getting hefty and unwieldy to work
with across the network.

## Task

Configure your current VPS (or you can make a new one) so that it syncs and
backs up all of your schoolwork (just in case you acciedentally it all).

Things that I expect from this project:

1. Archiving your backups (zip, tar, ...), and using cronjobs to schedule their
   creation.
2. A network filesystem (NFS, Samba, ...)
3. (Optional) Using some file-syncing program (syncthing, rsync, ...)
