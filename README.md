## HelloWorld test - Install HelloWorld

* Install HelloWorld into VB

https://code.google.com/p/android-x86/downloads/list

## Compile Kernel for VB

* Download Kernel for VB 

** https://www.kernel.org

** http://android.googlesource.com

*. Use Android 4.x prebuilt toolchain

* Read Documentation/fb/vesafb.txt

*. Tune e2fs [Optional]

$ sudo tune2fs /dev/sdb1
$ sudo e2fsck -DC0 /deb/sdb1

### Partition Layout

```
# mount -t ext2 /dev/sdb2 /system
# mount -t ext2 /dev/sdb3 /data
# mount -t ext2 /dev/sdb4 /cache
```

### fdisk 

```
# fdisk ...
# mkfs.ext2 ...
# tune2fs ...
# e2fsck 
```














