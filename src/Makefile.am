# SUBDIRS = po

pkgconfigdir = $(libdir)/pkgconfig
pkgincludedir = $(includedir)/hildon-notify/hildon
pkgconfig_DATA = hildon-notify.pc
pkginclude_HEADERS = hildon-notification.h
		     
INCLUDES = \
	$(GTK_CFLAGS) \
	$(LIBNOTIFY_CFLAGS) 

lib_LTLIBRARIES = libhildonnotify.la

libhildonnotify_la_SOURCES = \
	hildon-notification.c \
	hildon-notification.h

libhildonnotify_la_LIBADD =     \
	$(GTK_LIBS)	    \
	$(LIBNOTIFY_LIBS)

CLEANFILES = *~
