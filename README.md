# Yet-another-chroot-for-android

`integerating linux with android-apis`


i will be sharing scripts , modules and guides related to android in this repo.

Feel free to share any cool stuff related to chroot / xposed / kernel-related or anything that someone else may find interesting.

my setup in chroot :

*  mounts neccessary for chroot and a sshd starts at boot with service.d scripts
*  u can find it in chroot_sshd.sh
* a proper android su wrapper in chroot (in asu)


`run android apis with this daemon in chroot`
https://github.com/vaibhav423/Sushi

`work-in-progress`
https://github.com/vaibhav423/Sushi-x

## things to do:
* cli way to add android widgets
* lsposed daemon 4 code exec
* add termux-api in sushi
* v4l2loopback ?

## timepass stuff
u could use this to run a cative portal on android , i use it to share files by turning on hotspot
and by letting users connected to it to download , similar way to let others upload 

https://github.com/vaibhav423/android-captive-portal

use this to emulate phone as a bootdevice
requires kernel with usb gadget support and mass storage support

https://github.com/vaibhav423/dotfiles/blob/main/chroot/scripts/bootmode



