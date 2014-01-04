xbmcpi
======

xbmc img

find the device name of the disk
df -h to

#unmount the disk
sudo diskutil unmount /dev/disk2s1

#clone the disk to an image file
sudo dd if=/dev/disk2s1 of=/path/to/image/raspbmc.img bs=1m

#unmount the disk
sudo diskutil unmount /dev/disk2s1

#restore the image to disk
sudo dd if=/path/to/image/raspbmc.img of=/dev/disk2s1 bs=1m

#eject the disk
sudo diskutil eject /dev/disk2s1


