ccflags-y += -DCONFIG_TOUCHSCREEN_JADARD_DEBUG=y
ccflags-y += -DCONFIG_TOUCHSCREEN_JADARD_SORTING=y
ccflags-y += -D__JADARD_KMODULE__
obj-$(CONFIG_TOUCHSCREEN_JADARD_CHIPSET) += jadard_touch.o
jadard_touch-y := jadard_module.o
jadard_touch-y += jadard_ic_JD9366TP.o
jadard_touch-y += jadard_common.o
jadard_touch-y += jadard_platform.o
jadard_touch-y += jadard_debug.o
jadard_touch-y += jadard_sorting.o
#obj-m += jadard_touch.o
