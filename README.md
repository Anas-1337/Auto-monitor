### Auto-Monitor

Auto-Monitor is a shell script I wrote to :

* Easily put the interface in `Monitor` or `Managed`

* Auto change the `mac` `address` using __macchanger__

* Set the `Tx`-`power` of the wifi interface


### Install

```bash
# Make sure the script is in your $PATH
git clone 
cd 
chmod +x wlan
```
#### Dependensies

* `ifconfig` (net-tools)
* `iwconfig` (wireless_tools)
* `aircrack`-`ng`
* `rfkill` From (__util__-__linux__ Or __netctl__)
* `grep`
* `git`

For Arch
```bash
sudo pacman -S net-tools wireless_tools aircrack-ng util-linux grep git
```
For Debian , Ubuntu Etc

```bash
sudo apt install net-tools wireless_tools aircrack-ng util-linux grep git
```
