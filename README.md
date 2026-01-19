# Arch-Set-Re
how to fully setup my arch linux setup

1. Install Arch as normal

2. Install Yay:
          '''$ sudo pacman -Sy --needed base-devel git'''
          $ git clone https://aur.archlinux.org/yay.git
          $ cd yay
          $ makepkg -si
          $ cd ..
          $ rm -rf yay

3. Clone this repo:
          $ git clone https://github.com/mahmoodie/Arch-Set-Re.git

4. Change directory:
          $ cd Arch-Set-Re


5. Install pacman packages:
          $ sudo pacman --needed -S - < pacman-pkgs.txt

6. Install AUR packages:
          $ yay --needed -S - < aur-pkgs.txt

