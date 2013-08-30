Linux Malware Detect
====================

Linux Malware Detect install script

Installs all dependencies using apt or yum

Tested on:
* CentOS 5.8/6.4
* Debian 6.0/7.0
* Fedora 17
* Ubuntu 10.04/12.04/12.10

Default temp dir is ````/tmp/lmd````, this can be changed in install script.

By default, the installer logs into ````$TMP/install.log```` and ````$TMP/error.log````. Check these for further info about the installation process.

## Dependencies
* Package manager (apt or yum)
* HTTP Client (curl, wget or fetch)
* TAR executable
* Mail (Debian/Ubuntu: mailutils, RHEL: mailx)

Dependencies will be installed during the progress, but installing them on your own is advised.

## Installation

Download and run ````install.sh````

### Offline installation

Clone this repository or download ````install.sh```` and download the following file manually into the install script path:

[LMD Archive](http://www.rfxn.com/downloads/maldetect-current.tar.gz)

Run ````install.sh````


For further info check [Official website](http://www.rfxn.com/projects/linux-malware-detect/)

[README](http://www.rfxn.com/appdocs/README.maldetect)

[Installation tutorial](http://www.tecmint.com/install-linux-malware-detect-lmd-in-rhel-centos-and-fedora/)