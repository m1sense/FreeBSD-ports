# Created by: Bartek Rutkowski <robak@FreeBSD.org>

PORTNAME=	nginx
PORTREVISION=	7
PKGNAMESUFFIX=	-full

MAINTAINER=	joneum@FreeBSD.org
COMMENT=	Robust and small WWW server (full package)

MASTERDIR=	${.CURDIR}/../nginx

CONFLICTS=	nginx-1.* \
		nginx-devel-1.* \
                nginx-lite-1.* \
                nginx-naxsi-1.*

OPTIONS_DEFAULT=DSO DEBUG DEBUGLOG FILE_AIO GOOGLE_PERFTOOLS \
		HTTP HTTP_ADDITION HTTP_AUTH_REQ HTTP_CACHE HTTP_DAV \
		HTTP_FLV HTTP_GZIP_STATIC HTTP_GUNZIP_FILTER \
		HTTP_IMAGE_FILTER HTTP_MP4 HTTP_PERL HTTP_RANDOM_INDEX \
		HTTP_REALIP HTTP_REWRITE HTTP_SECURE_LINK HTTP_SLICE \
		HTTP_SSL HTTP_STATUS HTTP_SUB HTTP_XSLT MAIL MAIL_IMAP \
		MAIL_POP3 MAIL_SMTP MAIL_SSL HTTPV2 NJS STREAM STREAM_SSL \
		THREADS WWW AJP AWS_AUTH CACHE_PURGE CLOJURE CT ECHO \
		FASTDFS HEADERS_MORE HTTP_ACCEPT_LANGUAGE \
		HTTP_AUTH_DIGEST HTTP_AUTH_KRB5 HTTP_AUTH_LDAP HTTP_AUTH_PAM \
		HTTP_DAV_EXT HTTP_EVAL HTTP_FANCYINDEX HTTP_FOOTER \
		HTTP_GEOIP2 HTTP_JSON_STATUS HTTP_MOGILEFS HTTP_MP4_H264 \
		HTTP_NOTICE HTTP_PUSH HTTP_PUSH_STREAM HTTP_REDIS \
		HTTP_RESPONSE HTTP_SUBS_FILTER HTTP_TARANTOOL HTTP_UPLOAD \
		HTTP_UPLOAD_PROGRESS HTTP_UPSTREAM_CHECK HTTP_UPSTREAM_FAIR \
		HTTP_UPSTREAM_STICKY HTTP_VIDEO_THUMBEXTRACTOR HTTP_ZIP \
		ARRAYVAR BROTLI DRIZZLE DYNAMIC_UPSTREAM ENCRYPTSESSION \
		FORMINPUT GRIDFS ICONV LET LUA MEMC MODSECURITY \
		NAXSI PASSENGER POSTGRES RDS_CSV RDS_JSON REDIS2 \
		RTMP SET_MISC SFLOW SHIBBOLETH SLOWFS_CACHE SMALL_LIGHT \
		SRCACHE STATSD UDPLOG X11 XSS

.include "${MASTERDIR}/Makefile"
