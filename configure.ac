AC_INIT([unclutter-xfixes], [1.2])

AC_CONFIG_SRCDIR([src/unclutter.c])

AM_INIT_AUTOMAKE([subdir-objects])

AM_CONFIG_HEADER([config.h])

AC_PROG_CC

PKG_CHECK_MODULES(XDEPS, x11 xi xfixes)

AC_CHECK_FUNCS([atexit])
AC_CHECK_FUNCS([memset])
AC_CHECK_FUNCS([strtol])
AC_CHECK_HEADERS([limits.h])
AC_CHECK_HEADERS([stdlib.h])
AC_CHECK_HEADERS([string.h])
AC_CHECK_HEADERS([unistd.h])
AC_CHECK_HEADER_STDBOOL
AC_FUNC_FORK
AC_PATH_X
AC_PREREQ
AC_TYPE_PID_T

AC_PROG_INSTALL

AC_CONFIG_FILES([Makefile src/Makefile man/Makefile])

AC_OUTPUT

