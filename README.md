I first made the installmullvad script for installing Mullvad VPN on Gentoo Linux but then I wanted to also support systemd and maybe SysVinit one day so I made a version of the script for systemd.
Requirements: A base system ofc, binutils, The .deb file, A supported init system, bash and all dirs mentioned in the script so /opt, .local/share/applications and the directory where init scripts are stored. 
This script needs to be run as root.
