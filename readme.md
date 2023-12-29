# linux distro

my own Linux distro...

for now this is just a bunch of files which I use to manually make a sort of "distro".

# files

initramfs/init: init file that gets read and executed by the kernel when it boots.

rootfs/custominit: setups some stuff before asking the user to login.
rootfs/group: a default groups file with the root group.
rootfs/inittab: very basic busybox inittab file that executes custominit and also sets some other useful things.
rootfs/passwd: default passwd file with just the root user and blank password.
