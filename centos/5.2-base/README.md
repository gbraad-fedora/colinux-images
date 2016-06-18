CentOS 5.2 coLinux install process
==================================

This file contains what is needed to install the CentOS 5.2 image for
use with coLinux:

   system.img		4Gb system image, formatted as Ext3
   swap512m.img		512Mb swap location

   Batch and parameters file needed to start coLinux
   install.bat, install.txt	Installation process (needed once)
   run.bat, run.txt		Start the environment after install

   instructions.txt	file containing the performed commands


You would also need to download the businesscard ISO from Debian.
You could find this at:

   http://cdimage.debian.org/debian-cd/5.0.0/i386/iso-cd/

The businesscard ISO is about 35Mb.

With a tool like winrar (or mount it using a tool like Daemon Tools),
you can extract the file /install.386/initrd.gz and save it as

  install_initrd.gz

in the directory where you extracted this base directory.

If you prefer to only download the initrd.gz, you can find it on:

   http://dl.getdropbox.com/u/131903/debian-500-i386-initrd.gz

and rename it to install_initrd.gz.


After installing coLinux to the standard location you can run the
install.bat and start the installation process. When the installation
process interface is shown, you should toggle with ALT+F2 to a
console.

   Please press Enter to activate this console.

When you do so, you will see a BusyBox prompt where you can perform
the instructions as shown in the instructions.txt.

A more detailed instruction can be found at:

   http://blog.gbraad.nl/2009/03/manually-installing-centos-52-on.html

Any comments are welcome at me+colinux@gbraad.nl.


_Gerard Braad <me@gbraad.nl>_