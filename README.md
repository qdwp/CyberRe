# Install

```
./install.sh
sudo copy -rf ./CyberRe /boot/grub/themes/CyberRe
```

## Update Theme

```
echo 'GRUB_THEME="/boot/grub/themes/CyberRe/theme.txt"' >> /etc/default/grub
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

