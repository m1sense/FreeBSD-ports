PORTNAME=	libretro-picodrive
PORTVERSION=	0.20200504
CATEGORIES=	games

MAINTAINER=	dmenelkir@gmail.com
COMMENT=	Fast MegaDrive/MegaCD/32X emulator

LICENSE=	MAME-License
LICENSE_NAME=	MAME license
LICENSE_FILE=	${WRKSRC}/COPYING
LICENSE_PERMS=	dist-mirror no-dist-sell pkg-mirror no-pkg-sell auto-accept

ONLY_FOR_ARCHS=		amd64 i386
ONLY_FOR_ARCHS_REASON=	all archs except x86 report error: unsupported arch

USES=		compiler:c++11-lib gmake
USE_LDCONFIG=	yes

USE_GITHUB=	yes
GH_ACCOUNT=	libretro
GH_PROJECT=	picodrive
GH_TAGNAME=	600894e

PLIST_FILES=	lib/libretro/picodrive_libretro.so

MAKEFILE=	Makefile.libretro

do-install:
	${MKDIR} ${STAGEDIR}/${PREFIX}/lib/libretro;
	${INSTALL_LIB} ${WRKSRC}/picodrive_libretro.so ${STAGEDIR}/${PREFIX}/lib/libretro;

.include <bsd.port.mk>
