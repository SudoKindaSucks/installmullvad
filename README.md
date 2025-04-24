installmullvad is a simple script I made to install mullvad vpn on Gentoo Linux with OpenRC.
I made this script because I did it manually and thought "why not make a scipt for this."
All you need before running this script is a .deb file for mullvad vpn, Directories the script mentions
such as /opt, /usr/bin, /etc/init.d and .local/share/applications, sudo rights and a base Gentoo system ofc.
Before you run this script make sure your in the same directory as your .deb file, script and your not root
because this script relies on folders in the home directory such as .local.

To run:

sudo ./installmullvad

or for doas:

doas ./installmullvad

And as you should do with any script you download make sure to check it so you know what its doing especially if your running it with elevated priviliges.
