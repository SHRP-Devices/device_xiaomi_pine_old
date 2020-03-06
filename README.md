# twrp_device_pine
Codename: pine


---------------------------------
SKYHAWK Recovery tree for pine 
---------------------------------

*To build*-

1) Sync Sources 

``$ repo init -u git://github.com/SKYHAWK-Recovery-Project/platform_manifest_twrp_omni.git -b 9.0``

``$ repo sync``


2) Build process

``$ cd SOURCE_DIR``

``$ git clone https://github.com/AndroJr7/twrp_device_pine.git -b SHRP device/xiaomi/pine``

``$ . build/env*``

``$ lunch omni_pine-userdebug``

``$ mka recoveryimage``


That's all ! Enjoy...
