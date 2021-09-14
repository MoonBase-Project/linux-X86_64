ifneq ($(KBUILD_EXTMOD),)
src = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/spl
obj = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/spl
mfdir = $(obj)
else
mfdir = $(srctree)/$(src)
endif

MODULE := spl

obj-$(CONFIG_ZFS) := $(MODULE).o

include $(mfdir)/../os/linux/spl/Makefile
