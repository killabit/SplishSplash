######################################################################
#   _____       _ _     _      _____       _           _              #
#  / ____|     | (_)   | |    / ____|     | |         | |             #
# | (___  _ __ | |_ ___| |__ | (___  _ __ | | __ _ ___| |__           #
#  \___ \| '_ \| | / __| '_ \ \___ \| '_ \| |/ _` / __| '_ \          #
#  ____) | |_) | | \__ \ | | |____) | |_) | | (_| \__ \ | | |         #
# |_____/| .__/|_|_|___/_| |_|_____/| .__/|_|\__,_|___/_| |_|         #
#        | |                        | |                               #
#        |_|                        |_|                               #
# By: Obsidian Intelligenece Group                           killabit #
######################################################################

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
