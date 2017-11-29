# SPDX-License-Identifier: GPL-2.0
ccflags-y += -I$(src)			# needed for trace events

obj-$(CONFIG_ASHMEM_C)			+= ashmem-legacy.o
obj-$(CONFIG_ASHMEM_RUST)		+= ashmem.o
obj-$(CONFIG_ANDROID_FWDATA)		+= fwdata.o
ashmem-objs += ashmem.o ashmem_exports.o