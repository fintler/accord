include $(top_srcdir)/common.mk

bin_PROGRAMS = qbench
qbench_SOURCES = adler32.c queue.c
qbench_LDADD = -lpthread -lacrd
qbench_CPPFLAGS = -I$(top_srcdir)/include
