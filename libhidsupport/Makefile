include $(THEOS)/makefiles/common.mk

LIBRARY_NAME = libhidsupport
libhidsupport_FILES = client.c
libhidsupport_INSTALL_PATH = /usr/local/lib
libhidsupport_FRAMEWORKS = CoreFoundation

# rocketbootstrap
libhidsupport_CFLAGS     = -I../3rdParty/RocketBootstrap/include
libhidsupport_LDFLAGS   += -L../3rdParty/RocketBootstrap/lib
libhidsupport_LIBRARIES += substrate rocketbootstrap

include $(FW_MAKEDIR)/library.mk
