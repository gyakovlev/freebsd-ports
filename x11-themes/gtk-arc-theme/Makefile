# $FreeBSD$

PORTNAME=       gtk-arc-theme
PORTVERSION=    20151002
PORTREVISION=   1
CATEGORIES=     x11-themes
MASTER_SITES=   https://github.com/horst3180/Arc-theme/archive/
DISTNAME=       20151002

MAINTAINER=     delycid@gmail.com
COMMENT=        Arc is a flat theme with transparent elements for GTK

LICENSE=        GPLv3

RUN_DEPENDS=    gtk-murrine-engine>=0.98.1:${PORTSDIR}/x11-themes/gtk-murrine-engine

USES=           autoreconf gmake pathfix pkgconfig
GNU_CONFIGURE=	yes

WRKSRC= ${WRKDIR}/Arc-theme-${PORTVERSION}
CONFIGURE_WRKSRC=${WRKSRC}
BUILD_WRKSRC=${WRKSRC}

pre-patch:
	@${REINPLACE_CMD} -e 's|--no-preserve=mode,ownership||g' ${WRKSRC}/common/Makefile.am
.include <bsd.port.mk>
