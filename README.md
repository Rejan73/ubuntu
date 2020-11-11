# ubuntu
configuration du réseau : https://guide.ubuntu-fr.org/server/network-configuration.html

#wifi
https://doc.ubuntu-fr.org/wifi_chipset_realtek_rtl8812au
iwconfig

git clone https://github.com/abperiasamy/rtl8812AU_8821AU_linux.git
cd rtl8812AU_8821AU_linux
sudo make -f Makefile.dkms install

```
cd 
sudo modprobe -r rtl8812au
rm -rfv rtl8812AU_8821AU_linux
git clone https://github.com/gnab/rtl8812au.git
cd rtl8812au
make
sudo make install
sudo modprobe 8812au
sudo lshw -class network
```
