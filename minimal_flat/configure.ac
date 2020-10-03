# -*- Autoconf -*-
AC_PREREQ([2.69])
AC_INIT([minimal_flat.c],[0.1.0],[bug-me@fqdn])

AM_MAINTAINER_MODE
AC_CONFIG_MACRO_DIR([m4])
#AC_CONFIG_HEADERS([config.h])
AC_CONFIG_AUX_DIR([build])

AM_INIT_AUTOMAKE([1.16 -Wall -Werror foreign subdir-objects])

# Checks for programs.
AC_PROG_CC
AC_PROG_CXX
AC_LANG([C],[C++])

# Check for C++11
AC_LANG_PUSH([C++])
AX_CXX_COMPILE_STDCXX_11([noext])
AC_LANG_POP([C++])

# GCC specific configuration (optional)
GCC_WARN_CXXFLAGS="-fdiagnostics-color=auto -Wall -Wextra -Wpedantic -Wfatal-errors"
GCC_WARN_CXXFLAGS_EXTRA="-Wcast-align -Wcast-qual -Wformat -Wpointer-arith -Wwrite-strings"
GCC_DEBUG_CXXFLAGS="-g -O0 -fno-omit-frame-pointer -fno-inline"

AC_CONFIG_SRCDIR([minimal_flat.c])

AC_PROG_CC
AC_PROG_CXX

AC_HEADER_STDC

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
