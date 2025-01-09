#
# Copyright 2024 NXP
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx91_microgea.o
obj-y += ../../freescale/common/

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX91_MICROGEA_LPDDR4) += lpddr4_timing_2400mts.o
endif
