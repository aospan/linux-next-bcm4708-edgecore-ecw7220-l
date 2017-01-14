#Compilation:
```
make -j 4 LOADADDR=0x82008000 ARCH=arm CROSS_COMPILE=arm-linux-gnueabi- ecw7220l_defconfig
make -j 4 LOADADDR=0x82008000 ARCH=arm CROSS_COMPILE=arm-linux-gnueabi- uImage
```

#Boot from tftp
```
tftpboot 0x80000000 192.168.1.121:bcm4708-edgecore-ecw7220-l.dtb
tftpboot 0x82007FC0 192.168.1.121:uImage
bootm 0x82007FC0
```
