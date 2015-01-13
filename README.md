Frank
=================
To get Frank

repo init -u https://github.com/The-Ancile-Project/platform_manifest.git -b frankie-mr-1

To Compile

source build/envsetup.sh

Pick a device you want to build for

lunch frank_n7_2013_lte-userdebug

lunch frank_n7_2013_wifi-userdebug

lunch frank_n7_2012_wifi-userdebug

lunch frank_n5-userdebug

lunch frank_n4-userdebug

lunch frank_n10-userdebug

lunch frank_n6-userdebug

then compile

make otapackage -j#

-j# means amount of cores plus one so a I7 with 4 cores plus hyperthreading would be 8 cores = -j9
or for max speed

linaro 4.8 is the default gcc compiler 


