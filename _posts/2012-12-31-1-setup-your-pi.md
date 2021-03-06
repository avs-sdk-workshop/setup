---
title: '1. Setup Your Pi'


layout: nil
---

### Get your required hardware!

**You'll need a Raspberry Pi 3, SD Card, USB Mic, and 3.5mm Earbuds (or a Speaker).**

If you don't already have these items, you can find what you need on Amazon by clicking [here](http://a.co/46Jz9vy).

![ShoppingCart](https://alexavoiceservice.github.io/setup/assets/ShoppingList.PNG)

**First, use your PC to image your SD card with Raspbian OS and the AVS Device SDK.**

You can download the precompiled SD card image [here](https://fakelinkdropbox.com). 


### Download the workshop image onto your SD Card for the Raspberry Pi

**Windows PC:**
Get [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/) and follow the instructions [here](https://fakelink.com) to burn the pre-compiled image to your SD card.

**Mac OSX:**
Get [Etcher.io](https://etcher.io/) and follow the instructions [here](https://fakelink.com) to burn the pre-compiled image to your SD card.
 


### Plug everything in to your Raspberry Pi: 

1. Check that your micro SD card is inserted into the micro SD card slot on your Pi.  Contacts face up.
2. Plug in the USB microphone and 3.5mm earbuds.
3. Connect the keyboard and mouse to the USB ports.  Make sure you don't cover the USB mic!
4. Connect your monitor using the HDMI port.
5. Connect the Ethernet Cable (if not using Wifi)

**Your completed setup should look something like this:**

![Setup_Pi](https://alexavoiceservice.github.io/setup/assets/Rasp_Pi.jpg)


### Start up your Raspberry Pi!

Plug in the power supply to the micro USB connector on the Pi.  You should see a loading screen go through some startup steps before booting to desktop - if you run into any errors, try imaging a new SD micro card to boot the OS from.  Ensure your SD card was inserted upside-down (contacts facing up).

If not using wired Ethernet, activate wifi on your Raspberry Pi by clicking on the wifi icon in the top right corner of the toolbar and selecting your SSID.

Verify connectivity by opening a web browser - click on the globe icon in the top left toolbar.

{:.verify}
### Checkpoint 1
1. Make sure you're connected to the internet and are able to navigate to the developer homepage at [https://developer.amazon.com](https://developer.amazon.com).
