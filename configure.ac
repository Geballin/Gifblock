AC_INIT(Gifblock, 1.0)
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([library/pkgIndex.tcl])

AC_CHECK_PROGS(TCL_TK_CHECK,tclsh,no)
AS_IF([test x"TCL_TK_CHECK" == x"no"], [AC_MSG_ERROR([Please install TCL before configuring.])])

AC_CONFIG_FILES([Makefile library/Makefile])
AC_OUTPUT
