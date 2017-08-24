#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([dbus_test], [1.0], [pengyizh@nestlabs.com])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([src])

# Checks for programs.
AC_PROG_CC
AC_PROG_CXX

# Checks for libraries.
PKG_CHECK_MODULES([DBUS], [dbus-1])
PKG_CHECK_MODULES([GLIB], [glib-2.0 dbus-glib-1])

PKG_CHECK_MODULES([DBUS_CPP], [dbus-c++-1])
# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_OUTPUT(Makefile build/Makefile echo/Makefile)
