PKG_NAME = expat
PKG_VERS = 2.2.7
PKG_EXT = tar.bz2
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)
PKG_DIST_SITE = http://downloads.sourceforge.net/project/$(PKG_NAME)/$(PKG_NAME)/$(PKG_VERS)
PKG_DIST_NAME = $(PKG_DIR).$(PKG_EXT)

DEPENDS =

HOMEPAGE = http://expat.sourceforge.net/
COMMENT  = Expat is an XML parser library written in C. It is a stream-oriented parser in which an application registers handlers for things the parser might find in the XML document (like start tags).
LICENSE  = MIT

GNU_CONFIGURE = 1

# TODO check "getrandom" syscall availability for each arch/DSM versions
CONFIGURE_ARGS = CFLAGS=-DXML_POOR_ENTROPY

include ../../mk/spksrc.cross-cc.mk
