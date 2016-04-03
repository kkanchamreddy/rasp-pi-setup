# Raspberry Pi Setup

After I got my Rasp pi, I was excited to get started on it, but the setup wasn't that easy as it was suppoesed to be, thanks to the [NOOBS setup](https://www.raspberrypi.org/help/noobs-setup/) which needs USB keyboard/mouse & monitor, which I didn't have.  

So I thought I could just SSH into the Pi, and ovecome the lack of keyboard. But only after spending an hour or so and using nmap to make sure the port is open on the Pi, learnt that SSH is not open by default with NOOBS SD card.

So I next downloaded the [Raspbian image](https://www.raspberrypi.org/downloads/raspbian/), and format the NOOBS SD card, and [create an image](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md) of it on the SD Card
