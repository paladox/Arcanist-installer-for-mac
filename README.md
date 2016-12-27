# Arcanist installer for mac
This is a mac installer to install Arcanist for mac

To build this for yourself do the following from bash

git init

git submodule update

then run the following script from bash (Note: You may need to do sudo ./installer.sh)

You may need to chmod these shell scripts so do the following

chmod a+x installer.sh

chmod a+x uninstaller/uninstaller.sh

chmod a+x scripts/*

chmod a+x uninstaller/scripts/*

./installer.sh

To create the uninstaller run the following script from bash (Note: You may need to do sudo ./uninstaller.sh)

cd uninstaller

./uninstaller.sh

You will find it generates two files in this folder called arcanist-installer.pkg and uninstaller/arcanist-uninstaller.pkg these files are the installer and uninstaller.

Click on arcanist-installer.pkg which will start the installation process then follow the install steps.

You will find the files installed in /private/var/arcanist/ and /private/var/libphutil/ (Note these folders are not easily accisible by the macs finder. To find them you need to
go to the finder application then on the top bar click go and then click go to folder and type in /private/var/arcanist/ or /private/var/libphutil/)

Note: You will need to restart your terminal for the changes to be applied.

in uninstaller folder you will find file arcanist-uninstaller.pkg which will uninstall arcanist from your mac.