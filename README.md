# My Unix Cheat Sheet

Clener way to show what mounted and not from live usb:

```bash
lsblk -f
```

Mount Virtual Filesystems to log in:

```bash
# Mount root and boot then:
sudo mount --bind /dev  /mnt/dev
sudo mount --bind /proc /mnt/proc
sudo mount --bind /sys  /mnt/sys
```
