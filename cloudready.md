# This is needed to disable File System hash checking, or rather the equivalent of it. Note it decreases security (although Chromium OS based systems are already ahead of most linux distros in terms of security)
  For Chromium OS, see below
-----------------------------------------------------------------------------------------------------------------
  Chromium OS, i.e. self-compiled builds or others like Arnold the Bat's, you should use instructions @ 
[Disable Root FS Verity in Chromium OS](https://chromium.googlesource.com/chromiumos/docs/+/master/developer_mode.md#disable-verity "Chromium OS FS Verification")

**UPDATE** - This is probably not necessary for dev/test builds, but may be useful for base builds.
-----------------------------------------------------------------------------------------------------------------
# This is directly from https://cloudreadykb.neverware.com/s/article/Disabling-RootFS-Verification

shell

sudo disable_verity

sudo reboot

sudo mount -o rw,remount /
