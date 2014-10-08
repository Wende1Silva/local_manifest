local_manifest to build CM11 for Nanhu
======================================

Manifest File - All Repos Needed to Build CM11 For Nanhu.

======================================

In The repo of TeamXE

Compiling CM11 For Xperia E without Bluetooth, use nanhu.xml as normal.

======================================

Compiling CM11 For Xperia E with Bluetooth, use nanhu_bt.xml 
and apply the following commits to android_bionic:

https://code.google.com/p/aosp-bluez/source/detail?r=bb1eb0c7cf42783e96020013615b00d70579123f&repo=platform-bionic

and

https://code.google.com/p/aosp-bluez/source/detail?r=7a98e7997d6849083347746d0d9727d8439ef4c4&repo=platform-bionic
