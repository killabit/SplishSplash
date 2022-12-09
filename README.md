![image](https://user-images.githubusercontent.com/51775887/206725042-986b0483-e73e-469a-a7f5-c5cae493fd62.png)

# SplishSplash
A command line tool unpack/repack oppo/realme/oneplus splash image

#DEPS

libzstd-devel

# BUILD
make

## As python library
Coming Soon..

## Usage
### Unpack oppo splash image    
``` sh
./splishsplash unpack -i splash.img -o pic
```
    
### Repack oppo splash image
``` sh
./splishsplash repack -i splash.img -o new-splash.img
```

### Only read image info
``` sh
./splishsplash readinfo -i splash.img
```
