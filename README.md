# Space Nerds in Space Flatpak

Space Nerds in Space is a linux only space bridge simulator.

You can build it yourself here:

https://smcameron.github.io/space-nerds-in-space/

Or:

# Install with flatpak

If your distro does not already have flatpak installed, install flatpak for your linux distro as per: https://flatpak.org/setup/

Then install Space Nerds In Space: 
- flatpak install --user -v https://vpelss.github.io/snis_flatpak/io.github.vpelss.snis_flatpak.flatpakref

Then run it: 
- flatpak run io.github.vpelss.snis_flatpak

# AppImage

We also have an AppImage version: https://github.com/vpelss/Space-Nerds-In-Space-Appimage

-----------------

# WSL Installation Results

If SNIS is not working on your distribution, you might need to install some libraries. Not fuse is required for AppImage only.

Ubuntu WSL (sound does not work on WSL for me)

- sudo apt update
- sudo apt install xorg mesa-utils libportaudio2 libfuse2 

openSUSE WSL (sound works on WSL)

- sudo zypper install libfuse2
- sudo zypper install xorg-x11
- sudo zypper install Mesa
- sudo zypper install libportaudio2

Debian WSL (sound works on WSL)

- sudo apt install fuse libfuse2 xorg portaudio19-dev

Arch WSL


- to test
- sudo pacman -Syu
- sudo pacman -S fuse2
- sudo pacman -S portaudio
-  


