include $(TOPDIR)/rules.mk

PKG_NAME:=bsp-bcm2711
PKG_RELEASE=3

PKG_LICENSE:=GPLv2
PKG_LICENSE_FILES:=

PKG_MAINTAINER:=OpenMANET
PKG_BUILD_PARALLEL:=1

include $(INCLUDE_DIR)/package.mk

define Package/bsp-bcm2711
	SECTION:=util
	CATEGORY:=OpenMANET
	SUBMENU:=Boards
	TITLE:=OpenMANET BCM2711 board support package
	DEPENDS:=+bsp-common
endef

define Package/bsp-bcm2711/description
This package provides board support for the OpenMANET BCM2711 board.
endef

define Build/Compile

endef

define Package/bsp-bcm2711/install
	$(INSTALL_DIR) $(1)/etc/board.d/
	$(CP) $(PKG_BUILD_DIR)/etc/board.d/* $(1)/etc/board.d/

	$(INSTALL_DIR) $(1)/lib/firmware/morse/
	$(CP) $(PKG_BUILD_DIR)/lib/firmware/morse/* $(1)/lib/firmware/morse/
endef

$(eval $(call BuildPackage,bsp-bcm2711))
