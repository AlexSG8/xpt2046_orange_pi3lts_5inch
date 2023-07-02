# cd /boot/overlay-user/
# armbian-add-overlay sun50i-h6-spi-touch.dts
# vi /etc/X11/xorg.conf.d/51-touch.conf

Section "InputClass"
        Identifier      "calibration"
        MatchProduct    "ADS7846 Touchscreen"
        Option  "Calibration"   "140 3951 261 3998"
        Option  "SwapAxes"      "0"
EndSection

# reboot
