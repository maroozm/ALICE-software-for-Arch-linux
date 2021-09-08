# BUILD ALICE software for Arch linux

These are the prerequisites to build ALICE software framework with **ROOTv6** and has been tested on *Manjaro Linux* and *Endeavour OS*. 

**sudo pacman -S libice libsm libx11 libxau libxaw libxcomposite libxcursor libxdamage libxdmcp libxext libxfixes libxfont libxft libx11i libxinerama libxkbfile libxmu libxpm libxrandr libxrender libxres libxss libxt libxtst libxv libxvmc libxxf86dga libxxf86vm xorg-server xorgproto xtrans cmake base-devel gsl gtk-doc gcc-fortran**

using an AUR helper: **paru -S libdmx env-modules**

**paru** is the helper I have, you can replace it with anyone you use.

These packages are enough. But if you can find any other package that is still missing, post an issue and contribute.

After installing the prerequisites, you can go to the alibuild page and install it via pip. The commands after this will ofcourse be the same as mentioned here:
https://alice-doc.github.io/alice-analysis-tutorial/building/custom.html

