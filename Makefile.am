bin_PROGRAMS=fastlzcat
lib_LTLIBRARIES=libfastlz.la
fastlzcat_SOURCES=fastlzcat.c
fastlzcat_LDADD = libfastlz.la
#fastlzcat_LDFLAGS = -DDLL_EXPORT
libfastlz_la_SOURCES=fastlzlib.c lz4/lz4.c lz4/lz4hc.c fastlz/fastlz.c
include_HEADERS=fastlzlib-zlib.h fastlzlib.h fastlz/fastlz.h lz4/lz4hc.h lz4/lz4.h
libfastlz_la_LDFLAGS = -version-info 1:0:0

docdir = $(datadir)/doc/@PACKAGE@
dist_doc_DATA = NEWS COPYING

AM_CFLAGS=-DZFAST_USE_LZ4 -DZFAST_USE_FASTLZ -DFASTLZ_INCLUDE_CONFIG_H -DDLL_EXPORT
ACLOCAL_AMFLAGS='-Im4'
