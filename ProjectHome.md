## What is opkg? ##
Opkg is a lightweight package management system. It is written in C and resembles apt/dpkg in operation. It is intended for use on embedded Linux devices and is used in this capacity in the [OpenEmbedded](http://www.openembedded.org/) and [OpenWrt](http://www.openwrt.org/) projects.


As best it can, opkg maintains backwards compatibility with ipkg and conforms to a subset of debian's policy manual regarding [control files](http://www.debian.org/doc/debian-policy/ch-controlfields.html).

## Git Repository ##
Opkg development now takes place in a Git repository hosted by The Yocto Project and can be found at http://git.yoctoproject.org/cgit/cgit.cgi/opkg/. You can clone this repository by running `git clone git://git.yoctoproject.org/opkg`.

The old Subversion repository is preserved here on Google Code for archival purposes, but all new development will be performed in the new Git repository.


## Download ##
opkg releases are now served from http://downloads.yoctoproject.org/releases/opkg as Google Code now longer allows new files to be made available for download.

The latest opkg release is [v0.2.4](http://downloads.yoctoproject.org/releases/opkg/opkg-0.2.4.tar.gz) ([mirror](http://www.paulbarker.me.uk/dist/opkg/opkg-0.2.4.tar.gz)), released 2014-11-14.

The latest opkg release candidate is [v0.3.0-rc2](http://downloads.yoctoproject.org/releases/opkg/opkg-0.3.0-rc2.tar.gz) ([mirror](http://www.paulbarker.me.uk/dist/opkg/opkg-0.3.0-rc2.tar.gz)), released 2014-12-23. This pre-release version may not be stable though!


## Contact ##
A mailing list for discussion is available here:
http://groups.google.com/group/opkg-devel

mailto: opkg-devel@googlegroups.com

## Reporting Bugs ##
If you find a bug, please report it in the [issue tracker](http://code.google.com/p/opkg/issues/list) or send mail to the mailing list.