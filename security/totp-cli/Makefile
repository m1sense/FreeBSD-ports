# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>

PORTNAME=	totp-cli
PORTVERSION=	1.1.17
DISTVERSIONPREFIX=	v
PORTREVISION=	1
CATEGORIES=	security

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Authy/Google Authenticator like TOTP CLI tool

LICENSE=	GPLv3
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=		go:modules

PLIST_FILES=	bin/totp-cli

GH_ACCOUNT=	yitsushi
GH_TUPLE=	golang:crypto:5e0467b:golang_crypto/vendor/golang.org/x/crypto \
		golang:sys:da31bd3:golang_sys/vendor/golang.org/x/sys \
		golang:term:03fcf44:golang_term/vendor/golang.org/x/term \
		golang:text:v0.3.7:golang_text/vendor/golang.org/x/text \
		kardianos:osext:2bc1f35:kardianos_osext/vendor/github.com/kardianos/osext \
		mitchellh:go-homedir:v1.1.0:mitchellh_gohomedir/vendor/github.com/mitchellh/go-homedir \
		yitsushi:github-release-check:v1.0.1:yitsushi_github_release_check/vendor/github.com/yitsushi/github-release-check \
		yitsushi:go-commander:v1.1.0:yitsushi_go_commander/vendor/github.com/yitsushi/go-commander
USE_GITHUB=	yes

.include <bsd.port.mk>
