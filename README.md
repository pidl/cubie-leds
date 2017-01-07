# cubie-leds
init.d script to disable leds of cubietruck during system start

## intstall
1. copy ```cubie-leds``` into ```/etc/init.d``` directory
1. make script executable (```sudo chmod 755 /etc/init.d/cubie-leds```)
1. test leds off: ```sudo /etc/init.d/cubie-leds start``` 
1. test leds on: ```sudo /etc/init.d/cubie-leds stop``` 
1. register script for auto start: ```sudo update-rc.d cubie-leds defaults```
