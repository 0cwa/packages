include $(TOPDIR)/rules.mk

PKG_NAME:=openmanet-bsp-common
PKG_RELEASE=2

PKG_LICENSE:=GPLv2
PKG_LICENSE_FILES:=

PKG_MAINTAINER:=OpenMANET

include $(INCLUDE_DIR)/package.mk

define Package/openmanet-bsp-common
  SECTION:=util
  CATEGORY:=OpenMANET
  SUBMENU:=Boards
  TITLE:=OpenMANET common board support package
endef

define Build/Compile
endef

define Package/openmanet-bsp-common/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults/
	$(CP) ./etc/uci-defaults/* $(1)/etc/uci-defaults/
endef

$(eval $(call BuildPackage,openmanet-bsp-common))
