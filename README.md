# ELITE_fingerprints

## INSTALL

1. get NOOBS on a card 
2. install recommended version of raspbian
3. update your raspberry and basic libs (python,...)
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3-dev python3-pip
```
4. clone this git project (for example I put it on /home/pi/ELITE_fingerprints)
5. launch `sudo pip3 install -r requirements.txt` to set your global environment to date to launch the script
6. TODO : add description of script to start it at launch (cf rc.start or whatever)

 



RFID configuration is inspired by https://pimylifeup.com/raspberry-pi-rfid-rc522/
