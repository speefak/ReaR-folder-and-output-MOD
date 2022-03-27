# ReaR-folder-and-output-MOD
I missed in the ReaR ( Relax and Recover ) programm/script suite some very useful functions like creation of ISO hybridimages for USB Stick use, USB stickbackup does not contain bootable systems and is not networkshare compatible, ReaR directories are located in /tmp and /var - for very large backups often too small diskspace.   

This script adds the features listet above to ReaR.

Usage: $(basename $0) <options> "

-h		=> help dialog \n"
-cib		=> create ISO Backup\n"
-cUSB		=> create bootable USB drive\n"
-eISO		=> external ISO file for -cUSB option (-eISO <file.iso|iso>)\n"
-sshcc		=> SSH connection check\n"
-cfrp		=> check for required packages\n"
-m		=> monochrome output\n"


