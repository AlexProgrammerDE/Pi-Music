# Musicpi

This repository is created to give everyone the possibility to play Music on the Raspberry Pi.

This Repository installs multiple music service repositorys to let you play music by Spotify Connect, Airplay and Bluetooth.

This is my first real projekt so dont be too hard to me when somethig not works.

I am not a good programmer.

But report me the Issue and I will try to fix it.

I am using already the following repositorys:

Spotify Connect: https://github.com/dtcooper/raspotify

Airplay: https://github.com/mikebrady/shairport-sync

Bluetooth: https://github.com/AdityaTelange/rpi-bluetooth-audio-player

Maybe can be found there help.

Now comes the fun part. 

First we update the system and install git.
```
sudo apt-get update && sudo apt-get install -y wget
```
This can take some time...

Now we clone my installation script.
```
wget https://raw.githubusercontent.com/AlexProgrammerDE/Musicpi/master/install.sh
```
Finally we run my installation script.
```
sudo bash install.sh
```
So youre finished good luck. :)
