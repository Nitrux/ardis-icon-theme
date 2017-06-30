Ardis (icon theme) - Upstream repository
==============

![Ardis preview](http://orig09.deviantart.net/69ed/f/2015/140/2/9/prevardis_v1_1_2015_3_by_deviantn7k1-d8u57nl.png "Ardis is an icon theme made to be simple and beautiful.")
> Ardis is an icon theme made to be simple and beautiful..

Source is licensed under the [GNU GENERAL PUBLIC LICENSE version 2](http://www.gnu.org/licenses/gpl-2.0.html).

The actual released package is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives International 4.0 License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

* Check **LICENSE** file inside the package for more information.

Download
========

Icons are available to download for GTK based environments (Gnome, Cinnamon, Mate, XFCE, LXDE), KDE (Plasma, Plasma 5) and Android at the [Nitrux Store](http://nitrux.in/store).

Install
========

* Move the folder *Ardis* to `/usr/share/icons`.
* And finally select it in the Settings.

Reporting missing icons
========

When reporting missing icons make sure to follow these steps so we can resolve it faster:

### For Linux:

1. Add **screenshots**, images speak louder than words. Add a screenshot of the missing icon and the instances where it's displayed  ` (menus, taskbars, panels, notifications, etc.).
2. Use the following title prefix (without the quotes): "[Linux] App_name Desktop_environment" - that way we can tag them appropriately.
3. Add the relevant launcher information, software in Linux DE uses files with the extension *.desktop* as launchers in menus (like Homerun, Mint menu, Gnome Shell overview, Unity, etc.), these launchers are stored in **/usr/share/applications** (there might be a */kde* folder for KDE apps) for software installed through a package or the package manager. Applications such as Google Chrome apps install their launchers here: **/home/$USER/.local/share/applications/**. Simply open these files with a text editor and copy their contents into your issue.
4. Add a description of the software, it's very important for us to know what the software does as we are not able to install every software under the sun and test them.

Some software uses *hardcoded paths* in their launchers, as such even when we add the icon the system will not load it, you may use [Hardcoded Icon Fixer](https://github.com/Foggalong/hardcode-fixer) to resolve this problem.

Disclaimer
==========

* New issues (starting from November 6th 2014) that do not meet the criteria above will not be fixed.
* Issues with paid bundles will not be discussed here, you can contact us at our mail.
* You are allowed to open issues about licensing the icons for inclusion in your distribution (if your intention is to include them in a commercial end-product) or including them in your distribution repositories and/or porting them to a non-supported platform.
* Issues that are missing information and are requested for it and see no activity within 24 hours will be labeled as *expiring* and closed 1 week after the request is done.
