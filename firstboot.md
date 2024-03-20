# First Boot

Plug in the ethernet cable to the Pi and the dongle.

Plug power into the Pi, either the USBc to USBc adapter from the box we just got or the power adapter from the CanaKit. 

The Pi should start flashing. Give it a bit to boot and then load up PuTTY or your favorite SSH client if you're nerdy enough to have a favorite SSH client. (Yes, I have a favorite, and it's not PuTTY)

    Side note. Don't forget to put the micro SD card into the Pi before turning it on. May be speaking from experience here. 

## PuTTY

Start up PuTTY and enter the IP address of the Pi into the box. Leave everything else as-is and click Open.

![](./img/putty.png)

You'll probably get a message about an unknown host key. Just accept it. It's a security warning to make sure you're connecting to the device you think you are. 

Next you'll see a login prompt. Enter the username and password you entered when you create the image a few steps ago. 

![](./img/logged-in.png)
