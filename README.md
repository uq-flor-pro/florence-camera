adafruit-pi-cam
===============

Camera project for Raspberry Pi + camera + Adafruit PiTFT
By PaintYourDragon (Phil B) for Adafruit Industries

Read how to build this project over at 
[http://learn.adafruit.com/diy-wifi-raspberry-pi-touch-cam](http://learn.adafruit.com/diy-wifi-raspberry-pi-touch-cam)
Enjoy!

Modified by Bernhard Bablok. For list of changes, see ChangeLog.md

Not that the prereqs have changed compared to the original documentation:

- python-picam    (current version, tested with 1.8)
- python-pyexiv2  (new prereq)

## Updated dependency instructions for python3
``` bash
sudo apt-get install python3-picamera
sudo apt install libexiv2-dev libboost-all-dev
pip install py3exiv2
python3 -m pip install -U pygame
```
