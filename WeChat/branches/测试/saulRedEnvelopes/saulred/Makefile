THEOS_DEVICE_IP = 192.168.20.230




include $(THEOS)/makefiles/common.mk

TWEAK_NAME = saulRed
saulRed_FILES = Tweak.xm

include $(THEOS_MAKE_PATH)/tweak.mk

after-install::
	install.exec "killall -9 WeChat"
