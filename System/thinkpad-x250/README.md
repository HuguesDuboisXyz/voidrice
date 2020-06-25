# Thinkpad x250

## Specs

| Feature                      | Configuration                       |
| ---------------------------- | ----------------------------------- |
| CPU                          | Intel i7-5600U                      |
| Graphics                     | Intel HD 5500                       |
| RAM                          | 8GB                                 |
| Disk                         | 465.78 GiB Crucial_CT500MX2         |
| Display                      | 12.5" IPS FHD (1920x1080) non-touch |
| Wireless                     | Intel Wireless 7265 AC              |
| Built-in Battery             | 9 Cell                              |
| Additional Pluggable Battery | 6 Cell 19+                          |
| Backlight Keyboard           | Yes                                 |
| Layout Keyboard              | DE                                  |
| ThinkLight                   | No                                  |
| Fingerprint Scanner          | Yes                                 |
| Bluetooth                    | Yes                                 |
| Camera                       | Yes                                 |
| WWAN                         | ?                                   |
| Smartcard reader             | ?                                   |

## System (Void linux)

- Add `/etc/locale.conf`
- Add `/etc/rc.conf`

## Xorg

### Display

- Add `/etc/X11/xorg.conf.d/90-monitor.conf`

### Keyboard (layout DE)

- Add `/etc/X11/xorg.conf.d/10-keyboard.conf`

##  Fix sound

- Add `/etc/modprobe.ḍ/thinkpad-x250.conf`

## Resources

- [Debian support on ThinkPad X250](https://www.corsac.net/X250/)
- [Thinkpad X250 - Debian, XFCE and X.org config](https://blog.mclemon.io/debian-on-a-thinkpad-x250)
- [Lenovo ThinkPad X250 (Arch Wiki)](https://wiki.archlinux.org/index.php/Lenovo_ThinkPad_X250)
- [Lenovo ThinkPad X250 (Gentoo Wiki)](https://wiki.gentoo.org/wiki/Lenovo_Thinkpad_X250)
