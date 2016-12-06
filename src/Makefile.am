## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(LIBLUNAR_CALENDAR_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

lib_LTLIBRARIES = liblunar_calendar.la


liblunar_calendar_la_SOURCES = \
	liblunar_calendar.c
	lunar-calendar-preload.c

liblunar_calendar_la_LDFLAGS = 

liblunar_calendar_la_LIBADD = $(LIBLUNAR_CALENDAR_LIBS)



include_HEADERS = \
	liblunar_calendar.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = liblunar_calendar-1.0.pc

EXTRA_DIST = \
	liblunar_calendar-1.0.pc.in
