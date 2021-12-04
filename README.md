# stremio-arm

Script that builds Stremio on armhf/arm64

Build to work on Ubuntu, but should also work on Debian

It also install nodeJS using NVM, but only if its missing

## Run in terminal:
```
wget -qO- https://raw.githubusercontent.com/rvmn/stremio-arm/main/stremio-build.sh | bash
```
It downloads the stremio icon from their mainpage and stores it into the hicolor theme (this is the fallback theme of most DEs), it should work on most cases, but if not copy the icon from the folder to your theme's name:
```
sudo cp /usr/share/icons/hicolor/scalable/apps/stremio.png /usr/share/icons/<<theme's name>>/scalable/apps/
```
to your theme


