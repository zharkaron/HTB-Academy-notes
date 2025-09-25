# Basic Tools
Daily Tools can be used are 
- SSH
- Netcat
- Tmux
- Vim

## Using SSH

Secure Shell(SSH) is a network protocol that its default port is 22 and its capable of using password authentication or it can be passwordless using **Public-key authentication** The way it can be used is like this:
```
zharkaron@[/htb]$ ssh zhark@10.10.10.10

zhark@removeHost's password: ********

zhark@remotehost#
```

## Using Netcat

Netcat, ncat, or nc, is the best thing to check out ports open on a ip address for example to figure out the version and service that the ip address has open for example:
```
zharkaron@htb[/htb]$ netcat 10.10.10.10 22

SSH-2.0-OpenSSH_8.4p1 Debian-3
```
