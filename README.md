# dmenu-kostas

Custom build of a suckless dynamic menu (dmenu) utility for dwm.

Table of Contents
=================
* [Applied Patches](#Applied-Patches)
* [Installation](#Installation)
* [Keybindings](#Keybindings)

# Applied Patches

In this section I will present patches that I've applied to my custom build of dmenu.

* [Alpha](../main/patches/dmenu-alpha-20210605-1a13d04.diff) - patch to add transparency to dmenu instance.
* [Border](../main/patches/dmenu-border-4.9.diff) - patch that adds an outside border of a dmenu instance.
* [Center](../main/patches/dmenu-center-20200111-8cd37e1.diff) - patch that centers dmenu instance instead of it showing on top of screen.
* [Grid](../main/patches/dmenu-grid-4.9.diff) - patch that adds grid layout of programs list within dmenu.
* [Gridnav](../main/patches/dmenu-gridnav-5.0.diff) - patch that allows to go left and right when searching for programs within an open dmenu instance.

# Installation

1. Clone dmenu git repository:

`git clone https://github.com/KostasEreksonas/dwm-kostas.git`

2. Go to the folder cloned repository:

`cd dwm-kostas`

3. Build the package:

`make`

4. Run a clean install of this package with ***root*** privilleges:

`make clean install`

# Keybindings

|  Keybind |	  Function		 |
|:--------:|:-------------------:|
| Ctrl + P | Open a program menu |
