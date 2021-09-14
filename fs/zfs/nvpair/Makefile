ifneq ($(KBUILD_EXTMOD),)
src = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/nvpair
obj = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/nvpair
endif

MODULE := znvpair

obj-$(CONFIG_ZFS) := $(MODULE).o

$(MODULE)-objs += nvpair.o
$(MODULE)-objs += fnvpair.o
$(MODULE)-objs += nvpair_alloc_spl.o
$(MODULE)-objs += nvpair_alloc_fixed.o
