# install  
cd /home/pi/Freeplay/  
git clone https://github.com/TheFlav/rpi-fan.git  
cd rpi-fan/  
sudo cp run-fan-service /lib/systemd/system/run-fan.service  
sudo systemctl enable run-fan.service  


# rpi-fan
Freeplay CM3 Fan

run-fan.py turns a fan on when CPU temperature exceeds a start temperature, and shuts the fan off when the temperature is below a stop temperature.

This is recommended for use with https://www.freeplaytech.com/product/freeplay-cm3-l2r2-adc-add-on-board/
