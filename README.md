# ubuntu
configuration du réseau : https://guide.ubuntu-fr.org/server/network-configuration.html

#wifi
https://doc.ubuntu-fr.org/wifi_chipset_realtek_rtl8812au
iwconfig

git clone https://github.com/abperiasamy/rtl8812AU_8821AU_linux.git
cd rtl8812AU_8821AU_linux
sudo make -f Makefile.dkms install

```
git clone -b v5.6.4.2 https://github.com/aircrack-ng/rtl8812au.git
cd rtl8812au
make
sudo make install
sudo modprobe 88XXau
sudo lshw -class network
nmcli dev wifi
```
git clone -b v5.6.4.2 https://github.com/aircrack-ng/rtl8812au.git
cd rtl8812au
make
sudo make install
sudo modprobe 88XXau
sudo lshw -class network
nmcli dev wifi
