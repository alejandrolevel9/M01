### fdisk ###
+100K LINUX
+70M LINUX
+205M LINUX
+100M LINUX
+100M LINUX
+2M LINUX

*Comandos*
# ionice -n7 dd if=/dev/zero/ of image.sda bs=1024 count=$[500*1024]
# losetup /dev/loop0 ~/image.sda
# fdisk /dev/loop0
n, p, enter, enter, +100K
n, p, enter, enter, +70M
n, e, enter, enter, +205M
n, l, enter, enter, +100M
n, l, enter, enter, +100M
n, l, enter, enter, +2M

*Activa*
a, enter, 1, enter
*Swap*
b, enter, 7, 82
