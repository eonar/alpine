# alpine
```
# apk add xfce4 xfce4-terminal xfce4-screensaver lightdm-gtk-greeter
# setup-devd udev
# rc-service lightdm start
# apk add bluez blueman-manager hidapi
# modprobe uhid btusb
# rc-service bluetooth start
# rc-update add bluetooth
[bluetooth]# show controller_mac_address
[bluetooth]# select controller_mac_address
[bluetooth]# power on
[bluetooth]# agent on
[bluetooth]# default-agent
[bluetooth]# discoverable on
[bluetooth]# pairable on
[bluetooth]# scan on
[bluetooth]# devices
[bluetooth]# pair device_mac_address
[agent] PIN code: ####
[bluetooth]# #trust device_mac_address
```
