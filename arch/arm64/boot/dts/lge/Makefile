ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_BOARD_TAIMEN) += \
	overlay-taimen-rev-0.dtbo \
	overlay-taimen-rev-a.dtbo \
	overlay-taimen-rev-b.dtbo \
	overlay-taimen-rev-c.dtbo \
	overlay-taimen-rev-d.dtbo \
	overlay-taimen-rev-e.dtbo \
	overlay-taimen-rev-1_0.dtbo
else
dtb-$(CONFIG_BOARD_TAIMEN) += msm8998-taimen-rev-1_0.dtb
endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
