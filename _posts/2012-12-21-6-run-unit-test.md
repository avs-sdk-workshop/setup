---
title: '6. Run Unit Test'


layout: nil
---

### Unit Tests

You've got your client built, your credentials and refresh token in your configuration JSON, and your device is ready to connect to Alexa!  But how do we know it's a fully functioning client?  The AVS Device SDK includes scripts that can execute a complete series of Unit and Integration tests for you.  Let's run **Unit Test** to ensure our client is behaving as expected before we connect it to the cloud. 

Go to the terminal window, and run the following steps to execute the series of Unit tests on your prototype.

`cd /home/pi/avs-sdk/build
make all test
`

For this workshop, tests have been pre-built to save time.  If you have your earbuds or speakers in, you'll hear Alexa run through a series of audio tests as well as functional tests.  Note the test descriptions as they fly by to understand what is being exercised on your client.

Your test should show success, with the possible exception of a few Sensory WWE fails.  As a developer, any time you modify your client's on-device software, you should run **Unit Test** to ensure nothing was unintentionally broken.  Now you're ready to launch your client!

![test_pass](https://alexavoiceservice.github.io/setup/assets/testPassed.png)
