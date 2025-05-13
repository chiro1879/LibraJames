# LibraJames
I'm like lebron james if he was a github repo
</br><img src="https://github.com/user-attachments/assets/12e2ee6f-c3d8-4f69-a7cc-9f63467e35bb" alt="drawing" width="500"/>

## Installing Dependencies 

Debian/Ubuntu:
```
sudo apt install libgtk-3-dev
```
Fedora:
```
sudo dnf install gtk3-devel
```
Arch:
```
sudo pacman -S gtk3
```

## Compiling
```
$ gcc `pkg-config --cflags gtk+-3.0` -o lebron lebron.c `pkg-config --libs gtk+-3.0`
```
