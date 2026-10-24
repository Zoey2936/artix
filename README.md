```sh
curl -sSfL https://zoey2936.github.io/artix/zoey2936.asc | sudo pacman-key --add -
sudo pacman-key --lsign-key 5F9F535F441EBD9AB3D44108E7582ABC4670AB6B
sudo nano /etc/pacman.conf
```
```
[custom]
SigLevel = Required
Server = https://zoey2936.github.io/artix
```
