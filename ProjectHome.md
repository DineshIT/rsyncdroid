Start/Stop rsync in android phones

# Installation #

**New version (0.4) have an embeded rsync bin and don't need to install or copy another files, simply install and use**

**Need rooted phone**

# Use it #
```
rsync -Pavz --no-g --no-p --no-numeric-ids \
    xx.xx.xx.xx::sdcard/ --delete ~/htcmagic/backup/
```
xx.xx.xx.xx is your Android IP (Use **MyIP** from Market to get it)


# Screenshots #

![http://rsyncdroid.googlecode.com/files/rsyncdroid1.png](http://rsyncdroid.googlecode.com/files/rsyncdroid1.png)
![http://rsyncdroid.googlecode.com/files/rsyncdroid2.png](http://rsyncdroid.googlecode.com/files/rsyncdroid2.png)
![http://rsyncdroid.googlecode.com/files/rsyncdroid3.png](http://rsyncdroid.googlecode.com/files/rsyncdroid3.png)
