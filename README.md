# Gatugrub
GRUB2 theme inspired by mundogaturro world selection screen

Testeado únicamente en resolución 1366x768, ¡puede que para otras resoluciones no ande!

# Instalación
1. Copiar `/gatugrub` a `/usr/share/grub/themes`
```console
sudo cp -r /path/to/gatogrub /usr/share/grub/themes
```
3. Cambiar el tema de grub en `/etc/default/grub`:
```console
GRUB_THEME="/usr/share/grub/themes/gatugrub/theme.txt"
```
3. Actualizar el grub con
```console
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
