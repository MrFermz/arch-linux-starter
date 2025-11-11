# Arch Linux Starter
1. `nano /etc/pacman.d/mirrorlist`
    * Change Thailand mirror to first line for fastest.
    * Ctrl+K to cut, Ctrl+U to paste
2. `archinstall`
3. reboot
4. `sudo pacman -Syu gnome-shell gnome-session gdm nautilus gnome-console gnome-control-center`
5. `sudo systemctl enable gdm.service`
6. reboot

## After login GNOME
1. `sudo pacman -S nano`
2. `sudo nano /etc/pacman.conf`
    * Uncomment [multilib] block for enable more software
3. `sudo pacman -Syu`
4. `sudo pacman -S --needed git base-devel`
5. `git clone https://aur.archlinux.org/yay.git`
6. `cd yay && makepkg -si`
7. `yay -S pamac-aur`
