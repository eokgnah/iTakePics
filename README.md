# iTakePics
Simple Bluetooth Intervalometer for iPhones or Android with a cheap ESP32

Just take a ESP32 and flash him over the Browser.

* Zero configuration neened
* Zero programming needed
* Zero soldering needed

Steps:
1. klick the WEB-Installer <a href="https://eokgnah.github.io/iTakePics/iTakePics_Web_Installer.html">HERE</a> with Chrome or Edge.
2. connect the ESP32 with a usb cable to your computer. (if needed push the boot button while plugging in)
3. select the wanted delay version you want. (at the moment there is only a 33s version)
4. klick "CONNECT"
5. select the com-port of the ESP32. (if unsure, unplug and replug the usb cable and look which com port left and joined again)
6. klick "install iTakePics"
7. klick "INSTALL" again for confirmation
8. let him do the magic
9. done
10. reboot the ESP32, look for a iTakePics bluetooth device on your mobile
11. connect to it and it will get a button press "volume up" every 33 seconds to trigger a picture
12. open your camera app and the "volume up" will trigger taking a picture like you press the "volume up" button yourself

Hardware:
ESP32 - D1 Mini - for example https://de.aliexpress.com/item/1005007467718708.html

Versions:
v2024111001: initial Version - 33 Seconds fixed - ideal for nightime photogra

ToDo:
* More zero configuration versions for different intervals.
* A version with a small oled display and a rotary knob to select custom intervals.
  <a href="https://youtu.be/gfzHsvtZ4U0">prototype ;-)</a>
