# amikitX_POL_script
AmiKit X is a package for installing AmigaOS 3.x on Windows and MacOS, using an emulator. The procedure to do that is really straight forward with AmiKit X. With this script you can install the Windows version under Linux, using WINE and PlayOnLinux.

Installation Procedure
----------------------
 1. Download the script ***POL_install_AmiKitX*** wherever you want
 3. When you start PlayOnLinux go to the menu "Tools > Run a local script". Choose the ***POL_install_AmiKitX*** file.
 4. Follow the instructions. You will see a message about the signature of the script, that it is not valid. Ignore and continue the installation.
 5. Follow and approve every step
 6. To setup the emulation under AmiKit X, read this [installation guide](http://bit.ly/AmiKit-QuickGuide)

**CAUTION:** This creates a wine prefix named AmiKitX. If one exists it will ask you what to do and if you want to overwrite the old one. If this is something you do not want to lose, then cancel the installation and give a different name at the line 18 of the script, so that there is no conflict.

Prerequisites
-------------
* You need to have installed at your system the [PlayOnLinux v4.2.10](https://www.playonlinux.com/en/download.html)
* wine 2.0-staging is also needed
* [AmigaOS & ROM Files](http://www.amikit.amiga.sk/getamigaos)


Credits
-------
AmiKit X by Ján Zahurančík & Contributors [www.amikit.amiga.sk](http://www.amikit.amiga.sk)
AmiKit includes more than [380 of the finest Amiga programs!](http://file.amiga.sk/amikit/doc/software.html)
Graphics by Kenneth E. Lester, Jr. [www.five-star.com](http://www.five-star.com)
WinUAE emulator engine by Toni Wilen [www.winuae.net](http://www.winuae.net)
Windows launcher and RomFind by Rex Schilasky
