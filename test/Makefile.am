include $(top_srcdir)/common.mk

bin_PROGRAMS = acrdbench watch_nodes watch_files

acrdbench_SOURCES = acrdbench.c
acrdbench_LDADD = -lpthread
acrdbench_CPPFLAGS = -I$(top_srcdir)/include

watch_nodes_SOURCES = watch_nodes.c
watch_nodes_LDADD = -lpthread
watch_nodes_CPPFLAGS = -I$(top_srcdir)/include

watch_files_SOURCES = watch_files.c
watch_files_LDADD = -lpthread
watch_files_CPPFLAGS = -I$(top_srcdir)/include
