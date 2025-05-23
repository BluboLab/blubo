# BLUBO
"Blubo" is an advanced sensor for monitoring light pollution in various environments, using Hamamatsu S2386-5K photodiodes, custom transimpedance amplifiers to measure sky brightness and Raspberry Pi Zero 2W. Essential for environmental research and crafting sustainable lighting policies.

## How to setup:

1. On a clean installation of Raspbian 11 Bullseye (Legacy, 32-bits), download the repo:
```
git clone https://github.com/BluboLab/blubo.git
```
2. Update your Raspberry:
```
sudo apt-get update

sudo apt-get upgrade
```  
3. Finally, you must set the file as an executable. Open terminal and run the following code:
````
cd blubo

dos2unix blubo-setup.sh

chmod +x blubo-setup.sh

./blubo-setup.sh
````
4. Follow the instructions in the script.
