ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/sensor/cci
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/sensor/io
obj-$(CONFIG_MSMB_CAMERA) += msm_flash.o
ifeq ($(CONFIG_MACH_ASUS_X00H),y)
obj-$(CONFIG_MSMB_CAMERA) += msm_subflash.o
endif
ifeq ($(CONFIG_MACH_ASUS_X00I),y)
obj-$(CONFIG_MSMB_CAMERA) += msm_subflash.o
endif
obj-$(CONFIG_MSMB_CAMERA) += msm_led_flash.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_trigger.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_i2c_trigger.o
obj-$(CONFIG_MSMB_CAMERA) += adp1660.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_torch.o