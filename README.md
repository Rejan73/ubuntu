# ubuntu
configuration du réseau : https://guide.ubuntu-fr.org/server/network-configuration.html

#wifi
https://doc.ubuntu-fr.org/wifi_chipset_realtek_rtl8812au
iwconfig

```
cd
git clone https://github.com/lwfinger/rtl8812au
cd rtl8812au
make
sudo make install
sudo modprobe 8812au
sudo lshw -class network

```
cf : https://forum.ubuntu-fr.org/viewtopic.php?pid=22307661#p22307661
