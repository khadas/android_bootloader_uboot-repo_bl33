#
# (C) Copyright 2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# (C) Copyright 2001
# Erik Theisen, Wave 7 Optics, etheisen@mindspring.com.
#
# SPDX-License-Identifier:	GPL-2.0+
#

#ccflags-y += -DDEBUG
ifdef CONFIG_DM_PWM
obj-y	+= pwm-uclass.o
obj-$(CONFIG_PWM_MESON)		+= pwm-meson.o
endif

obj-$(CONFIG_PWM_IMX) += pwm-imx.o pwm-imx-util.o