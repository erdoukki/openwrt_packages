# Copyright 2017-2019 Stan Grishin (stangri@melmac.net)
# This is free software, licensed under the GNU General Public License v3.

include $(TOPDIR)/rules.mk

PKG_LICENSE:=GPL-3.0-or-later
PKG_MAINTAINER:=Stan Grishin <stangri@melmac.net>

LUCI_TITLE:=VPN Bypass Web UI
LUCI_DESCRIPTION:=Provides Web UI for VPNBypass service.
LUCI_DEPENDS:=+luci-mod-admin-full +vpnbypass
LUCI_PKGARCH:=all
PKG_RELEASE:=12

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
