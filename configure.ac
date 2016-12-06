dnl Process this file with autoconf to produce a configure script.
dnl Created by Anjuta application wizard.

AC_INIT(liblunar_calendar, 1.0)

AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE([1.11])

AM_SILENT_RULES([yes])

AC_PROG_CC




dnl ***************************************************************************
dnl Internationalization
dnl ***************************************************************************
IT_PROG_INTLTOOL([0.35.0])

GETTEXT_PACKAGE=liblunar_calendar
AC_SUBST(GETTEXT_PACKAGE)
AC_DEFINE_UNQUOTED(GETTEXT_PACKAGE,"$GETTEXT_PACKAGE", [GETTEXT package name])
AM_GLIB_GNU_GETTEXT




AC_DISABLE_STATIC

LT_INIT

PKG_CHECK_MODULES(LUNAR_CALENDAR, lunar-date-2.0 >= $LUNAR_DATE_REQUIRED gtk+-3.0 >= $GTK2_REQUIRED  gdk-3.0 >= $GDK2_REQUIRED )




AC_OUTPUT([
Makefile
src/liblunar_calendar-1.0.pc
src/Makefile
tests/Makefile
po/Makefile.in])
