AC_PREREQ(2.52)

AC_INIT([Apertium Ukrainian], [0.1.1], [apertium-stuff@lists.sourceforge.net], [apertium-ukr], [https://wiki.apertium.org/wiki/Apertium-ukr])
AM_INIT_AUTOMAKE
AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.7.1)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.3)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.2)

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-ukr.pc])
