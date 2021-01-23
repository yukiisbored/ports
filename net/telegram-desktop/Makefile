# $OpenBSD$

COMMENT =	desktop client for telegram instant messenger

DISTNAME =	telegram-desktop-2.5.1
MASTER_SITES =  https://distfiles.yukiisbo.red/

CATEGORIES =	net

HOMEPAGE =	https://desktop.telegram.org

MAINTAINER =	Muhammad Kaisar Arkhan <hi@yukiisbo.red>

# GPLv3
PERMIT_PACKAGE =	Yes

# "make port-lib-depends-check" can help
#WANTLIB =		???

MODULES =		devel/cmake \
			x11/qt5

# Telegram API keys
TELEGRAM_API_ID = 2641617
TELEGRAM_API_HASH = 4364a8b389e06c1c50e6562707e2719a

# Dependencies
#BUILD_DEPENDS =	???
#RUN_DEPENDS =		???
#LIB_DEPENDS =		???
#TEST_DEPENDS =		???

# https://github.com/desktop-app/cmake_helpers/blob/master/variables.cmake
CONFIGURE_ARGS = -DTDESKTOP_API_ID='"${TELEGRAM_API_ID}"' \
		-DTDESKTOP_API_HASH='"${TELEGRAM_API_HASH}"' \
		-DDESKTOP_APP_DISABLE_AUTOUPDATE=ON \
		-DDESKTOP_APP_USE_PACKAGED=ON \
	        -DDESKTOP_APP_DISABLE_CRASH_REPORTS=ON \
		-DDESKTOP_APP_DISABLE_DBUS_INTEGRATION=ON \
		-DDESKTOP_APP_DISABLE_WAYLAND_INTEGRATION=ON \
		-DDESKTOP_APP_DISABLE_WEBRTC_INTEGRATION=ON

WRKDIST = ${WRKDIR}/tdesktop

.include <bsd.port.mk>
