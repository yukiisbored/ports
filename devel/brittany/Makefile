# $OpenBSD$

COMMENT =			haskell source code formatter

MODCABAL_STEM =			brittany
MODCABAL_VERSION =		0.13.1.0

CATEGORIES =			devel
HOMEPAGE =			https://github.com/lspitzner/brittany/

MAINTAINER =			Muhammad Kaisar Arkhan <hi@yukiisbo.red>

# AGPL-3.0
PERMIT_PACKAGE =		Yes

WANTLIB =			c curses ffi gmp iconv m pthread util

MODULES =			devel/cabal
MODCABAL_MANIFEST = \
	StateVar	1.2.1	0	\
	aeson	1.5.5.1	0	\
	assoc	1.0.2	0	\
	attoparsec	0.13.2.4	1	\
	base-compat	0.11.2	0	\
	base-compat-batteries	0.11.2	0	\
	base-orphans	0.8.4	0	\
	bifunctors	5.5.10	0	\
	brittany	0.13.1.0	0	\
	butcher	1.3.3.2	0	\
	clock	0.8.2	0	\
	cmdargs	0.10.20	0	\
	comonad	5.0.8	0	\
	conduit	1.3.4	0	\
	contravariant	1.5.3	0	\
	czipwith	1.0.1.3	0	\
	data-fix	0.3.0	0	\
	data-tree-print	0.1.0.2	2	\
	deque	0.4.3	0	\
	distributive	0.6.2.1	0	\
	dlist	1.0	0	\
	extra	1.7.9	0	\
	free	5.1.6	0	\
	ghc-exactprint	0.6.3.3	0	\
	ghc-paths	0.1.0.12	1	\
	hashable	1.3.0.0	2	\
	indexed-traversable	0.1.1	0	\
	integer-logarithms	1.0.3.1	0	\
	libyaml	0.1.2	0	\
	microlens	0.4.12.0	0	\
	microlens-th	0.4.3.9	0	\
	monad-control	1.0.2.3	0	\
	monad-memo	0.5.3	0	\
	mono-traversable	1.0.15.1	0	\
	multistate	0.8.0.3	0	\
	primitive	0.7.1.0	1	\
	profunctors	5.6.1	0	\
	random	1.1	1	\
	resourcet	1.2.4.2	0	\
	safe	0.3.19	0	\
	scientific	0.3.6.2	0	\
	semigroupoids	5.3.5	0	\
	semigroups	0.19.1	0	\
	split	0.2.3.4	0	\
	strict	0.4.0.1	0	\
	strict-list	0.1.5	0	\
	syb	0.7.2.1	0	\
	tagged	0.8.6.1	0	\
	th-abstraction	0.4.2.0	0	\
	these	1.1.1.1	0	\
	time-compat	1.9.5	0	\
	transformers-base	0.4.5.2	0	\
	transformers-compat	0.6.6	0	\
	uniplate	1.6.13	1	\
	unliftio-core	0.2.0.1	1	\
	unordered-containers	0.2.13.0	0	\
	unsafe	0.0	0	\
	uuid-types	1.0.3	3	\
	vector	0.12.1.2	0	\
	vector-algorithms	0.8.0.4	0	\
	void	0.7.3	0	\
	yaml	0.11.5.0	0	\

LIB_DEPENDS =			converters/libiconv \
				devel/gmp \
				devel/libffi

.include <bsd.port.mk>
