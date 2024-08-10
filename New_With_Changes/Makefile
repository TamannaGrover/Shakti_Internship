# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2022 Toco Technologies <info@toco.ae>
#

include $(TOPDIR)/rules.mk

ARCH:=riscv64
BOARD:=shakti              # Updated board name
BOARDNAME:=Shakti         
FEATURES:=fpu              # Updated features
KERNELNAME:=Image dtbs
SUBTARGETS:=generic

KERNEL_PATCHVER:=6.6       # Verify if this kernel version is suitable for Shakti

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for the Shakti RISC-V-based boards
endef

$(eval $(call BuildTarget))

