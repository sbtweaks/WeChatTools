THEOS_DEVICE_IP = 192.168.20.208




include $(THEOS)/makefiles/common.mk

TWEAK_NAME = saulThumb
saulThumb_FILES = Tweak.xm SaulWeChatPublicClass.m

include $(THEOS_MAKE_PATH)/tweak.mk

after-install::
	install.exec "killall -9 weChat"
