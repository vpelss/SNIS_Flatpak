# Space Nerds in Space Flatpak

Space Nerds in Space is a linux only space bridge simulator.

You can build it yourself here:

https://smcameron.github.io/space-nerds-in-space/

Or:

# Install woth flatpak

If your distro does not alreadt have flatpak installed, install flatpak for your linux distro as per: https://flatpak.org/setup/

Then install Space Nerds In Space:
- flatpak install --user -v https://vpelss.github.io/snis_flatpak/io.github.vpelss.snis_flatpak.flatpakref

Then run it:
- flatpak run io.github.vpelss.snis_flatpak

We also have an AppImage version: https://github.com/vpelss/Space-Nerds-In-Space-Appimage

-----------------

If SNIS is not working on your distribution, you might need to install some libraries.

ubuntu (sound does not work on WSL for me)

- sudo apt install libfuse2 xorg Mesa libportaudio2

openSUSE (sound works on WSL)

- sudo zypper install libfuse2
- sudo zypper install xorg-x11
- sudo zypper install Mesa
- sudo zypper install libportaudio2


Slakware

Debian

Arch

Kali
