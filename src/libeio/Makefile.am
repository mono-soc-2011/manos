AUTOMAKE_OPTIONS = foreign no-dependencies

VERSION_INFO = 1:0

EXTRA_DIST = LICENSE Changes

include_HEADERS = eio.h

pkglib_LTLIBRARIES = libeio.la

libeio_la_SOURCES = eio.c xthread.h config.h
libeio_la_LDFLAGS = -version-info $(VERSION_INFO)

