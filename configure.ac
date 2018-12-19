#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([Natural Mystic Shaders],
        [0.1.0],
        [https://github.com/depressed-pho/natural-mystic-shaders/issues],
        [],
        [https://github.com/depressed-pho/natural-mystic-shaders])
AM_INIT_AUTOMAKE([1.9])
AC_CONFIG_SRCDIR([src/manifest.json.in])

AM_MAINTAINER_MODE
AM_SILENT_RULES([yes])

# Checks for programs.
AC_ARG_VAR([SED], [The sed command @<:@autodetected@:>@])
AC_PROG_SED
AS_IF([test "x$SED" = x],
      [AC_MSG_ERROR([You need to install a sed command.])])

AC_ARG_VAR([ZIP], [The Info-Zip zip command @<:@autodetected@:>@])
AC_CHECK_PROGS([ZIP], [zip])
AS_IF([test "x$ZIP" = x],
      [AC_MSG_ERROR([You need to install the Info-Zip zip command.])])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([
    Makefile
    src/Makefile
    orig/Makefile
])
AC_OUTPUT