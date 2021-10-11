# io_uring examples

## prepare

- kernel version >= 5.1
- build liburing first
  - cd liburing
  - ./configure
  - make && make install


## cat

> gcc cat.c/cat_uring.c
>
> gcc cat_liburing.c -luring

