openSUSE 11.1 distribution and install process for use with coLinux.


This archive contains what is needed to install and run the openSUSE
image for use with coLinux:

   system.img                   4Gb system image
   swap512m.img                 512Mb swap location

   Batch and parameters file needed to start coLinux
   install.bat, install.txt     Installation process (needed once)
   runonce.bat                  Needed after installation
   run.bat, run.txt		Start the environment after install

   instructions-image.txt	How to install using image files
   instructions-rpm.txt         How to install using RPM



If you start the environment you need the following login credentials:

   username: root
   password: password

Network is configured from the parameters file 'run.txt'.



Installation was performed as described in the instructions. You would
need to download the businesscard ISO from Debian. You could find this
at:

   http://cdimage.debian.org/debian-cd/5.0.0/i386/iso-cd/

The businesscard ISO is about 35Mb.

With a tool like winrar (or mount it using a tool like Daemon Tools),
you can extract the file /install.386/initrd.gz and save it as

  install_initrd.gz

in the directory where you extracted this base directory.

If you prefer to only download the initrd.gz, you can find it on:

   http://dl.getdropbox.com/u/131903/debian-500-i386-initrd.gz

and rename it to install_initrd.gz.

An empty harddisk file can be created with this distribution or
download it from http://dl.getdropbox.com/u/131903/centos52-base.rar

After installing coLinux to the standard location you can run the
install.bat and start the installation process. When the installation
process interface is shown, you should toggle with ALT+F2 to a
console.

   Please press Enter to activate this console.

When you do so, you will see a BusyBox prompt where you can perform
the instructions as shown in the instructions.txt.

A more detailed instruction can be found at:

   http://blog.gbraad.nl/  [tagged as colinux opensuse]


It has been tested on the current stable version of coLinux, which is
0.7.3. Any comments are welcome at me+colinux@gbraad.nl.


Gerard Braad
