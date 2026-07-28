#
#
# This is free software, licensed under the BSD-3-Clause license.
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Support for the Matter network manager
# qrencode is optional: with it installed, the onboarding card renders
# the QR image server side; without it the payload string is shown.
LUCI_DEPENDS:=+luci-base +rpcd-mod-ucode
LUCI_PKGARCH:=all

PKG_LICENSE:=BSD-3-Clause
PKG_MAINTAINER:=Christian Glombek <c.glombek@cosa.systems>

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
