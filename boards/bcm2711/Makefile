include $(TOPDIR)/rules.mk

PKG_NAME:=openmanet-bcm2711
PKG_RELEASE=1

PKG_LICENSE:=GPLv2
PKG_LICENSE_FILES:=

PKG_MAINTAINER:=OpenMANET

include $(INCLUDE_DIR)/package.mk

define Package/openmanet-bcm2711
  SECTION:=util
  CATEGORY:=OpenMANET
  SUBMENU:=Boards
  TITLE:=OpenMANET BCM2711 board support package
endef

define Build/Compile
endef

define Package/openmanet-bcm2711/install
	$(INSTALL_DIR) $(1)/etc/board.d/
	$(CP) ./etc/board.d/* $(1)/etc/board.d/
endef

$(eval $(call BuildPackage,openmanet-bcm2711))