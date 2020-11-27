Python ST7735
=======================
Note:
Please try first the parent project [cskau/Python_ST7735](https://github.com/cskau/Python_ST7735) or [adafruit/Adafruit_Python_ILI9341 ](https://github.com/adafruit/Adafruit_Python_ILI9341).
If the setting did not worked for you then try the setting of my code in file st7735_truly_custom.py.
As info the code is very fast developed for the purpose to create a demonstrator and not to share it with others.
I included the code to github incase someone has similar issues and maybe the setting that I use helps.

Ps. Sorry that the code is note documented. I was little bit lazy.

Thanks to
=======================
* Adafruit
* cskau
* everybody who worked on the code.

Thanks that you shared your work, it helped me a lot. 


Text from original repo
=======================
Python library to control an ST7735 TFT LCD display.  Allows simple drawing on the display without installing a kernel module.

Designed specifically to work with a ST7735 based 128x160 pixel TFT SPI display.

For all platforms (Raspberry Pi and Beaglebone Black) make sure you have the following dependencies:

````
sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus python-pip python-imaging python-numpy
````

For a Raspberry Pi make sure you have the RPi.GPIO and Adafruit GPIO libraries by executing:

````
sudo pip install RPi.GPIO
sudo pip install Adafruit_GPIO
````

For a BeagleBone Black make sure you have the Adafruit_BBIO library by executing:

````
sudo pip install Adafruit_BBIO
````

Install the library by downloading with the download link on the right, unzipping the archive, navigating inside the library's directory and executing:

````
sudo python setup.py install
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Modified from 'Adafruit Python ILI9341' written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution

