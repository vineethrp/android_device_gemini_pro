## Getting Started ##
---------------

All credits goes to OMNI contributors and TWRP contributors!

To get started with OMNI ROM, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

    repo init -u git://github.com/vineethrp/platform_manifest_twrp_omni.git -b twrp-7.1

To initialize a shallow clone, whcih will save even more space, use a command like this:

    repo init --depth=1 -u git://github.com/vineethrp/platform_manifest_twrp_omni.git -b twrp-7.1

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch omni_g15v97_gq-userdebug; mka recoveryimage

