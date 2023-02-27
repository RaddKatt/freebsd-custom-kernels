# FreeBSD Custom Kernels (freebsd-custom-kernels)

These are some custom kernel configurations that I put together for FreeBSD.

Build the kernel using the `make buildkernel` command with `KERNCONF=<ident>`:
```
# cd /usr/src
# make KERNCOF=ASUS_CHROMEBOX_CN62 buildkernel

...

--------------------------------------------------------------
>>> Kernel build for ASUS_CHROMEBOX_CN62 completed on Sun Feb 26 21:04:14 EST 2023
--------------------------------------------------------------
```

Install the kernel using the `make installkernel` command:
```
# cd /usr/src
# make KERNCONF=<ident> installkernel
```

[FreeBSD Handbook](https://docs.freebsd.org/en/books/developers-handbook/kernelbuild/)
