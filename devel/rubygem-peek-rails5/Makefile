# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>
# $FreeBSD$

PORTNAME=	peek
PORTVERSION=	1.0.1
CATEGORIES=	devel rubygems
MASTER_SITES=	RG
PKGNAMESUFFIX=	-rails5

MAINTAINER=	mfechner@FreeBSD.org
COMMENT=	Take a peek into your Rails application

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE.txt

RUN_DEPENDS=	rubygem-concurrent-ruby>=0.9.0:devel/rubygem-concurrent-ruby \
		rubygem-concurrent-ruby-ext>=0.9.0:devel/rubygem-concurrent-ruby-ext \
		rubygem-railties5>=4.0.0:www/rubygem-railties5

USES=		gem
USE_RUBY=	yes

NO_ARCH=	yes

.include <bsd.port.mk>
