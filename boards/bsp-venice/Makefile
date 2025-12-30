include $(TOPDIR)/rules.mk

PKG_NAME:=bsp-venice
PKG_RELEASE=3

PKG_LICENSE:=GPLv2
PKG_LICENSE_FILES:=

PKG_MAINTAINER:=OpenMANET
PKG_BUILD_PARALLEL:=1

include $(INCLUDE_DIR)/package.mk

define Package/bsp-venice
	SECTION:=util
	CATEGORY:=OpenMANET
	SUBMENU:=Boards
	TITLE:=OpenMANET Venice board support package
	DEPENDS:=+bsp-common
endef

define Package/bsp-venice/description
This package provides board support for the OpenMANET Venice board.
endef

define Build/Compile

endef

define Package/bsp-venice/install
	$(INSTALL_DIR) $(1)/etc/board.d/
	$(CP) $(PKG_BUILD_DIR)/etc/board.d/* $(1)/etc/board.d/
endef

$(eval $(call BuildPackage,bsp-venice))
