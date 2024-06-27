# victron
This is for installing the venusos on raspberry pi 

Victron's Cerbo-S GX is like the ultimate solar system hub, connecting to the internet and showing off your solar data on their VRM portal.But why spend big bucks when you can DIY it cheaper and tailor it to your needs?Enter the Raspberry Pi! We're using the Raspberry Pi 4B 4GB, but a 3B works too. This little guy, with the help of the open-source community, can do wonders.

For more on the Cerbo-S GX, check out Victron's site. Let's get started!

What you will need
Raspberry Pi: Grab a Raspberry Pi 3 or newer for smooth sailing.
MicroSD Card: Minimum 16GB, preferably a reliable SD Card brand.
Victron Venus OS: Download this from Victron Energy's site and make sure it vibes with your Pi.
Victron Gear: Ensure your Victron gadgets can chat with Venus OS via USB or Ethernet.
Internet: Keep that connection steady for updates and remote monitoring.

Challenges and Considerations:
Compatibility: Make sure Venus OS plays nice with your Victron gadgets. Not everything might be best buddies.

Technical Knowledge: You'll need some tech smarts, especially writing images to the drive and when it comes to setting up networks and hooking up.

Support: DIY projects can be like a solo adventure, so community forums and online resources are your trusty sidekicks for troubleshooting.

Install:
Head over to the Raspberry Pi Imager page and grab the version for your operating system. Once installed the application will look like this.
Insert the SD Card you will be using into the SD Card Reader and plug it into your PC. Once it is plugged in make sure it shows up on the pc. Go to the VenusOS download page.

The raspberrypi2 image supports:
Raspberry Pi 2
Raspberry Pi 3 B
Raspberry Pi 3 B+
Raspberry Pi Zero 2W

The raspberrypi4 image supports:
Raspberry Pi 4
Raspberry PI CM4

Please make sure you download the correct image for your Raspberry Pi. Once you are in the folder that contains the correct image. Download the latest version of the VenusOS image.

The image will download. After the image is downloaded go back to the Raspberry Pi Imager. Choose the Raspberry Pi device that you are using.

After you have selected your device. You can choose the image file you have downloaded. You can drag and drop the file. Once the file is selected. You will see that the image name is now showing on the "operating system".

Go to the storage option and select your SD Card. It will wipe the SD Card and write the image you have added to the SD Card.

Press on next and confirm the message that it will erase all the data from the drive.

The image will be written to the SD Card or the drive that you chose. Once it is done remove the drive and insert it into your Raspberry Pi and boot it up.

Post installation:
If you have not installed the Victron Connect app go to the Google Play Store and install it. This is where you can connect it to the WiFi. The default pin to connect to the Raspberry Pi via Bluetooth is "000000".

On the first boot, there is a problem where if you connect to the Raspberry Pi with Bluetooth it connects and greys out the device, and if you try to go into it. There will be a message saying someone else is connected to it already.

Reboot the Raspberry Pi and connect to it again via Bluetooth through the Victron Connect app.

After you are connected to the Raspberry Pi it will show you the device information and from there you can connect it to the wifi.

If you are on the page you can tap on the settings icon in the top right-hand corner. The network settings tab will show there you can find the IP address of the Pi if you already connected it with an ethernet cable. If you have not connected it with a ethernet cable this is also the place to connect it to your wifi.

Once it is connected and has an IP address go to your browser and type in the IP address that the Pi is using. It will be your remote console of the device just like the Cerbo-S GX.

Transforming your Raspberry Pi into a Victron Cerbo-S GX is a rewarding project that enhances energy efficiency. Using open-source software and affordable hardware, you can create a customized energy monitoring system. This DIY approach not only saves costs but also provides a sense of accomplishment in managing your energy consumption and production.

Additional Resources:
https://github.com/victronenergy/venus/wiki/raspberrypi-install-venus-image
https://www.raspberrypi.com/software/
https://updates.victronenergy.com/feeds/venus/release/images/
