_spath=	${SRCTOP}/contrib/ofed/libcxgb4
.PATH: ${_spath}

SHLIBDIR?=	/usr/lib
LIB=		cxgb4
SHLIB_MAJOR=	1

SRCS= \
cq.c \
dev.c \
qp.c \
verbs.c

LIBADD=		ibverbs pthread
CFLAGS+=	-I${_spath}

.include <bsd.lib.mk>
