# Steps
1. create usb

atyu@pia:~ $ blkid
/dev/mmcblk0p1: LABEL_FATBOOT="boot" LABEL="boot" UUID="5203-DB74" TYPE="vfat" PARTUUID="6c586e13-01"
/dev/mmcblk0p2: LABEL="rootfs" UUID="2ab3f8e1-7dc6-43f5-b0db-dd5759d51d4e" TYPE="ext4" PARTUUID="6c586e13-02"
/dev/sda1: UUID="699ca72b-68e4-45b8-8038-20833b6056ae" TYPE="ext4" PARTUUID="337b3518-01"

script it, get line by label and filter UUID

1. create target dir

mkdir /.syspi
sudo chown atyu:atyu /.syspi/
chmod 777 /.syspi/

1. encrypt usb

1. mount it

add line to fstab with USB details

1. install motion

1. configure it
1. enable bcm module
   sudo modprobe bcm2835-v4l2

1. start the service
1. start it
