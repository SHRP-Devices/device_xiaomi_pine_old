# twrp_device_pine
Codename: pine


---------------------------------
PitchBlack Recovery tree for pine 
---------------------------------

*To build*-

1) Sync Sources 

``$ repo init -u git://github.com/PitchBlackRecoveryProject/manifest_pb.git -b android-9.0``

``$ repo sync``


2) Build process

``$ cd SOURCE_DIR``

``$ git clone https://github.com/AndroJr7/twrp_device_pine.git device/Xiaomi/pine``

``$ . build/env*``

``$ lunch omni_pine-eng``

``$ mka recoveryimage``


That's all ! Enjoy...
