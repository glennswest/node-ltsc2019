# Node

A Windows Server Core Docker container image with Node.js 10.14.0 installed.

## Images

- glennswest/node-windows:10.14.0-windowsservercore-ltsc2019  -> Nano Server + Node + NPM + Yarn + Git

## Building

To build the images yourself use the following commands:

```
./build-ltsc2019.ps1
```

## Prebult

docker pull glennswest/node-windows:10.14.0-windowsservercore-ltsc2019

## Size
REPOSITORY                             TAG                                  IMAGE ID            CREATED             SIZE
glennswest/node-windows                10.14.0-windowsservercore-ltsc2019   b24cf0b54508        18 minutes ago      4.11GB

## Credit to StefanScherer

Derivied from: https://github.com/StefanScherer/dockerfiles-windows/node

