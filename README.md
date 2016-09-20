# electron/d3 based Graphical Disk Mapper

Mostly just a skeleton repo for future projects; includes build scripts for cross compiling on Linux/Darwin/Windows and demonstrates use of node modules for raw file access.

![alt text](gdm.gif)

This is how I downloaded and compiled this skeleton app.

```sh
cd /opt/dev/
git clone https://github.com/kirjavascript/electron-diskmap.git
cd electron-diskmap
npm i
./darwin.sh
open /opt/dev/electron-diskmap/elek-darwin-x64/
```

Double click the icon, the app launches, to modify the root of the walk edit the following line: https://github.com/TyrfingMjolnir/electron-diskmap/blob/master/app/walk.js#L37

The app takes a while to quit though... is this normal? intentional? Or just the way JS works?

This app clocks in at 104MB compiled; could this be shrunk by using PLOVR or other javascript compilers?
