Check which disk, e.g. sdb:
> fdisk -l

Unmount drive:
> umount /dev/sdb 

Run dd:
# dd bs=4M if=input.iso of=/dev/sdb
> dd bs=4M if=lubuntu-16.04.1-desktop-amd64.iso of=/dev/sdb

To be sure:
> sync

