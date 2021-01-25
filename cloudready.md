# This is needed to put cloudready into "developer mode", or rather the equivalent of it.

Chromium OS, i.e. self-compiled builds or others like Arnold the Bat's, you should use instructions @ 
https://chromium.googlesource.com/chromiumos/docs/+/master/developer_mode.md#disable-verity

sudo /usr/share/vboot/bin/make_dev_ssd.sh --remove_rootfs_verification
-----------------------------------------------------------------------------------------------------------------
sudo disable_verity
