NOTES
=====

Handlers
--------

A SSH-Daemon Reload is not required because **socket activation** spawns a new sshd process.
Every new SSH connection automatically reads /etc/ssh/sshd_config from disk at the moment it connects.