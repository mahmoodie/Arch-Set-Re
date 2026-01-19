# Arch-Set-Re
How to fully setup my Arch Linux setup

1. Install Arch normally

2. Install Yay:
          `$ sudo pacman -Syu --needed base-devel git`
          `$ git clone https://aur.archlinux.org/yay.git`
          `$ cd yay`
          `$ makepkg -si`
          `$ cd ..`
          `$ rm -rf yay`

3. Clone this repo:
          `$ git clone https://github.com/mahmoodie/Arch-Set-Re.git`

4. Change directory:
          `$ cd Arch-Set-Re`


5. Install pacman packages:
          `$ sudo pacman --needed -S - < pacman-pkgs.txt`

6. Install AUR packages:
          `$ yay --needed -S - < aur-pkgs.txt`

7. Setup LazyVim:
         `$ git clone https://github.com/LazyVim/starter ~/.config/nvim`
         `$ rm -rf ~/.config/nvim/.git`
8. Test LazyVim:
         `$ nvim`

9. Setting up Caelesta-Shell (finally):
       - Install some dependencies:
                   `$ sudo pacman --needed -S git wget curl gcc fish`
       - Clone the installer script:
                  `$ git clone https://github.com/caelestia-dots/caelestia.git ~/.local/share/caelestia`
       - Run the installer script:
                  `$ ~/.local/share/caelestia/install.fish`
       - Follow the instructions

10. Installing Sober:
          `$ flatpak install flathub org.vinegarhq.Sober`

11. Enabling GDM:
          `$ sudo systemctl enable --now gdm`

12. Reboot

13. Copy the files from .config to your own .config (using nautilus)

14. Install ML4W Wallpapers:
         `$ mkdir $HOME/Pictures`
         `$ cd $HOME/Pictures`
         `$ git clone https://github.com/mylinuxforwork/wallpaper.git`

15: Sign into zen browser, Proton VPN, Steam, and Sober (Roblox)


That should be all! This should set up my Arch setup on a fresh install of Arch Linux
