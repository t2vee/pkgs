# vee pkgs
This is the repository for all of my custom freebsd packages.  
I don't particularly have the effort to maintain these packages properly on the freebsd ports tree, so that means these are only available via my own pkg repository.
---
## install instructions
### add the repository
```
$ doas curl -o /usr/local/etc/pkg/repos/vee.conf https://pkgs.vee.city/repo.conf
```
### update pkg
```
$ doas pkg update
```
### install packages
```
$ doas pkg install sheepit-client
```
