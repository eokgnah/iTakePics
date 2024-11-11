iTakePics

Simple Bluetooth Intervalometer for iPhones and Android using an affordable ESP32

Simply use an ESP32 and flash it through your browser.

* No configuration needed
* No programming needed
* No soldering needed

Steps:

1. Click on the WEB-Installer link <a href="https://eokgnah.github.io/iTakePics/iTakePics_Web_Installer.html">HERE</a> using Chrome or Edge.
2. Connect the ESP32 to your computer with a USB cable. (If necessary, hold down the boot button while plugging it in.)
3. Choose the desired delay version. (Currently, only a 33-second version is available.)
4. Click “CONNECT.”
5. Select the COM port of the ESP32. (If unsure, unplug and replug the USB cable to see which COM port disappears and appears.)
6. Click “Install iTakePics.”
7. Click “INSTALL” again to confirm.
8. Let it work its magic.
9. Done! Reboot the ESP32, then look for an "iTakePics" Bluetooth device on your mobile.
10. Connect to it, and it will trigger a "volume up" button press every 33 seconds to take a picture.
11. Open your camera app, and each "volume up" will trigger the shutter as if you pressed the button yourself.

Hardware: ESP32 - for example, here’s a link to a D1 mini: https://de.aliexpress.com/item/1005007467718708.html

Version: v2024111001: Initial version - fixed at 33 seconds, ideal for nighttime photography.

To-Do:

* Add more zero-configuration versions with different intervals.
* Develop a version with a small OLED display and rotary knob for custom intervals. (Prototype in progress!) <a href="https://youtu.be/gfzHsvtZ4U0">You may take a peek</a>
