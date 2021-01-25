# This is needed to put cloudready into "developer mode", or rather the equivalent of it.

Chromium OS, i.e. self-compiled builds or others like Arnold the Bat's, you should use instructions @ 
[Disable Root FS Verity](https://chromium.googlesource.com/chromiumos/docs/+/master/developer_mode.md#disable-verity "Chromium OS Dev Mode")

-----------------------------------------------------------------------------------------------------------------
shell

sudo disable_verity

sudo reboot

sudo mount -o rw,remount /
