---
title: '3. Copy Your Credentials'


layout: nil
---

### Load your Device Credentials onto your AVS Prototype

On your Raspberry Pi, open the File Explorer by clicking on the folder icon on your toolbar at the top left.  It should come up in the */home/pi* folder.  Navigate to the *avs-sdk* folder.  Right-click on **config.sh** and select "Text Editor" to open your configuration file.  

![config](https://alexavoiceservice.github.io/setup/assets/config_file.png)

It should contain the following fields:

`CLIENT_SECRET=""
DEVICE_SERIAL_NUMBER=""
CLIENT_ID=""
PRODUCT_ID=""
`
In your web browser, navigate back to the AVS dashboard, where you can see all of your products associated with your Developer Account:  [https://developer.amazon.com/avs/home.html#/avs/home](https://developer.amazon.com/avs/home.html#/avs/home).

Click **Manage**. From **Details and management** copy your **Product ID** (no spaces) into the **PRODUCT_ID** field of your **config.sh** file.  For this project, the Product ID should be "PROTOTYPE".

Locate your Client ID and Client Secret (it should be visible after clicking "manage" on your product).  Copy your **Client ID** and **Client Secret**.

Place the **ClientID** and **ClientSecret** into the **CLIENT_ID** and **CLIENT_SECRET** fields in your config.sh file. 

The **Device Serial Number** is created by device makers and isn't used by AVS - for this workshop, it can be any alpha-numeric value (here it's 123456):

Your completed config.sh fields will look something like this:

`CLIENT_SECRET="12345678901234567890128901234567890123456789012345678901234"
DEVICE_SERIAL_NUMBER="123456"
CLIENT_ID="amzn1.application-oa2-client.12345678901234567890123456789012"
PRODUCT_ID="PROTOTYPE"
`
{:.verify}
### Checkpoint 3

1. Make sure you've saved the **config.sh** file in your */home/pi/avs-sdk* folder with your **Product ID**, **Device Serial Number**, **Client ID** and **Client Secret**.
2.  Verify that your **Product ID** is "Prototype" for this project.
