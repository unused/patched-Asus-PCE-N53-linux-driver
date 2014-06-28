# Linux Driver Asus PCE-N53 (Ralink RT5592 chipset)

As the driver for Asus PCE-N53 offered by [Asus Support](http://www.asus.com/Networking/PCEN53/) is for very old Linux Kernel (before 2.8) i picked up the community patch and a further change necessary to pack the driver source needed for running this card or any on similar chipset.

Tested and running with Fedora 19.

## Install

Clone the repository, simply compile, install and use modprobe.

```
$ make
$ su -c 'make install'
$ modprobe rt5592sta
```


