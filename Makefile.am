## Process this file with automake to produce Makefile.in

## ------------------------------------------------------------------------
## Makefile.am (toplevel)
## ------------------------------------------------------------------------
## Authors: Richard Kirby <rkirkby (at) cs.waikato.ac.nz>
## Maintainer: Tony Cebzanov <tonyc@tonyc.org>
## ------------------------------------------------------------------------
## GNU General Public License (GPL) Rights pursuant to Version 2, June 1991
## ------------------------------------------------------------------------

# Avoid picking up MacOS X resource forks in "make dist"
am__tar = COPY_EXTENDED_ATTRIBUTES_DISABLE=1 COPYFILE_DISABLE=1 ${AMTAR} cof - "$$tardir"

ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src include
DIST_SUBDIRS = src include

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = vfdlib.pc
