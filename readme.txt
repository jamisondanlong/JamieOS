JamieOS is a debian distro with the budgie desktop it has many pre installed programs such as mate and gnome applacations.
It was made using linux live kit and sorry but it has that ugly bootsplash you can always change it. 
to make it an iso run gen_JamieOS_iso.sh (sudo bash gen_JamieOS_iso.sh) you can also run the zip script to make it a zip. 

Thank you for using JamieOS!
If you are reading this from a CD, it is already bootable.
Steps to make it bootable from your USB device are following:

1) Copy the entire /JamieOS/ directory to your USB drive.
   If you are using Windows, you will get for example E:\JamieOS\
   You probably already did this - just make sure you are on your
   USB drive now and not on your local harddisk.

2) Now navigate to directory /JamieOS/boot/ on your USB drive.
   In Windows, it will be E:\JamieOS\boot\ for example.
   Use explorer or any other file manager for this task.

3) While you're in the boot directory, locate file bootinst.bat
   Run it by doubleclicking it. It will setup your USB to boot.

-- That's it. Your USB device is now ready to boot JamieOS.
-- You can safely delete this file (readme.txt), it's not needed.
