ifneq ($(KBUILD_EXTMOD),)
src = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/unicode
obj = /var/tmp/portage/sys-fs/zfs-kmod-9999/work/zfs-kmod-9999/module/unicode
endif

MODULE := zunicode

obj-$(CONFIG_ZFS) := $(MODULE).o

$(MODULE)-objs += u8_textprep.o
$(MODULE)-objs += uconv.o
