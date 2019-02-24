# Rsync Time Machine

Rsync Time Machine is a backup system, based on rsync and very similar to
Apple's Time Machine. This means it will keep an history of each file at
different points in time.

## Pre-requisites

Rsync Time Machine is based on a Client-Server architecture. The clients are
the workstations to backup. The server is a remote server that will host the
backups.

Rsync Time Machine is based on rsync, so you will need it on both the
workstations and the server.

Rsync Time Machine uses SSH to transfer files and authenticate through SSH
keys, so your server must be reachable through SSH.
