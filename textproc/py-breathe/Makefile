# FreeBSD$

PORTNAME=	breathe
DISTVERSION=	4.26.1
CATEGORIES=	textproc python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	y@trombik.org
COMMENT=	Sphinx extension to be able to read and render Doxygen xml output

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=		python
USE_PYTHON=	autoplist distutils
BUILD_DEPENDS=	\
	${PYTHON_PKGNAMEPREFIX}Jinja2>0:devel/py-Jinja2@${PY_FLAVOR} \
	${PYTHON_PKGNAMEPREFIX}docutils>0:textproc/py-docutils@${PY_FLAVOR} \
	${PYTHON_PKGNAMEPREFIX}markupsafe>0:textproc/py-markupsafe@${PY_FLAVOR} \
	${PYTHON_PKGNAMEPREFIX}pygments>0:textproc/py-pygments@${PY_FLAVOR} \
	${PYTHON_PKGNAMEPREFIX}sphinx>0:textproc/py-sphinx@${PY_FLAVOR} \
	${PYTHON_PKGNAMEPREFIX}six>0:devel/py-six@${PY_FLAVOR}

.include <bsd.port.mk>
