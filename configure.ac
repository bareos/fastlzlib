#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([libfastlz], [1], [/dev/null])

AM_INIT_AUTOMAKE([1.11.1 gnu subdir-objects])

AC_CONFIG_MACRO_DIR([m4])

AC_CONFIG_SRCDIR([fastlzlib-zlib.h])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_MAKE_SET
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_RANLIB

AC_CHECK_HEADERS(zlib.h)

LT_INIT

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

AC_CONFIG_FILES([Makefile])


AC_OUTPUT
