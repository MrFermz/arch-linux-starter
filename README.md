# Arch Linux Starter
1. `nano /etc/pacman.d/mirrorlist`
    * Change Thanland mirror to first line for fastest.
    * Ctrl+K to cut, Ctrl+U to paste
2. `archinstall`
3. `sudo pacman -Syu`
4. `sudo pacman -S gnome-shell gnome-session gdm nautilus gnome-console gnome-control-center`
5. `sudo systemctl enable gdm.service`
6. `reboot`
