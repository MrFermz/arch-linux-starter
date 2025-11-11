# Arch Linux Installer
1. `nano /etc/pacman.d/mirrorlist`
    * Change Thailand mirror to first line for fastest.
    * Ctrl+K to cut, Ctrl+U to paste
2. `archinstall`
3. reboot
4. `sudo pacman -Syu gnome-shell gnome-session gdm nautilus gnome-console gnome-control-center`
5. `sudo systemctl enable gdm.service`
6. reboot

# After login GNOME
1. `sudo pacman -Syu nano git base-devel`
    * git, base-devel are optional
2. `sudo nano /etc/pacman.conf`
    * Uncomment [multilib] block for enable more software
3. `sudo pacman -Syu`
4. You can using more package.


### Add/Remove UI (Optional)
2. `git clone https://aur.archlinux.org/yay.git`
3. `cd yay && makepkg -si`
4. `yay -S pamac-aur`
5. You can using AUR package.
