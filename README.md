# sync-ssh

Purpose
=======
The perpose of this project is to be able to sync one's mercurial queue patches between local and remote locations. Not only this but it will also allow for one to be a ble to have a mechanism to allow copy from the remote machine back to the local machine. (supports macOS)

Installation
============
```
git clone git@github.com:byepolr/sync-ssh.git ~/.sync-ssh
ln -s ~/sync-ssh/sync-ssh /usr/local/bin/sync-ssh
. ~/.bashrc
```

Add the following to your .bashrc or .zshrc
-------------------------------------------
```
export SYNC_SSH_LOCAL_PATH=/path/to/local/mecurial/repo
export SYNC_SSH_REMOTE_PATH=/path/to/remote/mecurial/repo
```

Usage
=====
 `sync-ssh <username>@<ip_address>`
