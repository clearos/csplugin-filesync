AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

EXTRA_DIST = autogen.sh csplugin-filesync.conf csplugin-filesync.spec

AM_CFLAGS = ${CFLAGS}
AM_CXXFLAGS = ${CXXFLAGS}

lib_LTLIBRARIES = libcsplugin-filesync.la

libcsplugin_filesync_la_SOURCES = csplugin-filesync.cpp
libcsplugin_filesync_la_CXXFLAGS = ${AM_CXXFLAGS}
