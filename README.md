# LibraJames
I'm like lebron james if he was a github repo

## Installing Dependencies 

Debian/Ubuntu:
```
sudo apt install libgtk-4-dev
```
Fedora:
```
sudo dnf install gtk4-devel
```
Arch:
```
sudo pacman -S gtk4
```

## Compiling
```
$ gcc `pkg-config --cflags gtk+-3.0` -o lebron lebron.c `pkg-config --libs gtk+-3.0`
```
