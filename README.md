# Setup For Deployment 👇

- FORK THE REPOSITORY [Here](https://github.com/nimaofficial/Black-Dragon/fork)

## `Scan QR Code For Session`
[![Cheems Bot](https://repl.it/badge/github/quiec/whatsasena)](https://replit.com/@nimaofficial/BLACK-DRAGON-QR)

 ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/dashboard)

[![Deploy on Koyeb](https://telegra.ph/file/48228bbb836479f7a2863.png)](https://app.koyeb.com/deploy?type=git&repository=&branch=name&name=servicename)

[![Deploy on Mogenius](https://telegra.ph/file/946d83b461457a3c1598c.png)](https://studio.mogenius.com/studio/cloud-space/cloud-space-overview)

[![Deploy on Uffizzi](https://telegra.ph/file/e464e609e43eb3dfdc144.png)](https://app.uffizzi.com/projects)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nimaofficial/Black-Dragon-Lite/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/nimaofficial/Black-Dragon
cd Black-Dragon
npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/nimaofficial/Black-Dragon
cd Black-Dragon
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagrmagick
apt install bash
git clone https://github.com/nimaofficial/Black-Dragon
cd Black-Dragon
npm start
```
## `For 24/7 Activation (Termux)`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
