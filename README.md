# Grub2 Theme Minimal

## Installation

##### clone repo :
```shell
$ git clone https://github.com/ShikherVerma/grub2-theme-minimal.git /boot/grub/themes/minimal
```

##### Edit /etc/default/grub :
```shell
GRUB_THEME="/boot/grub/themes/minimal/minimal/theme.txt"
```
##### Update grub :
```shell
$ grub-mkconfig -o /boot/grub/grub.cfg
```
