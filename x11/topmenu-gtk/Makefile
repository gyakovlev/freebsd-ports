# $FreeBSD$

PORTNAME=	topmenu-gtk
PORTVERSION=	0.2.1
CATEGORIES=	x11
MASTER_SITES=	https://git.javispedro.com/cgit/topmenu-gtk.git/snapshot/
DISTNAME=	release_${PORTVERSION}

MAINTAINER=	delycid@gmail.com
COMMENT=	Gtk+ module and Mate/Xfce panel applets for a global menubar

LICENSE=        GPLv3

LIB_DEPENDS=    libcanberra-gtk.so:${PORTSDIR}/audio/libcanberra

USES=           autoreconf gmake libtool pathfix pkgconfig
GNU_CONFIGURE=	yes
INSTALL_TARGET=	install-strip

.include <bsd.port.mk>
