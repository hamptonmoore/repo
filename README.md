# repo
On occasion some of my projects get turned into useful daemons or programs. If so I tend to publish them here so that they can be easily installed by myself and others.

### apt/dpkg
Add the following to `/etc/apt/sources.list.d/hamptonmoore.list`
```
deb [trusted=yes] https://repo.hamptonmoore.com/apt /
```

### yum/rpm
Add the following to `/etc/yum.repos.d/hamptonmoore.repo`

```
[natesales]
name=Nate Sales
baseurl=https://repo.hamptonmoore.com/yum/
enabled=1
gpgcheck=0
```
