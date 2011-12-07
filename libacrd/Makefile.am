include $(top_srcdir)/common.mk

LIBACRD_VERSION = $(top_srcdir)/libacrd/libacrd.map

lib_LTLIBRARIES = libacrd.la

libacrd_la_LIBADD = $(MPI_CLDFLAGS)
libacrd_la_LDFLAGS = -version-script=$(LIBACRD_VERSION)
libacrd_la_SOURCES = libacrd.c
libacrd_la_CPPFLAGS = -I$(top_srcdir)/include

libacrd_includedir = $(includedir)/
nobase_libacrd_include_HEADERS = libacrd.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libacrd.pc
