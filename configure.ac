#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.65])
AC_INIT([MP Engine], [5],
        [rkus@fuw.edu.pl],
        [mp_engine], [https://escher.fuw.edu.pl/git/mp_engine])
AC_CONFIG_AUX_DIR([config])
AM_INIT_AUTOMAKE(foreign dist-bzip2 dist-lzma std-options silent-rules subdir-objects tar-pax -Wall -Werror -Wno-portability)
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_CONFIG_SRCDIR([src/mp5.c])
AC_CONFIG_HEADERS([config/config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL

AC_CHECK_LIB([fftw3], [fftw_execute])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT