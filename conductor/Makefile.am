include $(top_srcdir)/common.mk

bin_PROGRAMS = conductor
conductor_SOURCES = acrdnet.c acrdops.c conductor.c logger.c store.c
conductor_LDADD = -lpthread -ldb -lcpg
conductor_CPPFLAGS = -I$(top_srcdir)/include
