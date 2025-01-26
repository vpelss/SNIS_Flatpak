# Space Nerds in Space Flatpak

Space Nerds in Space is a linux only space bridge simulator.

You can build it yourself here:

https://smcameron.github.io/space-nerds-in-space/

Or:

To install and run Space Nerds in Space with a Flatpak, open a linux terminal and type the following (once installed you just need the last line to run):

Install flatpak for your lixux distro, if required as per: 
https://flatpak.org/setup/

Usually:
- sudo apt install flatpak
- flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

Then install Space Nerds In Space:
- flatpak install --user -v https://vpelss.github.io/snis_flatpak/io.github.vpelss.snis_flatpak.flatpakref

Then run it:
- flatpak run io.github.vpelss.snis_flatpak

We also have an AppImage version:

https://github.com/vpelss/Space-Nerds-In-Space-Appimage

-----------------

built using: https://github.com/marketplace/actions/flatpak-builder


