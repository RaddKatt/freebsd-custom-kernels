# FreeBSD Custom Kernels (freebsd-custom-kernels)

These are some custom kernel configurations that I put together for FreeBSD.

Build the kernel using the `make buildkernel` command:
```
cd /usr/src
make KERNCOF=<ident> buildkernel
```

Install the kernel using the `make installkernel` command:
```
cd /usr/src
make KERNCONF=<ident> installkernel
```

[FreeBSD Handbook](https://docs.freebsd.org/en/books/developers-handbook/kernelbuild/)
