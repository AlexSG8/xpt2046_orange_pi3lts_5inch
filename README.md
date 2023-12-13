![alt text](https://github.com/AlexSG8/xpt2046_orange_pi3lts_5inch/blob/main/images/photo_2023-12-13_14-43-55.jpg)
![alt text](https://github.com/AlexSG8/xpt2046_orange_pi3lts_5inch/blob/main/images/photo_2023-12-13_14-43-51.jpg)

1. solder the jumpers
![alt text](https://github.com/AlexSG8/xpt2046_orange_pi3lts_5inch/blob/main/images/photo_2023-12-13_14-43-46.jpg)
3. cd /boot/overlay-user/
4. armbian-add-overlay sun50i-h6-spi-touch.dts   
5. vi /etc/X11/xorg.conf.d/51-touch.conf
6. vi /boot/armbianEnv.txt   
7. reboot
