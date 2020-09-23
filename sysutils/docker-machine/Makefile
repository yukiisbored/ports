# $OpenBSD$

COMMENT =		tool to install and manage Docker engine on virtual hosts

GH_ACCOUNT =		docker
GH_PROJECT =		machine
V =			0.16.2
GH_TAGNAME =		v${V}
PKGNAME =		docker-machine-${V}

CATEGORIES =		sysutils

HOMEPAGE =		https://docs.docker.com/machine/overview/

MAINTAINER =		Muhammad Kaisar Arkhan <hi@yukiisbo.red>

# Apache 2.0
PERMIT_PACKAGE =	Yes

WANTLIB +=		c pthread

MODULES =		lang/go

GO_PKGNAME =		github.com/docker/machine
WRKSRC =		${MODGO_WORKSPACE}/src/${GO_PKGNAME}
ALL_TARGET =		github.com/docker/machine/cmd/docker-machine

.include <bsd.port.mk>
