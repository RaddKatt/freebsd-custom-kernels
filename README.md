# FreeBSD Custom Kernels (freebsd-custom-kernels)

These are some custom kernel configurations that I put together for FreeBSD.

First, make sure to back up the working kernel.

Build the kernel using the `make buildkernel` command with `KERNCONF=<ident>`:
```
# cd /usr/src
# make KERNCOF=ASUS_CHROMEBOX_CN62 buildkernel

...

--------------------------------------------------------------
>>> Kernel build for ASUS_CHROMEBOX_CN62 completed on Sun Feb 26 21:04:14 EST 2023
--------------------------------------------------------------
```

Install the kernel using the `make installkernel` command with `KERNCONF=<ident>`:
```
# cd /usr/src
# make KERNCONF=ASUS_CHROMEBOX_CN62 KODIR=/boot/kernel.ASUS_CHROMEBOX_CN62 installkernel

...

--------------------------------------------------------------
>>> Installing kernel ASUS_CHROMEBOX_CN62 completed on Sun Feb 26 21:36:25 EST 2023
--------------------------------------------------------------
```

Reboot. If there are problems, boot FreeBSD with your backup kernel, and troubleshoot.

[FreeBSD Handbook](https://docs.freebsd.org/en/books/developers-handbook/kernelbuild/)
