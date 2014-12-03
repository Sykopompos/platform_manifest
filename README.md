Frankened
=================
To get Frankened

repo init -u https://github.com/The-Ancile-Project/platform_manifest.git -b frankie-mr-1

To Compile

source build/envsetup.sh

Pick a device you want to build for

lunch frankened_deb-userdebug

lunch frankened_flo-userdebug

lunch frankened_grouper-userdebug

lunch frankened_hammerhead-userdebug

lunch frankened_mako-userdebug

lunch frankened_manta-userdebug

lunch frankened_shamu-userdebug

then compile

make otapackage -j#

-j# means amount of cores plus one so a I7 with 4 cores plus hyperthreading would be 8 cores = -j9
or for max speed


linaro 4.8 is the default gcc compiler 


