docker-ubuntu-vnc-desktop
=========================

From Docker Index
```
docker pull sidirius/docker-ubuntu-vnc-desktop
```

Build yourself
```
git clone https://github.com/Sidirius/docker-ubuntu-vnc-desktop.git
docker build --rm -t Sidirius/docker-ubuntu-vnc-desktop docker-ubuntu-vnc-desktop
```

Run
```
docker run -i -t -p 6080:6080 Sidirius/docker-ubuntu-vnc-desktop
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/Sidirius/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Trobleshooting
==================

1. boot2docker connection issue, https://github.com/Sidirius/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
