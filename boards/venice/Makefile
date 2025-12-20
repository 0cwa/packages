include $(TOPDIR)/rules.mk

PKG_NAME:=openmanet-venice
PKG_RELEASE=1

PKG_LICENSE:=GPLv2
PKG_LICENSE_FILES:=

PKG_MAINTAINER:=OpenMANET

include $(INCLUDE_DIR)/package.mk

define Package/openmanet-venice
  SECTION:=util
  CATEGORY:=OpenMANET
  SUBMENU:=Boards
  TITLE:=OpenMANET Venice board support package
endef

define Build/Compile
endef

define Package/openmanet-venice/install
	$(INSTALL_DIR) $(1)/etc/board.d/
	$(CP) ./etc/board.d/* $(1)/etc/board.d/
endef

$(eval $(call BuildPackage,openmanet-venice))