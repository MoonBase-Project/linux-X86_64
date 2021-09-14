ifneq ($(KBUILD_EXTMOD),)
src = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/avl
obj = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/avl
endif

MODULE := zavl

obj-$(CONFIG_ZFS) := $(MODULE).o

$(MODULE)-objs += avl.o
