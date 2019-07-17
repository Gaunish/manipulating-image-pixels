# Questions

## What's `stdint.h`?

It is used to define integer types having specified width

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

It is used to assign fixed wisth to integer data type.

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

4,5,4,4

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."
BM


## What's the difference between `bfSize` and `biSize`?

bfsize indicates size of bmp file.
bisize indicates size of BITMAPINFOHEADER.

## What does it mean if `biHeight` is negative?

if biheight is negative , the DIB of image is top down.

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

biXPelsPerMeter, biYPelsPerMeter

## Why might `fopen` return `NULL` in `copy.c`?

Because no infile is present

## Why is the third argument to `fread` always `1` in our code?

To read each element 1 by 1

## What value does `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3

## What does `fseek` do?

It is used to set file pointer to required position

## What is `SEEK_CUR`?

It returns the current position of file pointer
