---
title: '4. Install the AVS Device SDK'


layout: nil
---


### Run the AVS Device SDK Install Script

You are now ready to run the install script. This will install all dependencies, including the **Wake Word Engine** (WWE) from Sensory.  The WWE compares your captured audio to an onboard model of a wake word (in this case "Alexa") and will initiate the connection to send captured audio to the AVS when triggered.

To run the install script, open a **terminal** by clicking on the console window in the Pi's toolbar at the upper left of the screen. There should be two scripts in your */home/pi/avs-sdk* directory: **config.sh** that you just populated, and **setup.sh** which uses the data from your config file to run the install script. Copy and paste the following command into your terminal window, and hit return:

`cd /home/pi/avs-sdk
bash setup.sh config.sh
`

If you have made an error in filling out the **config.sh** file with your account-specific information, the script will error out and inform you which field needs to be fixed.  In this event, return to your **Dashboard** on your Developer page, click **Manage** on your "Prototype" product, and double-check your copy and paste into **config.sh** was correct.

If your build was successful, you'll receive a printout of your configuration details (such as Client ID and Client Secret) plus a message informing you that Configuration/Build was successful.

![build_success](https://alexavoiceservice.github.io/setup/assets/build_successful.png)

For this workshop, portions of the script have been pre-built to get your client up and running faster.  If you use this script for an install on a clean OS image, expect it to take around 20 minutes to build.  You can use the text editor to view the contents of the **setup.sh** file. It's a relatively simple script designed to run on a clean install of the Raspbian **stretch** OS.

{:.verify}
### Checkpoint 6

1. Build completed without error output.
