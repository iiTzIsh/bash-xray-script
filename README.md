# Bash|Xray-Script

* UPDATE 28/11/2022 - added xray-nodomain script (see usage and installation below)


![logo](https://user-images.githubusercontent.com/118674919/204209549-d719ed81-c152-4851-938f-938c8f82dee7.png)



Xray-Script එක Use කරල ඔයාට High speed Network Connection එකක් / Low ping / Full stable Connection එකක් අත්විදින්න පුලුවන් ...


Manage Script

## :heavy_exclamation_mark: Requirements

* Ubuntu 20.04 or Ubuntu-latest Os එක සහිත Vps එකක්.
* UUID එකක් (V2rayN මගින් හෝ http://uuidgenerator.net මගින් UUID එකක් Genarate කරගන්න).
* DNS use නොකර Ip එකෙන් direct connect කරගන්න xray-nodomain ස්ක්‍රිප්ට් එක භාවිතා කරන්න.

------------------------------------------
## :book: Installation - Without DNS

```sh 
 apt-get update -y && apt-get upgrade -y
  ```
```sh 
sudo reboot
 ```
 
```sh 
sudo git clone https://github.com/iiTzIsh/bash-xray-script
 ```
 
```sh 
cd bash-xray-script
 ```
 
```sh 
sudo chmod +x xray-nodomain.sh
 ```
 
```sh 
sudo ./xray-nodomain.sh
 ```
 
------------------------------------------

## :book: How To Connect

1)Android User කෙනෙක්නම් V2rayNG Download කරගන්න (
https://github.com/2dust/v2rayNG)

2)Windows User කෙනෙක්නම් V2rayN හො Netch Software දෙක Download කරගන්න

![logo](https://telegra.ph/file/372eb568ce7a7776aa8c4.jpg)

* Http Port =  80

* Xtls port = 443

## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

```sh 
sudo rm  -rf  ~/bash-xray-script
 ```

```sh 
sudo git clone https://github.com/iiTzIsh/bash-xray-script
 ```

```sh 
cd bash-xray-script
 ```

```sh 
sudo chmod 777 remove-xray.sh
 ```

```sh 
sudo ./remove-xray.sh
 ```
 ------------------------------------------
 
## :octocat: Credits

1. https://github.com/teddysun - BBR autoscript


☆ https://t.me/Hpimadushanka ☆
