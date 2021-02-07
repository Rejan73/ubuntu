# ubuntu
configuration du réseau : https://guide.ubuntu-fr.org/server/network-configuration.html

#wifi
https://doc.ubuntu-fr.org/wifi_chipset_realtek_rtl8812au
iwconfig

```
git clone -b v5.6.4.2 https://github.com/aircrack-ng/rtl8812au.git
cd rtl8812au
make
sudo make install
sudo modprobe 88XXau
sudo lshw -class network
nmcli dev wifi
```
cf : https://forum.ubuntu-fr.org/viewtopic.php?pid=22307661#p22307661


cd ~/rtl8812au
source dkms.conf
sudo mkdir /usr/src/$PACKAGE_NAME-$PACKAGE_VERSION
sudo cp -r * /usr/src/$PACKAGE_NAME-$PACKAGE_VERSION
sudo dkms add $PACKAGE_NAME/$PACKAGE_VERSION
sudo dkms autoinstall $PACKAGE_NAME/$PACKAGE_VERSION

#Raspberry
sudo rclone mount --umask=0 --allow-other --vfs-cache-mode full  hrgoogle: /home/shares/public/hrgoogle &

