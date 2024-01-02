put it into /usr/share/X11/xkb/symbols

add to /etc/default/keyboard
XKBLAYOUT="us_proger,ru_proger"

and
sudo dpkg-reconfigure keyboard-configuration


to test layout:
setxkbmap us_home
