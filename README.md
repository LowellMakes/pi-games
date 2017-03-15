# pi-games

Raspberry Pi Sense hat running 6 games/modes with a menu controlled by the onboard joystick.

## Installation

Following the instructions on https://www.adafruit.com/product/2738:

* Type: `wget -O - http://www.raspberrypi.org/files/astro-pi/astro-pi-install.sh --no-check-certificate | bash`
* Then reboot.
* `chmod +x menu.py`
* From there, either run the menu.py or add it to the end of /etc/rc.local before "exit 0".

## Usage

Use the onboard joytick to move the white dot up and down the menu items. Press down on the joystick to make your selection.

* Yellow - Where's the Treasure?
* Red - Random Sparkles (will run for 10 seconds)
* Orange - temperature (will run for 10 seconds)
* Green - Conways game of life (will run for 10 seconds)
* Purple - Nyan Cat (will run for 10 seconds) 
* Blue - Marble Maze 

Pressing and holding left on the joystick for 10 seconds will shut down the Raspberry Pi.

![Picture of Pi and Sense Hat in use](https://github.com/LowellMakes/pi-games/blob/master/picture-in-use.jpg "Picture of Pi and Sense Hat in use")


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

* @bradleypowers for helping me with the most important parts of the python code.
* Where's the Treasure? - From https://www.codeclubprojects.org/en-GB/sense-hat/wheres-the-treasure/
* Random Sparkles - From https://github.com/bennuttall/sense-hat-examples
* temperature - From https://github.com/bennuttall/sense-hat-examples
* Conways game of life - From https://github.com/bennuttall/sense-hat-examples
* Nyan Cat - From https://github.com/elsamuko/sense
* Marble Maze - From https://www.raspberrypi.org/learning/sense-hat-marble-maze/
