dnl Process this file with autoconf to produce a configure script

dnl ------------------------------------------------------------------------
dnl configure.in
dnl autotools build system for vfdlib
dnl ------------------------------------------------------------------------
dnl Authors: Richard Kirby <rkirkby (at) cs.waikato.ac.nz>
dnl Maintainer: Tony Cebzanov <tonyc@tonyc.org>
dnl ------------------------------------------------------------------------
dnl GNU General Public License (GPL) Rights pursuant to Version 2, June 1991
dnl ------------------------------------------------------------------------

dnl RCSIDENT("$Id:  $")

AC_PREREQ(2.59)
AC_INIT([vfdlib], [3.0.0], [tonyc@tonyc.org],[vfdlib])
AC_CONFIG_SRCDIR([include/vfdlib/vfdlib.h])
AC_CONFIG_HEADERS(include/vfdlib/config.h)
AC_COPYRIGHT([Copyright (C) 2002 Richard Kirkby
GNU Public License (GPL) Rights pursuant to Version 2, June 1991])
AC_REVISION([$Id: $])
AC_CONFIG_AUX_DIR([autoconf])
AM_INIT_AUTOMAKE([1.6.3 foreign])

AC_CONFIG_MACRO_DIR([autoconf])

AM_PROG_LIBTOOL

AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET
AC_HEADER_STDC
AC_LANG_C

AC_SUBST(AM_CPPFLAGS)
AC_SUBST(AM_CFLAGS)
AC_SUBST(AM_LDFLAGS)

CPPFLAGS='-I$(top_builddir)/include -I$(top_srcdir)/include'" $CPPFLAGS"

AM_PROG_CC_C_O

AC_HEADER_STDC

dnl automake 1.9 doesn't substitute these automatically, so we do it ourselves
dnl just in case
AC_SUBST([abs_top_srcdir])
AC_SUBST([abs_top_builddir])

AC_CONFIG_FILES([
    Makefile
    include/Makefile
    include/vfdlib/Makefile
    src/Makefile
    vfdlib.pc
])
    

dnl ----------------------------------------------------------------------
dnl Do output
dnl ----------------------------------------------------------------------

AC_OUTPUT
