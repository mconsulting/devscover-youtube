# YouTube Subscribers Ticker
## For Raspberry Pi

## Video Guide:
- Watch how to set this up here: 

## Guide:
- Connect to your Pi via SSH
- do `sudo raspi-config` , navigate to Interface Options, then enable SPI
- Connect the Pi to the LED Matrix
- Run the following commands:
sudo apt-get update --fix-missing

sudo usermod -a -G spi,gpio pi

sudo apt install build-essential python3-dev python3-pip libfreetype6-dev libjpeg-dev libopenjp2-7 libtiff5

sudo apt-get install git

sudo -H pip3 install --upgrade --ignore-installed pip3 setuptools
- Navigate to where you want to store the code
- git clone <this repository>
- run `cd devscover-youtube`
- run python3 examples/tick.py
- To alter to be your own channel name, edit the text inside the file using something like nano, then change the channel ID to be your own

## References:

- Luma Library is from: https://github.com/rm-hull/luma.led_matrix
- LED Matrix can be bought:
- Raspberry Pi can be bought: 
