CentOS 5.2 distribution for use with coLinux.


This archive contains the CentOS 5.2 installation which can be used with coLinux.
Included are the scripts to start the emulation environment.

The login for the environment is

   username: root
   password:

Network is configured from the parameters file 'run.txt'.

Installation was performed from a modified initrd.gz and the stage2.img as provided by CentOS.
These instructions will be published on http://blog.gbraad.nl/ [tagged as centos colinux].

Kernel modules for version 0.7.3 have been installed from the RPM:

   http://gbraad.fedorapeople.org/files/kernel-modules-2.6-co0.7.3.i386.rpm.

This way they can be easily upgraded to a newer version. The stock CentOS kernel is installed,
but is unused. I haven't removed it, since some packages may depend on having a kernel 
installed. I choose not to have the modules be seen as a kernel to avoid conflicts.

This environment has been tested on the current stable version of coLinux, which is 0.7.3. Any
comments are welcome at me+colinux@gbraad.nl.


Gerard Braad