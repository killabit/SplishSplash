![image](https://user-images.githubusercontent.com/51775887/206725042-986b0483-e73e-469a-a7f5-c5cae493fd62.png)

# SplishSplash
A command line tool unpack/repack oppo/realme/oneplus splash image

#DEPS

libzstd-devel

# BUILD
$ make

## Build Python
Coming Soon..

### Usage
## Decode image pack
+++
./splishsplash unpack -i LOGO.img -o pic
+++
    
## Repack and encode binary image
+++
./splishsplash repack -i LOGO.img -o new_LOGO.img
+++

## Read image info
+++
./splishsplash readinfo -i LOGO.img
+++
