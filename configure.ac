# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([erfa],[0.0.1])
AC_CONFIG_SRCDIR([src/erfa.h])
AC_CONFIG_HEADER([config.h])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([foreign])

AC_PROG_CC
LT_INIT

ERFA_NUMVER

# Checks for libraries.
AC_SEARCH_LIBS([sin], [m], , AC_MSG_ERROR([cannot find math functions]))

AC_CONFIG_FILES([Makefile
                 erfa.pc
                 src/Makefile
])
AC_OUTPUT
