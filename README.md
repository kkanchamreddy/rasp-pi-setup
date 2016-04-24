# Raspberry Pi Setup

 I was excited to get started on the Raspeberry Pi, but the setup wasn't that easy as it was suppoesed to be, thanks to the [NOOBS setup](https://www.raspberrypi.org/help/noobs-setup/) which needs USB keyboard/mouse & monitor, which I didn't have.  

My next thought was, just SSH into the Pi, and ovecome the lack of keyboard. But only after spending an hour or so and using nmap to make sure the port is open on the Pi, learnt that SSH is not open by default with NOOBS SD card.

So I next downloaded the [Raspbian image](https://www.raspberrypi.org/downloads/raspbian/), and format the NOOBS SD card, and [create an image](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md) of it on the SD Card. For some reason I was not able to format the NOOBS SD card, and gave up after multiple tries.

Finally got a new micro SD Card, and was able to SSH into it. and setup the [VNC Server](https://www.raspberrypi.org/documentation/remote-access/vnc/), and [connect from Mac](https://www.raspberrypi.org/documentation/remote-access/vnc/mac.md) 
