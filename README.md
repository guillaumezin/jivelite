This is a slighty modifier version of JiveLite made to work on Rasbperry Pi with Adafruit 320x240 2.8" touchscreen with 4 buttons.

You need to install Adafruit retrogame software to emulate keyboard inputs from buttons.

This version can handle multimedia key volume up/down and mute buttons. This way, it can work with USB speakers with volume buttons (you need to edit /etc/asound.conf too, as shown in scripts/rasbian/etc/asound.conf file)

In scripts directory, there are various script for raspbian, including boot script and Adafruit retrogame configuration.

Please note that parameters of jivelite is hidden, unless Raspberry Pi is booted with 4th button (#27) is pressed.
