AC_INIT([hybrid-screenclone], [20120821.0])
AM_INIT_AUTOMAKE([foreign subdir-objects])
AC_CONFIG_SRCDIR([configure.ac])

AC_PROG_CXX
AX_CXX_COMPILE_STDCXX_0X
AX_PTHREAD
PKG_CHECK_MODULES([xdamage], [xdamage])
PKG_CHECK_MODULES([xrandr], [xrandr])
PKG_CHECK_MODULES([x11], [x11])
PKG_CHECK_MODULES([xtst], [xtst])
PKG_CHECK_MODULES([xcursor], [xcursor])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
